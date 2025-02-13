# simple-rag
Simple Rag to ask a file


#### Steps

Create venv

```
python3.10 -m venv myenv;source myenv/bin/activate
```

Pip install 

```
 pip install -r requirements.txt  
```


Install Ollama

```
 curl -fsSL https://ollama.com/install.sh | sh
```

Pull Models

```
 ollama pull llama3.1:latest
```

```
  ollama pull nomic-embed-text
```

Run the code

```
python main.py
```

Ask a question about **Peter Pan**

Example:

```
what do you want to know? -> Who is Peter Pan?
Peter Pan is a mischievous and adventurous boy who refuses to grow up. He lives in Neverland with the Lost Boys, fairies, and other mythical creatures.
```



