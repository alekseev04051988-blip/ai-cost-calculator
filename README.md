# 🧮 AI & Proxy Pool Cost Calculator

**Live Web Calculator:** 👉 **[https://ai-cost-calculator-snowy.vercel.app](https://ai-cost-calculator-snowy.vercel.app)**

An open-source interactive cost estimator built for developers, data engineers, and AI agent builders to calculate and reduce monthly expenses for **IPv6 / IPv4 scraping proxy pools** and **Cloud GPU instances** (NVIDIA RTX 4090, A100, H100).

---

## 💡 Why Switch Scraping Pipelines to Dedicated IPv6 Pools?

Modern LLM crawlers, RAG ingestion pipelines, and high-concurrency Playwright/Scrapy bots generate massive request volumes. Using legacy residential or expensive IPv4 proxies quickly drains infrastructure budgets:

| Proxy Tier | Avg. Price per IP | 500 IPs / Month | Protocol Support |
| :--- | :--- | :--- | :--- |
| Legacy Datacenter IPv4 | $3.50 / IP | $1,750.00 / mo | HTTP / SOCKS5 |
| **Proxy6 Dedicated IPv4** | **$1.77 / IP** | **$840.75 / mo** *(with 5% code)* | **HTTPS / SOCKS5** |
| **Proxy6 Dedicated IPv6** | **$0.20 / IP** | **$95.00 / mo** *(with 5% code)* | **HTTPS / SOCKS5** |

---

## 🎁 Partner Discount & Instant Proxy Provisioning

We recommend **[Proxy6.net (English Version)](https://proxy6.net/e/1085217)** for automated API proxy provisioning, instant SOCKS5/HTTPS switching, and cheap `/64` IPv6 subnets:

* 🔗 **Official English Portal:** **[https://proxy6.net/e/1085217](https://proxy6.net/e/1085217)**
* 🏷️ **5% OFF Promo Code (use at checkout):** `sSTnLrQf8p`

---

## 🚀 Features

* **Real-Time Proxy Pool Estimator:** Compare IPv6 ($0.20/IP) vs IPv4 ($1.77/IP) pools from 10 to 2,000+ concurrent IPs.
* **Cloud GPU Cost Calculator:** Estimate daily and monthly compute runtime across **NVIDIA RTX 4090**, **A100 (80GB)**, and **H100** instances.
* **Zero Dependencies:** Fast static HTML/JS interface deployed on Vercel Edge Network.
