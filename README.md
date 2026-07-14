## <p align='center'>Hey, I'm Souvik  <p/>


<p align='center'>
<a href="https://git.io/typing-svg" align='center'><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=0D6EFD&center=true&vCenter=true&width=435&lines=DEVOPS+ENGINEER+@+ToolJet;AWS+SOLUTION+ARCHITECT;TERRAFORM+ASSOCIATE" alt="Typing SVG" /></a>
</p>

<p align='center'>I am a B.Tech graduate in Computer Science and Engineering with hands-on experience as a DevOps engineer. I am certified as an AWS Solutions Architect and also hold a Terraform certification. I specialize in cloud infrastructure, automation, and deployment. My skill set includes managing scalable applications on AWS/Azure and optimizing DevOps processes, security, and monitoring. I am currently working as a DevOps Engineer at ToolJet.</p>
<p align='center'>
  <img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*Fr_KLvOIFIXioOFGQNmglQ.png" width="100" title="AWS Certified Solutions Architect - Associate"/>
  <img src="https://images.credly.com/size/680x680/images/0dc62494-dc94-469a-83af-e35309f27356/blob" width="100" title="HashiCorp Certified: Terraform Associate"/>
</p>

<h3 align="left">Connect with me:</h3>
<p align="left">
 
<a href="https://www.linkedin.com/in/souvik-paul-653a291b9/">
  <img align="left" width="24px" src="https://cdn-icons-png.flaticon.com/512/174/174857.png"  />
</a>
<a href="https://twitter.com/Souvikp21570038">
  <img align="left" width="26px" src="https://logodownload.org/wp-content/uploads/2014/09/twitter-logo-6.png" />
</a>

<a href="https://www.instagram.com/slender_singer/">
  <img align="left" width="26px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a5/Instagram_icon.png/1024px-Instagram_icon.png" />
</a>

<a href="mailto:psouvik260@gmail.com">
  <img align="left" width="26px" src="https://cdn-icons-png.flaticon.com/512/281/281769.png" />
</a>


  

<br />
<br />

# Current Project:
## 📱 InvoicePro — Smart Invoice Manager

<div align="center">

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
[![Play Store](https://img.shields.io/badge/Google%20Play-414141?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.slancerk.invoicepro&pcampaignid=web_share)

**A production-grade invoice management app built for Indian freelancers & small businesses.**

*GST-compliant invoicing • PDF generation • Cloud backup • Subscription billing*

---

</div>

### ✦ What It Does

> Generate professional GST invoices, track payments, manage clients — all from your phone.
> Built with a dark, modern UI and optimized for real-world freelancer workflows.

### ✦ Key Features

| Feature | Details |
|:--------|:--------|
| 🧾 **Smart Invoicing** | Auto-numbered invoices with GST (CGST/SGST/IGST), discounts & multi-currency (₹ / $) |
| 📄 **PDF Templates** | 3 professionally designed templates — Minimal, Modern & Classic |
| 🔁 **Recurring Invoices** | Weekly, monthly, quarterly & yearly auto-generation |
| 💰 **Payment Tracking** | Partial payments, balance due, auto status updates (Draft → Sent → Paid) |
| ☁️ **Google Drive Backup** | One-tap cloud backup & restore with Google Sign-In |
| 📊 **Dashboard Analytics** | Revenue insights with all-time / monthly toggle, overdue tracking |
| 📱 **UPI QR Codes** | Auto-generated UPI payment QR on invoices for instant payments |
| 🔗 **WhatsApp Sharing** | Share invoices directly via WhatsApp with one tap |
| 💎 **In-App Subscriptions** | Freemium model with Google Play Billing (INR & USD pricing) |

### ✦ Tech Stack

Frontend       Flutter 3.x + Dart • Custom dark theme • flutter_animate
Database       SQLite (sqflite) • SharedPreferences
Cloud          Google Sign-In • Google Drive API (googleapis)
Billing        in_app_purchase (Google Play Billing)
PDF Engine     pdf + printing packages • Custom painters
Architecture   Singleton services • Clean separation of concerns



### ✦ Architecture Highlights

- **Singleton service layer** — `DatabaseService`, `BackupService`, `SubscriptionService`, `ProfileService`
- **WAL-safe backup** — SQLite WAL checkpoint before cloud backup to prevent data loss
- **Resilient restore** — Full DB + SharedPreferences restore with automatic invoice count sync
- **Reactive IAP** — Purchase stream with `Completer` pattern for reliable subscription activation
- **Smart navigation** — Post-restore routing based on actual data state, not stale flags

<div align="center">

---

*Made with ❤️ in India*

</div>
  

