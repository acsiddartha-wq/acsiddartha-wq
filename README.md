👋 Hi, I'm Chandra Siddhartha
🔍 QA Automation Engineer | Selenium • Java • TestNG • REST Assured
📍 Bangalore | Immediate Joiner
🔗 LinkedIn: linkedin.com/in/siddhartha-069555244
chandra-openmrs-testing/
│
├── src/
│   └── test/
│       └── java/
│           ├── base/
│           │   └── BaseClass.java          ← move here
│           │
│           ├── pages/
│           │   ├── LoginPage.java          ← move here
│           │   └── PatientPage.java        ← move here
│           │
│           ├── tests/
│           │   ├── LoginTest.java          ← move here
│           │   └── PatientTest.java        ← move here
│           │
│           └── utils/
│               └── ExcelReader.java        ← move here
│
├── api-testing/
│   └── OpenMRS_API_Tests.postman_collection.json   ← move here
│
├── manual-testing/
│   └── TestCases_BugReport_RTM.xlsx        ← move here
│
├── database-testing/
│   └── SQLQueries.sql                      ← move here
│
├── agile-docs/
│   └── Agile_SDLC_QA_Guide.docx           ← move here
│
├── screenshots/                            ← NEW: add test run screenshots here
│   └── (paste any test execution screenshots)
│
├── pom.xml                                 ← stays in root
├── testng.xml                              ← stays in root
└── README.md                              ← stays in root
