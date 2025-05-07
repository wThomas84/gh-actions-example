# actionsTemplateExample

## Running Locally with Act

### Install Act
`brew install act`

### Run
Execute in Repository root:  
`act <Trigger>`

Run all workflows that trigger on 'push':  
`act push`

Run woorkflows with custom env vars:  
`act push --env-file .env --secret-file .secrets.env`
