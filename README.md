### Folder creation

```
mkdir document_portal
cd document_portal
```

```
code .
```

### Virtual Env setup with conda

```
conda create -p env python==3.10 -y
```

```
conda activate env-path
```

```
pip install -r requirements.txt
```

### Git Command for code update from local to Repo

```
git init
```

```
git add .
```

```
git commit -m "<Write the commit message>"
```

```
git push
```

#### Git Clone

````
git clone <GIT URL>
````

### Changes pull to local

```
git pull <URL>
```

### minimum requirement for this project

1. LLM Models: groq(Freely), Gemini(only 15 days access), Openai(Paid), Claude(Paid), HuggingFace(Freely), Ollama(Local setup)

2. Embedding Model: Openai(Paid), HuggingFace, Gemini

3. vectordatabase #varients ##in-memory(Cromadb), #on-disk, #cloudbased(aws bedrock, asthadb, mongodb)