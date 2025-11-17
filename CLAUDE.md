# Claude Repository Guide: Parabolas for Profit PBL Unit

## Project Overview

This repository contains complete curriculum materials for **"Parabolas for Profit"** – a 6-week Project-Based Learning (PBL) unit for Algebra 2 students. The project engages students in analyzing real-world business pricing problems using linear regression, quadratic functions, and data analysis.

### Project Driving Question
*"How can we help a local business make the most money?"*

### What This Is NOT
- **Not a software project**: No build system, compilation, or automated testing
- **Not code-heavy**: Contains educational documents, not source code
- **No programming required**: Materials designed for Word, Google Docs, spreadsheets, and Desmos

### What This IS
- **Educational curriculum**: Complete lesson sequences, activities, templates, and assessments
- **Data-driven materials**: Synthetic datasets, CSV files, and survey templates for student analysis
- **Teacher-friendly resources**: Planning documents, rubrics, exemplars, and reference guides

---

## Directory Structure and Organization

The repository uses a numbered prefix system for navigation. All files follow strict naming conventions to indicate their type and purpose.

### `00_TEACHER_PLANNING_AND_RESOURCES/`
**Purpose**: Teacher preparation, planning, and reference materials

| File | Type | Description |
|------|------|-------------|
| `PLAN_6-Week_Teacher_Calendar.txt` | Calendar | Day-by-day breakdown of all 19 teaching days with learning goals, activities, deliverables, and resource links |
| `PLAN_4-Week_Teacher_Calendar.docx` | Calendar | Condensed version for accelerated or shorter implementations |
| `PLAN_Useable_Calendar_Revised_by_Claude.xlsx` | Planning | Interactive Excel calendar with notes and timings |
| `PLAN_Useable_Calendar_Source.xlsx` | Planning | Original calendar source file |
| `PLAN_PBLWorks_Project_Planner.docx` | Planning | PBLWorks framework project planner template |
| `PLAN_PBLWorks_Full_Planner_and_Rubric.docx` | Planning | Extended planner with integrated rubric |
| `alg2_parabolas_for_profit_project_planner.pdf` | Planning | PDF reference for project overview |
| `REF_PBL_Design_Rubric.pdf` | Reference | PBL design quality rubric |
| `REF_Project_Based_Teaching_Rubric.pdf` | Reference | Teaching quality assessment rubric |
| `REF_Peer_Feedback_ChoiceBoard.pdf` | Reference | Structured feedback options for peer review |
| `REF_Project_Path_Diagram.pdf` | Reference | Visual map of project flow and milestones |

**Key Resource**: Start with `PLAN_6-Week_Teacher_Calendar.txt` for complete lesson sequence overview.

### `01_PROJECT_LAUNCH_AND_SETUP/`
**Purpose**: Entry event materials, business data, and project initialization documents

| File | Type | Description |
|------|------|-------------|
| `ENTRY_Failing_Food_Truck.docx` | Activity | Primary entry event introducing the driving question and context |
| `ENTRY_Candy_Auction_and_Demand_Activity.docx` | Activity | Alternative entry event using auction/demand mechanics |
| `TPL_Team_Contract.docx` | Template | Team agreement document for establishing norms |
| `TPL_NTK_Question_Organizer.docx` | Template | "Need to Know" question brainstorm organizer |
| `foodtruckhook.pdf` | Hook | Visual/background material for food truck entry event |
| `student_auction.pdf` | Activity | Student-facing auction materials |
| `teacher_auction.docx` | Activity | Teacher notes and guidance for auction |
| `teacher_auction.pdf` | Activity | Printable teacher auction materials |
| `laund_wksheet.pdf` | Worksheet | Additional supplementary worksheet |
| `a2_parabola_profit_key_terms.csv` | Vocabulary | Blooket import CSV with 23 vocabulary questions covering revenue, cost, profit, demand, break-even concepts |
| `goldenmonkey_menu.json` / `goldenmonkey_menu.txt` | Business Data | Golden Monkey Bubble Tea menu (structured data format and text) |
| `mandees_menu.json` / `mandees_menu.txt` | Business Data | Mandee's Pizza menu (structured data format and text) |
| `yaschicken_menu.json` / `yaschicken_menu.txt` | Business Data | Yas Chicken restaurant menu (structured data format and text) |

