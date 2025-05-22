## Read nImages and Convert to Text using PHP
BASIC CODE ON HOW TO USE TESSERACT OCR IN PHP

DOCKERIZE By GROUP 9
NOTE: INSTALL Docker Desktop

# Step 1: Clone the repo
git clone https://github.com/yourusername/Test_OCR.git
cd Test_OCR

# Step 2: Build the Docker image
docker build -t test_ocr .

# Step 3: Run the container and expose port
docker run -d -p 8080:80 test_ocr

# Step 4: Visit it in the browser
http://localhost:8080
