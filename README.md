# c7-camunda-spring-boot-application
Camunda 7 study project with processes, DMNs, Java delegates and logger

- Web Site: https://www.camunda.org/
- Getting Started: https://docs.camunda.org/get-started/

### Process examples:
- getting-joke
- loan-request
- payment-retrival
- request-car-insurance

### DMN:
- approve-payment (for process payment-retrival)
- determine-risk (for process request-car-insurance)
- dish-drg (consisting of two dmns; drg meaning Decision Requirement Diagram)

### Java Delegates:
- GettingJokeDelegate (using open/public GET API without authorization)
- LoggerDelegate (logging)
- ToUpperCaseDelegate (getting variable from Camunda process and creating a new one)
