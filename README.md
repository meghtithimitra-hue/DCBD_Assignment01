# DCBD_Assignment01
DCBD Assignment: Analyzing Publication Metadata via RPC


## Author

**Name:** Meghthithi Mitra
**Roll Number:** MDS202520

---

## Project Description

This project analyzes publication metadata using RPC-based processing.
The objective is to extract and identify the **top 10 first words** from publication titles and verify the results.

---

## Technologies Used

* Python 3.11-slim
* Docker
* GitHub Codespaces

---

## Project Structure

```
.
├── Dockerfile
├── requirements.txt
├── run.py
├── README.md
```

---

## How to Run (Codespaces)

1. Open the repository in GitHub Codespaces
2. Open terminal
3. Run:

```bash
python run.py
```

Or run using Docker container :
``` bash
docker build -t myapp .
docker run myapp
```

---

## Expected Output

```
Verification Result:
{'correct': True, 'message': 'Congratulations! You found all top 10 first words.', 'score': 10, 'total': 10}
```

---

## Docker Instructions

### Build Docker Image

```bash
docker build -t myapp .
```

### Run Docker Container

```bash
docker run myapp
```

---

## 📸 Output Screenshot

The output of the program is visible in the Codespaces terminal as required.

---

## 👥 Collaborators

* [ramaseshan.dcbd@gmail.com](mailto:ramaseshan.dcbd@gmail.com)
* [vardhan.vkr@gmail.com](mailto:vardhan.vkr@gmail.com)
* [mohit.sinsniwal@gmail.com](mailto:mohit.sinsniwal@gmail.com)

---

## 📦 Submission Details

* Docker image exported as `.tar` file (submitted separately, not included in GitHub repository)
* Source code uploaded to GitHub
* Codespaces execution verified
* Screenshot included

---

## 🎯 Result

✔ Successfully executed with **score: 10/10**

---
