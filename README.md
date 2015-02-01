# openChat
json-config-manager is a configuration manager for node js application"
# Example
 ***config.json in folder config***   
 {
	"port" : "8080",   
	"indexUrl" : "monkeyDLuffy"   
}
   
 ***server***   
 var conf = require("json-config-manager").requireModule();   
 var port = conf.port;   
 var indexUrl = conf.indexUrl;