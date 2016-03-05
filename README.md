Swagger Spec for the IDX Broker API
 Initially created/edited with http://editor.swagger.io/#/ using the Uber example.

 I did find some errors thrown in the editor that didn't really seem valid. Notably when using $ref

Still need to:
 remove old definitions from original example
 add all methods
 add example returns
 explore combining all response codes above 400 in to a single $ref

 You can download https://github.com/swagger-api/swagger-ui and change line 39 of index.html in the dist folder to use the YAML in this repo.

 Run locally. You only really need the contents of dist to run on local and see the Swagger UI and this YAML spec.

 Should this spec get to be too big I will need to break this up into smaller files as shown in this article: http://azimi.me/2015/07/16/split-swagger-into-smaller-files.html
