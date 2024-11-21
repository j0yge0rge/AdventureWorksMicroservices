# AdventureWorksMicroservices

AdventureWorksMicroservices هو مشروع لتطبيق بنية ميكروسيرفيسيز باستخدام ASP.NET Core و MS SQL Server. يهدف المشروع لتوفير واجهة API لإدارة البيانات الخاصة بمخزن AdventureWorks باستخدام تقنيات Docker و CI/CD.

## Objectives
- بناء API لاستخراج، إضافة، وتحديث البيانات في قاعدة بيانات AdventureWorks.
- استخدام بنية Microservices لفصل الخدمات.
- توفير عملية CI/CD باستخدام Jenkins.

## Technologies Used
- **ASP.NET Core**: لبناء الـ REST API.
- **MS SQL Server**: لإدارة قاعدة البيانات.
- **Docker**: لتشغيل التطبيق في حاويات.
- **Jenkins**: لإعداد الـ CI/CD pipeline.

## Local Setup

### Prerequisites
- Docker
- .NET SDK
- SQL Server (أو يمكنك استخدام Docker لقاعدة البيانات)

### Steps
1. استنساخ المشروع:
   ```bash
   git clone <repository-url>
   cd AdventureWorksMicroservices
