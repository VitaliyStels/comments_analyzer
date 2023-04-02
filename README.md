# ChatGPT comment analiser

## Installing(if you want to redo all the prompts - all the components required)

1. install required libraries
```
    pip3 install jupyterlab requests pandas beautifulsoup4 openai
```
2. past valid API token(existing token was created for first run and no more available)
```
    openai.api_key = os.environ['OPENAI_API_KEY']
```

## Running
```
    jupyter lab
```