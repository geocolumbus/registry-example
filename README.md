# Registry Example

## Usage

```
git clone https://github.com/geocolumbus/registry-example.git
cd registry-example
npm install
```

edit ```src/registry.js``` and put in 5 pieces of information:
 
* WSKey Client ID
* WSKey Secret
* PrincipalID
* PrincipalIDNS
* AuthenticationInstitutionID
 
Run the program

```
node src/registry.js
```

Assuming your WSKey is set up properly, you should get back a json response.