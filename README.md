# TrivialPDFViewer

This is a very simple PDF viewer created using the [PDF.js](https://github.com/mozilla/pdf.js/) library and viewer. In addition to loading and rendering a page from a PDF, this code clearly shows how to use the new `PDFLinkService` and `AnnotationLayer` classes to add annotations(such as clickable links) to your page.

The entire code is in one HTML document for easy readability. Feel free to create issues and PRs if you want to extend the scope/functionality of this little PDF viewer.

### Get Started

```bash
https://github.com/hathibelagal-dev/TrivialPDFViewer.git
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
