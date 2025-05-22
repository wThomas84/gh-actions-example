# actionsTemplateExample
## Running Locally with Act
### Install Act

[Installation guide](https://nektosact.com/installation/index.html)

e.g.:
```bash
  brew install act 
```

### Run
Execute in Repository root:  
`act <Trigger>`

Run all workflows that trigger on 'push':  
`act push`

Run workflows with repository variables:  
`act push --env-file .env --secret-file .secrets.env`