**Note**: Menu files exist in both JSON (for programmatic use) and TXT (human-readable) formats.

### `02_MATH_LESSONS_AND_MODULES/`
**Purpose**: Instructional content for core mathematical concepts

| File | Type | Description |
|------|------|-------------|
| `LESSON_Linear_Regression_Mini-Lesson_Pack.docx` | Lesson | Complete linear regression instructional unit with examples and practice |
| `MOD_M2_Break-Even_Challenge.docx` | Module | Module on finding break-even points (profit = 0) |
| `MOD_M3_Vertex_by_Hand_Audit.docx` | Module | Guided practice for finding quadratic vertex without technology |
| `MOD_M6_Profit_Zone_Explorer.docx` | Module | Module on identifying profitable price ranges |
| `REF_Revenue_Cost_Profit_Formulas.docx` | Reference | Comprehensive guide to business formulas: Revenue = Price × Quantity, Cost = Fixed + Variable, Profit = Revenue - Cost |
| `REF_Desmos_Demand_Exploration_Guide.docx` | Reference | Step-by-step guide for using Desmos graphing calculator |
| `GAME_Blooket_Vocab_Import.csv` | Game Data | CSV file for importing vocabulary questions into Blooket game platform (23 questions) |

**Math Topics Covered**:
- Linear regression and scatterplot analysis
- Quadratic functions and vertex form
- Break-even analysis
- Cost, revenue, and profit calculations
- Parabola properties (vertex, intercepts, domains)

### `03_DATA_AND_SURVEY_MATERIALS/`
**Purpose**: Data resources, datasets, and survey templates for student analysis

| File | Type | Description |
|------|------|-------------|
| `DATA_Business_List_Inspiration.xlsx` | Reference | Spreadsheet with business ideas for local businesses to analyze |
| `REF_Product_Cost_Data_and_Selection.docx` | Reference | Guide for selecting products and researching realistic costs |
| `TPL_Customer_Pricing_Survey.docx` (in SURVEY_Extra_Credit_Materials/) | Template | Template for creating customer pricing surveys |

#### `DATA_Synthetic_Datasets/` Subdirectory
Three complete synthetic datasets, each with 37 data points showing price-demand relationships:

| File | Description |
|------|-------------|
| `DATA_GoldenMonkey_BubbleTea.csv` | Golden Monkey bubble tea pricing study (price range: ~$5-$8) |
| `DATA_MandeesPizza_Specialty.csv` | Mandee's Pizza 16" specialty slice pricing data (price range: $15-$30) |
| `DATA_YasChicken_Combo.csv` | Yas Chicken combo meal pricing analysis (price range varies) |

**CSV Structure** (standard for all datasets):
```
business, price_usd, demand_customers, variable_cost_per_item_usd, fixed_cost_per_day_usd, revenue_usd, total_cost_usd, profit_usd
```

Example:
```
"Mandee's Pizza - 16\" Specialty Slice Deal", 15.0, 85, 7.2, 260, 1275.0, 872.0, 403.0
```

**Data Quality Notes**:
- All data is synthetic, designed for learning
- Price-demand inverse relationship is realistic (higher price = lower demand)
- Fixed and variable costs are realistic for food service
- Profit calculations are accurate: Profit = Revenue - Total Cost
- 37 data points per business provide sufficient points for regression analysis

### `04_FINAL_PRODUCT_FILES_AND_REPORTS/`
**Purpose**: Templates for student final deliverables

| File | Type | Description |
|------|------|-------------|
| `TPL_PowerPoint_Presentation.docx` | Template | Template for final presentation slides |
| `TPL_Tri-Fold_Poster_Specifications.docx` | Template | Format guide for tri-fold poster product |
| `WKS_Mathematical_Market_Analysis.docx` | Worksheet | Major deliverable: structured report template for analysis (includes sections for tables, regression equations, graphs, profit analysis) |
| `TPL_TAG_Peer_Feedback_Form.docx` | Template | Think-Aloud-Guess (TAG) feedback form for peer review |

