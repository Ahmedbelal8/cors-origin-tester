You can use a simple HTTP server to serve your frontend. If you have Python installed, navigate to the directory containing your index.html and run:

For Python 3:
python -m http.server 3000

For Python 2:
python -m SimpleHTTPServer 3000

Alternatively, you can use Node.js's http-server:
npx http-server -p 3000

Open your browser and go to http://localhost:3000. Click the "Test CORS" button.