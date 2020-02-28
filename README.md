# Funda Neighbourhooods

Chrome / Edge extension that adds useful info about a neighbourhood to funda.nl pages.

**Adds info about**:

- how old are houses in the neighbourhood
- average income of residents
- residents age statistics
- marital status of residents
- immigration background statistics
- other stuff

Data comes from Dutch census bureau (CBS) API and is from 2015.

---

### Install extension

**Chrome**: [pending review]  
**Edge**: [pending review]

---

### Commands

`yarn build` - build for production  
`yarn start` - build for development (no minification, uses webpack watch mode)  
`yarn zip` - package build folder into a ZIP, so it can be uploaded to extensions store dashboard

---

### Tools used

**Extension code**: Vanilla JS  
**Bundling**: Webpack 4  
**Zipcode API**: AWS Lambda + DynamoDB  
**Neighbourhood info API**: http://geodata.nationaalgeoregister.nl/

---

### Future plans

- [ ] Translate to Dutch
- [ ] Find / build a more up-to-date API for neighbourhood info
