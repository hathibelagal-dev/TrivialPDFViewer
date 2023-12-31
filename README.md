# TrivialPDFViewer

This is a very simple PDF viewer created using the [PDF.js](https://github.com/mozilla/pdf.js/) library and viewer. In addition to loading and rendering a page from a PDF, this code clearly shows how to use the new `PDFLinkService` and `AnnotationLayer` classes to add annotations(such as clickable links) to your page.

The entire code is in one HTML document for easy readability. Feel free to create issues and PRs if you want to extend the scope/functionality of this little PDF viewer.

Accepts two optional parameters through the query string:

- **f** - Name of PDF file
- **n** - Page number to show

If these are not passed, it tries to show the first page of a file named **test.pdf**.

### Get Started

```bash
git clone https://github.com/hathibelagal-dev/TrivialPDFViewer.git
cd TrivialPDFViewer
```

### Start an HTTP server

Using **npx**
```bash
npx http-server -p 8000
```

or using **python3**
```bash
python3 -m http.server 8000
```

### Done

Now visit http://localhost:8000/ on any browser!

### Screenshot

Trivial PDF viewer running on Chrome

![Screenshot from 2023-06-22 14-22-17](https://github.com/hathibelagal-dev/TrivialPDFViewer/assets/42626106/94f3b98f-2ccc-4ed8-9fff-892b04144b7e)
