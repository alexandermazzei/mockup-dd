## 1. BRAND IDENTITY & VISUAL LANGUAGE

### 1.1 Brand Positioning

### 1.1.1 Brand Values

- **Trust**: Conveying reliability and security through design elements
- **Intelligence**: Reflecting the AI-powered nature of the platform
- **Efficiency**: Communicating streamlined workflows and time-saving
- **Precision**: Emphasizing accuracy and attention to detail
- **Clarity**: Making complex financial data understandable

### 1.1.2 Brand Personality

- **Professional**: Sophisticated and trustworthy tone for financial professionals
- **Forward-thinking**: Modern approach to due diligence
- **Approachable**: Despite technical complexity, maintaining usability
- **Authoritative**: Conveying expertise in financial analysis
- **Reliable**: Design that communicates stability and dependability

### 1.2 Logo System

### 1.2.1 Primary Logo

- **Design**: Geometric abstraction of "DD" with AI integration symbol
- **Clearspace**: Minimum clear space equal to height of "D" in all directions
- **Minimum Size**: 32px height for digital, 10mm for print
- **Versions**: Full logo, monogram (for space-constrained scenarios)

### 1.2.2 Logo Variations

- **Full Color**: Primary application on white/light backgrounds
- **Reversed**: White version for dark backgrounds
- **Monochrome**: Black version for one-color applications
- **App Icon**: Square format for application icons

## 2. COLOR SYSTEM

### 2.1 Primary Palette

### 2.1.1 Core Brand Colors

