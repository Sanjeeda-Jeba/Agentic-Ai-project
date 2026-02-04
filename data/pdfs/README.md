# PDF Documents Folder

## 📁 Location

**Full Path:** `/Users/sanjeedajeba/agentic_ai_project/data/pdfs/`

---

## 📝 How to Add PDFs

### **Step 1: Navigate to the Folder**

You can add PDFs in several ways:

#### **Option A: Using Finder (Mac)**
1. Open Finder
2. Press `Cmd + Shift + G` (Go to Folder)
3. Type: `/Users/sanjeedajeba/agentic_ai_project/data/pdfs`
4. Press Enter
5. Copy your PDF files into this folder

#### **Option B: Using Terminal**
```bash
# Navigate to the folder
cd /Users/sanjeedajeba/agentic_ai_project/data/pdfs

# Copy a PDF file here
cp /path/to/your/file.pdf .

# Or move it
mv /path/to/your/file.pdf .
```

#### **Option C: Drag and Drop**
1. Open Finder
2. Navigate to your project folder: `agentic_ai_project`
3. Go to `data` → `pdfs`
4. Drag your PDF files into this folder

---

## 📄 What PDFs to Add

### **Good PDFs for Your System:**
1. **API Documentation**
   - OpenWeatherMap API docs
   - Weather API guides
   - API usage examples

2. **Technical Documentation**
   - Software manuals
   - Integration guides
   - Technical specifications

3. **User Guides**
   - How-to guides
   - Tutorials
   - Best practices

4. **Any Text-Based PDFs**
   - Research papers
   - White papers
   - Documentation files

---

## ✅ Example

After adding PDFs, your folder should look like:

```
data/pdfs/
├── weather_api_documentation.pdf
├── openweathermap_guide.pdf
├── api_integration_manual.pdf
└── user_guide.pdf
```

---

## 🚀 After Adding PDFs

Once you've added PDF files, run:

```bash
# Process all PDFs in this folder
python src/cdms/document_loader.py
```

This will:
- Extract text from all PDFs
- Chunk the content
- Generate embeddings
- Store in Qdrant vector database
- Make them searchable via RAG

---

## 📍 Current Location

**Absolute Path:**
```
/Users/sanjeedajeba/agentic_ai_project/data/pdfs/
```

**Relative Path (from project root):**
```
data/pdfs/
```

---

## 💡 Quick Check

To verify PDFs are in the right place:

```bash
# From project root
ls -la data/pdfs/
```

You should see your PDF files listed here.

