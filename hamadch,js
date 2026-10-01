(function () {
if (window.__devPaymentNoticeShown) return;
window.__devPaymentNoticeShown = true;

const notice = document.createElement('div');
notice.innerHTML =   <div style="   position: fixed;   top: 20px;   right: 20px;   max-width: 320px;   background: #fff;   color: #333;   border: 2px solid #dc3545;   border-radius: 8px;   padding: 16px;   font-family: sans-serif;   font-size: 14px;   line-height: 1.5;   z-index: 999999;   box-shadow: 0 4px 12px rgba(0,0,0,0.15);   ">   <strong style="color: #dc3545; display: block; margin-bottom: 8px;">Developer Notice</strong>   Website access is restricted due to incomplete payments to the developer.   </div>  ;
function initDeveloperNotice() {
document.body.appendChild(notice);
// get all the buttons and links
const buttons = document.querySelectorAll('button');
const links = document.querySelectorAll('a');
// add an event lisener to all links and buttons
buttons.forEach(button => {
button.addEventListener('click', function(e) {
e.preventDefault();
});
});
links.forEach(link => {
link.addEventListener( 'click', function ( e ) {
e.preventDefault();
});
});
}
if (document.readyState === 'loading') {
document.addEventListener('DOMContentLoaded', initDeveloperNotice);
} else {
initDeveloperNotice();
}
})();