**Primary Student Deliverable**: `WKS_Mathematical_Market_Analysis.docx` – a comprehensive report requiring students to submit:
1. Price-demand data table
2. Regression equation with interpretation
3. Scatterplot with trend line
4. Profit function and graph
5. Break-even analysis
6. Optimal price recommendation with justification

### `05_ASSESSMENT_AND_RUBRICS/`
**Purpose**: Grading criteria and student self-assessment tools

| File | Type | Description |
|------|------|-------------|
| `RUBRIC_Teacher_Version.docx` | Rubric | Teacher rubric with scoring criteria, success indicators, and point allocations |
| `RUBRIC_Student_Version.docx` | Rubric | Student-facing version for self-assessment and goal-setting |

**Assessment Focus Areas**:
- Mathematical accuracy (calculations, graphing, algebra)
- Data interpretation and reasoning
- Communication of findings
- Real-world application and sense-making
- Collaboration (if group-based portions)

### `ZZ_STUDENT_EXEMPLARS/`
**Purpose**: Model work demonstrating proficiency and draft progression examples

| File | Type | Description |
|------|------|-------------|
| `EX_Exemplar_Report_6-Week.pdf` | Exemplar | High-quality final report from a 6-week implementation |
| `EX_Exemplar_Report_GPT.pdf` | Exemplar | Report generated using GPT assistance (for comparison) |
| `EX_Exemplar_Report_Opus.pdf` | Exemplar | Report generated using Claude Opus (for comparison) |
| `EX_Final_Report_MandeesPizza.pdf` | Exemplar | Student-quality final report on Mandee's Pizza |
| `EX_Final_Report_SweetDreamsBakery.pdf` | Exemplar | Student-quality final report on Sweet Dreams Bakery |
| `EX_Presentation_Summary_MandeesPizza.pdf` | Exemplar | Example presentation summary for Mandee's Pizza |
| `EX_Draft_Progression_SeasideScoops/` | Example | Folder containing 4-draft progression showing teacher feedback loop: |
|   - `EX_Draft_1_of_4_(Teacher_Feedback).pdf` | | Initial draft with teacher feedback |
|   - `EX_Draft_2_of_4_(Teacher_Feedback).pdf` | | Revision 1 with additional feedback |
|   - `EX_Draft_3_of_4_(Teacher_Feedback).pdf` | | Revision 2 with final guidance |
|   - `EX_Draft_4_of_4_(Final_Version).pdf` | | Final polished version |

**Exemplar Use**: Show students what proficiency looks like; use draft progression to illustrate feedback-revision cycle.

---

## File Naming Conventions

All files follow strict prefixes to indicate their purpose. When adding new materials, maintain these conventions:

| Prefix | Meaning | Example |
|--------|---------|---------|
| `PLAN_` | Planning documents, calendars | `PLAN_6-Week_Teacher_Calendar.txt` |
| `REF_` | Reference materials, guides, rubrics | `REF_Revenue_Cost_Profit_Formulas.docx` |
| `TPL_` | Templates for student or teacher use | `TPL_Team_Contract.docx` |
| `WKS_` | Worksheets, assignments, deliverables | `WKS_Mathematical_Market_Analysis.docx` |
| `DATA_` | Data files and datasets | `DATA_MandeesPizza_Specialty.csv` |
| `RUBRIC_` | Assessment rubrics | `RUBRIC_Student_Version.docx` |
| `EX_` | Exemplars and student work samples | `EX_Exemplar_Report_6-Week.pdf` |
| `MOD_` | Math modules/lessons | `MOD_M2_Break-Even_Challenge.docx` |
| `LESSON_` | Comprehensive lessons | `LESSON_Linear_Regression_Mini-Lesson_Pack.docx` |
| `GAME_` | Game-related materials | `GAME_Blooket_Vocab_Import.csv` |
| `ENTRY_` | Entry event materials | `ENTRY_Failing_Food_Truck.docx` |
| `SURVEY_` | Survey materials | Within survey directories |

