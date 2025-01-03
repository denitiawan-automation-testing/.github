# About


---

# Table of Contents
- [TestCase API Suite](#testcase-api-suite)
- [Webapp Test Suite](#webapp-test-suite)

---

## Testcase API Suite
**TestCaseAPISuite** adalah sebuah tool untuk mengotomatisasi pengujian API dengan skenario yang atur oleh data dari file Excel. Proyek ini memungkinkan pengujian beberapa skenario API secara efisien dengan mengelola input dan output yang bervariasi melalui lembar Excel. 

### Features
- **Data-Driven Testing**: 
  - Memanfaatkan Excel sebagai sumber data untuk skenario pengujian API, termasuk URL, headers, body, dan ekspektasi hasil.
- **Automated API Testing**: 
  - Menjalankan pengujian otomatis berdasarkan data yang diinputkan.
- **Response Validation**: 
  - Membandingkan respons API dengan ekspektasi secara otomatis.
- **Reports and Logs**: 
  - Menghasilkan laporan pengujian dalam format Excel, JSON, dan log untuk debugging.
- **Extensibility**:
  - Dirancang untuk mendukung modul tambahan untuk pengujian API lainnya.
 
### Spesifications
|stack|Version|
|--|--|
|python|3.12.4|
|openpyxl|3.1.4|
|pandas|2.2.2|
|requests|2.32.2|

### Folder Structure
```
TestCaseAPISuite/
├── commons/                  # Common utility services
│   ├── common_service.py      # Core common functions
│   ├── config_service.py      # Configuration management services
│   └── httpclient_service.py  # HTTP client service for API requests
│
├── documentation/            # Documentation and diagrams
│   └── sequence.puml          # Sequence diagram in PlantUML format
│
├── test_gropromotion/        # Tests for GroPromotion APIs
│   ├── data/                  # Data folder
│   │   ├── input/             # Input test cases
│   │   │   └── testcase_promotion_voucher.xlsx # Test case Excel file
│   │   └── output/            # Generated outputs
│   │       ├── bdd/           # Gherkin/BDD files
│   │       ├── json/          # JSON data files
│   │       ├── postman/       # Postman collection files
│   │       └── report/        # Test case reports
│   │
│   ├── test/                  # Test scripts
│   │   ├── test_calculate_promotion.py  # Test for promotion calculation logic
│   │   ├── test_calculate_voucher.py    # Test for voucher calculation logic
│   │   ├── test_excel_to_bdd.py         # Test for Excel to Gherkin conversion
│   │   ├── test_excel_to_json.py        # Test for Excel to JSON conversion
│   │   ├── test_excel_to_postman.py     # Test for Excel to Postman conversion
│   │   ├── test_logical_calculate.py    # Test for logical calculation
│   │   └── test_report_testcase.py      # Test for report generation
│   │
│   ├── scope_test.txt          # Scope of tests
│   ├── config.json             # Configuration file
│   └── main.py                 # Entry point for GroPromotion tests
│
├── test_kaisirpos/            # Placeholder for KaisirPOS test suite (to be implemented)
│
├── generate_requirement.py    # Script to generate dependency requirements
├── requirement.txt            # Python dependency requirements
├── main.py                    # Main entry point for the project
└── readme.md                  # Project documentation

```

### Sequence Diagram
<img width="900" src="https://www.plantuml.com/plantuml/svg/ZLLDKzim4BtxL-nmWXaWznmwVAJDq4DXcj8JCsHZRn8LMrArwq3_VQsLuyfjW5wGs7sxxsa_d0iM3D8sTL68aPfWXe8m2sP75huHYx6R1tlPYcjGI2rmUNS3QnTW7jpPNN2D4-FiWxtd3gk8QsHIrA8rGh3w1JEo1XOa1f_H5WMMqiNVCmL0XhOx2uz1J6ayMe5hPzTc4rsbtaREenlhMpcANXDlOsUdfoHcI8gZC4NwP1vZhx1y8bjrkiAEWk9MoJJ6tRQoPtHwrGUO7GebxV4Fd7terKxZGrlV_zS6LG7EzeRp7-nibg5_OZgw9FgeAGYnF6w2yx70awrZWMbKeBTrPznh1LRvxoH0pngEtZ2qeMPuDdKDArBSVoMiK72YTrMYWIKogQDB9rkms10izuv7ln-Envrhoos5yvUQNvQ7CwVIfjGRiXHGg58NGssUYE5OItSAth4q6EjPrrIAYRRpLLMTmi0SoBiWIdTILFHtiOUEzNFHjIok0U0mDI3zfEVHCIhht31KwOG_3vgJfAlg7oAIhKYUivnUjsxjMbiblXm-vCy3Fhv8m3Bbr-vrbf9g40UV5xTVyfXKsEw9k2DrHj0oMIUneiliJSbya7BUDmNcMmfFnawkPZDOcvfO1RpDEs1pygvdo-9jhhk-rzT3hzybEnIKi_haVOLvGRRIRrUWdosnn6y2KmNE_iFPxyiKFhdmZ64SDfHq3olwSyJsbTWxM-dsf70rC74-1ttaOS7ViJPLH8t20JTeB4kQuxWJ_4wb1o2avO7ZD55h5ngKarUBdT1vWPDbcRyWUN85kaon0D86E-YUPXzkA5tZQnBATs9OkkA2R1L_jtu3" >

---


## Webapp Test Suite
**Webapp Test Suite** adalah sebuah tool untuk mengotomatisasi pengujian Website dengan skenario yang atur oleh data dari file Excel. Proyek ini memungkinkan pengujian beberapa skenario API secara efisien dengan mengelola input dan output yang bervariasi melalui lembar Excel. 

### Features
- **Data-Driven Testing**: 
  - Memanfaatkan Excel sebagai sumber data untuk skenario pengujian API, termasuk URL, headers, body, dan ekspektasi hasil.
- **Reports and Logs**: 
  - Menghasilkan laporan pengujian dalam format Excel, JSON, dan log untuk debugging.

### Spesifications
|stack|Version|
|--|--|
|python|3.12.4|
|selenium||

