# Registry Example

## Usage

```
git clone https://github.com/geocolumbus/registry-example.git
npm install
```

edit registry.js and put in 5 pieces of information:
 
* WSKey Client ID (line 12)
* WSKey Secret (line 13)
* PrincipalID (line 18)
* PrincipalIDNS (line 19)
* AuthenticationInstitutionID (line 17)
 
Run the program

```
node src/registry.js
```

Assuming your WSKey is set up properly, you should get back a json response.