**Naming Best Practices**:
- Use underscores to separate words (not spaces)
- Use module codes (M2, M3, M6) for related content
- Keep names descriptive but concise
- Examples: `MOD_M3_Vertex_by_Hand_Audit.docx` (good) vs. `Module 3 - Finding the Vertex` (avoid spaces)

---

## Project Timeline: 6-Week Implementation (19 Days)

### Week 1: Launch and Foundation
- **Day 1**: Project launch with business owner entry event
- **Day 2**: Project overview, team formation, team contracts
- **Day 3-4**: Survey design foundations and peer review
- **Day 5**: Launch surveys and begin data collection

### Week 2-3: Data Analysis and Linear Regression
- **Day 6**: Explore demand relationships (I Notice, I Wonder protocol)
- **Day 7**: Create tables and scatterplots
- **Day 8**: Linear regression and demand curve fitting
- **Day 9**: Connect demand to cost, revenue, profit concepts
- **Day 10**: Practice profit calculations

### Week 3-4: Quadratic Functions and Optimization
- **Day 11**: Graph profit equations (quadratic functions)
- **Day 12**: Link linear and quadratic relationships; identify optimal price
- **Day 13**: Draft Mathematical Market Analysis Report (major deliverable)

### Week 4-5: Review, Refinement, and Feedback
- **Day 14**: Gallery walk and peer feedback
- **Day 15**: Revise reports based on feedback
- **Day 16**: Final presentations and poster creation

### Week 5-6: Showcase and Reflection
- **Day 17**: Final project showcase (optional local business owner attendance)
- **Day 18-19**: Reflection, celebration, and assessment

**Flexible Adaptation**: 4-week calendar included for accelerated or condensed implementations.

---

## Key Concepts and Mathematical Content

### Business Vocabulary
Students learn and use these terms throughout the project:
- **Revenue**: Total money from sales (Revenue = Price × Quantity)
- **Cost**: Expenses for production (Total Cost = Fixed Cost + Variable Cost)
- **Fixed Cost**: Costs that don't change (rent, salaries)
- **Variable Cost**: Costs that change with production volume (materials)
- **Profit**: Money earned after expenses (Profit = Revenue - Cost)
- **Demand**: How many customers will buy at a given price (inverse relationship with price)
- **Break-Even Point**: Price/quantity where Profit = 0

### Mathematical Functions
- **Demand Function**: Linear relationship (usually `Demand = mx + b`)
- **Revenue Function**: Quadratic (derived from `Revenue = Price × Demand(Price)`)
- **Cost Function**: Linear (Fixed + Variable)
- **Profit Function**: Quadratic (Profit = Revenue - Cost)
- **Vertex**: Maximum profit point on profit parabola

### Analytical Methods
- **Scatterplot Analysis**: Visualizing price-demand relationships
- **Linear Regression**: Fitting lines to data using Desmos or spreadsheets
- **Graphing**: Using Desmos for exploring quadratic profit functions
- **Optimization**: Finding the vertex (maximum profit) algebraically or graphically

---

## Tools and External Resources

