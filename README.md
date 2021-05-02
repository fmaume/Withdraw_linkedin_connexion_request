# Withdraw_linkedin_connexion_request

You can use the following code to withdraw old connexion request:

``(function(){var i=0;var f=function(){let
l=document.querySelector("*[data-control-name=withdraw_single]");
if (!!l){setTimeout(function(){l.click();}, 100);
setTimeout(function()
{document.querySelectorAll(".artdeco-modal__confirm-dialog-btn")[1].click();},1500);
setTimeout(function(){f();},2500);}};f();})()``

Check out [this youtube video](https://www.youtube.com/watch?v=KX7JYqAdo1I) for more info.
