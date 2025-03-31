# FAL Documentation

> [!info] Introduction
> **FPT Admission Livestream System (FAL)** is a livestreaming system tailored for the admissions department of FPT University, designed to enhance recruitment efforts through modern livestream technology.

---

## 1. General Information

### 1.1 Project Name
- **English**: FPT Admission Livestream System  
- **Vietnamese**: Hệ thống livestream tuyển sinh Đại học FPT  
- **Abbreviation**: FAL  

### 1.2 Customer/Sponsor
- **Entity**: Admissions Department of FPT University  
- **Description**: As a leading university in Vietnam, FPT University requires an innovative solution to engage prospective students through professional livestream events while leveraging data analytics to optimize recruitment strategies.

---

## 2. Context

> [!note] Current Challenges
> Livestreaming has become a vital tool for university admissions, yet managing multiple streams for various academic programs presents challenges:  
> - Lack of seamless coordination across departments.  
> - Maintaining high levels of student engagement.  
> - Analyzing data to assess student interest effectively.

### Proposed Solution
- **Professional Livestream Platform**: Supports multiple channels like Facebook Live, TikTok, and an internal platform.  
- **Enhanced Interaction**: Real-time Q&A, dynamic surveys, and AI-powered chatbots.  
- **Data Analytics**: Tracks student interest by academic major, providing actionable insights for strategy refinement.  
- **Automation**: Sends automated notifications, securely stores content, and reduces manual workload by 50%.

---

## 3. Functional Requirements

### 3.1 User Groups

#### Students
- **Account Creation**: Register using email, phone number, or social login (Google, Facebook).  
- **Livestreams & Events**:  
  - Browse and register for admission-related livestreams and events.  
  - Personalized recommendations based on engagement history and interests.  
  - Automated reminders for registered events.  
  - Seamless integration with YouTube, Facebook Live, TikTok, and internal systems.  
  - Submit real-time questions and participate in surveys/polls.  
- **Admission Support**:  
  - Connect directly with admission representatives.  
  - AI chatbot provides 24/7 responses to FAQs.  
  - Access news, articles, and blogs on admissions and scholarships.

#### Staff
- **Blog Management**: Write, edit, and publish admission-related blog posts.  
- **Consultation**: Chat directly with prospective students for guidance.  
- **Livestream Management**:  
  - Join livestreams with specific roles (e.g., speaker, moderator).  
  - Manage live Q&A sessions and share streams across platforms.  
  - Pin important comments or block inappropriate messages.  
  - Create and manage surveys, polls, and interactive activities.

#### Administrators
- **Blog Oversight**: Review and approve blog posts for compliance with university policies.  
- **Livestream Management**:  
  - Create and schedule livestream events for academic programs.  
  - Assign roles (moderators, speakers, technical staff).  
  - Set permissions for chat, surveys, and speaking rights.  
- **Reports**:  
  - Data Collection: Tracks attendance and academic interests.  
  - Trend Analysis: Identifies popular majors and peak engagement times.  
  - Performance Reports: Measures engagement and drop-off rates.  
  - Exportable Reports: Available in PDF, Excel, or dashboards.

---

## 4. Non-Functional Requirements

- **Performance**: Fast loading times and smooth user experience.  
- **Availability**: High uptime with minimal interruptions.  
- **Usability & Accessibility**: Responsive design for mobile, tablet, and desktop devices.  
- **Maintainability & Extensibility**: Microservices architecture, adhering to SOLID and clean code principles.  
- **Logging & Monitoring**: Detailed analytics dashboards and notifications for system errors.

---

## 5. Main Proposal Content

### 5.1 Theory and Practice
- **Process**: Apply software development lifecycle and UML 2.0 for system modeling.

### 5.2 Required Documents
- [[User Requirements]]  
- [[Software Requirement Specifications]]  
- [[Architecture Design]]  
- [[Detailed Design]]  
- [[System Implementation]]  
- [[Testing Document]]  
- [[Installation Guide]]  

### 5.3 Technologies
#### Server-Side
- **Framework**: ASP .NET Core  
- **Database**: SQL Server, MongoDB  

#### Client-Side
- **Web Client**: ReactJS  

#### Supporting Technologies
- **SignalR, WebRTC**: Real-time chat, video, and notifications.  
- **Firebase**: Real-time data sync, authentication, and cloud storage.  
- **AI Chatbot**: Automated FAQ responses.  
- **Livestream API**: Facebook Live API, TikTok API.  
- **Google Analytics, AI**: User behavior and engagement analysis.

### 5.4 Products
- Web-based administrative interface.  
- Web-based user interface.  
- API services.

### 5.5 Proposed Tasks
- [[Task 1 - Web Admin]]  
- [[Task 2 - Web Students]]  
- [[Task 3 - Web API]]  
- [[Task 4 - AI Chatbot]]  
- [[Task 5 - Notification System]]  
- [[Task 6 - Documentation]]

---

> [!tip] Optimization in Obsidian
> - Use **Graph View** (`Ctrl + G`) to visualize links between documents and tasks.  
> - Add tags like `#FAL`, `#AndroidDev` for easy searching.