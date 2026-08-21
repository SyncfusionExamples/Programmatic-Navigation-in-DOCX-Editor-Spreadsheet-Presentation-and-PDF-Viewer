# Programmatic Navigation in DOCX Editor, Spreadsheet Editor, Presentation, and PDF Viewer
 
This sample demonstrates programmatic search, highlighting, and navigation capabilities across Syncfusion DOCX Editor, Presentation, Spreadsheet Editor, and PDF Viewer using a React frontend and Python backend.

## Components Used

The application utilizes the following Syncfusion components:

- DOCX Editor
- PDF Viewer
- Spreadsheet Editor
- Presentation Viewer

---

## Word Document

### Requirement 1: Highlight and Navigate

This sample demonstrates how to identify multiple paragraphs in a document, highlight them dynamically, and navigate between them without modifying the original document.

### Features

- Highlight multiple paragraphs simultaneously.
- Display highlighted findings in a side panel.
- Navigate directly to highlighted content using bookmarks.
- Sequential navigation using the **Next Highlight** button.

---

### Requirement 2: Highlight and Link Text

This sample demonstrates how to create clickable highlighted text that navigates to another location within the same document.

### Features

- Custom context menu integration.
- Create hyperlinks using bookmarks.
- Highlight linked text for visual identification.
- Navigate instantly to bookmarked content.

---

## Presentation

### Requirement

Extract speaker notes from all slides and provide programmatic navigation to specific slides.

### Features

- Speaker notes extraction.
- PPTX to PDF conversion.
- Slide-to-note mapping.
- Direct slide navigation.
- Sequential navigation using **Next Highlight**.
- Optional **View Notes** mode.

---

## Spreadsheet

### Requirement

Search workbook content and navigate directly to matching cells.

### Features

- Workbook-wide search.
- Display all matching results.
- Show worksheet name and cell address.
- Navigate directly to selected cells.

---

## PDF Document

### Requirement

Highlight multiple passages and navigate between them without modifying the original PDF document.

### Features

- Search predefined content.
- Highlight all matching occurrences.
- Display search results in a side panel.
- Direct navigation to selected findings.
- Sequential navigation using **Next Highlight**.

---

# Running the Sample

## Server-Side Setup (Python Web Service)

### Navigate to the .NET Wrapper Project

```bash
cd .NET Standard Wrapper Library
```

### Build and Publish the .NET Standard Wrapper Library

```bash
dotnet build -c Release
dotnet publish -c Release
```

### Navigate to the Python Web Service

```bash
cd ../python-web-service
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Start the Python Service

```bash
python app.py

or

py app.py
```

Service URL:

```text
http://127.0.0.1:5000/
```

---

## Client-Side Setup

### Navigate to the React Application

```bash
cd frontend
```

### Install Dependencies

```bash
npm install
```

### Configure Service URLs

**Document Editor**

```typescript
serviceUrl = "http://127.0.0.1:5000/"
```

**Spreadsheet**

```typescript
openUrl = "http://127.0.0.1:5000/OpenExcel"
saveUrl = "http://127.0.0.1:5000/SaveExcel"
```

**Presentation**

```typescript
url = "http://127.0.0.1:5000/PPTLoadFile"
```

### Run the Application

```bash
npm run dev
```

Open the application using the URL displayed in the terminal.

---

## Screenshots

### Word Documents

<p align="center"> 
<img src="Images/Word-Document-Demo.png" alt="Word Document Demo page"/> 
</p>

### Presentation Viewer

<p align="center"> 
<img src="Images/Presentation-Demo.png" alt="Presentation Demo page"/> 
</p>

### Spreadsheet Viewer
<p align="center"> 
<img src="Images/Spreadsheet-Demo.png" alt="Spreadsheet Demo page"/> 
</p>

### PDF Viewer

<p align="center"> 
<img src="Images/Pdf-Viewer-Demo.png" alt="PDF Viewer Demo page"/> 
</p>

# License 

This is a commercial product and requires a paid license for possession or use. Syncfusion's licensed software, including this component, is subject to the terms and conditions of [Syncfusion's EULA](https://www.syncfusion.com/license/studio/22.2.5/syncfusion_essential_studio_eula.pdf?utm_source=github&utm_medium=listing&utm_campaign=github-react-docx-editor-examples). You can purchase a license [here](https://www.syncfusion.com/sales/products?utm_source=github&utm_medium=listing&utm_campaign=github-react-docx-editor-examples) or start a free 30\-day trial [here](https://www.syncfusion.com/account/manage-trials/start-trials?utm_source=github&utm_medium=listing&utm_campaign=github-react-docx-editor-examples).

# About Syncfusion&reg;

Founded in 2001 and headquartered in Research Triangle Park, N.C., Syncfusion&reg; has more than 29,000 customers and more than 1 million users, including large financial institutions, Fortune 500 companies, and global IT consultancies.

Today, we provide 1700+ components and frameworks for web ([Blazor](https://www.syncfusion.com/blazor-components?utm_source=github&utm_medium=listing&utm_campaign=github-react-docx-editor-examples), [ASP.NET Core](https://www.syncfusion.com/aspnet-core-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=github-react-docx-editor-examples), [ASP.NET MVC](https://www.syncfusion.com/aspnet-mvc-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=github-react-docx-editor-examples), [ASP.NET WebForms](https://www.syncfusion.com/jquery/aspnet-webforms-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=github-react-docx-editor-examples), [JavaScript](https://www.syncfusion.com/javascript-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=github-react-docx-editor-examples), [Angular](https://www.syncfusion.com/angular-ui-components?utm_source=github&utm_medium=listing&utm_campaign=github-react-docx-editor-examples), [React](https://www.syncfusion.com/react-ui-components?utm_source=github&utm_medium=listing&utm_campaign=github-react-docx-editor-examples), [Vue](https://www.syncfusion.com/vue-ui-components?utm_source=github&utm_medium=listing&utm_campaign=github-react-docx-editor-examples), and [Flutter](https://www.syncfusion.com/flutter-widgets?utm_source=github&utm_medium=listing&utm_campaign=github-react-docx-editor-examples)), mobile ([Xamarin](https://www.syncfusion.com/xamarin-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=github-react-docx-editor-examples), [Flutter](https://www.syncfusion.com/flutter-widgets?utm_source=github&utm_medium=listing&utm_campaign=github-react-docx-editor-examples), [UWP](https://www.syncfusion.com/uwp-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=github-react-docx-editor-examples), and [JavaScript](https://www.syncfusion.com/javascript-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=github-react-docx-editor-examples), [.NET MAUI](https://www.syncfusion.com/maui-controls?utm_source=github&utm_medium=listing&utm_campaign=github-react-docx-editor-examples)) and desktop development ([WinForms](https://www.syncfusion.com/winforms-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=github-react-docx-editor-examples), [WPF](https://www.syncfusion.com/wpf-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=github-react-docx-editor-examples), [WinUI](https://www.syncfusion.com/winui-controls?utm_source=github&utm_medium=listing&utm_campaign=github-react-docx-editor-examples), [Flutter](https://www.syncfusion.com/flutter-widgets?utm_source=github&utm_medium=listing&utm_campaign=github-react-docx-editor-examples), [UWP](https://www.syncfusion.com/uwp-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=github-react-docx-editor-examples), and [.NET MAUI](https://www.syncfusion.com/maui-controls?utm_source=github&utm_medium=listing&utm_campaign=github-react-docx-editor-examples)) a. We provide ready-to-deploy enterprise software for dashboards, reports, data integration, and big data processing. Many customers have saved millions in licensing fees by deploying our software.
