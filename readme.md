# Repository Sample Power Components Framework

### Documentation

- [Overview](https://learn.microsoft.com/en-us/power-apps/developer/component-framework/overview)
- [Instalation Microsoft Power Platform CLI](https://learn.microsoft.com/pt-br/power-platform/developer/cli/introduction)
- [Get Started - Create your first component](https://learn.microsoft.com/pt-br/power-apps/developer/component-framework/implementing-controls-using-typescript?tabs=before)
- [Best Pratices](https://learn.microsoft.com/pt-br/power-apps/developer/component-framework/code-components-best-practices)
- [Event - addonoutputchange](https://learn.microsoft.com/en-us/power-apps/developer/model-driven-apps/clientapi/reference/controls/addonoutputchange)

### Reference typscript 
- [React Typescript](https://www.typescriptlang.org/pt/docs/handbook/react.html)
- [@types/xrm](https://www.npmjs.com/package/@types/xrm)

### MVP's Blog
- [Diana birkelbach](https://dianabirkelbach.wordpress.com)
- [Scott Durow](https://www.develop1.net/public/)

### Comands
- [Reference](https://learn.microsoft.com/en-us/power-platform/developer/cli/reference/pcf#pac-pcf-init)


##### Create project bolth template:
```  
pac pcf init -ns [NAMESPACE] -n [NOMECONTROLE] -t field
```
```  
pac pcf init -ns [NAMESPACE] -n [NOMECONTROLE] -t field -fw react -npm
```  
```  
pac pcf init -ns [NAMESPACE] -n [NOMECONTROLE] -t dataset
```  
```  
pac pcf init -ns [NAMESPACE] -n [NOMECONTROLE] -t dataset -fw react -npm
```  

#####  Install npm in project.  
```  
npm install 
```  

##### Build project
```  
npm run build 
```  

##### Preview 
```  
npm start watch 
```  

##### Create authentication
```  
pac auth create -u [URL DA ORGANIZAÇÃO] 
```  

##### Publish pcf 
```  
pac pcf push -pp [PREFIXO PUBLICADOR EXISTENTE]
```  

