# DNSPro Domain Submission

Welcome to the **DNSPro Custom Domain Repository**!  
Here you can request support for your own domains to be served via **DNSPro's infrastructure**.

---

## 📌 Purpose

If you'd like your domain name to be resolved by our DNSPro service, you can submit it through this repository. Domains listed in the `domains` file will be reviewed and, if approved, integrated into our DNS system.

---

## 📝 How to Submit Your Domain

Follow the steps below to add your domain to the `domains` file.

### ✅ Step-by-Step Guide

1. **Fork this repository**  
Click the `Fork` button in the top-right corner of this page.

2. **Clone your fork** (optional):
```bash
git clone https://github.com/DNSProIR/DNSPro.git
cd DNSPro
````

3. **Edit the `domains` file**
Add your domain at the end of the file, each on a **new line**:

```
example.com
anotherdomain.org
```

4. **Commit your changes**
Commit the updated file with a short message like:

```
Add example.com to domain list
```

5. **Create a Pull Request**
Go to the "Pull Requests" tab and click **"New Pull Request"** to submit your change for review.

---

## ✅ Domain Approval Process

All submitted domains will be manually reviewed. Once approved, they will be integrated into the DNSPro system and served accordingly.

> ⚠️ Make sure the domain is under your control and not managed by a third party.

---

## 🗂️ Format Rules

* One domain per line
* No subdomains or wildcards
* No blank lines or comments
* Example:

```
site1.com
mysite.net
```

---

Thank you for helping expand DNSPro’s capabilities!
For any questions, feel free to contact our support or open an issue.
