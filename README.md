## Introduction

Alphalyzer is a **Python 3.11 / PySide6-based desktop application** designed to load, manipulate, and analyze tabular data with the ease and power of SAS or JMP.

---

## Key Features

### 1. Data Management & File Handling

| Feature | Description |
|---------|-------------|
| **Project-Based File Management** | Organized project folder structure with intuitive file tree view |
| **Multi-Format Support** | CSV, Excel (.xlsx/.xls), Parquet, DuckDB, text files, images |
| **Large-Scale Data Processing** | High-speed loading via Polars/PyArrow (1GB+ files with Lazy Preview) |
| **Smart Parsing** | Auto header detection, encoding conversion (UTF-8/CP949), data type inference |
| **Export** | CSV (UTF-8-SIG), Excel, Parquet, JSON |

### 2. Data Manipulation & Transformation

| Feature | Description |
|---------|-------------|
| **Join / Merge** | Inner, Left, Right, Outer, Cross and other join strategies |
| **Pivot / Unpivot** | Pivot table generation with subtotals |
| **Expression Filter** | Formula-based advanced data filtering and selection |
| **Deduplication** | Multi-column duplicate detection and removal |
| **Stratification** | Value/Date-based hierarchical grouping and classification |
| **Summarization** | Various aggregation functions (sum, mean, max/min, count, etc.) |
| **Gap Detection** | Automatic detection of missing values in sequences |
| **Find & Replace** | Bulk text search and batch replacement |

### 3. Statistical Analysis & Visualization

| Feature | Description |
|---------|-------------|
| **Descriptive Statistics** | Mean, median, std deviation, quartiles, min/max, etc. |
| **Benford's Law** | First-digit distribution analysis for anomaly detection |
| **Advanced Calculations** | Z-Score, cumulative sum, reverse cumsum, Shift, VLookup, percentages |
| **Charts** | Line, Bar, Scatter, Pie, Area charts (Matplotlib-based) |
| **Index Operations** | Add index columns with customizable formats |

### 4. AI Assistant (RAG Pipeline)

| Feature | Description |
|---------|-------------|
| **GPT Models** | gpt-5.2, gpt-5.1, gpt-4.1-mini |
| **Gemini Models** | gemini-3-flash-preview, gemini-3-pro-preview, gemini-2.5-flash/pro |
| **Real-Time Streaming** | Live streaming output of AI responses |
| **Document Upload** | Upload target documents for vector embedding |
| **Domain-Specific** | System prompts optimized for financial data analysis |

### 5. Korea Financial Data APIs

#### DART (Financial Supervisory Service Electronic Disclosure)
| Series | Category | Content |
|--------|----------|---------|
| **DS001** | Disclosure Info | Company search, filing lookup, full document text |
| **DS002** | Periodic Report Summary | Stock issuance, dividends, treasury stock, executive/employee info (28+ APIs) |
| **DS003** | Financial Statements | Single/multi-company financial statements, key financial accounts |
| **DS004** | Equity Disclosure | Major shareholding reports, executive/shareholder ownership changes |
| **DS005** | Material Event Reports | Mergers, asset transfers, dividends, dissolution, spin-offs |
| **DS006** | Correction Info | Securities issuance corrections, merger/exchange/spin-off amendments |

#### Other APIs
| API | Description |
|-----|-------------|
| **Korea Customs Service API** | Import/export data retrieval and automation |
| **National Pension Service API** | NPS data integration |
| **KRX Data** | Korea Exchange securities listing (12,025 securities) |

### 6. Development Environment & Tools

| Feature | Description |
|---------|-------------|
| **Python Shell** | Built-in REPL with auto-binding of loaded DataFrames |
| **Script Editor** | Code authoring, editing, and execution environment |
| **Streamlit Integration** | Instantly launch Streamlit apps from custom code |
| **Database Connectivity** | Oracle, PostgreSQL, MySQL/MariaDB, SQLite, DuckDB |
| **Package Management** | Install pip packages directly within the app |

### 7. User Interface

| Feature | Description |
|---------|-------------|
| **Table View** | Sorting, filtering, cell editing, pagination |
| **Stratified View** | Hierarchical display with group-level subtotals |
| **Light/Dark Theme** | Theme switching via pyqtdarktheme |
| **Font Size Adjustment** | Customizable font settings |
| **Background Tasks** | Status bar progress indicators with async processing |
| **Internationalization (i18n)** | Korean-first with extensible multi-language support |

---

## License

Proprietary Software - Korean Institute of Certified Public Accountants (KICPA)
