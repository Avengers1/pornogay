API.chatLog("Running Running AvengersBot!", true);
function initEnvironment(){
}
$(".background").html("<img src=\"http://i.imgur.com/pxZ3QSM.png\" style=\"width: 921px; height: 285px; left: -218.5px;\">");
initEnvironment();
if (RMEnhanced !== undefined)
    RMEnhanced.close();
String.prototype.equalsIgnoreCase = function(other) {
    return this.toLowerCase() === other.toLowerCase();
};
document.getElementById('woot').click(); 
API.on(API.DJ_ADVANCE, callback); 
function callback(obj) { 
document.getElementById('woot').click(); 
}
var plugCubed,
RMEnhancedModel = require('app/base/Class').extend({
    init: function(){
        var Lang = require('lang/Lang');
        setTimeout($.proxy(this.initCSS,this), 1500)
		this.proxy = {
            onChat: $.proxy(this.onChat, this)
        };
        API.on(API.CHAT,this.proxy.onChat)
    },
    initCSS: function() {
        $('body').attr('style','overflow: hidden; background-image: url(http://image-upload.de/image/2rhlyf/86c3dcaa92.jpg); background-color: rgb(0, 0, 0); background-position: -12.5px 54px; background-repeat: no-repeat no-repeat;');
            $('head').append('<link rel="stylesheet" type="text/css" href="https://dl.dropboxusercontent.com/u/82153790/rmplug.css"><style type="text/css" id="TFL-css">'
        + '</style>');
},
    onChat: function(data){
		if(data.message == "!testing" && data.fromID == "5121578196fba506408bb9eb"){
            API.chatLog("Command Recieved!",true);
        }
		if(data.message == "!whoisrunning" && data.fromID == "5121578196fba506408bb9eb"){
            API.sendChat("I'm Running AvengersBot");
        }
    },
});
var RMEnhanced = new RMEnhancedModel;