### Required/Recommended Tools
1. **Desmos Graphing Calculator** (https://www.desmos.com/calculator)
   - Free online graphing tool
   - Used throughout for regression and profit graphing
   - Students don't need to register
   - Can share graphs via links

2. **Google Forms & Sheets**
   - Survey creation and data collection
   - Data organization and initial graphing
   - Collaborative student work

3. **Microsoft Word / Google Docs**
   - All `.docx` files (templates, lessons, reports)
   - Used for writing reports and organizing work

4. **Microsoft Excel / Google Sheets**
   - All `.xlsx` files (calendars, data planning)
   - Data analysis and table creation

5. **Blooket** (optional, for vocabulary games)
   - Game-based learning platform
   - Import vocabulary CSV for review activities

### Key External Resources (from calendar)
- **Khan Academy**: Study design, quadratic functions
- **Pew Research Center**: Survey design best practices
- **NCTM**: I Notice, I Wonder teaching strategy
- **BBC Bitesize**: Cost-revenue-profit function explanations
- **YouTube**: Linear regression and Desmos tutorials

---

## How to Use This Repository

### For a Teacher Implementing the Unit
1. **Start here**: Read `00_TEACHER_PLANNING_AND_RESOURCES/PLAN_6-Week_Teacher_Calendar.txt`
2. **Prepare**: Review all `PLAN_*` and `REF_*` files in `00_TEACHER_PLANNING_AND_RESOURCES/`
3. **Launch**: Use `01_PROJECT_LAUNCH_AND_SETUP/` entry event materials
4. **Teach**: Follow the calendar; use `02_MATH_LESSONS_AND_MODULES/` for instruction
5. **Support**: Use `03_DATA_AND_SURVEY_MATERIALS/` datasets and survey templates
6. **Assess**: Reference `05_ASSESSMENT_AND_RUBRICS/` and `ZZ_STUDENT_EXEMPLARS/`
7. **Guide**: Use templates in `04_FINAL_PRODUCT_FILES_AND_REPORTS/`

### For a Teacher Modifying or Customizing
- **Add new datasets**: Follow CSV structure in `03_DATA_AND_SURVEY_MATERIALS/DATA_Synthetic_Datasets/`
- **Create new exemplars**: Add files to `ZZ_STUDENT_EXEMPLARS/` with `EX_` prefix
- **Adapt lessons**: Copy and rename any module or lesson, maintaining the prefix system
- **Maintain structure**: Keep directories organized by the numbered sections

### For Content Curation and Updates
- **Never delete student exemplars**: Add new ones instead (see `ZZ_STUDENT_EXEMPLARS/`)
- **Use clear commit messages**: E.g., "Update launch materials for 2025 unit" or "Add profit zone module worksheet"
- **Group related changes**: Organize commits by phase/week of the unit
- **Document changes**: Note breaking changes to existing lesson plans in PR descriptions

---

## Data Files and Formats

### CSV Dataset Format
All datasets in `03_DATA_AND_SURVEY_MATERIALS/DATA_Synthetic_Datasets/` follow this structure:

```csv
business, price_usd, demand_customers, variable_cost_per_item_usd, fixed_cost_per_day_usd, revenue_usd, total_cost_usd, profit_usd
```

**Field Descriptions**:
- `business`: Name and product (e.g., "Mandee's Pizza - 16\" Specialty Slice Deal")
- `price_usd`: Price point being tested (decimal, e.g., 15.0)
- `demand_customers`: Number of customer purchases at this price
- `variable_cost_per_item_usd`: Cost per unit sold (decimal, e.g., 7.2)
- `fixed_cost_per_day_usd`: Daily operating costs (decimal, e.g., 260)
- `revenue_usd`: Total revenue (Price × Demand)
- `total_cost_usd`: Total cost (Fixed + Variable×Demand)
- `profit_usd`: Profit (Revenue - Total Cost)

**Key Data Patterns**:
- Demand decreases as price increases (realistic inverse relationship)
- Same fixed costs across all price points for a business
- Same variable cost per item for all price points
- Profit data shows a clear parabolic pattern when graphed

### JSON Menu Format
Menu files (e.g., `yaschicken_menu.json`) structure restaurant menus for analysis:

```json
{
  "category_name": {
    "item_key": {
      "price": "X.XX",
      "description": "item description"
    }
  }
}
```

**Purpose**: Provide realistic business context; used in entry events and student discussions.

### Vocabulary CSV Format
`02_MATH_LESSONS_AND_MODULES/GAME_Blooket_Vocab_Import.csv` follows Blooket's import specification:

```
Question #, Question Text, Answer 1, Answer 2, Answer 3, Answer 4, Correct Answer(s), Time Limit (sec)
```

**Example**:
```
1, "What does 'Revenue' mean in business terms?", Money from sales, Money spent on production/operations, Money saved in the bank, Money borrowed from investors, 1, 45
```

---

## File Size and Repository Scale

- **Total files**: 58 (excluding .git)
- **Total size**: ~4.5 MB (mostly PDFs and Word docs)
- **Git history**: Single initial commit; repository actively curated
- **Remote**: GitHub (https://github.com/robjohncolson/a2_unit2_para_profit.git)

---

## Workflow Guidelines and Conventions

### Editing Guidelines
1. **Word documents (.docx)**: Edit in Word, Google Docs, or LibreOffice
2. **Spreadsheets (.xlsx)**: Edit in Excel or Google Sheets
   - After edits, save with Excel compatibility
   - Verify delimiters and headers match existing files
3. **CSV files**: Edit in spreadsheets (not text editors) to avoid delimiter corruption
4. **PDFs**: These are usually reference/exemplar materials; don't edit (create new versions instead)
5. **JSON menus**: Can edit in any text editor; validate syntax if modifying structure

### Quality Assurance for Data Files
- **CSV headers**: Verify they match existing datasets before sharing with students
- **Numeric fields**: Check for obvious errors (negative revenues, impossible prices)
- **Structure**: Ensure new datasets follow the established format
- **Documentation**: Add a .txt note near new datasets explaining their context or source

### Commit Message Examples
- "Add profit zone module worksheet"
- "Update launch materials for 2025 unit"
- "Add new exemplar: Sweet Dreams Bakery final report"
- "Revise Break-Even Challenge module for clarity"
- "Fix typo in vocabulary import CSV"

### Pull Request Best Practices
1. **Summarize instructional changes**: What topics or phases are affected?
2. **List major files touched**: Which directories were modified?
3. **Note breaking changes**: Will existing lesson plans be disrupted?
4. **Reference exemplars**: If adding new student work samples

---

## Repository Settings and Permissions

### Git Configuration
- **User**: Robert Colson (robjohncolson@protonmail.com)
- **Remote**: https://github.com/robjohncolson/a2_unit2_para_profit.git
- **Branch**: main (primary working branch)
- **Credential**: Using store helper

### Agent-Specific Permissions (Claude-specific)
- Check `.claude/settings.local.json` for tool restrictions
- Currently allows: `Bash(find:*)` and `Bash(git config:*)`

### Workflow
- This is a curated, actively maintained repository
- Changes are grouped by teaching phase
- Prefer adding new content over deleting or overwriting
- Student exemplars are historical records; preserve them

---

## Common Tasks and How to Accomplish Them

### Task: Add a New Lesson Module
1. Create a `.docx` file with prefix `MOD_` (e.g., `MOD_M7_Sensitivity_Analysis.docx`)
2. Place it in `02_MATH_LESSONS_AND_MODULES/`
3. Reference it in the appropriate day of `PLAN_6-Week_Teacher_Calendar.txt`
4. Commit with message: "Add [module name] module"

### Task: Add a New Business Dataset
1. Create a CSV file named `DATA_[BusinessName]_[Product].csv`
2. Follow the structure from existing datasets in `03_DATA_AND_SURVEY_MATERIALS/DATA_Synthetic_Datasets/`
3. Place it in the `DATA_Synthetic_Datasets/` subdirectory
4. Include a .txt note explaining the business context (optional but recommended)
5. Commit with message: "Add [Business] dataset for analysis"

### Task: Update a Teacher Calendar or Plan
1. Open the `.xlsx` or `.txt` file
2. Make changes (clear, imperative language)
3. Save with the same filename (revisions preserve history)
4. Commit with message: "Update [calendar/plan] for [school year or reason]"

### Task: Add Student Exemplar Work
1. Save new student work as a PDF
2. Name with `EX_` prefix (e.g., `EX_Final_Report_Riverside_Tacos.pdf`)
3. Place in `ZZ_STUDENT_EXEMPLARS/`
4. For multi-draft progressions, create a folder (e.g., `EX_Draft_Progression_[StudentBusiness]`)
5. Commit with message: "Add exemplar: [Student Name/Business] final report"

### Task: Revise an Existing Module or Lesson
1. Open the file in appropriate editor
2. Make revisions
3. **Option A (Preferred)**: Save with a version indicator (e.g., `MOD_M3_Vertex_by_Hand_Audit_v2.docx`)
4. **Option B**: Overwrite the original only if it's a minor bug fix (not a substantive change)
5. Commit with message: "Revise [module]: [specific improvement]"

### Task: Check Data File Integrity
1. Open CSV files in a spreadsheet tool (Excel, Google Sheets)
2. Verify:
   - Headers match the standard format
   - No unexpected characters or delimiters in cells
   - Numeric columns contain valid numbers
   - No empty rows in the middle of data
3. Save and test with Desmos (load data to verify parsing)

---

## Troubleshooting and Common Issues

### CSV Not Opening Correctly
- **Cause**: Corrupted delimiter or encoding
- **Solution**: Open in spreadsheet tool (not text editor), verify columns are properly separated, save as CSV (Windows or UTF-8)

### Desmos Graphs Not Working
- **Cause**: Incorrect regression equation syntax or data format
- **Solution**: Double-check CSV structure, manually verify a few data points, ensure price and demand columns are correctly identified

### Word Document Won't Open
- **Cause**: Corruption or unsupported version
- **Solution**: Convert to `.docx` (if older format), or use Google Docs import/export

### Students Getting Different Results from Exemplars
- **Cause**: Using different data or regression methods
- **Solution**: Ensure students are using the same dataset, emphasize that slight variations are normal (different rounding, graphing tool precision)

---

## Notes for Future Claude Instances

### What This Repository Needs
- Content curation and enhancement (new exemplars, datasets, activities)
- Instructional clarity reviews
- Alignment checks with Algebra 2 standards
- Updates to external resource links (websites change)

### What This Repository Does NOT Need
- Code refactoring, optimization, or new programming structures
- Automated testing or build systems
- Dependency management or package configuration
- Version control beyond simple git commits

### Before Making Large Changes
- Consult the existing `AGENTS.md` file for agent-specific guidelines
- Respect the directory structure and naming conventions
- Preserve student exemplars (add new ones instead of overwriting)
- Group related changes by teaching phase, not by random file editing

### Key Files to Reference
1. `AGENTS.md` - Repository guidelines for AI agents
2. `PLAN_6-Week_Teacher_Calendar.txt` - Complete project sequence
3. Exemplar PDFs in `ZZ_STUDENT_EXEMPLARS/` - Standard for student proficiency
4. CSV files in `03_DATA_AND_SURVEY_MATERIALS/` - Data structure and quality standards

---

## Quick Reference: File Locations by Common Need

| If you need... | Go to... |
|---|---|
| Full lesson sequence | `00_TEACHER_PLANNING_AND_RESOURCES/PLAN_6-Week_Teacher_Calendar.txt` |
| Entry event materials | `01_PROJECT_LAUNCH_AND_SETUP/ENTRY_*.docx` |
| Business menu data | `01_PROJECT_LAUNCH_AND_SETUP/*_menu.json` |
| Vocabulary for review | `02_MATH_LESSONS_AND_MODULES/GAME_Blooket_Vocab_Import.csv` |
| Math instruction | `02_MATH_LESSONS_AND_MODULES/` (lessons and modules) |
| Student data to analyze | `03_DATA_AND_SURVEY_MATERIALS/DATA_Synthetic_Datasets/` (CSV files) |
| Report template | `04_FINAL_PRODUCT_FILES_AND_REPORTS/WKS_Mathematical_Market_Analysis.docx` |
| Grading rubric | `05_ASSESSMENT_AND_RUBRICS/RUBRIC_*.docx` |
| Example student work | `ZZ_STUDENT_EXEMPLARS/EX_*.pdf` |

---

## Summary

This is a **well-organized, teacher-centered educational curriculum repository** with clear structure, strong naming conventions, and curated exemplars. It requires content stewardship, not software engineering. Maintain the existing organization, respect the naming patterns, preserve exemplars, and focus on enhancing instructional quality and relevance.

**When in doubt**: Check `AGENTS.md` for additional guidelines and reference the `PLAN_6-Week_Teacher_Calendar.txt` for the complete project context.
