## Pre-Requisites
  <ul>
    <li>
        Modern Office 365 sharepoint site with Library Name EffortManagement having field
    </li>
  </ul>
 1.Modern Office 365 sharepoint site with Library Name EffortManagement having field
    Title(Single line of text	)
		Effort(Number)
		Description(Multiple lines of text)
		Category(Managed Metadata)
		Approver(Person or Group )
 2. 

### Building the code

```bash
git clone the repo
npm i
npm i -g gulp
gulp
```

This package produces the following:

* lib/* - intermediate-stage commonjs build artifacts
* dist/* - the bundled script, along with other resources
* deploy/* - all resources which should be uploaded to a CDN.

### Build options

gulp clean - TODO
gulp test - TODO
gulp serve - TODO
gulp bundle - TODO
gulp package-solution - TODO
