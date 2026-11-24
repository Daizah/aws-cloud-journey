# Project 8: Portfolio Site on S3 with a Contact Form

Built and hosted a portfolio site on Amazon S3 static website hosting in my cloud bootcamp, with a custom error page and a working contact form powered by Formspree. The page started from the bootcamp's portfolio template. `index.html` here is the exact copy running in the bucket.

**Live site:** [daizah.com.s3-website.us-east-2.amazonaws.com](http://daizah.com.s3-website.us-east-2.amazonaws.com)

## Architecture

```
User → S3 Website Endpoint (HTTP) → S3 Bucket (index.html, error.html)
Contact form → Formspree → Email inbox
```

## Services and Tools

| Tool | Used for |
|------|----------|
| Amazon S3 | Static website hosting, object storage |
| S3 bucket policy (JSON) | Public read access to site files |
| S3 Block Public Access, ACLs | Testing private vs public objects |
| Formspree | Contact form submissions without a backend server |
| HTML, Tailwind CSS | Page layout and styling |

## Steps

1. Created a bucket and uploaded test objects (a .txt file and an image).
2. Opened the object URLs and confirmed private objects return `AccessDenied`.
3. Enabled ACLs and turned off Block Public Access to make single objects public, then compared the results.
4. Created the site bucket, turned off Block Public Access, and added a bucket policy allowing `s3:GetObject` on every object.
5. Enabled static website hosting with `index.html` as the index document and `error.html` as the error document.
6. Customized the portfolio template with my details, cleaned up code that broke when copied from the PDF instructions, and connected the contact form to a Formspree endpoint.
7. Tested the website endpoint, the error page (by visiting a page that does not exist), every link, and a form submission.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Portfolio page (exact copy of the live site) |
| `bucket-policy.json` | Bucket policy granting public read access |

## Verification

- Website endpoint loads the portfolio page.
- A missing page returns the custom error page.
- Contact form submissions arrive by email through Formspree.

## Lessons Learned

- S3 objects are private by default, and Block Public Access overrides any public policy until it is turned off.
- A bucket policy is the recommended way to make a site public. ACLs are an older method and are disabled on new buckets.
- The website endpoint and the object URL are different. Only the website endpoint serves the index and error documents.
- The S3 website endpoint is HTTP only. HTTPS needs CloudFront in front of the bucket.
- Code copied from a PDF can carry hidden line breaks and page numbers that break HTML.

## Next Steps

- Add CloudFront and an ACM certificate for HTTPS.
- Connect a custom subdomain with Route 53.
# Project 8: Portfolio Site on S3 with a Contact Form

Built and hosted my cloud portfolio on Amazon S3 static website hosting, with a custom error page and a working contact form powered by Formspree. Every project card on the site links back to its folder in this repo.

**Live site:** [daizah.com.s3-website.us-east-2.amazonaws.com](http://daizah.com.s3-website.us-east-2.amazonaws.com)

## Architecture

```
User → S3 Website Endpoint (HTTP) → S3 Bucket (index.html, error.html)
Contact form → Formspree → Email inbox
```

## Services and Tools

| Tool | Used for |
|------|----------|
| Amazon S3 | Static website hosting, object storage |
| S3 bucket policy (JSON) | Public read access to site files |
| S3 Block Public Access, ACLs | Testing private vs public objects |
| Formspree | Contact form submissions without a backend server |
| HTML, Tailwind CSS | Page layout and styling |

## Steps

1. Created a bucket and uploaded test objects (a .txt file and an image).
2. Opened the object URLs and confirmed private objects return `AccessDenied`.
3. Enabled ACLs and turned off Block Public Access to make single objects public, then compared the results.
4. Created the site bucket, turned off Block Public Access, and added a bucket policy allowing `s3:GetObject` on every object.
5. Enabled static website hosting with `index.html` as the index document and `error.html` as the error document.
6. Built the portfolio page, connected the contact form to a Formspree endpoint, and linked every project to this repo.
7. Tested the website endpoint, the error page (by visiting a page that does not exist), every link, and a form submission.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Portfolio page with projects and the contact form |
| `bucket-policy.json` | Bucket policy granting public read access |

## Verification

- Website endpoint loads the portfolio page.
- A missing page returns the custom error page.
- Contact form submissions arrive by email through Formspree.

## Lessons Learned

- S3 objects are private by default, and Block Public Access overrides any public policy until it is turned off.
- A bucket policy is the recommended way to make a site public. ACLs are an older method and are disabled on new buckets.
- The website endpoint and the object URL are different. Only the website endpoint serves the index and error documents.
- The S3 website endpoint is HTTP only. HTTPS needs CloudFront in front of the bucket.
- Code copied from a PDF can carry hidden line breaks and page numbers that break HTML.

## Next Steps

- Add CloudFront and an ACM certificate for HTTPS.
- Connect a custom subdomain with Route 53.
