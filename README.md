# SGLang Support for Groq

Set your GROQ API key as an environment variable:
```
export GROQ_API_KEY=your-api-key
```


## Customization

```
if __name__ == "__main__":
    sgl.set_default_backend(sgl.Groq("llama3-8b-8192")) # model name llama3-8b-819 can be chnaged
```

#### Supports
+ llama3-8b-8192
+ llama3-70b-8192
+ mixtral-8x7b-32768
+ gemma-7b-it"
