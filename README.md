# Technical Specification Framework
**Institutional Infrastructure:** Kamphaeng Phet Community Municipal Hospital  
**Document Identifier:** KPC-HIS-LINEOA-001  
**Subject:** Integrated Health Information Gateway (LINE Messaging Interface)  
**Classification:** Internal Use Only (Confidential)  
**Revision:** 1.0.4 (2026)

---


<p align="center">
  <img src="richmenu.png" alt="Hospital Rich Menu Interface" width="550" style="border: 3px solid #007c91; border-radius: 15px; box-shadow: 0 4px 15px rgba(0,0,0,0.1);">
  <br>
  <em><strong>Exhibit A:</strong> Architectural Layout of Client-Side Service Interface (8-Grid System)</em>
</p>

### 2.2 Service Domain & Functional Protocols

| Service Domain | Triggering Keyword Aliases | Functional Protocol |
|:---|:---|:---|
| **Telemedicine** | เริ่มใช้บริการ telemedicine, เริ่มต้น, ใช้งาน telemedicine | `getTelemedSession()` |
| **Service Info** | ข้อมูลเพิ่มเติมเกี่ยวกับ telemedicine, บริการ, ดูเพิ่มเติม | `getMoreTelemed()` |
| **Public Relations** | ประชาสัมพันธ์, ข่าวสารประชาสัมพันธ์ | `getLatestNews()` |
| **Contact/Profile** | ติดต่อเรา, เกี่ยวกับเรา | `getContactInfo()` |
| **Clinical Services** | ตรวจโรคทั่วไป, แพทย์แผนไทย, แพทย์แผนจีน | `getClinicalInquiry()` |
| **Knowledge Base** | คำถามที่พบบ่อย, FAQ, สาระสุขภาพ | `getFaqKnowledgeBase()` |
| **Navigation** | บริการของเรา, เมนูหลัก | `servicesQuickReply()` |

---