- **Deep Navy** (#0A2342)
    - RGB: 10, 35, 66
    - CMYK: 100, 85, 45, 45
    - Usage: Primary brand color, headers, key UI elements
- **Azure Blue** (#2D72D9)
    - RGB: 45, 114, 217
    - CMYK: 80, 55, 0, 0
    - Usage: Interactive elements, buttons, links
- **Slate Gray** (#3C4858)
    - RGB: 60, 72, 88
    - CMYK: 78, 64, 53, 44
    - Usage: Secondary text, UI containers, borders

### 2.1.2 Accent Colors

- **Mint Green** (#00BFA5)
    - RGB: 0, 191, 165
    - CMYK: 75, 0, 46, 0
    - Usage: Positive indicators, success states, growth
- **Coral Red** (#FF5252)
    - RGB: 255, 82, 82
    - CMYK: 0, 80, 70, 0
    - Usage: Alerts, errors, risk indicators
- **Amber Yellow** (#FFC107)
    - RGB: 255, 193, 7
    - CMYK: 0, 23, 98, 0
    - Usage: Warnings, pending states, cautionary indicators

### 2.2 Secondary Palette

### 2.2.1 Extended Blues

- **Light Blue** (#E1F5FE)
    - RGB: 225, 245, 254
    - CMYK: 12, 0, 0, 0
    - Usage: Backgrounds, highlights, non-critical information
- **Sky Blue** (#81D4FA)
    - RGB: 129, 212, 250
    - CMYK: 45, 0, 0, 0
    - Usage: Charts, graphs, secondary interactive elements
- **Dark Blue** (#01579B)
    - RGB: 1, 87, 155
    - CMYK: 100, 70, 10, 10
    - Usage: Depth, emphasis, advanced features

### 2.2.2 Neutral Palette

- **Charcoal** (#263238)
    - RGB: 38, 50, 56
    - CMYK: 80, 65, 55, 60
    - Usage: Deep backgrounds, footer areas
- **Medium Gray** (#78909C)
    - RGB: 120, 144, 156
    - CMYK: 60, 40, 35, 5
    - Usage: Subtle UI elements, disabled states
- **Light Gray** (#ECEFF1)
    - RGB: 236, 239, 241
    - CMYK: 5, 3, 3, 0
    - Usage: Backgrounds, table stripes, dividers
- **White** (#FFFFFF)
    - RGB: 255, 255, 255
    - CMYK: 0, 0, 0, 0
    - Usage: Primary background, text on dark colors

### 2.3 Color Application

### 2.3.1 Functional Color Coding

- **Data Visualization Colors**:
    - Primary data: Azure Blue (#2D72D9)
    - Secondary data: Sky Blue (#81D4FA)
    - Tertiary data: Slate Gray (#3C4858)
    - Quaternary data: Light Gray (#ECEFF1)
    - Highlight data: Mint Green (#00BFA5)
- **Risk Indicators**:
    - Low risk: Mint Green (#00BFA5)
    - Medium risk: Amber Yellow (#FFC107)
    - High risk: Coral Red (#FF5252)
    - Unknown/neutral: Slate Gray (#3C4858)

### 2.3.2 Color Accessibility

- All color combinations meet WCAG 2.1 AA standards for contrast
- Critical information never relies solely on color
- Alternative visual indicators (icons, patterns) accompany color coding
- Color blind-friendly palette selections

### 2.3.3 Dark Mode Palette

- **Background**: Dark Navy (#0F172A)
- **Surface**: Midnight Blue (#1E293B)
- **Primary Text**: White (#FFFFFF) at 90% opacity
- **Secondary Text**: White (#FFFFFF) at 70% opacity
- **Primary Action**: Azure Blue (#3B82F6)
- **Secondary Action**: Steel Blue (#64748B)
- **Borders**: Gray Blue (#334155)

## 3. TYPOGRAPHY SYSTEM

### 3.1 Primary Typefaces

### 3.1.1 Primary Font

- **Font Family**: Inter (Sans-serif)
- **Weights Used**: Regular (400), Medium (500), Semibold (600), Bold (700)
- **Primary Usage**: UI text, body content, buttons, labels

```css
/* CSS Implementation */
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');

:root {
  --font-primary: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI',
                   Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
}

```

### 3.1.2 Display Font

- **Font Family**: Manrope (Sans-serif)
- **Weights Used**: Bold (700), ExtraBold (800)
- **Primary Usage**: Headings, key statistics, large numbers

```css
/* CSS Implementation */
@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@700;800&display=swap');

:root {
  --font-display: 'Manrope', var(--font-primary);
}

```

### 3.1.3 Monospace Font

- **Font Family**: JetBrains Mono
- **Weights Used**: Regular (400), Medium (500)
- **Primary Usage**: Code blocks, financial figures, tabular data

```css
/* CSS Implementation */
@import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500&display=swap');

:root {
  --font-mono: 'JetBrains Mono', SFMono-Regular, Consolas, 'Liberation Mono', Menlo, monospace;
}

```

### 3.2 Type Scale

### 3.2.1 Size Scale

- **Base Size**: 16px (1rem)
- **Scale Ratio**: 1.2 (Minor Third)
- **Sizes**:
    - xs: 0.75rem (12px)
    - sm: 0.875rem (14px)
    - base: 1rem (16px)
    - lg: 1.125rem (18px)
    - xl: 1.25rem (20px)
    - 2xl: 1.5rem (24px)
    - 3xl: 1.875rem (30px)
    - 4xl: 2.25rem (36px)
    - 5xl: 3rem (48px)
    - 6xl: 3.75rem (60px)

```css
/* CSS Implementation */
:root {
  --text-xs: 0.75rem;
  --text-sm: 0.875rem;
  --text-base: 1rem;
  --text-lg: 1.125rem;
  --text-xl: 1.25rem;
  --text-2xl: 1.5rem;
  --text-3xl: 1.875rem;
  --text-4xl: 2.25rem;
  --text-5xl: 3rem;
  --text-6xl: 3.75rem;
}

```

### 3.2.2 Line Height Scale

- **Default Body**: 1.5 (24px for 16px text)
- **Headings**: 1.2 (tighter for larger text)
- **Small Text**: 1.25 (looser for legibility)
- **Data Tables**: 1.4 (balanced for dense information)

```css
/* CSS Implementation */
:root {
  --leading-none: 1;
  --leading-tight: 1.2;
  --leading-snug: 1.375;
  --leading-normal: 1.5;
  --leading-relaxed: 1.625;
  --leading-loose: 2;
}

```

### 3.3 Typography Usage

### 3.3.1 Heading System

- **H1**: Manrope, ExtraBold, 2.25rem (36px), leading-tight
    - Usage: Page titles, major section headers
- **H2**: Manrope, Bold, 1.875rem (30px), leading-tight
    - Usage: Section headers, dashboard titles
- **H3**: Manrope, Bold, 1.5rem (24px), leading-tight
    - Usage: Sub-sections, card titles
- **H4**: Inter, SemiBold, 1.25rem (20px), leading-snug
    - Usage: Minor headings, group titles
- **H5**: Inter, SemiBold, 1.125rem (18px), leading-snug
    - Usage: Small section headers, emphasized text
- **H6**: Inter, SemiBold, 1rem (16px), leading-normal
    - Usage: Small headings, table headers

### 3.3.2 Body Text

- **Body Large**: Inter, Regular, 1.125rem (18px), leading-relaxed
    - Usage: Primary content, important paragraphs
- **Body Default**: Inter, Regular, 1rem (16px), leading-normal
    - Usage: Standard content, descriptions
- **Body Small**: Inter, Regular, 0.875rem (14px), leading-normal
    - Usage: Secondary information, captions
- **Body XSmall**: Inter, Regular, 0.75rem (12px), leading-snug
    - Usage: Legal text, footnotes, metadata

### 3.3.3 Specialized Text

- **Financial Figures**: JetBrains Mono, Medium, various sizes
    - Usage: Monetary values, percentages, key metrics
- **Data Labels**: Inter, Medium, 0.875rem (14px), leading-tight
    - Usage: Axis labels, data point annotations
- **UI Elements**: Inter, Medium, 0.875rem - 1rem (14px-16px), leading-tight
    - Usage: Buttons, form labels, navigation

### 3.4 Typography Examples

### 3.4.1 Heading Examples

```html
<h1 class="text-4xl font-extrabold font-display leading-tight text-navy">Financial Overview Dashboard</h1>
<h2 class="text-3xl font-bold font-display leading-tight text-navy mt-8">Q2 2025 Performance</h2>
<h3 class="text-2xl font-bold font-display leading-tight text-navy mt-6">Revenue Analysis</h3>
<h4 class="text-xl font-semibold leading-snug text-slate mt-4">Regional Breakdown</h4>
<h5 class="text-lg font-semibold leading-snug text-slate mt-4">Top Performing Products</h5>
<h6 class="text-base font-semibold leading-normal text-slate mt-4">Monthly Trends</h6>

```

### 3.4.2 Body Text Examples

```html
<p class="text-lg font-normal leading-relaxed text-slate-700 mt-4">
  This comprehensive analysis provides insights into financial performance across all business units.
</p>

<p class="text-base font-normal leading-normal text-slate-700 mt-4">
  Operating expenses decreased by 12% compared to the previous quarter, primarily due to the implementation
  of new automation technologies and optimization of the supply chain.
</p>

<p class="text-sm font-normal leading-normal text-slate-600 mt-2">
  Data sourced from consolidated financial statements as of April 30, 2025.
</p>

<p class="text-xs font-normal leading-snug text-slate-500 mt-2">
  Financial projections are estimates and should not be considered guarantees of future performance.
</p>

```

## 4. ICONOGRAPHY & IMAGERY

### 4.1 Icon System

### 4.1.1 Icon Style

- **Style**: Outlined with 1.5px stroke weight
- **Corner Radius**: 2px
- **Grid Size**: 24x24px with 1px padding
- **Design Principles**: Consistent visual weight, recognizable silhouettes, balanced negative space

### 4.1.2 Icon Categories

- **Navigation Icons**: Dashboard, Documents, Projects, Analytics, Settings
- **Action Icons**: Add, Edit, Delete, Download, Share, Filter, Sort
- **Status Icons**: Success, Warning, Error, Information, Pending
- **Financial Icons**: Currency, Trend, Chart, Graph, Statement, Report
- **Document Icons**: File types, Upload, Download, Sync, Verification
- **Communication Icons**: Message, Email, Notification, Comment

### 4.1.3 Icon Implementation

- **Format**: SVG with embedded CSS variables for color
- **Sizing**: 16px (small), 20px (default), 24px (large), 32px (extra large)
- **Implementation**: Icon component with size and color props

```jsx
// React Component Example
const Icon = ({ name, size = "default", color = "currentColor" }) => {
  const sizes = {
    small: "w-4 h-4",
    default: "w-5 h-5",
    large: "w-6 h-6",
    xlarge: "w-8 h-8"
  };

  return (
    <svg className={`${sizes[size]} ${color}`}>
      <use href={`/icons/sprite.svg#${name}`} />
    </svg>
  );
};

```

### 4.2 Illustration System

### 4.2.1 Illustration Style

- **Style**: Geometric abstraction with isometric elements
- **Color Usage**: Limited palette from brand colors
- **Line Work**: 2px stroke weight, rounded caps
- **Details**: Low to medium detail level for clarity at various sizes

### 4.2.2 Illustration Categories

- **Feature Illustrations**: Visual representations of key product features
- **Empty States**: Visuals for no data, search results, or completion states
- **Process Diagrams**: Step-by-step visualizations of workflows
- **Conceptual Images**: Abstract representations of financial concepts
- **Onboarding Visuals**: Guided tour illustrations

### 4.2.3 Illustration Usage Guidelines

- **Placement**: Strategic use to break up text-heavy sections
- **Purpose**: Always supports content rather than decorative only
- **Consistency**: Maintains visual coherence with overall design system
- **Accessibility**: Never conveys critical information without text equivalent
- **Responsive Behavior**: Simplified versions for mobile screens

### 4.3 Photography Guidelines

### 4.3.1 Photography Style

- **Style**: Clean, corporate, professional
- **Color Treatment**: Subtle blue toning to match brand palette
- **Composition**: Uncluttered, focused on subject matter
- **Subject Matter**: Business professionals, office environments, technology, abstract financial concepts

### 4.3.2 Photography Categories

- **Team/People Images**: Diverse professionals in business settings
- **Office/Environment**: Modern workspaces with technology
- **Abstract Concepts**: Visual metaphors for financial concepts
- **Technology**: Modern devices showing platform in use

### 4.3.3 Image Technical Requirements

- **Resolution**: Minimum 72dpi for screen, 300dpi for print materials
- **Format**: JPEG for photographs, PNG for images with transparency
- **Aspect Ratios**: 16:9 for hero images, 3:2 for content images, 1:1 for profiles
- **File Size**: Optimized for web (typically under 200KB)

### 4.4 Data Visualization

### 4.4.1 Chart and Graph Style

- **Style**: Clean, minimal, focused on data clarity
- **Color Usage**: Sequential and categorical color schemes from brand palette
- **Grid Lines**: Light gray (#ECEFF1), 1px
- **Labels**: Inter, Regular, 12px, positioned for maximum clarity
- **Tooltips**: Consistent format with clear hierarchy of information

### 4.4.2 Chart Types and Usage

- **Line Charts**: Trends over time, continuous data
- **Bar Charts**: Comparisons between categories
- **Pie/Donut Charts**: Limited to showing part-to-whole relationships with few categories
- **Heatmaps**: Showing relationships between variables
- **Scatter Plots**: Correlation between variables
- **Gauge Charts**: Single metric against a scale
- **Candlestick Charts**: Financial data showing open, high, low, close values

### 4.4.3 Data Visualization Best Practices

- **Clarity First**: Prioritize clear communication over decoration
- **Limited Variables**: Display no more than 5-7 categories in a single visualization
- **Consistent Scales**: Maintain consistent scales for accurate comparisons
- **Context**: Always provide context through titles, labels, and annotations
- **Color Usage**: Use color purposefully to highlight insights
- **Interactive Elements**: Consistent hover states and selection indicators

## 5. COMPONENT LIBRARY

### 5.1 Core Components

### 5.1.1 Buttons

- **Primary Button**:
    - Background: Azure Blue (#2D72D9)
    - Text: White (#FFFFFF)
    - Hover: Darker shade (#1A5DC7)
    - Active: Even darker (#154AA3)
    - Disabled: Gray (#D1D5DB) with reduced opacity
    - Border Radius: 4px
    - Padding: 12px 16px (default)
    - Typography: Inter, Medium, 14px, uppercase
- **Secondary Button**:
    - Background: White (#FFFFFF)
    - Text: Azure Blue (#2D72D9)
    - Border: 1px solid Azure Blue (#2D72D9)
    - Hover: Light blue background (#E1F5FE)
    - Active: Slightly darker blue background (#B3E5FC)
    - Disabled: Gray (#D1D5DB) with reduced opacity
    - Other properties: Same as Primary Button
- **Tertiary Button (Text Button)**:
    - Background: Transparent
    - Text: Azure Blue (#2D72D9)
    - Hover: Light blue background (#E1F5FE)
    - Active: Slightly darker blue background (#B3E5FC)
    - Disabled: Gray (#D1D5DB) with reduced opacity
    - Other properties: Same as Primary Button
- **Button Sizes**:
    - Small: Padding 8px 12px, Text 12px
    - Default: Padding 12px 16px, Text 14px
    - Large: Padding 14px 20px, Text 16px
- **Button with Icon**:
    - Icon: 16px (small), 20px (default), 24px (large)
    - Icon Position: Left or right of text
    - Icon Spacing: 8px from text

```jsx
// Button Component Examples
<Button variant="primary" size="default">Analyze Documents</Button>
<Button variant="secondary" size="default">Cancel</Button>
<Button variant="tertiary" size="default">Learn More</Button>
<Button variant="primary" size="default" iconLeft="upload">Upload Files</Button>

```

### 5.1.2 Form Controls

- **Text Input**:
    - Height: 40px (default)
    - Border: 1px solid Medium Gray (#78909C)
    - Border Radius: 4px
    - Background: White (#FFFFFF)
    - Text: Charcoal (#263238)
    - Placeholder: Medium Gray (#78909C)
    - Focus: 2px border Azure Blue (#2D72D9), subtle box shadow
    - Disabled: Light Gray background (#ECEFF1), reduced opacity
    - Padding: 12px
    - Typography: Inter, Regular, 14px
- **Dropdown Select**:
    - Same base styling as Text Input
    - Dropdown Icon: Custom chevron in Slate Gray (#3C4858)
    - Options Menu: White background with 2px border-radius
    - Option Hover: Light Blue background (#E1F5FE)
    - Selected Option: Azure Blue text (#2D72D9), Light Blue background (#E1F5FE)
- **Checkbox**:
    - Size: 18px × 18px
    - Border: 1px solid Medium Gray (#78909C)
    - Border Radius: 2px
    - Checked: Azure Blue background (#2D72D9), white checkmark
    - Focus: Azure Blue border, subtle box shadow
    - Typography: Inter, Regular, 14px, aligned with checkbox
- **Radio Button**:
    - Size: 18px × 18px
    - Border: 1px solid Medium Gray (#78909C)
    - Border Radius: 50%
    - Selected: Azure Blue outer ring (#2D72D9), Azure Blue center dot
    - Focus: Azure Blue border, subtle box shadow
    - Typography: Same as Checkbox
- **Toggle Switch**:
    - Height: 24px
    - Width: 44px
    - Border Radius: 12px
    - Off State: Light Gray background (#ECEFF1), white toggle
    - On State: Azure Blue background (#2D72D9), white toggle
    - Animation: Smooth transition between states
    - Focus: Azure Blue border, subtle box shadow

```jsx
// Form Control Examples
<Input
  label="Company Name"
  placeholder="Enter company name"
  helperText="As registered with SEC"
/>

<Select
  label="Document Type"
  options={[
    { value: "financial", label: "Financial Statement" },
    { value: "legal", label: "Legal Document" },
    { value: "tax", label: "Tax Return" }
  ]}
/>

<Checkbox
  label="Include subsidiaries in analysis"
  checked={true}
/>

<RadioGroup
  name="risk-level"
  options={[
    { value: "low", label: "Low Risk" },
    { value: "medium", label: "Medium Risk" },
    { value: "high", label: "High Risk" }
  ]}
  selectedValue="medium"
/>

<Toggle
  label="Enable advanced analysis"
  checked={false}
/>

```

### 5.1.3 Cards

- **Standard Card**:
    - Background: White (#FFFFFF)
    - Border: 1px solid Light Gray (#ECEFF1)
    - Border Radius: 8px
    - Shadow: Subtle drop shadow (0px 2px 6px rgba(0, 0, 0, 0.05))
    - Padding: 24px
    - Header: Manrope, SemiBold, 18px
    - Content Spacing: 16px between sections
- **Interactive Card**:
    - Base: Same as Standard Card
    - Hover: Enhanced shadow (0px 4px 12px rgba(0, 0, 0, 0.1))
    - Active/Selected: Left border 3px Azure Blue (#2D72D9)
    - Cursor: Pointer on hover
- **Metric Card**:
    - Base: Same as Standard Card
    - Value: Manrope, Bold, 28px
    - Label: Inter, Regular, 14px
    - Trend Indicator: Up/down arrow with appropriate color
    - Optional Icon: Top right, category indicator
- **Card Layouts**:
    - Simple: Header, content, optional footer
    - Media: Header, image/chart, content, optional footer
    - List: Header, scrollable list items, optional footer
    - Split: Two-column layout within card

```jsx
// Card Examples
<Card>
  <CardHeader>Financial Performance</CardHeader>
  <CardBody>
    <p>Quarterly financial results analysis and key metrics.</p>
  </CardBody>
  <CardFooter>
    <Button variant="tertiary">View Details</Button>
  </CardFooter>
</Card>

<MetricCard
  value="$1.2M"
  label="Revenue Growth"
  trend="+12.5%"
  trendDirection="up"
  icon="chart-line"
/>

```

### 5.1.4 Navigation Components

- **Top Navigation Bar**:
    - Height: 64px
    - Background: White (#FFFFFF) or Deep Navy (#0A2342)
    - Border Bottom: 1px solid Light Gray (#ECEFF1) (light theme only)
    - Logo: Left-aligned
    - Primary Navigation: Horizontal links
    - Secondary Elements: Right-aligned (search, notifications, user profile)
    - Active State: Border bottom 2px Azure Blue (#2D72D9) or Background highlight
    - Typography: Inter, Medium, 14px
- **Side Navigation**:
    - Width: 240px (expanded), 64px (collapsed)
    - Background: White (#FFFFFF) or Deep Navy (#0A2342)
    - Border Right: 1px solid Light Gray (#ECEFF1) (light theme only)
    - Item Height: 48px
    - Item Padding: 16px
    - Active State: Left border 3px Azure Blue (#2D72D9), Light Blue background (#E1F5FE) or Darker background (dark theme)
    - Icon: Left-aligned, 20px
    - Typography: Inter, Medium, 14px
    - Section Headers: Inter, SemiBold, 12px, uppercase, color Slate Gray (#3C4858)
- **Tabs**:
    - Height: 48px
    - Border Bottom: 1px solid Light Gray (#ECEFF1)
    - Padding: 12px 24px
    - Active State: Border bottom 2px Azure Blue (#2D72D9), Azure Blue text (#2D72D9)
    - Inactive State: Slate Gray text (#3C4858)
    - Hover: Light Blue background (#E1F5FE)
    - Typography: Inter, Medium, 14px
    - Optional Icon: Left of text, 16px
- **Breadcrumbs**:
    - Separator: Custom chevron icon in Light Gray (#ECEFF1)
    - Link Color: Slate Gray (#3C4858)
    - Active Page: Charcoal (#263238), non-clickable
    - Typography: Inter, Regular, 14px
    - Spacing: 8px between items

```jsx
// Navigation Examples
<TopNav>
  <Logo />
  <NavItems>
    <NavItem active href="/dashboard">Dashboard</NavItem>
    <NavItem href="/documents">Documents</NavItem>
    <NavItem href="/analysis">Analysis</NavItem>
    <NavItem href="/reports">Reports</NavItem>
  </NavItems>
  <NavActions>
    <SearchBar />
    <NotificationsMenu />
    <UserProfile />
  </NavActions>
</TopNav>

<Tabs>
  <Tab active>Overview</Tab>
  <Tab>Financial Analysis</Tab>
  <Tab>Risk Assessment</Tab>
  <Tab>Documents</Tab>
</Tabs>

<Breadcrumbs>
  <BreadcrumbItem href="/projects">Projects</BreadcrumbItem>
  <BreadcrumbItem href="/projects/finance">Finance</BreadcrumbItem>
  <BreadcrumbItem>Q2 Analysis</BreadcrumbItem>
</Breadcrumbs>

```

### 5.2 Specialized Components

### 5.2.1 Data Tables

- **Table Structure**:
    - Header: Background Light Gray (#ECEFF1), Sticky positioning
    - Header Cell: Inter, Medium, 14px, Slate Gray (#3C4858)
    - Row: White background, 1px Light Gray border bottom (#ECEFF1)
    - Alternate Row: Very Light Gray background (zebra striping)
    - Cell: Inter, Regular, 14px, Charcoal (#263238)
    - Cell Padding: 12px 16px
    - Row Hover: Light Blue background (#E1F5FE)
- **Table Functionality**:
    - Sorting: Header click with directional indicator
    - Filtering: Per-column filter options
    - Pagination: Bottom-aligned controls
    - Row Selection: Left-aligned checkbox column
    - Row Expansion: Expandable rows for additional details
    - Cell Types: Text, Numeric, Date, Status, Actions
- **Financial Data Formatting**:
    - Currency: Always with appropriate symbol and decimal places
    - Percentages: With % symbol, appropriate decimal places
    - Negative Values: Red text or parentheses based on settings
    - Large Numbers: With appropriate separators (comma or space)
    - Date Formatting: Consistent format based on region

```jsx
// Data Table Example
<DataTable
  columns={[
    { field: 'companyName', header: 'Company Name', sortable: true },
    { field: 'revenue', header: 'Revenue', sortable: true, type: 'currency' },
    { field: 'growth', header: 'YoY Growth', sortable: true, type: 'percentage' },
    { field: 'risk', header: 'Risk Level', sortable: true, type: 'status' },
    { field: 'actions', header: 'Actions', type: 'actions' }
  ]}
  data={companiesData}
  pagination={true}
  selectable={true}
/>

```

### 5.2.2 Dashboard Widgets

- **Widget Container**:
    - Base: Extended Card component
    - Height: Fixed or auto-adjusting based on content
    - Resize Handles: For user customization where applicable
    - Header: Title, optional actions (refresh, expand, settings)
- **Widget Types**:
    - Metric Widget: Large KPI display with trend
    - Chart Widget: Various chart types with minimal controls
    - List Widget: Scrollable list of items
    - Table Widget: Simplified data table
    - Status Widget: Visual indicators of system status
    - News/Updates Widget: Recent activities or news
- **Widget Layout System**:
    - Grid System: 12-column responsive grid
    - Spacing: 16px gutters between widgets
    - Sizes: Small (3 columns), Medium (6 columns), Large (9 columns), Full (12 columns)
    - Responsive Behavior: Stack on smaller screens

```jsx
// Dashboard Widget Examples
<DashboardGrid>
  <Widget size="small" title="Total Documents">
    <MetricDisplay value="1,248" trend="+23" trendPeriod="this month" />
  </Widget>

  <Widget size="medium" title="Revenue Analysis">
    <Chart type="line" data={revenueData} />
  </Widget>

  <Widget size="medium" title="Recent Activities">
    <ActivityList items={recentActivities} />
  </Widget>

  <Widget size="large" title="Risk Distribution">
    <Chart type="pie" data={riskDistribution} />
  </Widget>
</DashboardGrid>

```

### 5.2.3 Document Viewer

- **Viewer Container**:
    - Full-height container with flexible width
    - Toolbar: Top-aligned with document controls
    - Navigation: Page controls, zoom controls
    - Sidebar: Optional metadata and annotation panel

- **Document Display**:
    - Page Rendering: High-fidelity with proper text rendering
    - Zoom Levels: Presets (Fit to width, Fit to page, 100%, 150%, 200%)
    - Page Navigation: Prev/Next buttons, page jump, thumbnail navigation
    - Search: Text highlighting, result navigation
- **Annotation Tools**:
    - Highlighting: Multiple colors with semantic meaning
    - Comments: Margin notes with threading capability
    - Redaction: For sensitive information
    - Drawing: Simple shapes and freehand markup
    - Tags: Categorization of annotations by type or concern
- **Document Sidebar**:
    - Metadata Panel: Document properties and attributes
    - Outline View: Document structure navigation
    - Annotation List: Filtered view of all annotations
    - Activity Log: History of changes and comments
    - AI Insights: Automated analysis results

```jsx
// Document Viewer Example
<DocumentViewer>
  <ViewerToolbar>
    <ZoomControls />
    <PageNavigation />
    <AnnotationTools />
    <SearchBar />
  </ViewerToolbar>

  <ViewerContent>
    <DocumentPages document={currentDocument} />
  </ViewerContent>

  <ViewerSidebar>
    <TabPanel tabs={[
      { label: "Info", content: <DocumentInfo /> },
      { label: "Outline", content: <DocumentOutline /> },
      { label: "Annotations", content: <AnnotationList /> },
      { label: "AI Analysis", content: <AIInsights /> }
    ]} />
  </ViewerSidebar>
</DocumentViewer>

```

### 5.2.4 Financial Modeling Interface

- **Model Builder**:
    - Split View: Inputs panel and results panel
    - Formula Bar: Excel-like formula editing
    - Cell References: Named references to other model elements
    - Template Selection: Pre-built model templates
- **Input Controls**:
    - Parameter Inputs: Numeric inputs with validation
    - Assumption Tables: Editable tables for scenario data
    - Date Range Selectors: For time-based models
    - Source Selection: Data source mapping
- **Output Visualization**:
    - Result Tables: Formatted financial tables
    - Key Metrics: Highlighted performance indicators
    - Sensitivity Analysis: Interactive what-if tools
    - Charts: Integrated visualizations of results
- **Model Management**:
    - Version Control: Tracking of model changes
    - Scenario Manager: Named scenarios with saved inputs
    - Export Options: Excel, PDF, presentation formats
    - Sharing Controls: Permissions for collaborative editing

```jsx
// Financial Modeling Interface Example
<ModelBuilder>
  <ModelHeader>
    <ModelTitle>Acquisition Valuation Model</ModelTitle>
    <ModelActions>
      <Button iconLeft="save">Save</Button>
      <Button iconLeft="share">Share</Button>
      <DropdownMenu label="Export" options={exportOptions} />
    </ModelActions>
  </ModelHeader>

  <SplitView>
    <ModelInputs>
      <InputSection title="Target Company Data">
        <NumericInput
          label="Annual Revenue"
          value={10000000}
          prefix="$"
          precision={0}
        />
        <NumericInput
          label="EBITDA Margin"
          value={15}
          suffix="%"
          precision={1}
        />
        <NumericInput
          label="Growth Rate"
          value={5.5}
          suffix="%"
          precision={1}
        />
      </InputSection>

      <InputSection title="Valuation Assumptions">
        <NumericInput
          label="EBITDA Multiple"
          value={8.5}
          precision={1}
        />
        <NumericInput
          label="Discount Rate"
          value={12}
          suffix="%"
          precision={1}
        />
      </InputSection>
    </ModelInputs>

    <ModelResults>
      <ResultsSection title="Valuation Summary">
        <MetricCard
          label="Enterprise Value"
          value="$127.5M"
          formula="=Revenue * EBITDA_Margin * EBITDA_Multiple"
        />
        <MetricCard
          label="5-Year ROI"
          value="34.2%"
          trendDirection="up"
        />
      </ResultsSection>

      <ResultsSection title="Projected Performance">
        <Chart type="line" data={projectionData} />
      </ResultsSection>
    </ModelResults>
  </SplitView>

  <ScenarioManager scenarios={savedScenarios} />
</ModelBuilder>

```

### 5.2.5 Risk Assessment Dashboard

- **Risk Matrix**:
    - Visual grid showing impact vs. probability
    - Color coding for risk levels (green, amber, red)
    - Interactive risk plotting
    - Risk category filtering
- **Risk Detail Cards**:
    - Risk Title: Clear description of the risk
    - Risk Score: Numeric and visual representation
    - Impact & Probability: Individual ratings
    - Category: Risk classification
    - Mitigation: Recommended actions
    - Status: Current handling status
- **Risk Analytics**:
    - Distribution Charts: Risk spread by category
    - Trend Analysis: Risk evolution over time
    - Comparison Views: Against benchmarks or previous assessments
    - Combined Impact View: Aggregated risk exposure

```jsx
// Risk Assessment Dashboard Example
<RiskDashboard>
  <RiskOverview>
    <RiskSummary
      totalRisks={42}
      highRisks={7}
      mediumRisks={23}
      lowRisks={12}
    />

    <RiskByCategory
      data={riskCategoryData}
      chartType="horizontalBar"
    />
  </RiskOverview>

  <RiskMatrixSection>
    <RiskMatrix
      risks={riskItems}
      onRiskClick={handleRiskSelect}
    />

    <RiskFilters
      categories={riskCategories}
      statuses={riskStatuses}
      onFilterChange={handleFilterChange}
    />
  </RiskMatrixSection>

  <RiskDetailSection>
    <RiskList
      risks={filteredRisks}
      selectedRiskId={selectedRisk?.id}
      onRiskSelect={handleRiskSelect}
    />

    {selectedRisk && (
      <RiskDetail
        risk={selectedRisk}
        mitigationOptions={mitigationOptions}
        onStatusChange={handleStatusChange}
      />
    )}
  </RiskDetailSection>
</RiskDashboard>

```

### 5.3 Layout System

### 5.3.1 Grid System

- **Base Grid**:
    - 12-column layout
    - Responsive breakpoints:
        - Mobile: < 640px
        - Tablet: 640px - 1024px
        - Desktop: 1024px - 1440px
        - Large Desktop: > 1440px
    - Column gap: 16px (desktop), 8px (mobile)
    - Outer margin: 24px (desktop), 16px (mobile)
- **Container Widths**:
    - Default: 100% with max-width of 1440px
    - Narrow: 100% with max-width of 960px
    - Wide: 100% with max-width of 1920px
- **Responsive Behavior**:
    - Mobile: Single column stacked layout
    - Tablet: 6-column grid
    - Desktop: 12-column grid
    - Component-specific breakpoint adjustments

```jsx
// Grid System Example
<Container>
  <Row>
    <Col span={12} md={6} lg={3}>
      <Card>First card</Card>
    </Col>
    <Col span={12} md={6} lg={3}>
      <Card>Second card</Card>
    </Col>
    <Col span={12} md={6} lg={3}>
      <Card>Third card</Card>
    </Col>
    <Col span={12} md={6} lg={3}>
      <Card>Fourth card</Card>
    </Col>
  </Row>
</Container>

```

### 5.3.2 Spacing System

- **Spacing Scale**:
    - Base unit: 4px
    - Scale: 0, 4px, 8px, 12px, 16px, 24px, 32px, 48px, 64px, 96px, 128px
    - Named tokens: none, xs, sm, md, lg, xl, 2xl, 3xl, 4xl, 5xl, 6xl
- **Application**:
    - Margin: External spacing between components
    - Padding: Internal spacing within components
    - Gap: Spacing between items in a flex or grid container
- **Consistency Rules**:
    - Vertical rhythm: Consistent spacing between similar elements
    - Nesting: Smaller spacing for nested elements
    - Responsive adjustments: Reduced spacing on smaller screens

```css
/* CSS Implementation of Spacing System */
:root {
  --space-0: 0;
  --space-xs: 4px;
  --space-sm: 8px;
  --space-md: 12px;
  --space-lg: 16px;
  --space-xl: 24px;
  --space-2xl: 32px;
  --space-3xl: 48px;
  --space-4xl: 64px;
  --space-5xl: 96px;
  --space-6xl: 128px;
}

/* Responsive spacing example */
@media (max-width: 640px) {
  :root {
    --space-xl: 16px;
    --space-2xl: 24px;
    --space-3xl: 32px;
    --space-4xl: 48px;
    --space-5xl: 64px;
    --space-6xl: 96px;
  }
}

```

### 5.3.3 Page Templates

- **Dashboard Layout**:
    - Top navigation bar
    - Optional side navigation
    - Main content area with dashboard grid
    - Responsive adjustments for different devices
- **Analysis Detail Layout**:
    - Top navigation bar
    - Breadcrumb navigation
    - Two-column layout (70/30 split)
    - Main content with tabbed sections
    - Right sidebar with related information
- **Document Management Layout**:
    - Top navigation
    - Left sidebar for folders/filters (collapsible)
    - Main content with document grid or list
    - Preview panel (optional)
- **Workflow Layout**:
    - Top navigation
    - Progress indicator/steps
    - Form-centric main content
    - Action buttons (bottom or sidebar)

```jsx
// Dashboard Layout Example
<DashboardLayout>
  <TopNavigation />

  <SideNavigation />

  <MainContent>
    <PageHeader title="Financial Due Diligence Dashboard" />

    <DashboardGrid>
      {/* Dashboard widgets */}
    </DashboardGrid>
  </MainContent>
</DashboardLayout>

// Analysis Detail Layout Example
<AnalysisDetailLayout>
  <TopNavigation />

  <Breadcrumbs items={breadcrumbItems} />

  <TwoColumnLayout>
    <MainContent>
      <PageHeader title="Financial Performance Analysis" />

      <Tabs>
        <TabPanel label="Overview">
          {/* Overview content */}
        </TabPanel>
        <TabPanel label="Detailed Analysis">
          {/* Detailed analysis content */}
        </TabPanel>
        <TabPanel label="Recommendations">
          {/* Recommendations content */}
        </TabPanel>
      </Tabs>
    </MainContent>

    <Sidebar>
      <MetricsSummary />
      <RelatedDocuments />
      <AnalysisHistory />
    </Sidebar>
  </TwoColumnLayout>
</AnalysisDetailLayout>

```

## 6. INTERACTION PATTERNS

### 6.1 State Feedback

### 6.1.1 Loading States

- **Skeleton Loaders**:
    - Component-shaped placeholders
    - Subtle animation (pulse or wave)
    - Maintains layout during loading
    - Used for content loading over 300ms
- **Spinners**:
    - Circular animation in brand colors
    - Used for shorter operations or button feedback
    - Sizes: small (16px), default (24px), large (32px)
    - Optional text label for context
- **Progress Indicators**:
    - Linear progress for known duration operations
    - Percentage complete indicator where applicable
    - Step indicators for multi-stage processes

```jsx
// Loading State Examples
<Card>
  <SkeletonLoader type="text" lines={3} />
  <SkeletonLoader type="chart" height={200} />
</Card>

<Button variant="primary" loading>
  Upload Documents
</Button>

<ProgressBar
  value={75}
  label="Processing documents..."
/>

<StepIndicator
  steps={["Upload", "Process", "Review", "Approve"]}
  currentStep={2}
/>

```

### 6.1.2 Empty States

- **Empty Content**:
    - Friendly illustration
    - Clear, concise messaging
    - Action button for resolution
    - Contextual help or suggestions
- **Zero Results**:
    - Distinction from empty content
    - Search refinement suggestions
    - Alternative actions
    - Clear way to reset filters

```jsx
// Empty State Examples
<EmptyState
  illustration="documents"
  title="No documents yet"
  description="Upload documents to begin the due diligence process."
  action={<Button variant="primary">Upload Documents</Button>}
/>

<ZeroResults
  searchTerm="financial statements 2025"
  suggestions={[
    "Check the date range",
    "Try broader search terms",
    "Verify document categories"
  ]}
  action={<Button variant="secondary">Clear Filters</Button>}
/>

```

### 6.1.3 Error States

- **Form Validation**:
    - Inline error messages
    - Red text below input field
    - Icon indicator
    - Field highlighting
    - Accessibility considerations (aria-invalid, error messaging)
- **System Errors**:
    - Modal or inline error messages
    - Clear problem description
    - Suggested resolution steps
    - Contact information for support
    - Error codes for reference
- **Network Errors**:
    - Offline indicator
    - Retry mechanisms
    - Local data persistence where possible
    - Recovery instructions

```jsx
// Error State Examples
<Input
  label="Revenue Projection"
  value="-50000"
  error="Value must be positive"
  aria-invalid={true}
/>

<SystemError
  title="Unable to process document"
  message="The system encountered an error while processing your document. This may be due to an unsupported format."
  actions={[
    <Button variant="primary">Try Again</Button>,
    <Button variant="secondary">Contact Support</Button>
  ]}
  errorCode="DOC-3542"
/>

<OfflineNotice
  message="You're currently offline"
  subtext="Changes will be saved locally and synchronized when connection is restored."
/>

```

### 6.2 User Workflows

### 6.2.1 Document Upload & Processing

- **Upload Interaction**:
    - Drag-and-drop zone
    - File browser button
    - Progress indication
    - File validation feedback
    - Batch upload support
- **Processing Feedback**:
    - Step indication for multi-stage processing
    - Time estimates where possible
    - Preview generation
    - Error handling with retry options
- **Post-Upload Actions**:
    - Quick categorization
    - Tagging interface
    - Basic metadata entry
    - Related document linkage

```jsx
// Document Upload Workflow Example
<DocumentUpload>
  <UploadZone
    accept=".pdf,.docx,.xlsx,.pptx"
    maxSize={50}
    multiple={true}
    onDrop={handleFileDrop}
  >
    <UploadIcon />
    <UploadText>Drag files here or click to browse</UploadText>
    <UploadSubtext>Supports PDF, Word, Excel, and PowerPoint files up to 50MB</UploadSubtext>
  </UploadZone>

  <UploadQueue>
    {files.map(file => (
      <FileItem
        key={file.id}
        filename={file.name}
        size={file.size}
        progress={file.progress}
        status={file.status}
        error={file.error}
        onRemove={() => removeFile(file.id)}
        onRetry={() => retryUpload(file.id)}
      />
    ))}
  </UploadQueue>

  <ProcessingStatus
    totalFiles={files.length}
    processedFiles={processedCount}
    currentStage={processingStage}
    timeRemaining={timeEstimate}
  />
</DocumentUpload>

```

### 6.2.2 Analysis Workflow

- **Analysis Setup**:
    - Configuration wizard
    - Parameter selection
    - Template-based starting points
    - Scope definition
- **Analysis Execution**:
    - Progress indication
    - Preliminary results preview
    - Cancellation option
    - Resource utilization feedback
- **Results Review**:
    - Summary visualization
    - Drill-down capability
    - Export/share options
    - Action recommendations

```jsx
// Analysis Workflow Example
<AnalysisWorkflow>
  <AnalysisSetup>
    <StepIndicator
      steps={["Configure", "Review", "Execute", "Results"]}
      currentStep={0}
    />

    <TemplateSelector
      templates={analysisTemplates}
      onSelect={selectTemplate}
      selectedId={selectedTemplate?.id}
    />

    <ParameterConfig
      parameters={currentParameters}
      onChange={updateParameter}
      validation={parameterValidation}
    />

    <NavigationButtons
      onBack={() => {}}
      onNext={() => nextStep()}
      nextDisabled={!isConfigValid}
    />
  </AnalysisSetup>

  {/* Additional workflow steps would follow */}
</AnalysisWorkflow>

```

### 6.2.3 Collaborative Review

- **Comment System**:
    - Comment threading
    - Mentions (@username)
    - Rich text formatting
    - Attachment support
    - Resolution workflow
- **Review Assignments**:
    - Task assignment interface
    - Due date selection
    - Priority indication
    - Status tracking
- **Approval Process**:
    - Multi-level approval chains
    - Approval/rejection with comments
    - Audit trail
    - Notification system

```jsx
// Collaborative Review Example
<ReviewWorkspace>
  <DocumentPreview document={currentDocument} />

  <CommentThread>
    <Comment
      author="Sarah Chen"
      timestamp="10:32 AM"
      content="The revenue projections seem optimistic given the market conditions."
      mentions={["@david"]}
    />

    <Comment
      author="David Kim"
      timestamp="10:45 AM"
      content="Good point. I've added a more conservative scenario in the latest version."
      replyTo="Sarah Chen"
    />

    <CommentComposer
      placeholder="Add a comment..."
      mentionSuggestions={teamMembers}
    />
  </CommentThread>

  <ApprovalFlow
    stages={[
      { name: "Financial Review", approver: "Sarah Chen", status: "approved" },
      { name: "Legal Review", approver: "Michael Johnson", status: "pending" },
      { name: "Executive Review", approver: "Jennifer Lee", status: "not started" }
    ]}
  />
</ReviewWorkspace>

```

### 6.3 Mobile & Responsive Patterns

### 6.3.1 Mobile Navigation

- **Bottom Navigation**:
    - 4-5 key destinations
    - Icon + label
    - Active state indication
    - Badge notifications where relevant
- **Drawer Navigation**:
    - Hamburger menu trigger
    - Full navigation tree
    - User profile access
    - Settings access
- **Page Navigation**:
    - Back button
    - Page title
    - Action buttons
    - Overflow menu for additional actions

```jsx
// Mobile Navigation Examples
<MobileLayout>
  <TopBar>
    <BackButton />
    <PageTitle>Financial Analysis</PageTitle>
    <ActionButton icon="share" />
    <OverflowMenu items={additionalActions} />
  </TopBar>

  <MainContent>
    {/* Page content */}
  </MainContent>

  <BottomNav>
    <NavItem icon="dashboard" label="Dashboard" active />
    <NavItem icon="documents" label="Documents" />
    <NavItem icon="analytics" label="Analysis" />
    <NavItem icon="profile" label="Profile" />
  </BottomNav>
</MobileLayout>

```

### 6.3.2 Responsive Content

- **Card Stacking**:
    - Multi-column to single-column transition
    - Priority-based reordering
    - Content adaptation (truncation, summarization)
    - Touch-optimized controls
- **Table Adaptations**:
    - Horizontal scrolling for wide tables
    - Column priority (hide less important columns)
    - Card view transformation
    - Expandable rows for details
- **Form Adjustments**:
    - Full-width inputs
    - Larger touch targets
    - Input-specific keyboards
    - Progressive disclosure

```jsx
// Responsive Content Examples
<ResponsiveCard adaptiveHeight stackOnMobile>
  <CardHeader responsiveBehavior="sticky" />
  <CardContent
    maxLinesOnMobile={3}
    showMoreOption={true}
  />
  <CardActions stackOnMobile />
</ResponsiveCard>

<ResponsiveTable>
  <ResponsiveColumn priority="high">Company</ResponsiveColumn>
  <ResponsiveColumn priority="high">Revenue</ResponsiveColumn>
  <ResponsiveColumn priority="medium">Growth</ResponsiveColumn>
  <ResponsiveColumn priority="low">Employees</ResponsiveColumn>
  <ResponsiveColumn priority="low">Founded</ResponsiveColumn>
  <CardViewFallback template={companyCardTemplate} />
</ResponsiveTable>

```

### 6.3.3 Touch Interaction

- **Touch Targets**:
    - Minimum 44px × 44px
    - Adequate spacing between targets
    - Visual feedback on touch
    - Accessibility considerations
- **Gestures**:
    - Swipe actions for common operations
    - Pinch to zoom for documents and images
    - Pull to refresh for content updates
    - Long press for contextual menus
- **Input Optimization**:
    - Simplified forms for mobile
    - Input masks for formatted data
    - Autocomplete suggestions
    - Specialized input controls (date pickers, etc.)

```jsx
// Touch Interaction Examples
<SwipeableList>
  <SwipeableItem
    leftActions={[
      { icon: "archive", color: "blue", onAction: archiveItem }
    ]}
    rightActions={[
      { icon: "delete", color: "red", onAction: deleteItem }
    ]}
  >
    <ListItemContent />
  </SwipeableItem>
</SwipeableList>

<TouchFriendlyForm>
  <DatePickerField
    label="Report Date"
    value={reportDate}
    onChange={setReportDate}
    touchOptimized
  />

  <CurrencyInput
    label="Revenue"
    value={revenue}
    onChange={setRevenue}
    keyboardType="numeric"
    formatWhileTyping
  />
</TouchFriendlyForm>

```

## 7. ACCESSIBILITY GUIDELINES

### 7.1 Core Principles

### 7.1.1 Perceivable

- **Color Contrast**:
    - Text: WCAG AA minimum (4.5:1 for normal text, 3:1 for large text)
    - UI Components: 3:1 contrast ratio against adjacent colors
    - Color contrast testing for all component states
- **Text Legibility**:
    - Minimum text size: 14px for body text
    - Line height: Minimum 1.5 for body text
    - Adjustable text size without breaking layouts
    - Avoidance of justified text
- **Alternative Text**:
    - All images have appropriate alt text
    - Complex charts include text descriptions
    - Icons with decorative icons have empty alt attributes
    - Functional icons include descriptive text

### 7.1.2 Operable

- **Keyboard Navigation**:
    - All interactive elements are keyboard accessible
    - Logical tab order follows visual layout
    - Focus indicators are clearly visible
    - No keyboard traps
- **Timing**:
    - Adjustable timing for time-sensitive content
    - No sudden, unexpected changes
    - Session timeout warnings with extension options
    - Auto-save for form data
- **Navigation**:
    - Clear page titles
    - Descriptive link text (no "click here" or "read more")
    - Multiple ways to access content
    - Skip-to-content links

### 7.1.3 Understandable

- **Consistent Interface**:
    - Consistent navigation placement
    - Consistent component behavior
    - Predictable interactive patterns
    - Standard iconography
- **Error Prevention**:
    - Clear error messages
    - Validation before submission
    - Confirmation for irreversible actions
    - Undo functionality where possible
- **Input Assistance**:
    - Clear labels for all form fields
    - Helpful instructions and examples
    - Format requirements communicated up front
    - Autocomplete attributes

### 7.1.4 Robust

- **Standards Compliance**:
    - Valid HTML
    - ARIA roles and attributes used correctly
    - Semantic HTML elements
    - Device and browser compatibility
- **Assistive Technology**:
    - Screen reader compatibility
    - Support for text-to-speech
    - Support for screen magnification
    - Compatibility with input devices

### 7.2 Implementation Guidelines

### 7.2.1 Component-Specific Guidelines

- **Buttons and Links**:
    - Distinct visual styles between buttons and links
    - Focus states clearly visible
    - Descriptive text or aria-label
    - Appropriate use of button vs. link
- **Forms**:
    - Labels for all form controls
    - Error messages linked to inputs
    - Grouped controls with fieldsets and legends
    - Required fields clearly marked
- **Tables**:
    - Proper table markup (th, caption, etc.)
    - Row and column headers
    - Scope attributes
    - Table summaries for complex tables
- **Modals and Dialogs**:
    - Focus management (trap focus within dialog)
    - Proper ARIA roles (dialog, alertdialog)
    - Close mechanisms (button, escape key)
    - Return focus on close

```jsx
// Accessible Component Examples
<Button
  variant="primary"
  aria-label="Create new project"
>
  <Icon name="add" />
  New Project
</Button>

<FormField>
  <Label htmlFor="revenue">Annual Revenue</Label>
  <Input
    id="revenue"
    type="text"
    aria-describedby="revenue-help"
    required
  />
  <HelperText id="revenue-help">
    Enter the annual revenue in USD
  </HelperText>
  {error && (
    <ErrorMessage id="revenue-error" role="alert">
      {error}
    </ErrorMessage>
  )}
</FormField>

<Table aria-label="Financial Performance by Quarter">
  <Caption>Quarterly Revenue and Growth (2024-2025)</Caption>
  <TableHeader>
    <TableRow>
      <TableHeaderCell scope="col">Quarter</TableHeaderCell>
      <TableHeaderCell scope="col">Revenue (USD)</TableHeaderCell>
      <TableHeaderCell scope="col">YoY Growth (%)</TableHeaderCell>
    </TableRow>
  </TableHeader>
  <TableBody>
    {/* Table rows */}
  </TableBody>
</Table>

```

### 7.2.2 Testing and Validation

- **Automated Testing**:
    - Accessibility linting in development
    - Integration with CI/CD pipeline
    - Regular automated scans
- **Manual Testing**:
    - Keyboard-only navigation testing
    - Screen reader testing
    - Color contrast verification
    - Zoom testing (up to 200%)
- **User Testing**:
    - Testing with users with disabilities
    - Testing with various assistive technologies
    - Collection and incorporation of feedback

## 8. IMPLEMENTATION RESOURCES

### 8.1 Design Assets

### 8.1.1 Component Library

- **Figma Component Library**:
    - Complete component set
    - Variants and states
    - Responsive variants
    - Design tokens
- **Icon Library**:
    - SVG icon set
    - Multiple sizes
    - Categories and search tags
    - Export options
- **Illustration Library**:
    - Core illustrations
    - Empty state visuals
    - Process diagrams
    - Thematic variations

### 8.1.2 Design Templates

- **Page Templates**:
    - Dashboard templates
    - Analysis view templates
    - Document management templates
    - Settings page templates
- **Common Flows**:
    - Onboarding sequence
    - Document upload flow
    - Analysis setup flow
    - Collaborative review flow

### 8.1.3 Design Token Files

- **Format Support**:
    - CSS Variables
    - SCSS Variables
    - JavaScript Objects
    - Design Token JSON (Style Dictionary compatible)
    - Tailwind Config

```jsx
// Example Design Token Export (JavaScript)
export const tokens = {
  colors: {
    navy: {
      900: "#0A2342",
      800: "#0E2E5C",
      700: "#123976",
      600: "#164390",
      500: "#1A4EAA",
      400: "#3B69BA",
      300: "#5C84CA",
      200: "#7D9FDA",
      100: "#9EBBEA",
      50: "#BFD6FA"
    },
    // Other color scales...
  },
  spacing: {
    0: "0",
    xs: "4px",
    sm: "8px",
    // Other spacing values...
  },
  // Other token categories...
};

```

### 8.2 Development Guidelines

### 8.2.1 Component Implementation

- **Accessibility Requirements**:
    - Required ARIA attributes
    - Keyboard interaction patterns
    - Focus management
    - Screen reader considerations
- **Responsive Behavior**:
    - Breakpoint-specific adjustments
    - Touch accommodations
    - Content adaptation rules
    - Testing requirements
- **State Management**:
    - Required states (hover, focus, active, disabled)
    - State transition guidelines
    - Loading/error state implementations
    - Animation guidelines

### 8.2.2 Code Examples

- **React Component Structure**:
    - Composition patterns
    - Prop interface definitions
    - Default props
    - Accessibility implementations
- **CSS Implementation**:
    - BEM naming conventions
    - CSS-in-JS patterns
    - Tailwind utility usage
    - Custom property integration
- **Performance Considerations**:
    - Code splitting recommendations
    - Lazy loading patterns
    - Render optimization
    - Bundle size management

### 8.3 Governance and Contribution

### 8.3.1 Design System Team

- **Team Structure**:
    - Design system owners
    - Core contributors
    - Subject matter experts
    - Contact information
- **Support Channels**:
    - Design system documentation
    - Internal chat channel
    - Issue tracking
    - Office hours

### 8.3.2 Contribution Process

- **Design Contributions**:
    - Proposal template
    - Design review process
    - User testing requirements
    - Acceptance criteria
- **Development Contributions**:
    - Code contribution guidelines
    - Pull request template
    - Testing requirements
    - Documentation requirements

### 8.3.3 Versioning and Updates

- **Versioning Strategy**:
    - Semantic versioning
    - Deprecation policy
    - Breaking change guidelines
- **Release Communication**:
    - Release notes
    - Migration guides
    - Showcase of new components
    - Deprecation notices
- **Feedback Loops**:
    - User feedback collection
    - Usage analytics
    - Performance monitoring
    - Accessibility audits

## 9. MOTION & ANIMATION

### 9.1 Motion Principles

### 9.1.1 Animation Philosophy

- **Purpose-Driven**: Animation serves functional purposes, not merely decorative
- **Subtle & Efficient**: Animations are subtle and quick, respecting user focus
- **Informative**: Motion provides feedback and guides attention
- **Consistent**: Similar actions share similar motion patterns
- **Performance-Oriented**: Animations optimize for smooth performance

### 9.1.2 Animation Timing

- **Duration Scale**:
    - Extra Fast: 100ms (micro-interactions, button states)
    - Fast: 150ms (dropdown reveals, focus states)
    - Medium: 300ms (panel transitions, modal displays)
    - Slow: 450ms (page transitions, complex animations)
    - Extra Slow: 600ms (onboarding sequences, celebrations)
- **Easing Curves**:
    - Standard: Cubic-bezier(0.4, 0.0, 0.2, 1) - Most UI transitions
    - Entrance: Cubic-bezier(0.0, 0.0, 0.2, 1) - Elements entering the screen
    - Exit: Cubic-bezier(0.4, 0.0, 1, 1) - Elements exiting the screen
    - Emphasis: Cubic-bezier(0.2, 0.6, 0.4, 1) - Attention-drawing animations

```css
/* CSS Animation Variables */
:root {
  /* Duration */
  --duration-xs: 100ms;
  --duration-sm: 150ms;
  --duration-md: 300ms;
  --duration-lg: 450ms;
  --duration-xl: 600ms;

  /* Easing Curves */
  --ease-standard: cubic-bezier(0.4, 0.0, 0.2, 1);
  --ease-entrance: cubic-bezier(0.0, 0.0, 0.2, 1);
  --ease-exit: cubic-bezier(0.4, 0.0, 1, 1);
  --ease-emphasis: cubic-bezier(0.2, 0.6, 0.4, 1);
}

```

### 9.2 Animation Types

### 9.2.1 Micro-Interactions

- **Button States**:
    - Hover: Subtle background lightening (100ms)
    - Active: Quick scale down to 95% (100ms)
    - Focus: Border highlight with subtle glow (150ms)
- **Form Controls**:
    - Input Focus: Border transition and subtle background shift (150ms)
    - Checkbox/Toggle: Smooth state transition with position and color change (150ms)
    - Dropdown Select: Chevron rotation and menu reveal (200ms)
- **Interactive Elements**:
    - Card Hover: Subtle elevation increase with shadow enhancement (200ms)
    - Link Hover: Text color transition and subtle underline animation (100ms)
    - Icon Buttons: Rotation or color transitions for state changes (150ms)

```jsx
// Button Animation Example
const buttonStyles = css`
  transition:
    background-color var(--duration-xs) var(--ease-standard),
    transform var(--duration-xs) var(--ease-standard),
    box-shadow var(--duration-sm) var(--ease-standard);

  &:hover {
    background-color: var(--color-azure-400);
  }

  &:active {
    transform: scale(0.98);
  }

  &:focus {
    box-shadow: 0 0 0 2px var(--color-azure-200);
  }
`;

```

### 9.2.2 Functional Animations

- **Loading Indicators**:
    - Spinner: Continuous rotation animation (1.2s per rotation)
    - Progress Bar: Smooth fill animation at calculated speed
    - Skeleton Loaders: Subtle pulse effect (2s cycle)
- **Transitions**:
    - Page Transitions: Fade combined with slight vertical movement (300ms)
    - Tab Switches: Content crossfade with indicator movement (200ms)
    - Modal Dialog: Background dim with modal scale/fade in (300ms)
- **Data Visualization**:
    - Chart Loading: Progressive reveal of data points (500ms staggered)
    - Value Changes: Number transitions with counting animation (600ms)
    - Selection Highlighting: Quick highlight pulse (200ms)

```jsx
// Page Transition Example
const pageTransition = {
  initial: { opacity: 0, y: 10 },
  animate: { opacity: 1, y: 0 },
  exit: { opacity: 0, y: -10 },
  transition: {
    duration: 0.3,
    ease: [0.4, 0.0, 0.2, 1]
  }
};

// Usage with Framer Motion
<motion.div
  initial="initial"
  animate="animate"
  exit="exit"
  variants={pageTransition}
>
  {pageContent}
</motion.div>

```

### 9.2.3 Expressive Animations

- **Onboarding**:
    - Feature Introductions: Sequential element reveals (600ms per element)
    - Celebration Moments: More dynamic animations for achievements (800ms)
    - Progress Milestones: Visual rewards for completing major steps (600ms)
- **Status Changes**:
    - Success: Check mark animation with green highlight (450ms)
    - Error: Subtle shake animation with red highlight (300ms)
    - Warning: Pulsing yellow highlight (450ms)
- **Data Updates**:
    - New Data Arrival: Subtle highlight and fade (300ms)
    - Significant Changes: Attention-drawing pulse for important metrics (450ms)
    - Threshold Crossing: Visual indicator when values cross predefined thresholds (400ms)

```jsx
// Success Animation Example
<StatusChange status="success">
  <motion.div
    animate={{
      scale: [1, 1.1, 1],
      backgroundColor: ['transparent', 'rgba(0, 191, 165, 0.1)', 'transparent']
    }}
    transition={{
      duration: 0.45,
      ease: "easeOut"
    }}
  >
    <SuccessIcon />
    <span>Document processed successfully</span>
  </motion.div>
</StatusChange>

```

### 9.3 Implementation Guidelines

### 9.3.1 Performance Considerations

- **Optimization Techniques**:
    - Animate only transform and opacity properties when possible
    - Use will-change for complex animations
    - Implement throttling for frequent updates
    - Consider reduced motion settings
- **Animation Budgets**:
    - Limit concurrent animations, especially on mobile devices
    - Simplify animations for lower-end devices
    - Consider skeleton loaders for content over 300ms load time
    - Progressive enhancement approach

### 9.3.2 Accessibility Considerations

- **Respecting User Preferences**:
    - Honor prefers-reduced-motion setting
    - Provide alternative static states
    - Never rely solely on animation to convey information
    - Avoid animations that could trigger vestibular disorders
- **Implementation Example**:

```css
/* Respecting reduced motion preferences */
@media (prefers-reduced-motion: reduce) {
  * {
    animation-duration: 0.01ms !important;
    animation-iteration-count: 1 !important;
    transition-duration: 0.01ms !important;
    scroll-behavior: auto !important;
  }

  .animate-entrance {
    opacity: 1 !important;
    transform: none !important;
  }
}

```

### 9.3.3 Motion Library

- **Recommended Tools**:
    - Framer Motion for React components
    - GSAP for complex animations
    - CSS Transitions for simple state changes
    - Lottie for complex illustrative animations
- **Animation Composition**:
    - Staggered animations for related elements
    - Choreographed sequences for multi-step processes
    - Contextual animation based on user actions
    - Shared element transitions for related views

## 10. VOICE & TONE

### 10.1 Content Principles

### 10.1.1 Brand Voice

- **Professional**: Conveys expertise and reliability
- **Clear**: Straightforward, jargon-free when possible
- **Confident**: Authoritative without being arrogant
- **Helpful**: Supportive and solution-oriented
- **Precise**: Accurate and specific, especially with financial terms

### 10.1.2 Writing Guidelines

- **Clarity First**: Prioritize clear communication over cleverness
- **Conciseness**: Use direct language, avoid unnecessary words
- **Active Voice**: Prefer active voice for instructions and actions
- **Technical Accuracy**: Ensure precise use of financial and legal terminology
- **Scannable Content**: Use headers, bullets, and short paragraphs

### 10.1.3 Terminology Management

- **Glossary**: Consistent definitions for financial and technical terms
- **Industry-Specific Terms**: Clear explanations for specialized jargon
- **Product Terminology**: Consistent naming for features and actions
- **Abbreviations**: Define on first use with consistent formatting

### 10.2 Content Applications

### 10.2.1 UI Text Patterns

- **Button Labels**:
    - Action-oriented verbs (Create, Analyze, Generate)
    - Concise, typically 1-3 words
    - Consistent across similar actions
    - Clear about the result of the action
- **Form Labels & Help Text**:
    - Descriptive field labels
    - Concise placeholder text (not instructions)
    - Help text for complex inputs
    - Clear validation messages
- **Navigation Labels**:
    - Nouns or short phrases for destinations
    - Consistent capitalization (sentence case)
    - Distinct, non-overlapping terms
    - Avoid unclear abbreviations

### 10.2.2 System Messages

- **Success Messages**:
    - Confirm the completed action
    - Positive, affirming tone
    - Next steps when applicable
    - Example: "Analysis complete. 23 documents processed successfully."
- **Error Messages**:
    - Clear explanation of the issue
    - Constructive guidance for resolution
    - Non-technical language when possible
    - Example: "Unable to process this document. The file format is not supported. Please upload a PDF, Word, or Excel file."
- **Warning Messages**:
    - Clear about potential consequences
    - Actionable guidance
    - Non-alarming but noticeable
    - Example: "This action will remove all annotations. You cannot undo this change."

### 10.2.3 Documentation Style

- **User Guides**:
    - Task-oriented structure
    - Step-by-step instructions
    - Visual aids with text alternatives
    - Consistent formatting for procedures
- **Technical Documentation**:
    - Structured hierarchy of information
    - Code examples where applicable
    - Parameter and return value documentation
    - Version compatibility notes

### 10.3 Content Examples

### 10.3.1 UI Text Examples

```
// Button Labels
"Upload Documents"
"Run Analysis"
"Generate Report"

// Form Labels
Label: "Annual Revenue"
Placeholder: "e.g., $1,500,000"
Help Text: "Enter the most recent annual revenue from audited financial statements."

// Error Messages
"Invalid date range. End date must be after start date."
"Connection lost. Check your internet connection and try again."
"Insufficient data for analysis. At least 3 years of financial history required."

```

### 10.3.2 Confirmation Dialogs

```
// Deletion Confirmation
Title: "Delete Financial Model"
Message: "Are you sure you want to delete this financial model? This action cannot be undone."
Buttons: "Cancel" / "Delete Model"

// Discard Changes
Title: "Unsaved Changes"
Message: "You have unsaved changes to this document. Do you want to save before leaving?"
Buttons: "Discard Changes" / "Save and Continue" / "Cancel"

```

### 10.3.3 Empty States

```
// Empty Document Library
Title: "No Documents Yet"
Message: "Upload documents to begin your due diligence process."
Action: "Upload Documents"

// No Search Results
Title: "No Results Found"
Message: "We couldn't find any documents matching your search criteria."
Suggestion: "Try using different keywords or adjusting your filters."

```

## 11. IMPLEMENTATION ROADMAP

### 11.1 Phased Approach

### 11.1.1 Phase 1: Foundation (Months 1-2)

- **Core Components**:
    - Typography system
    - Color system
    - Grid and layout system
    - Basic inputs and buttons
    - Card components
    - Navigation components
- **Design Token Architecture**:
    - Token definition and organization
    - Build pipeline for token distribution
    - Integration with development environment
- **Documentation Start**:
    - Design principles
    - Core component documentation
    - Usage guidelines

### 11.1.2 Phase 2: Specialized Components (Months 3-4)

- **Financial Components**:
    - Data tables
    - Financial charts and graphs
    - Metric displays
    - Form controls for financial data
- **Document Components**:
    - Document viewer
    - Annotation tools
    - Upload and processing interfaces
    - Document management UI
- **Expanded Documentation**:
    - Specialized component guidelines
    - Accessibility specifications
    - Interactive examples

### 11.1.3 Phase 3: Advanced Features (Months 5-6)

- **Complex Interactions**:
    - Drag and drop interfaces
    - Advanced filtering and search
    - Collaborative features
    - Analysis configuration interfaces
- **Animation System**:
    - Motion principles
    - Interaction animations
    - Loading states
    - Transition effects
- **Comprehensive Documentation**:
    - Pattern library
    - Full component API
    - Design tokens reference
    - Accessibility guidelines

### 11.2 Adoption Strategy

### 11.2.1 Migration Plan

- **Audit Existing UI**:
    - Component inventory
    - Design inconsistency documentation
    - Technical debt assessment
- **Implementation Priorities**:
    - High-visibility components first
    - Critical user flows
    - New features built with new system
    - Gradual replacement of legacy components
- **Team Support**:
    - Design system workshops
    - Office hours for implementation questions
    - Code reviews for design system adoption
    - Design reviews for consistency

### 11.2.2 Measuring Success

- **Adoption Metrics**:
    - Percentage of UI using design system
    - Component usage statistics
    - Design token implementation coverage
    - Design debt reduction
- **Quality Metrics**:
    - User feedback on consistency
    - Accessibility compliance scores
    - Development velocity improvements
    - Design handoff efficiency

This comprehensive design system establishes a solid foundation for creating a cohesive, accessible, and professional due diligence AI platform. By following these guidelines, the product will maintain visual and functional consistency while delivering an efficient user experience tailored to the specific needs of financial professionals conducting due diligence.