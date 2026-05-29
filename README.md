<!DOCTYPE html>
<html lang="en"><head><script src="https://apis.google.com/_/scs/abc-static/_/js/k=gapi.lb.en.ch0Jz-JlMrQ.O/m=gapi_iframes/rt=j/sv=1/d=1/ed=1/rs=AHpOoo_YD4KoV8fTh_kLhktsiThAm3yJ5A/cb=gapi.loaded_0?le=scs" async=""></script><script>(function(firebaseConfig, initialAuthToken, appId) {
        window.__firebase_config = firebaseConfig;
        window.__initial_auth_token = initialAuthToken;
        window.__app_id = appId;
            })("\n{\n  \"apiKey\": \"AIzaSyCqyCcs2R2e7AegGjvFAwG98wlamtbHvZY\",\n  \"authDomain\": \"bard-frontend.firebaseapp.com\",\n  \"projectId\": \"bard-frontend\",\n  \"storageBucket\": \"bard-frontend.firebasestorage.app\",\n  \"messagingSenderId\": \"175205271074\",\n  \"appId\": \"1:175205271074:web:2b7bd4d34d33bf38e6ec7b\"\n}\n","eyJhbGciOiJSUzI1NiIsImtpZCI6ImE1MTMzNTUyZGIzZmQ1ZWM5NjdlZWFkNjk3ZjNhZTgwYjliNzk1ZjQiLCJ0eXAiOiJKV1QifQ.eyJzdWIiOiJmaXJlYmFzZS1hZG1pbnNkay1mYnN2Y0BiYXJkLWZyb250ZW5kLmlhbS5nc2VydmljZWFjY291bnQuY29tIiwiYXVkIjoiaHR0cHM6Ly9pZGVudGl0eXRvb2xraXQuZ29vZ2xlYXBpcy5jb20vZ29vZ2xlLmlkZW50aXR5LmlkZW50aXR5dG9vbGtpdC52MS5JZGVudGl0eVRvb2xraXQiLCJ1aWQiOiIwNTU1NzE0NjM4Mjg4MzA2OTc0NSIsImlzcyI6ImZpcmViYXNlLWFkbWluc2RrLWZic3ZjQGJhcmQtZnJvbnRlbmQuaWFtLmdzZXJ2aWNlYWNjb3VudC5jb20iLCJjbGFpbXMiOnsiYXBwSWQiOiJjXzdiMzEzMzA2ZjRjNmE3ZmZfaW5kZXguaHRtbC0yMzkifSwiZXhwIjoxNzc5NzA5OTIwLCJpYXQiOjE3Nzk3MDYzMjAsImFsZyI6IlJTMjU2In0.mfwsGBDBEgWvBPl7lX9U2dfJ_Btj2IeZLYZT_SCgiisFXgIiH4DAZOdQGs4GUYsPKhBssYfxVhT3dS-gPWaB5o-eU-s_GtwRejJnu10R-l91au97NUth6DuW748zBRMbJfzR-BOb6roLv35__ix1CESDYpyppubK436Jk10YpXzvMPcjW4t-QGhWVHPdy5QzItI6RZbCiVSSCnYHhkWmg7d0hFnoZBDHvoArBEdfrjIX-_YijG3LgCoYDNcXuhVqMIEtwrZkDDKYa5wWIuiArPU2g8JYpZ00ZrxB9gxdFFDXzxPTk9Gcob8XQReEucmoi_CTXMt3XRDeyeqMFY-0Lg","c_7b313306f4c6a7ff_index.html-239")</script><script>(function(){'use strict';var h=typeof Object.defineProperties=="function"?Object.defineProperty:function(a,b,d){if(a==Array.prototype||a==Object.prototype)return a;a[b]=d.value;return a};function l(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var d=a[b];if(d&&d.Math==Math)return d}throw Error("Cannot find global object");}var n=l(this);
function p(a,b){if(b)a:{var d=n;a=a.split(".");for(var c=0;c<a.length-1;c++){var e=a[c];if(!(e in d))break a;d=d[e]}a=a[a.length-1];c=d[a];b=b(c);b!=c&&b!=null&&h(d,a,{configurable:!0,writable:!0,value:b})}}function r(a){function b(c){return a.next(c)}function d(c){return a.throw(c)}return new Promise(function(c,e){function f(g){g.done?c(g.value):Promise.resolve(g.value).then(b,d).then(f,e)}f(a.next())})}function t(a){return r(a())}
p("Object.values",function(a){return a?a:function(b){var d=[],c;for(c in b)Object.prototype.hasOwnProperty.call(b,c)&&d.push(b[c]);return d}});p("Array.prototype.includes",function(a){return a?a:function(b,d){var c=this;c instanceof String&&(c=String(c));var e=c.length;d=d||0;for(d<0&&(d=Math.max(d+e,0));d<e;d++){var f=c[d];if(f===b||Object.is(f,b))return!0}return!1}});/*

 MIT License

 Copyright (c) 2017-2023 W.Y.

 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to deal
 in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:

 The above copyright notice and this permission notice shall be included in
 all copies or substantial portions of the Software.

 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
 IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 SOFTWARE.

*/
function u(a,b){var d=a.style;b.backgroundColor&&(d.backgroundColor=b.backgroundColor);b.width&&(d.width=`${b.width}px`);b.height&&(d.height=`${b.height}px`);var c=b.style;c!=null&&Object.keys(c).forEach(e=>{d[e]=c[e]})};var v=(()=>{var a=0;return()=>{a+=1;return`u${`0000${(Math.random()*1679616<<0).toString(36)}`.slice(-4)}${a}`}})();function w(a){var b=[];for(let d=0,c=a.length;d<c;d++)b.push(a[d]);return b}let x=null;function y(a={}){return x?x:a.l?x=a.l:x=w(window.getComputedStyle(document.documentElement))}function z(a,b){return(a=(a.ownerDocument.defaultView||window).getComputedStyle(a).getPropertyValue(b))?parseFloat(a.replace("px","")):0}
function A(a,b={}){var d;if(!(d=b.width)){d=z(a,"border-left-width");var c=z(a,"border-right-width");d=a.clientWidth+d+c}(b=b.height)||(b=z(a,"border-top-width"),c=z(a,"border-bottom-width"),b=a.clientHeight+b+c);return{width:d,height:b}}function B(a){return new Promise((b,d)=>{var c=new Image;c.onload=()=>{c.decode().then(()=>{requestAnimationFrame(()=>b(c))})};c.onerror=d;c.crossOrigin="anonymous";c.decoding="async";c.src=a})}
function C(a){return t(function*(){return Promise.resolve().then(()=>(new XMLSerializer).serializeToString(a)).then(encodeURIComponent).then(b=>`data:image/svg+xml;charset=utf-8,${b}`)})}
function D(a,b,d){return t(function*(){var c=document.createElementNS("http://www.w3.org/2000/svg","svg"),e=document.createElementNS("http://www.w3.org/2000/svg","foreignObject");c.setAttribute("width",`${b}`);c.setAttribute("height",`${d}`);c.setAttribute("viewBox",`0 0 ${b} ${d}`);e.setAttribute("width","100%");e.setAttribute("height","100%");e.setAttribute("x","0");e.setAttribute("y","0");e.setAttribute("externalResourcesRequired","true");c.appendChild(e);e.appendChild(a);return C(c)})}
var E=(a,b)=>{if(a instanceof b)return!0;a=Object.getPrototypeOf(a);return a===null?!1:a.constructor.name===b.name||E(a,b)};function F(a,b){return y(b).map(d=>{var c=a.getPropertyValue(d),e=a.getPropertyPriority(d);return`${d}: ${c}${e?" !important":""};`}).join(" ")}
function G(a,b,d,c){a=window.getComputedStyle(a,d);var e=a.getPropertyValue("content");if(e!==""&&e!=="none"){var f=v();try{b.className=`${b.className} ${f}`}catch(k){return}e=document.createElement("style");var g=e.appendChild;d=`.${f}:${d}`;a.cssText?(c=a.getPropertyValue("content"),c=`${a.cssText} content: '${c.replace(/'|"/g,"")}';`):c=F(a,c);g.call(e,document.createTextNode(`${d}{${c}}`));b.appendChild(e)}};function H(a){return a.search(/^(data:)/)!==-1}function I(a,b,d){return t(function*(){var c=yield fetch(a,b);if(c.status===404)throw Error(`Resource "${c.url}" not found`);var e=yield c.blob();return new Promise((f,g)=>{var k=new FileReader;k.onerror=g;k.onloadend=()=>{try{f(d({o:c,result:k.result}))}catch(m){g(m)}};k.readAsDataURL(e)})})}const J={};function K(a,b,d){var c=a.replace(/\?.*/,"");d&&(c=a);/ttf|otf|eot|woff2?/i.test(c)&&(c=c.replace(/.*\//,""));return b?`[${b}]${c}`:c}
function L(a,b,d){return t(function*(){var c=K(a,b,d.C);if(J[c]!=null)return J[c];d.u&&(a+=(/\?/.test(a)?"&":"?")+(new Date).getTime());try{let f=yield I(a,d.i,({o:g,result:k})=>{b||(b=g.headers.get("Content-Type")||"");return k.split(/,/)[1]});var e=`data:${b};base64,${f}`}catch(f){e=d.B||""}return J[c]=e})};const M={P:"application/font-woff",R:"application/font-woff",N:"application/font-truetype",v:"application/vnd.ms-fontobject",H:"image/png",F:"image/jpeg",D:"image/jpeg",A:"image/gif",M:"image/tiff",L:"image/svg+xml",O:"image/webp"};function N(a){return(a=/\.([^./]*?)$/g.exec(a))?a[1]:""};function O(a){return t(function*(){var b=a.toDataURL();return b==="data:,"?a.cloneNode(!1):B(b)})}function aa(a,b){return t(function*(){if(a.currentSrc){var d=document.createElement("canvas");let c=d.getContext("2d");d.width=a.clientWidth;d.height=a.clientHeight;c==null||c.drawImage(a,0,0,d.width,d.height);d=d.toDataURL();return B(d)}d=a.poster;d=yield L(d,M[N(d).toLowerCase()]||"",b);return B(d)})}
function ba(a,b){return t(function*(){try{let d;if(a==null?0:(d=a.contentDocument)==null?0:d.body)return yield P(a.contentDocument.body,b,!0)}catch(d){}return a.cloneNode(!1)})}function ca(a,b){return t(function*(){return E(a,HTMLCanvasElement)?O(a):E(a,HTMLVideoElement)?aa(a,b):E(a,HTMLIFrameElement)?ba(a,b):a.cloneNode(a.tagName!=null&&a.tagName.toUpperCase()==="SVG")})}
function da(a,b,d){return t(function*(){if(b.tagName!=null&&b.tagName.toUpperCase()==="SVG")return b;var c=[];if(a.tagName!=null&&a.tagName.toUpperCase()==="SLOT"&&a.assignedNodes)c=w(a.assignedNodes());else{let e;if(E(a,HTMLIFrameElement)&&((e=a.contentDocument)==null?0:e.body))c=w(a.contentDocument.body.childNodes);else{let f;c=w(((f=a.shadowRoot)!=null?f:a).childNodes)}}if(c.length===0||E(a,HTMLVideoElement))return b;yield c.reduce((e,f)=>e.then(()=>P(f,d)).then(g=>{g&&b.appendChild(g)}),Promise.resolve());
return b})}function ea(a,b,d){var c=b.style;if(c){var e=window.getComputedStyle(a);e.cssText?(c.cssText=e.cssText,c.transformOrigin=e.transformOrigin):y(d).forEach(f=>{var g=e.getPropertyValue(f);f==="font-size"&&g.endsWith("px")&&(g=`${Math.floor(parseFloat(g.substring(0,g.length-2)))-.1}px`);E(a,HTMLIFrameElement)&&f==="display"&&g==="inline"&&(g="block");f==="d"&&b.getAttribute("d")&&(g=`path(${b.getAttribute("d")})`);c.setProperty(f,g,e.getPropertyPriority(f))})}}
function fa(a,b){E(a,HTMLSelectElement)&&(b=Array.from(b.children).find(d=>a.value===d.getAttribute("value")))&&b.setAttribute("selected","")}
function ha(a,b){return t(function*(){var d=a.querySelectorAll?a.querySelectorAll("use"):[];if(d.length===0)return a;var c={};for(var e=0;e<d.length;e++){var f=d[e].getAttribute("xlink:href");if(f){let g=document.querySelector(f);a.querySelector(f)||!g||c[f]||(c[f]=yield P(g,b,!0))}}d=Object.values(c);if(d.length){c=document.createElementNS("http://www.w3.org/1999/xhtml","svg");c.setAttribute("xmlns","http://www.w3.org/1999/xhtml");c.style.position="absolute";c.style.width="0";c.style.height="0";
c.style.overflow="hidden";c.style.display="none";e=document.createElementNS("http://www.w3.org/1999/xhtml","defs");c.appendChild(e);for(f=0;f<d.length;f++)e.appendChild(d[f]);a.appendChild(c)}return a})}
function P(a,b,d){return t(function*(){return d||!b.filter||b.filter(a)?Promise.resolve(a).then(c=>ca(c,b)).then(c=>da(a,c,b)).then(c=>{E(c,Element)&&(ea(a,c,b),G(a,c,":before",b),G(a,c,":after",b),E(a,HTMLTextAreaElement)&&(c.textContent=a.value),E(a,HTMLInputElement)&&c.setAttribute("value",a.value),fa(a,c));return c}).then(c=>ha(c,b)):null})};const Q=/url\((['"]?)([^'"]+?)\1\)/g,ia=/url\([^)]+\)\s*format\((["']?)([^"']+)\1\)/g,ja=/src:\s*(?:url\([^)]+\)\s*format\([^)]+\)[,;]\s*)+/g;function ka(a){var b=[];a.replace(Q,(d,c,e)=>{b.push(e);return d});return b.filter(d=>!H(d))}
function la(a,b,d,c){return t(function*(){try{let e=d?(new URL(b,d||void 0)).toString():b,f;f=yield L(e,M[N(b).toLowerCase()]||"",c);return a.replace(new RegExp(`(url\\(['"]?)(${b.replace(/([.*+?^${}()|\[\]\/\\])/g,"\\$1")})(['"]?\\))`,"g"),`$1${f}$3`)}catch(e){}return a})}function ma(a,{I:b}){return b?a.replace(ja,d=>{for(;;){let [c,,e]=ia.exec(d)||[];if(!e)return"";if(e===b)return`src: ${c};`}}):a}
function R(a,b,d){return t(function*(){if(a.search(Q)===-1)return a;var c=ma(a,d);return ka(c).reduce((e,f)=>e.then(g=>la(g,f,b,d)),Promise.resolve(c))})};function S(a,b,d){return t(function*(){var c,e=(c=b.style)==null?void 0:c.getPropertyValue(a);return e?(c=yield R(e,null,d),b.style.setProperty(a,c,b.style.getPropertyPriority(a)),!0):!1})}function na(a,b){return t(function*(){(yield S("background",a,b))||(yield S("background-image",a,b));(yield S("mask",a,b))||(yield S("-webkit-mask",a,b))||(yield S("mask-image",a,b))||(yield S("-webkit-mask-image",a,b))})}
function oa(a,b){return t(function*(){var d=E(a,HTMLImageElement);if(d&&!H(a.src)||E(a,SVGImageElement)&&!H(a.href.baseVal)){var c=d?a.src:a.href.baseVal,e=yield L(c,M[N(c).toLowerCase()]||"",b);yield new Promise((f,g)=>{a.onload=f;a.onerror=b.m?(...k)=>{try{f(b.m(...k))}catch(m){g(m)}}:g;a.decode&&(a.decode=f);a.loading==="lazy"&&(a.loading="eager");d?(a.srcset="",a.src=e):a.href.baseVal=e})}})}
function pa(a,b){return t(function*(){var d=w(a.childNodes).map(c=>T(c,b));yield Promise.all(d).then(()=>a)})}function T(a,b){return t(function*(){E(a,Element)&&(yield na(a,b),yield oa(a,b),yield pa(a,b))})};const U={};function V(a){return t(function*(){var b=U[a];if(b!=null)return b;b=yield(yield fetch(a)).text();b={url:a,cssText:b};return U[a]=b})}function W(a,b){return t(function*(){var d=a.cssText,c=/url\(["']?([^"')]+)["']?\)/g,e=(d.match(/url\([^)]+\)/g)||[]).map(f=>t(function*(){var g=f.replace(c,"$1");g.startsWith("https://")||(g=(new URL(g,a.url)).href);return I(g,b.i,({result:k})=>{d=d.replace(f,`url(${k})`);return[f,k]})}));return Promise.all(e).then(()=>d)})}
function X(a){if(a==null)return[];var b=[];a=a.replace(/(\/\*[\s\S]*?\*\/)/gi,"");for(var d=RegExp("((@.*?keyframes [\\s\\S]*?){([\\s\\S]*?}\\s*?)})","gi");;){var c=d.exec(a);if(c===null)break;b.push(c[0])}a=a.replace(d,"");d=/@import[\s\S]*?url\([^)]*\)[\s\S]*?;/gi;for(c=RegExp("((\\s*?(?:\\/\\*[\\s\\S]*?\\*\\/)?\\s*?@media[\\s\\S]*?){([\\s\\S]*?)}\\s*?})|(([\\s\\S]*?){([\\s\\S]*?)})","gi");;){let e=d.exec(a);if(e===null)if(e=c.exec(a),e===null)break;else d.lastIndex=c.lastIndex;else c.lastIndex=
d.lastIndex;b.push(e[0])}return b}
function qa(a,b){return t(function*(){var d=[],c=[];a.forEach(e=>{if("cssRules"in e)try{w(e.cssRules||[]).forEach((f,g)=>{if(f.type===CSSRule.IMPORT_RULE){let k=g+1;f=V(f.href).then(m=>W(m,b)).then(m=>X(m).forEach(q=>{try{e.insertRule(q,q.startsWith("@import")?k+=1:e.cssRules.length)}catch(Da){}})).catch(()=>{});c.push(f)}})}catch(f){let g=a.find(k=>k.href==null)||document.styleSheets[0];e.href!=null&&c.push(V(e.href).then(k=>W(k,b)).then(k=>X(k).forEach(m=>{g.insertRule(m,g.cssRules.length)})).catch(()=>
{}))}});return Promise.all(c).then(()=>{a.forEach(e=>{if("cssRules"in e)try{w(e.cssRules||[]).forEach(f=>{d.push(f)})}catch(f){}});return d})})}function ra(a){return a.filter(b=>b.type===CSSRule.FONT_FACE_RULE).filter(b=>b.style.getPropertyValue("src").search(Q)!==-1)}function sa(a,b){return t(function*(){if(a.ownerDocument==null)throw Error("Provided element is not within a Document");var d=w(a.ownerDocument.styleSheets);d=yield qa(d,b);return ra(d)})}
function ta(a){function b(c){(c.style.fontFamily||getComputedStyle(c).fontFamily).split(",").forEach(e=>{d.add(e.trim().replace(/["']/g,""))});Array.from(c.children).forEach(e=>{e instanceof HTMLElement&&b(e)})}var d=new Set;b(a);return d}function ua(a,b){return t(function*(){var d=yield sa(a,b),c=ta(a);return(yield Promise.all(d.filter(e=>c.has(e.style.fontFamily.trim().replace(/["']/g,""))).map(e=>R(e.cssText,e.parentStyleSheet?e.parentStyleSheet.href:null,b)))).join("\n")})}
function va(a,b){return t(function*(){var d=b.j!=null?b.j:b.K?null:yield ua(a,b);if(d){let c=document.createElement("style");c.appendChild(document.createTextNode(d));a.firstChild?a.insertBefore(c,a.firstChild):a.appendChild(c)}})};function wa(a,b={}){return t(function*(){var {width:d,height:c}=A(a,b),e=yield P(a,b,!0);yield va(e,b);yield T(e,b);u(e,b);return yield D(e,d,c)})}
function xa(a,b={}){return t(function*(){var {width:d,height:c}=A(a,b),e=yield wa(a,b);e=yield B(e);var f=document.createElement("canvas"),g=f.getContext("2d"),k=b.G||window.devicePixelRatio||1,m=b.h||d,q=b.g||c;f.width=m*k;f.height=q*k;!b.J&&(f.width>16384||f.height>16384)&&(f.width>16384&&f.height>16384?f.width>f.height?(f.height*=16384/f.width,f.width=16384):(f.width*=16384/f.height,f.height=16384):f.width>16384?(f.height*=16384/f.width,f.width=16384):(f.width*=16384/f.height,f.height=16384));
f.style.width=`${m}`;f.style.height=`${q}`;b.backgroundColor&&(g.fillStyle=b.backgroundColor,g.fillRect(0,0,f.width,f.height));g.drawImage(e,0,0,f.width,f.height);return f})}function ya(a,b={}){return t(function*(){return(yield xa(a,b)).toDataURL()})};const za=["gemini.google.com","corp.google.com","proxy.googlers.com"];function Y(){return document.body.querySelectorAll('[class*="animate"]').length>0}function Z(a){return t(function*(){try{return yield ya(a,{h:a.offsetWidth,g:a.offsetHeight})}catch(d){var b=a.offsetHeight;let c=document.createElement("canvas");c.width=a.offsetWidth;c.height=b;return c.toDataURL("image/png")}})}
function Aa(){return t(function*(){var a=document.body.offsetWidth,b=document.body.offsetHeight,d=document.body.cloneNode(!0);d.querySelectorAll('[class*="animate"]').forEach(c=>{c.classList.remove(...Array.from(c.classList).filter(e=>e.startsWith("animate")))});d.style.width=`${a}px`;d.style.height=`${b}px`;return d})}
function Ba(a){return t(function*(){var b=document.body;if(Y()){var d=yield Aa();b=d;document.body.appendChild(d)}d=yield Z(b);Y()&&document.body.removeChild(b);window.parent.postMessage({type:"SEND_SCREENSHOT",image:d,topOffset:document.documentElement.scrollTop},a.origin)})}function Ca(a){return t(function*(){var b={type:"SEND_SCREENSHOT_FOR_DATA_VISUALIZATION",image:yield Z(document.body),topOffset:0};window.parent.postMessage(b,a.origin)})}
window.addEventListener("message",a=>t(function*(){if(za.some(d=>a.origin.includes(d))){var b=a.data;b&&(b.type==="MAKE_SCREENSHOT"&&(yield Ba(a)),b.type==="MAKE_SCREENSHOT_FOR_DATA_VISUALIZATION"&&(yield Ca(a)))}}));
})();</script><script>(function() {
  // Ensure this script is executed only once
  if (window.firebaseAuthBridgeScriptLoaded) {
    return;
  }
  window.firebaseAuthBridgeScriptLoaded = true;

  let nextTokenPromiseId = 0;

  // Stores { resolve, reject } for ongoing token requests
  const pendingTokenPromises = {};

  // Listen for messages from the Host Application
  window.addEventListener('message', function(event) {

    const messageData = event.data;

  if (messageData && messageData.type === 'RESOLVE_NEW_FIREBASE_TOKEN') {
      const { success, token, error, promiseId } = messageData ?? {};
      if (pendingTokenPromises[promiseId]) {
        if (success) {
          pendingTokenPromises[promiseId].resolve(token);
        } else {
          pendingTokenPromises[promiseId].reject(new Error(error || 'Token refresh failed from host.'));
        }
        delete pendingTokenPromises[promiseId];
      }
    }
  });

  // Expose a function for the Generated App to request a new Firebase token
  window.requestNewFirebaseToken = function() {
    const currentPromiseId = nextTokenPromiseId++;
    const promise = new Promise((resolve, reject) => {
      pendingTokenPromises[currentPromiseId] = { resolve, reject };
    });
    if (window.parent && window.parent !== window) {
      window.parent.postMessage({
        type: 'REQUEST_NEW_FIREBASE_TOKEN',
        promiseId: currentPromiseId
      }, '*');
    } else {
      pendingTokenPromises[currentPromiseId].reject(new Error('No parent window to request token from.'));
      delete pendingTokenPromises[currentPromiseId];
    }
    return promise;
  };
})();</script><script>
let realOriginalGetUserMedia = null;
if (navigator.mediaDevices && navigator.mediaDevices.getUserMedia) {
  realOriginalGetUserMedia = navigator.mediaDevices.getUserMedia.bind(navigator.mediaDevices);
}

(function() {
  if (navigator.mediaDevices && navigator.mediaDevices.__proto__) {
    try {
      Object.defineProperty(navigator.mediaDevices.__proto__, 'getUserMedia', {
        get: function() {
          return undefined; // Or throw an error
        },
        configurable: false
      });
    } catch (error) {
      console.error("Error defining prototype getter:", error);
    }
  }
})();

(function() {
  const pendingMediaResolvers = {};
  let nextMediaPromiseId = 0;

  function requestMediaPermissions(constraints) {
    const mediaPromiseId = nextMediaPromiseId++;
    const promise = new Promise((resolve, reject) => {
      pendingMediaResolvers[mediaPromiseId] = (granted) => {
        delete pendingMediaResolvers[mediaPromiseId];
        resolve(granted);
      };
    });

    window.parent.postMessage({
      type: 'requestMediaPermission',
      constraints: constraints,
      promiseId: mediaPromiseId,
    }, '*');

    return promise;
  }

  let originalGetUserMedia = realOriginalGetUserMedia;

  function interceptGetUserMedia() {
    if (navigator.mediaDevices) {
      Object.defineProperty(navigator.mediaDevices, 'getUserMedia', {
        value: function(constraints) {
          return requestMediaPermissions(constraints).then((granted) => {
            if (granted) {
              if (originalGetUserMedia) {
                return originalGetUserMedia(constraints);
              } else {
                throw new Error("Original getUserMedia not available.");
              }
            } else {
              throw new DOMException('Permission denied', 'NotAllowedError');
            }
          });
        },
        writable: false,
        configurable: false
      });
    }
  }

  interceptGetUserMedia();

  const observer = new MutationObserver(function(mutationsList, observer) {
    for (const mutation of mutationsList) {
      if (mutation.type === 'reconfigured' && mutation.name === 'getUserMedia' && mutation.object === navigator.mediaDevices) {
        interceptGetUserMedia();
      } else if (mutation.type === 'attributes' && mutation.attributeName === 'getUserMedia' && mutation.target === navigator.mediaDevices) {
        interceptGetUserMedia();
      } else if (mutation.type === 'childList' && mutation.addedNodes) {
        mutation.addedNodes.forEach(node => {
          if (node === navigator.mediaDevices) {
            interceptGetUserMedia();
          }
        });
      }
    }
  });

  function interceptSpeechRecognition() {
    if (!window.SpeechRecognition && !window.webkitSpeechRecognition) {
      return;
    }

    const OriginalSpeechRecognition = window.SpeechRecognition || window.webkitSpeechRecognition;

    const SpeechRecognitionWrapper = function(...args) {
      const recognizer = new OriginalSpeechRecognition(...args);
      const originalStart = recognizer.start.bind(recognizer);

      recognizer.start = function() {
        requestMediaPermissions({ audio: true }).then(granted => {
          if (granted) {
            originalStart();
          } else {
            const errorEvent = new SpeechRecognitionErrorEvent('error');
            errorEvent.error = 'not-allowed'; // This is the standard error for permission denial.
            recognizer.dispatchEvent(errorEvent);
          }
        });
      };

      return recognizer;
    };

    SpeechRecognitionWrapper.prototype = OriginalSpeechRecognition.prototype;
    SpeechRecognitionWrapper.prototype.constructor = SpeechRecognitionWrapper;

    if (window.SpeechRecognition) {
      window.SpeechRecognition = SpeechRecognitionWrapper;
    }
    if (window.webkitSpeechRecognition) {
      window.webkitSpeechRecognition = SpeechRecognitionWrapper;
    }
  }

  interceptSpeechRecognition();

  window.addEventListener('message', function(event) {
    if (event.data) {
      if (event.data.type === 'resolveMediaPermission') {
        const { promiseId, granted } = event.data;
        if (pendingMediaResolvers[promiseId]) {
          pendingMediaResolvers[promiseId](granted);
        }
      }
    }
  });

})();</script><script ws-interception-config="{&quot;parentOrigin&quot;:&quot;https://gemini.google.com&quot;,&quot;proxiedDomains&quot;:[]}">(function(){'use strict';var u=typeof Object.defineProperties=="function"?Object.defineProperty:function(b,d,e){if(b==Array.prototype||b==Object.prototype)return b;b[d]=e.value;return b};function v(b){b=["object"==typeof globalThis&&globalThis,b,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var d=0;d<b.length;++d){var e=b[d];if(e&&e.Math==Math)return e}throw Error("Cannot find global object");}var w=v(this);
function y(b,d){if(d)a:{var e=w;b=b.split(".");for(var h=0;h<b.length-1;h++){var k=b[h];if(!(k in e))break a;e=e[k]}b=b[b.length-1];h=e[b];d=d(h);d!=h&&d!=null&&u(e,b,{configurable:!0,writable:!0,value:d})}}function z(b){function d(h){return b.next(h)}function e(h){return b.throw(h)}return new Promise(function(h,k){function m(n){n.done?h(n.value):Promise.resolve(n.value).then(d,e).then(m,k)}m(b.next())})}y("globalThis",function(b){return b||w});/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
function A(b,d){function e(){}e.prototype=d.prototype;b.i=d.prototype;b.prototype=new e;b.prototype.constructor=b;b.g=function(h,k,m){for(var n=Array(arguments.length-2),p=2;p<arguments.length;p++)n[p-2]=arguments[p];return d.prototype[k].apply(h,n)}};function B(b,d,e="*"){function h(a){if(typeof a==="string")return F.encode(a).buffer;if(a instanceof ArrayBuffer)return a.slice(0);if(ArrayBuffer.isView(a))return a.buffer.slice(a.byteOffset,a.byteOffset+a.byteLength);throw Error("Invalid data type");}function k(a){a=h(a);var f={type:"send",data:new Uint8Array(a)},g;(g=r)==null||g.postMessage(f,[a])}function m(){if(!r)throw Error("Data port not captured yet.");r.onmessage=a=>{if(a.data.type==="message"){a=new MessageEvent("message",{data:G.decode(a.data.data)});
let f;(f=c.onmessage)==null||f.call(c,a);c.dispatchEvent(a)}}}function n(){if(!t)throw Error("Control port not captured yet.");t.onmessage=a=>{switch(a.data.type){case "open":l=1;var f=new Event("open"),g;(g=c.onopen)==null||g.call(c,f);c.dispatchEvent(f);q.forEach(H=>{k(H)});q=[];break;case "close":g=a.data;l=3;g=new CloseEvent("close",{code:g.code,reason:g.reason,wasClean:g.wasClean});(f=c.onclose)==null||f.call(c,g);c.dispatchEvent(g);break;case "error":l=3;f=new Event("error");let x;(x=c.onerror)==
null||x.call(c,f);c.dispatchEvent(f)}}}function p(a){return z(function*(){var f=new MessageChannel;t=f.port1;var g=new MessageChannel;r=g.port1;n();m();window.parent.postMessage({type:"websocket_open",portOrdering:["control","data"],url:b,protocols:a||[],connectionId:I},e,[f.port2,g.port2])}())}var c=Reflect.construct(EventTarget,[],new.target);c.CONNECTING=0;c.OPEN=1;c.CLOSING=2;c.CLOSED=3;c.url=b;c.binaryType="arraybuffer";c.protocol="";c.h="";var l=0,t=null,r=null,q=[],F=new TextEncoder,G=new TextDecoder;
c.onopen=null;c.onmessage=null;c.onclose=null;c.onerror=null;Object.defineProperty(c,"readyState",{get:()=>l,enumerable:!0,configurable:!0});Object.defineProperty(c,"bufferedAmount",{get:()=>{var a=0;q.forEach(f=>{a+=typeof f==="string"?f.length:f.byteLength});return a},enumerable:!0,configurable:!0});var I=function(){var a;return((a=globalThis.crypto)==null?0:a.randomUUID)?globalThis.crypto.randomUUID():"xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx".replace(/[xy]/g,f=>{var g=Math.random()*16|0;return(f===
"x"?g:g&3|8).toString(16)})}();c.send=a=>{if(l===1)a instanceof Blob?a.arrayBuffer().then(f=>{k(f)}):k(a);else if(l===0)if(typeof a==="string")q.push(a);else if(a instanceof ArrayBuffer||ArrayBuffer.isView(a))q.push(h(a));else throw Error("Sending Blob is not supported before the connection is open.");else console.debug("WebSocket send called in CLOSING or CLOSED state; ignored.")};c.close=(a=1E3,f="")=>{if(l!==2&&l!==3){l=2;a={type:"close",code:a,reason:f,wasClean:a===1E3};var g;(g=t)==null||g.postMessage(a)}};
Promise.resolve().then(()=>p(d));return c}A(B,EventTarget);var C=document.currentScript,D=C==null?void 0:C.getAttribute("ws-interception-config");if(!D)throw Error("WebSocket Interceptor: Missing ws-interception-config attribute in the script tag.");var E=JSON.parse(D);if(!E.parentOrigin||typeof E.parentOrigin!=="string")throw Error("WebSocket Interceptor: Invalid parentOrigin in ws-interception-config");
(function(b){var d=Object.getOwnPropertyDescriptor(window,"WebSocket");if(!d||d.writable||d.configurable)d=Object.assign(function(e,h){try{let k=(new URL(e)).hostname;if(b.proxiedDomains.some(m=>k===m||k.endsWith(`.${m}`)))return new B(e,h,b.parentOrigin)}catch(k){throw window.parent.postMessage({type:"websocket_blocked",url:e,reason:"blocked_invalid_url"},b.parentOrigin),new DOMException(`WebSocket connection to '${e}' is not allowed in Canvas.`,"SecurityError");}window.parent.postMessage({type:"websocket_blocked",
url:e,reason:"blocked_domain_not_allowlisted"},b.parentOrigin);throw new DOMException(`WebSocket connection to '${e}' is not allowed in Canvas.`,"SecurityError");},{CONNECTING:0,OPEN:1,CLOSING:2,CLOSED:3}),Object.defineProperty(window,"WebSocket",{value:d,writable:!1,configurable:!1})})({proxiedDomains:E.proxiedDomains||[],parentOrigin:E.parentOrigin});}).call(this);
</script><script>((function(modelInformation) {
  const originalFetch = window.fetch;
  // TODO: b/421908508 - Move these out of the script and match all generative AI model calls.
  let googleLlmBaseApiUrls = [
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.textModelName + ':streamGenerateContent',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.textModelName + ':generateContent',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.imageModelName + ':predict',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.imageModelName + ':predictLongRunning',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.imageEditModelName + ':generateContent',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.imageTransformModelName + ':generateContent',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.videoModelName + ':predict',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.videoModelName + ':predictLongRunning',
    'https://generativelanguage.googleapis.com/v1beta/models/' + modelInformation.ttsModelName + ':generateContent',
  ];
  modelInformation.deprecatedTextModelNames.forEach((modelName) => {
    googleLlmBaseApiUrls.push(
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':streamGenerateContent',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':generateContent',
    );
  });
  modelInformation.deprecatedImageModelNames.forEach((modelName) => {
    googleLlmBaseApiUrls.push(
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':predict',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':predictLongRunning',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':generateContent',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':streamGenerateContent',
    );
  });
  modelInformation.deprecatedGenerateImageModelNames.forEach((modelName) => {
    googleLlmBaseApiUrls.push(
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':generateContent',
      'https://generativelanguage.googleapis.com/v1beta/models/' + modelName + ':streamGenerateContent',
    );
  });

  const pendingFetchResolvers = {};
  let nextPromiseId = 0;

  function handleStringInput(input, optionsArgument) {
    const actualUrl = input;
    const fetchCallArgs = [actualUrl, optionsArgument];
    const effectiveOptions = optionsArgument || {};
    const bodyForApiKeyCheck = effectiveOptions.body;
    const bodyForPostMessage = effectiveOptions.body;
    return { actualUrl, fetchCallArgs, effectiveOptions, bodyForApiKeyCheck, bodyForPostMessage };
  }

  function handleRequestInput(input, optionsArgument) {
    const actualUrl = input.url;
    const fetchCallArgs = [input, optionsArgument];
    const effectiveOptions = { method: input.method, headers: new Headers(input.headers) };
    let bodyForApiKeyCheck;
    let bodyForPostMessage;

    if (optionsArgument) {
      if (optionsArgument.method) effectiveOptions.method = optionsArgument.method;
      if (optionsArgument.headers) effectiveOptions.headers = new Headers(optionsArgument.headers);
      if ('body' in optionsArgument) {
        bodyForApiKeyCheck = optionsArgument.body;
        bodyForPostMessage = optionsArgument.body;
      } else {
        bodyForApiKeyCheck = undefined;
        bodyForPostMessage = input.body;
      }
    } else {
      bodyForApiKeyCheck = undefined;
      bodyForPostMessage = input.body;
    }
    return { actualUrl, fetchCallArgs, effectiveOptions, bodyForApiKeyCheck, bodyForPostMessage };
  }

  window.fetch = function(input, optionsArgument) {
    let actualUrl;
    let fetchCallArgs;
    let effectiveOptions = {};
    let bodyForApiKeyCheck;
    let bodyForPostMessage;

    if (typeof input === 'string') {
      ({actualUrl, fetchCallArgs, effectiveOptions, bodyForApiKeyCheck, bodyForPostMessage} = handleStringInput(input, optionsArgument));
    } else if (input instanceof Request) {
      ({actualUrl, fetchCallArgs, effectiveOptions, bodyForApiKeyCheck, bodyForPostMessage} = handleRequestInput(input, optionsArgument));
    } else {
      return originalFetch.apply(window, [input, optionsArgument]);
    }

    effectiveOptions.method = effectiveOptions.method || 'GET';
    if (!effectiveOptions.headers) {
      effectiveOptions.headers = new Headers();
    }


    if (typeof actualUrl === 'string' && googleLlmBaseApiUrls.some((url) => actualUrl.startsWith(url))) {
      let apiKeyIsNull = true;

      const regex = new RegExp("models/([^:]+)");
      const modelNameMatch = actualUrl.match(regex);
      const modelName = modelNameMatch ? modelNameMatch[1] : 'unspecified';


      try {
        const urlObject = new URL(actualUrl);  // Use URL object for robust parsing
        const apiKeyParam = urlObject.searchParams.get('key');
        if (apiKeyParam) {
          apiKeyIsNull = false;
        }
      } catch (e) {
        // Continue checks even if URL parsing fails
      }

      if (apiKeyIsNull && effectiveOptions.headers) {
        const h = new Headers(effectiveOptions.headers);
        const apiKeyHeaderValue = h.get('X-API-Key') || h.get('x-api-key');
        if (apiKeyHeaderValue) {
          apiKeyIsNull = false;
          return originalFetch.apply(window, fetchCallArgs);
        }
      }

      if (apiKeyIsNull && effectiveOptions.method && ['POST', 'PUT', 'PATCH'].includes(effectiveOptions.method.toUpperCase()) && typeof bodyForApiKeyCheck === 'string') {
        try {
          const bodyData = JSON.parse(bodyForApiKeyCheck);
          if (bodyData && bodyData.apiKey) {
            apiKeyIsNull = false;
            return originalFetch.apply(window, fetchCallArgs);
          }
        } catch (e) {
          // Ignore JSON parsing errors
        }
      }

      if(apiKeyIsNull) {
        const promiseId = nextPromiseId++;
        const promise = new Promise((resolve) => {
          pendingFetchResolvers[promiseId] = (resolvedResponse) => {
            delete pendingFetchResolvers[promiseId];
            resolve(resolvedResponse);
          };
        });

        let serializedBodyForPostMessage;
        if (typeof bodyForPostMessage === 'string' || bodyForPostMessage == null) {
            serializedBodyForPostMessage = bodyForPostMessage;
        } else if (bodyForPostMessage instanceof ReadableStream) {
            serializedBodyForPostMessage = null;
        } else {
            try {
                serializedBodyForPostMessage = JSON.stringify(bodyForPostMessage);
            } catch (e) {
                serializedBodyForPostMessage = null;
            }
        }

        const messageOptions = {
            method: effectiveOptions.method,
            headers: Object.fromEntries(new Headers(effectiveOptions.headers).entries()),
            body: serializedBodyForPostMessage
        };

        window.parent.postMessage({
          type: 'requestFetch',
          url: actualUrl,
          modelName: modelName,
          options: messageOptions,
          promiseId: promiseId,
        }, '*');

        return promise;
      }
      return originalFetch.apply(window, fetchCallArgs);
    }
    return originalFetch.apply(window, fetchCallArgs);
  };

  window.addEventListener('message', function(event) {
    if (event.data && event.data.type === 'resolveFetch') {
      const { promiseId, response } = event.data;
      if (pendingFetchResolvers[promiseId]) {
        try {
          const reconstructedResponse = new Response(response.body, {
            status: response.status,
            statusText: response.statusText,
            headers: new Headers(response.headers),
          });
          pendingFetchResolvers[promiseId](reconstructedResponse);
        } catch (error) {
          pendingFetchResolvers[promiseId](new Response(null, { status: 500, statusText: "Interceptor Response Reconstruction Error" }));
        }
      }
    }
  });

}))({"textModelName":"gemini-3-flash-preview","imageModelName":"imagen-4.0-generate-001","imageEditModelName":"gemini-3.1-flash-image-preview","imageTransformModelName":"gemini-3-pro-image-preview-11-2025","videoModelName":"veo-2.0-generate-001","ttsModelName":"gemini-2.5-flash-preview-tts","deprecatedTextModelNames":["gemini-2.0-flash","gemini-2.5-flash","gemini-2.5-flash-preview-04-17","gemini-2.5-flash-preview-05-20","gemini-2.5-flash-preview-09-2025"],"deprecatedImageModelNames":["imagen-3.0-generate-001","imagen-3.0-generate-002"],"deprecatedGenerateImageModelNames":["gemini-2.5-flash-image-preview","gemini-2.5-flash-image"]})</script><script>(function(){'use strict';function a(){window.parent.postMessage({type:"interaction"},"*")}window.addEventListener("click",a,{capture:!0,passive:!0});window.addEventListener("touchstart",a,{capture:!0,passive:!0});window.addEventListener("keydown",a,{capture:!0,passive:!0});}).call(this);
</script><script>(function() {
  const originalConsoleLog = console.log;
  const originalConsoleError = console.error;

    /**
   * Normalizes an error event or a promise rejection reason into a structured error object.
   * @param {*} errorEventOrReason The error object or reason.
   * @return {object} Structured error data { message, name, stack }.
   */
  function getErrorObject(errorEventOrReason) {
    if (errorEventOrReason instanceof Error) {
      return {
        message: errorEventOrReason.message,
        name: errorEventOrReason.name,
        stack: errorEventOrReason.stack,
      };
    }
    // Fallback for non-Error objects.
    try {
      return {
        message: JSON.stringify(errorEventOrReason),
        name: 'UnknownErrorType',
        stack: null,
      };
    } catch (e) {
      return {
        message: String(errorEventOrReason),
        name: 'UnknownErrorTypeNonStringifiable',
        stack: null,
      };
    }
  }

  /**
   * Converts an array of arguments (from log/error) into a single string.
   * Handles Error objects specially to include their message and stack.
   * @param {Array<*>} args - Arguments passed to console methods.
   * @return {string} A string representation of the arguments.
   */
  function stringifyArgs(args) {
    return args
      .map((arg) => {
        if (arg instanceof Error) {
          const {message, stack} = arg;
          return `Error: ${message}${stack ? ('\nStack: ' + stack) : ''}`;
        }
        if (typeof arg === 'object' && arg !== null) {
          try {
            return JSON.stringify(arg);
          } catch (error) {
            return '[Circular Object]';
          }
        } else {
          return String(arg);
        }
      })
      .join(' ');
  }

  console.log = function(...args) {
    const logString = stringifyArgs(args);
    window.parent.postMessage({ type: 'log', message: logString }, '*');
    originalConsoleLog.apply(console, args);
  };

  console.error = function(...args) {
    let errorData;
    if (args.length > 0 && args[0] instanceof Error) {
      const err = args[0];
      // If the first arg is an Error, capture its details.
      errorData = {
        type: 'error',
        source: 'CONSOLE_ERROR',
        ...getErrorObject(err),
        rawArgsString: stringifyArgs(args.slice(1)),
        timestamp: new Date().toISOString(),
      };
    } else {
      // If not an Error object, treat all args as a general error message.
      errorData = {
        type: 'error',
        source: 'CONSOLE_ERROR',
        message: stringifyArgs(args),
        name: 'ConsoleLoggedError',
        stack: null,
        timestamp: new Date().toISOString(),
      };
    }
    window.parent.postMessage(errorData, '*');
    originalConsoleError.apply(console, args);
  };

  // Listen for global unhandled synchronous errors.
  window.addEventListener('error', function(event) {
    const errorDetails = event.error ? getErrorObject(event.error) : {
      message: event.message,
      name: 'GlobalError',
      stack: null,
      filename: event.filename,
      lineno: event.lineno,
      colno: event.colno,
    };

    window.parent.postMessage({
      type: 'error',
      source: 'global',
      ...errorDetails,
      message: errorDetails.message || event.message,
      timestamp: new Date().toISOString(),
    }, '*');
  });

  // Listen for unhandled promise rejections (asynchronous errors).
  window.addEventListener('unhandledrejection', function(event) {
    const errorDetails = getErrorObject(event.reason);

    window.parent.postMessage({
      type: 'error',
      source: 'unhandledrejection',
      ...errorDetails,
      message: errorDetails.message || 'Unhandled Promise Rejection',
      timestamp: new Date().toISOString(),
    }, '*');
  });

})();</script>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FC Elite Clash Result and Fixture</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&amp;display=swap" rel="stylesheet">
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: #0f172a; /* Slate 900 */
        }
        .custom-scrollbar::-webkit-scrollbar {
            width: 6px;
            height: 6px;
        }
        .custom-scrollbar::-webkit-scrollbar-track {
            background: #1e293b;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb {
            background: #475569;
            border-radius: 3px;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb:hover {
            background: #64748b;
        }
    </style>
<style>*, ::before, ::after{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }::backdrop{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }/* ! tailwindcss v3.4.17 | MIT License | https://tailwindcss.com */*,::after,::before{box-sizing:border-box;border-width:0;border-style:solid;border-color:#e5e7eb}::after,::before{--tw-content:''}:host,html{line-height:1.5;-webkit-text-size-adjust:100%;-moz-tab-size:4;tab-size:4;font-family:ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";font-feature-settings:normal;font-variation-settings:normal;-webkit-tap-highlight-color:transparent}body{margin:0;line-height:inherit}hr{height:0;color:inherit;border-top-width:1px}abbr:where([title]){-webkit-text-decoration:underline dotted;text-decoration:underline dotted}h1,h2,h3,h4,h5,h6{font-size:inherit;font-weight:inherit}a{color:inherit;text-decoration:inherit}b,strong{font-weight:bolder}code,kbd,pre,samp{font-family:ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;font-feature-settings:normal;font-variation-settings:normal;font-size:1em}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sub{bottom:-.25em}sup{top:-.5em}table{text-indent:0;border-color:inherit;border-collapse:collapse}button,input,optgroup,select,textarea{font-family:inherit;font-feature-settings:inherit;font-variation-settings:inherit;font-size:100%;font-weight:inherit;line-height:inherit;letter-spacing:inherit;color:inherit;margin:0;padding:0}button,select{text-transform:none}button,input:where([type=button]),input:where([type=reset]),input:where([type=submit]){-webkit-appearance:button;background-color:transparent;background-image:none}:-moz-focusring{outline:auto}:-moz-ui-invalid{box-shadow:none}progress{vertical-align:baseline}::-webkit-inner-spin-button,::-webkit-outer-spin-button{height:auto}[type=search]{-webkit-appearance:textfield;outline-offset:-2px}::-webkit-search-decoration{-webkit-appearance:none}::-webkit-file-upload-button{-webkit-appearance:button;font:inherit}summary{display:list-item}blockquote,dd,dl,figure,h1,h2,h3,h4,h5,h6,hr,p,pre{margin:0}fieldset{margin:0;padding:0}legend{padding:0}menu,ol,ul{list-style:none;margin:0;padding:0}dialog{padding:0}textarea{resize:vertical}input::placeholder,textarea::placeholder{opacity:1;color:#9ca3af}[role=button],button{cursor:pointer}:disabled{cursor:default}audio,canvas,embed,iframe,img,object,svg,video{display:block;vertical-align:middle}img,video{max-width:100%;height:auto}[hidden]:where(:not([hidden=until-found])){display:none}.pointer-events-none{pointer-events:none}.pointer-events-auto{pointer-events:auto}.fixed{position:fixed}.absolute{position:absolute}.relative{position:relative}.sticky{position:sticky}.inset-0{inset:0px}.bottom-5{bottom:1.25rem}.right-4{right:1rem}.right-5{right:1.25rem}.top-0{top:0px}.top-4{top:1rem}.z-40{z-index:40}.z-50{z-index:50}.mx-auto{margin-left:auto;margin-right:auto}.mb-1{margin-bottom:0.25rem}.mb-2{margin-bottom:0.5rem}.mb-3{margin-bottom:0.75rem}.mt-6{margin-top:1.5rem}.block{display:block}.flex{display:flex}.inline-flex{display:inline-flex}.grid{display:grid}.hidden{display:none}.h-12{height:3rem}.h-2{height:0.5rem}.h-7{height:1.75rem}.h-2\.5{height:0.625rem}.max-h-\[350px\]{max-height:350px}.max-h-\[460px\]{max-height:460px}.min-h-screen{min-height:100vh}.w-12{width:3rem}.w-16{width:4rem}.w-2{width:0.5rem}.w-20{width:5rem}.w-full{width:100%}.w-7{width:1.75rem}.w-\[20\%\]{width:20%}.w-\[40\%\]{width:40%}.w-2\.5{width:0.625rem}.min-w-\[550px\]{min-width:550px}.max-w-7xl{max-width:80rem}.max-w-\[130px\]{max-width:130px}.max-w-md{max-width:28rem}.max-w-sm{max-width:24rem}.flex-1{flex:1 1 0%}.border-collapse{border-collapse:collapse}.translate-y-2{--tw-translate-y:0.5rem;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.translate-y-1{--tw-translate-y:0.25rem;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.transform{transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}@keyframes pulse{50%{opacity:.5}}.animate-pulse{animation:pulse 2s cubic-bezier(0.4, 0, 0.6, 1) infinite}@keyframes spin{to{transform:rotate(360deg)}}.animate-spin{animation:spin 1s linear infinite}@keyframes bounce{0%, 100%{transform:translateY(-25%);animation-timing-function:cubic-bezier(0.8,0,1,1)}50%{transform:none;animation-timing-function:cubic-bezier(0,0,0.2,1)}}.animate-bounce{animation:bounce 1s infinite}.grid-cols-1{grid-template-columns:repeat(1, minmax(0, 1fr))}.grid-cols-2{grid-template-columns:repeat(2, minmax(0, 1fr))}.grid-cols-3{grid-template-columns:repeat(3, minmax(0, 1fr))}.flex-col{flex-direction:column}.flex-wrap{flex-wrap:wrap}.items-start{align-items:flex-start}.items-center{align-items:center}.justify-center{justify-content:center}.justify-between{justify-content:space-between}.gap-1\.5{gap:0.375rem}.gap-2{gap:0.5rem}.gap-3{gap:0.75rem}.gap-4{gap:1rem}.gap-6{gap:1.5rem}.space-x-2 > :not([hidden]) ~ :not([hidden]){--tw-space-x-reverse:0;margin-right:calc(0.5rem * var(--tw-space-x-reverse));margin-left:calc(0.5rem * calc(1 - var(--tw-space-x-reverse)))}.space-x-3 > :not([hidden]) ~ :not([hidden]){--tw-space-x-reverse:0;margin-right:calc(0.75rem * var(--tw-space-x-reverse));margin-left:calc(0.75rem * calc(1 - var(--tw-space-x-reverse)))}.space-x-4 > :not([hidden]) ~ :not([hidden]){--tw-space-x-reverse:0;margin-right:calc(1rem * var(--tw-space-x-reverse));margin-left:calc(1rem * calc(1 - var(--tw-space-x-reverse)))}.space-y-1 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(0.25rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(0.25rem * var(--tw-space-y-reverse))}.space-y-2 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(0.5rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(0.5rem * var(--tw-space-y-reverse))}.space-y-3 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(0.75rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(0.75rem * var(--tw-space-y-reverse))}.space-y-4 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(1rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(1rem * var(--tw-space-y-reverse))}.space-y-5 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(1.25rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(1.25rem * var(--tw-space-y-reverse))}.space-y-6 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(1.5rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(1.5rem * var(--tw-space-y-reverse))}.divide-y > :not([hidden]) ~ :not([hidden]){--tw-divide-y-reverse:0;border-top-width:calc(1px * calc(1 - var(--tw-divide-y-reverse)));border-bottom-width:calc(1px * var(--tw-divide-y-reverse))}.divide-slate-800\/50 > :not([hidden]) ~ :not([hidden]){border-color:rgb(30 41 59 / 0.5)}.overflow-hidden{overflow:hidden}.overflow-x-auto{overflow-x:auto}.overflow-y-auto{overflow-y:auto}.truncate{overflow:hidden;text-overflow:ellipsis;white-space:nowrap}.rounded-2xl{border-radius:1rem}.rounded-full{border-radius:9999px}.rounded-lg{border-radius:0.5rem}.rounded-xl{border-radius:0.75rem}.rounded-md{border-radius:0.375rem}.border{border-width:1px}.border-2{border-width:2px}.border-b{border-bottom-width:1px}.border-t{border-top-width:1px}.border-dashed{border-style:dashed}.border-amber-500\/20{border-color:rgb(245 158 11 / 0.2)}.border-emerald-500\/20{border-color:rgb(16 185 129 / 0.2)}.border-emerald-500\/30{border-color:rgb(16 185 129 / 0.3)}.border-indigo-500{--tw-border-opacity:1;border-color:rgb(99 102 241 / var(--tw-border-opacity, 1))}.border-red-500\/20{border-color:rgb(239 68 68 / 0.2)}.border-slate-700{--tw-border-opacity:1;border-color:rgb(51 65 85 / var(--tw-border-opacity, 1))}.border-slate-800{--tw-border-opacity:1;border-color:rgb(30 41 59 / var(--tw-border-opacity, 1))}.border-slate-800\/50{border-color:rgb(30 41 59 / 0.5)}.border-slate-800\/80{border-color:rgb(30 41 59 / 0.8)}.bg-amber-500{--tw-bg-opacity:1;background-color:rgb(245 158 11 / var(--tw-bg-opacity, 1))}.bg-amber-500\/10{background-color:rgb(245 158 11 / 0.1)}.bg-emerald-500{--tw-bg-opacity:1;background-color:rgb(16 185 129 / var(--tw-bg-opacity, 1))}.bg-emerald-500\/10{background-color:rgb(16 185 129 / 0.1)}.bg-indigo-500\/10{background-color:rgb(99 102 241 / 0.1)}.bg-red-500{--tw-bg-opacity:1;background-color:rgb(239 68 68 / var(--tw-bg-opacity, 1))}.bg-red-500\/10{background-color:rgb(239 68 68 / 0.1)}.bg-rose-500\/10{background-color:rgb(244 63 94 / 0.1)}.bg-slate-800{--tw-bg-opacity:1;background-color:rgb(30 41 59 / var(--tw-bg-opacity, 1))}.bg-slate-800\/20{background-color:rgb(30 41 59 / 0.2)}.bg-slate-900{--tw-bg-opacity:1;background-color:rgb(15 23 42 / var(--tw-bg-opacity, 1))}.bg-slate-900\/20{background-color:rgb(15 23 42 / 0.2)}.bg-slate-900\/40{background-color:rgb(15 23 42 / 0.4)}.bg-slate-900\/60{background-color:rgb(15 23 42 / 0.6)}.bg-slate-900\/80{background-color:rgb(15 23 42 / 0.8)}.bg-slate-950\/40{background-color:rgb(2 6 23 / 0.4)}.bg-slate-950\/60{background-color:rgb(2 6 23 / 0.6)}.bg-slate-950\/85{background-color:rgb(2 6 23 / 0.85)}.bg-amber-500\/5{background-color:rgb(245 158 11 / 0.05)}.bg-amber-700\/10{background-color:rgb(180 83 9 / 0.1)}.bg-slate-300\/10{background-color:rgb(203 213 225 / 0.1)}.bg-slate-800\/10{background-color:rgb(30 41 59 / 0.1)}.bg-emerald-950{--tw-bg-opacity:1;background-color:rgb(2 44 34 / var(--tw-bg-opacity, 1))}.bg-gradient-to-br{background-image:linear-gradient(to bottom right, var(--tw-gradient-stops))}.bg-gradient-to-r{background-image:linear-gradient(to right, var(--tw-gradient-stops))}.bg-gradient-to-tr{background-image:linear-gradient(to top right, var(--tw-gradient-stops))}.from-emerald-400{--tw-gradient-from:#34d399 var(--tw-gradient-from-position);--tw-gradient-to:rgb(52 211 153 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.from-emerald-500{--tw-gradient-from:#10b981 var(--tw-gradient-from-position);--tw-gradient-to:rgb(16 185 129 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.from-indigo-600{--tw-gradient-from:#4f46e5 var(--tw-gradient-from-position);--tw-gradient-to:rgb(79 70 229 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.from-slate-900{--tw-gradient-from:#0f172a var(--tw-gradient-from-position);--tw-gradient-to:rgb(15 23 42 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.via-slate-800\/50{--tw-gradient-to:rgb(30 41 59 / 0)  var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), rgb(30 41 59 / 0.5) var(--tw-gradient-via-position), var(--tw-gradient-to)}.to-blue-600{--tw-gradient-to:#2563eb var(--tw-gradient-to-position)}.to-slate-900{--tw-gradient-to:#0f172a var(--tw-gradient-to-position)}.to-slate-950{--tw-gradient-to:#020617 var(--tw-gradient-to-position)}.to-teal-200{--tw-gradient-to:#99f6e4 var(--tw-gradient-to-position)}.to-teal-500{--tw-gradient-to:#14b8a6 var(--tw-gradient-to-position)}.bg-clip-text{-webkit-background-clip:text;background-clip:text}.p-2{padding:0.5rem}.p-2\.5{padding:0.625rem}.p-3{padding:0.75rem}.p-4{padding:1rem}.p-5{padding:1.25rem}.p-6{padding:1.5rem}.p-1\.5{padding:0.375rem}.px-2{padding-left:0.5rem;padding-right:0.5rem}.px-2\.5{padding-left:0.625rem;padding-right:0.625rem}.px-3{padding-left:0.75rem;padding-right:0.75rem}.px-3\.5{padding-left:0.875rem;padding-right:0.875rem}.px-4{padding-left:1rem;padding-right:1rem}.py-0\.5{padding-top:0.125rem;padding-bottom:0.125rem}.py-1{padding-top:0.25rem;padding-bottom:0.25rem}.py-1\.5{padding-top:0.375rem;padding-bottom:0.375rem}.py-10{padding-top:2.5rem;padding-bottom:2.5rem}.py-2{padding-top:0.5rem;padding-bottom:0.5rem}.py-2\.5{padding-top:0.625rem;padding-bottom:0.625rem}.py-3\.5{padding-top:0.875rem;padding-bottom:0.875rem}.py-4{padding-top:1rem;padding-bottom:1rem}.py-8{padding-top:2rem;padding-bottom:2rem}.py-3{padding-top:0.75rem;padding-bottom:0.75rem}.pb-12{padding-bottom:3rem}.pb-2{padding-bottom:0.5rem}.pb-3{padding-bottom:0.75rem}.pt-1{padding-top:0.25rem}.pt-2{padding-top:0.5rem}.pl-2{padding-left:0.5rem}.pr-2{padding-right:0.5rem}.text-left{text-align:left}.text-center{text-align:center}.text-right{text-align:right}.font-mono{font-family:ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace}.text-2xl{font-size:1.5rem;line-height:2rem}.text-\[10px\]{font-size:10px}.text-\[11px\]{font-size:11px}.text-base{font-size:1rem;line-height:1.5rem}.text-lg{font-size:1.125rem;line-height:1.75rem}.text-sm{font-size:0.875rem;line-height:1.25rem}.text-xl{font-size:1.25rem;line-height:1.75rem}.text-xs{font-size:0.75rem;line-height:1rem}.font-bold{font-weight:700}.font-extrabold{font-weight:800}.font-medium{font-weight:500}.font-semibold{font-weight:600}.font-black{font-weight:900}.uppercase{text-transform:uppercase}.leading-relaxed{line-height:1.625}.tracking-tight{letter-spacing:-0.025em}.tracking-wide{letter-spacing:0.025em}.tracking-wider{letter-spacing:0.05em}.tracking-widest{letter-spacing:0.1em}.text-slate-100{--tw-text-opacity:1;color:rgb(241 245 249 / var(--tw-text-opacity, 1))}.text-amber-400{--tw-text-opacity:1;color:rgb(251 191 36 / var(--tw-text-opacity, 1))}.text-amber-500{--tw-text-opacity:1;color:rgb(245 158 11 / var(--tw-text-opacity, 1))}.text-emerald-400{--tw-text-opacity:1;color:rgb(52 211 153 / var(--tw-text-opacity, 1))}.text-emerald-500{--tw-text-opacity:1;color:rgb(16 185 129 / var(--tw-text-opacity, 1))}.text-indigo-400{--tw-text-opacity:1;color:rgb(129 140 248 / var(--tw-text-opacity, 1))}.text-red-400{--tw-text-opacity:1;color:rgb(248 113 113 / var(--tw-text-opacity, 1))}.text-red-500{--tw-text-opacity:1;color:rgb(239 68 68 / var(--tw-text-opacity, 1))}.text-rose-400{--tw-text-opacity:1;color:rgb(251 113 133 / var(--tw-text-opacity, 1))}.text-slate-200{--tw-text-opacity:1;color:rgb(226 232 240 / var(--tw-text-opacity, 1))}.text-slate-300{--tw-text-opacity:1;color:rgb(203 213 225 / var(--tw-text-opacity, 1))}.text-slate-400{--tw-text-opacity:1;color:rgb(148 163 184 / var(--tw-text-opacity, 1))}.text-slate-500{--tw-text-opacity:1;color:rgb(100 116 139 / var(--tw-text-opacity, 1))}.text-slate-950{--tw-text-opacity:1;color:rgb(2 6 23 / var(--tw-text-opacity, 1))}.text-transparent{color:transparent}.text-white{--tw-text-opacity:1;color:rgb(255 255 255 / var(--tw-text-opacity, 1))}.text-amber-600{--tw-text-opacity:1;color:rgb(217 119 6 / var(--tw-text-opacity, 1))}.text-emerald-400\/90{color:rgb(52 211 153 / 0.9)}.text-rose-400\/90{color:rgb(251 113 133 / 0.9)}.text-emerald-300{--tw-text-opacity:1;color:rgb(110 231 183 / var(--tw-text-opacity, 1))}.opacity-60{opacity:0.6}.opacity-0{opacity:0}.shadow-2xl{--tw-shadow:0 25px 50px -12px rgb(0 0 0 / 0.25);--tw-shadow-colored:0 25px 50px -12px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.shadow-lg{--tw-shadow:0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 10px 15px -3px var(--tw-shadow-color), 0 4px 6px -4px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.shadow-xl{--tw-shadow:0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 20px 25px -5px var(--tw-shadow-color), 0 8px 10px -6px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.shadow-md{--tw-shadow:0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 4px 6px -1px var(--tw-shadow-color), 0 2px 4px -2px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.shadow-emerald-500\/10{--tw-shadow-color:rgb(16 185 129 / 0.1);--tw-shadow:var(--tw-shadow-colored)}.shadow-emerald-500\/20{--tw-shadow-color:rgb(16 185 129 / 0.2);--tw-shadow:var(--tw-shadow-colored)}.shadow-indigo-600\/20{--tw-shadow-color:rgb(79 70 229 / 0.2);--tw-shadow:var(--tw-shadow-colored)}.shadow-red-500\/15{--tw-shadow-color:rgb(239 68 68 / 0.15);--tw-shadow:var(--tw-shadow-colored)}.shadow-emerald-500\/50{--tw-shadow-color:rgb(16 185 129 / 0.5);--tw-shadow:var(--tw-shadow-colored)}.ring-1{--tw-ring-offset-shadow:var(--tw-ring-inset) 0 0 0 var(--tw-ring-offset-width) var(--tw-ring-offset-color);--tw-ring-shadow:var(--tw-ring-inset) 0 0 0 calc(1px + var(--tw-ring-offset-width)) var(--tw-ring-color);box-shadow:var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow, 0 0 #0000)}.ring-amber-500\/20{--tw-ring-color:rgb(245 158 11 / 0.2)}.ring-amber-700\/20{--tw-ring-color:rgb(180 83 9 / 0.2)}.ring-slate-300\/20{--tw-ring-color:rgb(203 213 225 / 0.2)}.backdrop-blur{--tw-backdrop-blur:blur(8px);-webkit-backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia);backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia)}.backdrop-blur-sm{--tw-backdrop-blur:blur(4px);-webkit-backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia);backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia)}.transition-all{transition-property:all;transition-timing-function:cubic-bezier(0.4, 0, 0.2, 1);transition-duration:150ms}.transition-colors{transition-property:color, background-color, border-color, fill, stroke, -webkit-text-decoration-color;transition-property:color, background-color, border-color, text-decoration-color, fill, stroke;transition-property:color, background-color, border-color, text-decoration-color, fill, stroke, -webkit-text-decoration-color;transition-timing-function:cubic-bezier(0.4, 0, 0.2, 1);transition-duration:150ms}.transition-opacity{transition-property:opacity;transition-timing-function:cubic-bezier(0.4, 0, 0.2, 1);transition-duration:150ms}.duration-300{transition-duration:300ms}.hover\:border-slate-700\/80:hover{border-color:rgb(51 65 85 / 0.8)}.hover\:bg-emerald-400:hover{--tw-bg-opacity:1;background-color:rgb(52 211 153 / var(--tw-bg-opacity, 1))}.hover\:bg-red-500\/20:hover{background-color:rgb(239 68 68 / 0.2)}.hover\:bg-red-600:hover{--tw-bg-opacity:1;background-color:rgb(220 38 38 / var(--tw-bg-opacity, 1))}.hover\:bg-slate-700:hover{--tw-bg-opacity:1;background-color:rgb(51 65 85 / var(--tw-bg-opacity, 1))}.hover\:bg-slate-800\/40:hover{background-color:rgb(30 41 59 / 0.4)}.hover\:from-indigo-500:hover{--tw-gradient-from:#6366f1 var(--tw-gradient-from-position);--tw-gradient-to:rgb(99 102 241 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.hover\:to-blue-500:hover{--tw-gradient-to:#3b82f6 var(--tw-gradient-to-position)}.hover\:text-slate-100:hover{--tw-text-opacity:1;color:rgb(241 245 249 / var(--tw-text-opacity, 1))}.hover\:text-emerald-400:hover{--tw-text-opacity:1;color:rgb(52 211 153 / var(--tw-text-opacity, 1))}.focus\:outline-none:focus{outline:2px solid transparent;outline-offset:2px}.focus\:ring-1:focus{--tw-ring-offset-shadow:var(--tw-ring-inset) 0 0 0 var(--tw-ring-offset-width) var(--tw-ring-offset-color);--tw-ring-shadow:var(--tw-ring-inset) 0 0 0 calc(1px + var(--tw-ring-offset-width)) var(--tw-ring-color);box-shadow:var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow, 0 0 #0000)}.focus\:ring-2:focus{--tw-ring-offset-shadow:var(--tw-ring-inset) 0 0 0 var(--tw-ring-offset-width) var(--tw-ring-offset-color);--tw-ring-shadow:var(--tw-ring-inset) 0 0 0 calc(2px + var(--tw-ring-offset-width)) var(--tw-ring-color);box-shadow:var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow, 0 0 #0000)}.focus\:ring-emerald-500:focus{--tw-ring-opacity:1;--tw-ring-color:rgb(16 185 129 / var(--tw-ring-opacity, 1))}.active\:scale-95:active{--tw-scale-x:.95;--tw-scale-y:.95;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}@media (min-width: 768px){.md\:flex-row{flex-direction:row}.md\:items-center{align-items:center}.md\:text-sm{font-size:0.875rem;line-height:1.25rem}.md\:text-xl{font-size:1.25rem;line-height:1.75rem}}@media (min-width: 1024px){.lg\:col-span-2{grid-column:span 2 / span 2}.lg\:col-span-5{grid-column:span 5 / span 5}.lg\:col-span-7{grid-column:span 7 / span 7}.lg\:grid-cols-12{grid-template-columns:repeat(12, minmax(0, 1fr))}.lg\:grid-cols-3{grid-template-columns:repeat(3, minmax(0, 1fr))}.lg\:grid-cols-4{grid-template-columns:repeat(4, minmax(0, 1fr))}}</style><script src="https://apis.google.com/js/api.js?onload=__iframefcb439110" type="text/javascript" charset="UTF-8" gapi_processed="true"></script></head>
<body class="text-slate-100 min-h-screen flex flex-col pb-12">

    <!-- Header / Navbar -->
    <header class="border-b border-slate-800 bg-slate-900/80 backdrop-blur sticky top-0 z-40 px-4 py-4">
        <div class="max-w-7xl mx-auto flex flex-wrap items-center justify-between gap-4">
            <div class="flex items-center space-x-3">
                <div class="bg-gradient-to-tr from-emerald-500 to-teal-500 p-2.5 rounded-xl shadow-lg shadow-emerald-500/20">
                    <i class="fa-solid fa-trophy text-slate-950 text-xl"></i>
                </div>
                <div>
                    <h1 class="text-lg md:text-xl font-extrabold tracking-tight bg-gradient-to-r from-emerald-400 to-teal-200 bg-clip-text text-transparent">
                        FC ELITE CLASH
                    </h1>
                    <p class="text-xs text-slate-400 font-medium flex items-center gap-1.5">
                        <span id="sync-status-dot" class="w-2.5 h-2.5 rounded-full bg-emerald-500 shadow-md shadow-emerald-500/50"></span>
                        <span id="sync-status-text">Live - Synced with Cloud</span>
                    </p>
                </div>
            </div>

            <div class="flex items-center space-x-2 flex-wrap gap-2">
                <!-- SPECIAL DEVELOPER COPY CODE BUTTON (USER REQUESTED) -->
                <button id="copy-source-btn" class="px-3.5 py-2 bg-gradient-to-r from-indigo-600 to-blue-600 hover:from-indigo-500 hover:to-blue-500 active:scale-95 transition-all text-xs md:text-sm font-bold rounded-xl border border-indigo-500 flex items-center gap-2 text-white shadow-lg shadow-indigo-600/20">
                    <i class="fa-solid fa-code"></i>
                    <span>Copy Website Code</span>
                </button>

                <!-- Share Button -->
                <button id="share-btn" class="px-3.5 py-2 bg-slate-800 hover:bg-slate-700 active:scale-95 transition-all text-xs md:text-sm font-semibold rounded-xl border border-slate-700 flex items-center gap-2 text-emerald-400">
                    <i class="fa-solid fa-share-nodes"></i>
                    <span>Share Website</span>
                </button>
                
                <!-- Admin Lock/Unlock Button -->
                <button id="admin-toggle-btn" class="px-4 py-2 bg-slate-800 hover:bg-slate-700 active:scale-95 transition-all text-xs md:text-sm font-semibold rounded-xl border border-slate-700 flex items-center gap-2">
                    <i id="admin-icon" class="fa-solid fa-lock text-amber-500"></i>
                    <span id="admin-btn-text">Admin Mode</span>
                </button>
            </div>
        </div>
    </header>

    <main class="max-w-7xl mx-auto w-full px-4 mt-6 flex-1 space-y-6">

        <!-- Info / Welcome banner for Touhid & teams -->
        <div class="bg-gradient-to-r from-slate-900 via-slate-800/50 to-slate-900 border border-slate-800 rounded-2xl p-6 flex flex-col md:flex-row items-start md:items-center justify-between gap-4 shadow-xl">
            <div class="space-y-1">
                <h2 class="text-lg font-bold text-slate-100">🏆 FC Elite Clash Live Results &amp; Fixtures</h2>
                <p class="text-sm text-slate-400">Welcome to the official dashboard. 8 Teams, 14 Matchdays, Double Round-Robin. Real-time updates managed by Touhid.</p>
            </div>
            <div class="flex flex-wrap gap-2 text-xs">
                <span class="bg-slate-800 border border-slate-700 px-3 py-1.5 rounded-full text-slate-300 font-medium">
                    ⚽ 3 pts for a Win
                </span>
                <span class="bg-slate-800 border border-slate-700 px-3 py-1.5 rounded-full text-slate-300 font-medium">
                    🤝 1 pt for a Draw
                </span>
            </div>
        </div>

        <!-- Dashboard Stat Cards -->
        <div class="grid grid-cols-2 lg:grid-cols-4 gap-4">
            <div class="bg-slate-900/60 border border-slate-800/80 p-4 rounded-2xl flex items-center space-x-4">
                <div class="p-3 bg-indigo-500/10 text-indigo-400 rounded-xl"><i class="fa-solid fa-users text-xl"></i></div>
                <div>
                    <p class="text-xs text-slate-400 font-medium">Total Teams</p>
                    <p class="text-xl font-bold text-slate-100" id="stat-total-teams">8</p>
                </div>
            </div>
            <div class="bg-slate-900/60 border border-slate-800/80 p-4 rounded-2xl flex items-center space-x-4">
                <div class="p-3 bg-emerald-500/10 text-emerald-400 rounded-xl"><i class="fa-solid fa-circle-play text-xl"></i></div>
                <div>
                    <p class="text-xs text-slate-400 font-medium">Matches Played</p>
                    <p class="text-xl font-bold text-slate-100" id="stat-matches-played">0</p>
                </div>
            </div>
            <div class="bg-slate-900/60 border border-slate-800/80 p-4 rounded-2xl flex items-center space-x-4">
                <div class="p-3 bg-amber-500/10 text-amber-400 rounded-xl"><i class="fa-solid fa-soccer-ball text-xl"></i></div>
                <div>
                    <p class="text-xs text-slate-400 font-medium">Total Goals</p>
                    <p class="text-xl font-bold text-slate-100" id="stat-total-goals">0</p>
                </div>
            </div>
            <div class="bg-slate-900/60 border border-slate-800/80 p-4 rounded-2xl flex items-center space-x-4">
                <div class="p-3 bg-rose-500/10 text-rose-400 rounded-xl"><i class="fa-solid fa-crown text-xl"></i></div>
                <div>
                    <p class="text-xs text-slate-400 font-medium">Current Leader</p>
                    <p class="text-lg font-bold text-rose-400 truncate max-w-[130px]" id="stat-leader">Amith</p>
                </div>
            </div>
        </div>

        <!-- Live Standings and Fixtures Split -->
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
            
            <!-- League Table Panel (Takes 7 columns) -->
            <div class="lg:col-span-7 bg-slate-900/60 border border-slate-800/80 rounded-2xl shadow-xl overflow-hidden flex flex-col">
                <div class="p-5 border-b border-slate-800/80 bg-slate-900/40 flex justify-between items-center">
                    <h3 class="font-bold text-slate-200 flex items-center gap-2">
                        <i class="fa-solid fa-list-ol text-emerald-500"></i> Live Standings
                    </h3>
                    <div id="admin-indicator" class="hidden px-2.5 py-1 bg-emerald-500/10 border border-emerald-500/20 text-emerald-400 rounded-lg text-xs font-bold animate-pulse">
                        <i class="fa-solid fa-user-gear"></i> Admin Active
                    </div>
                </div>
                
                <div class="overflow-x-auto custom-scrollbar">
                    <table class="w-full text-left border-collapse min-w-[550px]">
                        <thead>
                            <tr class="border-b border-slate-800/80 text-slate-400 text-xs font-semibold uppercase tracking-wider bg-slate-900/20">
                                <th class="py-3.5 px-4 text-center w-12">Pos</th>
                                <th class="py-3.5 px-4">Team</th>
                                <th class="py-3.5 px-3 text-center w-12">P</th>
                                <th class="py-3.5 px-3 text-center w-12">W</th>
                                <th class="py-3.5 px-3 text-center w-12">D</th>
                                <th class="py-3.5 px-3 text-center w-12">L</th>
                                <th class="py-3.5 px-3 text-center w-12">GD</th>
                                <th class="py-3.5 px-4 text-center w-16 bg-slate-800/20">PTS</th>
                                <th class="py-3.5 px-4 text-center w-20 admin-actions hidden">Actions</th>
                            </tr>
                        </thead>
                        <tbody id="league-table-body" class="divide-y divide-slate-800/50 text-sm"><tr class="hover:bg-slate-800/40 transition-colors bg-amber-500/5">
                    <td class="py-3 px-4 text-center">
                        <span class="inline-flex items-center justify-center w-7 h-7 rounded-lg text-xs bg-amber-500/10 text-amber-500 font-extrabold ring-1 ring-amber-500/20">
                            1
                        </span>
                    </td>
                    <td class="py-3 px-4 font-semibold text-slate-100">
                        <div class="flex items-center space-x-2">
                            <span>Amith</span>
                            <i class="fa-solid fa-crown text-amber-500 text-xs animate-bounce"></i>
                        </div>
                    </td>
                    <td class="py-3 px-3 text-center text-slate-300 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-emerald-400/90 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-slate-400 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-rose-400/90 font-medium">0</td>
                    <td class="py-3 px-3 text-center font-bold text-slate-400">
                        0
                    </td>
                    <td class="py-3 px-4 text-center font-black text-slate-100 bg-slate-800/10 text-base">0</td>
                    <td class="py-3 px-4 text-center admin-actions hidden">
                        <button onclick="window.openEditModal('team-8')" class="p-1.5 bg-slate-800 hover:bg-slate-700 text-slate-300 rounded-lg hover:text-emerald-400 active:scale-95 transition-all text-xs border border-slate-700">
                            <i class="fa-regular fa-pen-to-square"></i> Edit
                        </button>
                    </td>
                </tr><tr class="hover:bg-slate-800/40 transition-colors ">
                    <td class="py-3 px-4 text-center">
                        <span class="inline-flex items-center justify-center w-7 h-7 rounded-lg text-xs bg-slate-300/10 text-slate-300 font-bold ring-1 ring-slate-300/20">
                            2
                        </span>
                    </td>
                    <td class="py-3 px-4 font-semibold text-slate-100">
                        <div class="flex items-center space-x-2">
                            <span>Ashraf</span>
                            
                        </div>
                    </td>
                    <td class="py-3 px-3 text-center text-slate-300 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-emerald-400/90 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-slate-400 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-rose-400/90 font-medium">0</td>
                    <td class="py-3 px-3 text-center font-bold text-slate-400">
                        0
                    </td>
                    <td class="py-3 px-4 text-center font-black text-slate-100 bg-slate-800/10 text-base">0</td>
                    <td class="py-3 px-4 text-center admin-actions hidden">
                        <button onclick="window.openEditModal('team-7')" class="p-1.5 bg-slate-800 hover:bg-slate-700 text-slate-300 rounded-lg hover:text-emerald-400 active:scale-95 transition-all text-xs border border-slate-700">
                            <i class="fa-regular fa-pen-to-square"></i> Edit
                        </button>
                    </td>
                </tr><tr class="hover:bg-slate-800/40 transition-colors ">
                    <td class="py-3 px-4 text-center">
                        <span class="inline-flex items-center justify-center w-7 h-7 rounded-lg text-xs bg-amber-700/10 text-amber-600 font-bold ring-1 ring-amber-700/20">
                            3
                        </span>
                    </td>
                    <td class="py-3 px-4 font-semibold text-slate-100">
                        <div class="flex items-center space-x-2">
                            <span>Comeonbro</span>
                            
                        </div>
                    </td>
                    <td class="py-3 px-3 text-center text-slate-300 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-emerald-400/90 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-slate-400 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-rose-400/90 font-medium">0</td>
                    <td class="py-3 px-3 text-center font-bold text-slate-400">
                        0
                    </td>
                    <td class="py-3 px-4 text-center font-black text-slate-100 bg-slate-800/10 text-base">0</td>
                    <td class="py-3 px-4 text-center admin-actions hidden">
                        <button onclick="window.openEditModal('team-6')" class="p-1.5 bg-slate-800 hover:bg-slate-700 text-slate-300 rounded-lg hover:text-emerald-400 active:scale-95 transition-all text-xs border border-slate-700">
                            <i class="fa-regular fa-pen-to-square"></i> Edit
                        </button>
                    </td>
                </tr><tr class="hover:bg-slate-800/40 transition-colors ">
                    <td class="py-3 px-4 text-center">
                        <span class="inline-flex items-center justify-center w-7 h-7 rounded-lg text-xs text-slate-400">
                            4
                        </span>
                    </td>
                    <td class="py-3 px-4 font-semibold text-slate-100">
                        <div class="flex items-center space-x-2">
                            <span>Olderback</span>
                            
                        </div>
                    </td>
                    <td class="py-3 px-3 text-center text-slate-300 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-emerald-400/90 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-slate-400 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-rose-400/90 font-medium">0</td>
                    <td class="py-3 px-3 text-center font-bold text-slate-400">
                        0
                    </td>
                    <td class="py-3 px-4 text-center font-black text-slate-100 bg-slate-800/10 text-base">0</td>
                    <td class="py-3 px-4 text-center admin-actions hidden">
                        <button onclick="window.openEditModal('team-5')" class="p-1.5 bg-slate-800 hover:bg-slate-700 text-slate-300 rounded-lg hover:text-emerald-400 active:scale-95 transition-all text-xs border border-slate-700">
                            <i class="fa-regular fa-pen-to-square"></i> Edit
                        </button>
                    </td>
                </tr><tr class="hover:bg-slate-800/40 transition-colors ">
                    <td class="py-3 px-4 text-center">
                        <span class="inline-flex items-center justify-center w-7 h-7 rounded-lg text-xs text-slate-400">
                            5
                        </span>
                    </td>
                    <td class="py-3 px-4 font-semibold text-slate-100">
                        <div class="flex items-center space-x-2">
                            <span>pichi</span>
                            
                        </div>
                    </td>
                    <td class="py-3 px-3 text-center text-slate-300 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-emerald-400/90 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-slate-400 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-rose-400/90 font-medium">0</td>
                    <td class="py-3 px-3 text-center font-bold text-slate-400">
                        0
                    </td>
                    <td class="py-3 px-4 text-center font-black text-slate-100 bg-slate-800/10 text-base">0</td>
                    <td class="py-3 px-4 text-center admin-actions hidden">
                        <button onclick="window.openEditModal('team-3')" class="p-1.5 bg-slate-800 hover:bg-slate-700 text-slate-300 rounded-lg hover:text-emerald-400 active:scale-95 transition-all text-xs border border-slate-700">
                            <i class="fa-regular fa-pen-to-square"></i> Edit
                        </button>
                    </td>
                </tr><tr class="hover:bg-slate-800/40 transition-colors ">
                    <td class="py-3 px-4 text-center">
                        <span class="inline-flex items-center justify-center w-7 h-7 rounded-lg text-xs text-slate-400">
                            6
                        </span>
                    </td>
                    <td class="py-3 px-4 font-semibold text-slate-100">
                        <div class="flex items-center space-x-2">
                            <span>Rejuwan</span>
                            
                        </div>
                    </td>
                    <td class="py-3 px-3 text-center text-slate-300 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-emerald-400/90 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-slate-400 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-rose-400/90 font-medium">0</td>
                    <td class="py-3 px-3 text-center font-bold text-slate-400">
                        0
                    </td>
                    <td class="py-3 px-4 text-center font-black text-slate-100 bg-slate-800/10 text-base">0</td>
                    <td class="py-3 px-4 text-center admin-actions hidden">
                        <button onclick="window.openEditModal('team-2')" class="p-1.5 bg-slate-800 hover:bg-slate-700 text-slate-300 rounded-lg hover:text-emerald-400 active:scale-95 transition-all text-xs border border-slate-700">
                            <i class="fa-regular fa-pen-to-square"></i> Edit
                        </button>
                    </td>
                </tr><tr class="hover:bg-slate-800/40 transition-colors ">
                    <td class="py-3 px-4 text-center">
                        <span class="inline-flex items-center justify-center w-7 h-7 rounded-lg text-xs text-slate-400">
                            7
                        </span>
                    </td>
                    <td class="py-3 px-4 font-semibold text-slate-100">
                        <div class="flex items-center space-x-2">
                            <span>Tahsan</span>
                            
                        </div>
                    </td>
                    <td class="py-3 px-3 text-center text-slate-300 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-emerald-400/90 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-slate-400 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-rose-400/90 font-medium">0</td>
                    <td class="py-3 px-3 text-center font-bold text-slate-400">
                        0
                    </td>
                    <td class="py-3 px-4 text-center font-black text-slate-100 bg-slate-800/10 text-base">0</td>
                    <td class="py-3 px-4 text-center admin-actions hidden">
                        <button onclick="window.openEditModal('team-4')" class="p-1.5 bg-slate-800 hover:bg-slate-700 text-slate-300 rounded-lg hover:text-emerald-400 active:scale-95 transition-all text-xs border border-slate-700">
                            <i class="fa-regular fa-pen-to-square"></i> Edit
                        </button>
                    </td>
                </tr><tr class="hover:bg-slate-800/40 transition-colors ">
                    <td class="py-3 px-4 text-center">
                        <span class="inline-flex items-center justify-center w-7 h-7 rounded-lg text-xs text-slate-400">
                            8
                        </span>
                    </td>
                    <td class="py-3 px-4 font-semibold text-slate-100">
                        <div class="flex items-center space-x-2">
                            <span>Touhid</span>
                            
                        </div>
                    </td>
                    <td class="py-3 px-3 text-center text-slate-300 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-emerald-400/90 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-slate-400 font-medium">0</td>
                    <td class="py-3 px-3 text-center text-rose-400/90 font-medium">0</td>
                    <td class="py-3 px-3 text-center font-bold text-slate-400">
                        0
                    </td>
                    <td class="py-3 px-4 text-center font-black text-slate-100 bg-slate-800/10 text-base">0</td>
                    <td class="py-3 px-4 text-center admin-actions hidden">
                        <button onclick="window.openEditModal('team-1')" class="p-1.5 bg-slate-800 hover:bg-slate-700 text-slate-300 rounded-lg hover:text-emerald-400 active:scale-95 transition-all text-xs border border-slate-700">
                            <i class="fa-regular fa-pen-to-square"></i> Edit
                        </button>
                    </td>
                </tr></tbody>
                    </table>
                </div>
            </div>

            <!-- Complete Fixtures / Match Day Panel (Takes 5 columns) -->
            <div class="lg:col-span-5 bg-slate-900/60 border border-slate-800/80 rounded-2xl shadow-xl overflow-hidden flex flex-col">
                <div class="p-4 border-b border-slate-800/80 bg-slate-900/40 space-y-3">
                    <div class="flex items-center justify-between">
                        <h3 class="font-bold text-slate-200 flex items-center gap-2 text-sm">
                            <i class="fa-solid fa-calendar-days text-emerald-400"></i> Season Fixtures
                        </h3>
                        <span class="text-xs bg-emerald-500/10 text-emerald-400 px-2.5 py-1 rounded-full font-bold">14 Rounds</span>
                    </div>
                    
                    <!-- Round Selectors & Team Filters -->
                    <div class="flex flex-wrap gap-2 items-center justify-between">
                        <div class="flex items-center space-x-2">
                            <label for="round-select" class="text-xs text-slate-400">Round:</label>
                            <select id="round-select" class="bg-slate-800 border border-slate-700 text-slate-200 text-xs rounded-lg px-2.5 py-1 focus:ring-1 focus:ring-emerald-500 focus:outline-none"><option value="1">Round 1</option><option value="2">Round 2</option><option value="3">Round 3</option><option value="4">Round 4</option><option value="5">Round 5</option><option value="6">Round 6</option><option value="7">Round 7</option><option value="8">Round 8</option><option value="9">Round 9</option><option value="10">Round 10</option><option value="11">Round 11</option><option value="12">Round 12</option><option value="13">Round 13</option><option value="14">Round 14</option></select>
                        </div>
                        <div class="flex items-center space-x-2">
                            <label for="filter-team-select" class="text-xs text-slate-400">Filter Team:</label>
                            <select id="filter-team-select" class="bg-slate-800 border border-slate-700 text-slate-200 text-xs rounded-lg px-2.5 py-1 focus:ring-1 focus:ring-emerald-500 focus:outline-none">
                                <option value="all">All Teams</option>
                                <!-- Team options here -->
                            <option value="team-1">Touhid</option><option value="team-2">Rejuwan</option><option value="team-3">pichi</option><option value="team-4">Tahsan</option><option value="team-5">Olderback</option><option value="team-6">Comeonbro</option><option value="team-7">Ashraf</option><option value="team-8">Amith</option></select>
                        </div>
                    </div>
                </div>

                <!-- Fixtures List -->
                <div id="fixtures-container" class="p-4 space-y-3 overflow-y-auto max-h-[460px] custom-scrollbar"><div class="bg-slate-900/80 border border-slate-800 p-3 rounded-xl hover:border-slate-700/80 transition-all">
                    <div class="flex items-center justify-between text-[11px] text-slate-400 mb-2">
                        <span class="font-semibold text-slate-500">Match 1</span>
                        <div class="flex items-center gap-1.5">
                            <i class="fa-regular fa-clock"></i>
                            <span>Kick-off: <strong class="text-indigo-400 font-medium">6:00 PM</strong></span>
                        </div>
                    </div>

                    <div class="flex items-center justify-between text-xs">
                        <div class="w-[40%] truncate text-right pr-2">
                            <span class="font-semibold text-slate-100">Touhid</span>
                        </div>

                        <div class="w-[20%] text-center">
                            
                                <span class="bg-slate-800 text-slate-400 px-2 py-0.5 rounded-md font-bold text-[10px] uppercase">
                                    VS
                                </span>
                            
                        </div>

                        <div class="w-[40%] truncate text-left pl-2">
                            <span class="font-semibold text-slate-100">Rejuwan</span>
                        </div>
                    </div>

                    
                </div><div class="bg-slate-900/80 border border-slate-800 p-3 rounded-xl hover:border-slate-700/80 transition-all">
                    <div class="flex items-center justify-between text-[11px] text-slate-400 mb-2">
                        <span class="font-semibold text-slate-500">Match 2</span>
                        <div class="flex items-center gap-1.5">
                            <i class="fa-regular fa-clock"></i>
                            <span>Kick-off: <strong class="text-indigo-400 font-medium">1:30 PM</strong></span>
                        </div>
                    </div>

                    <div class="flex items-center justify-between text-xs">
                        <div class="w-[40%] truncate text-right pr-2">
                            <span class="font-semibold text-slate-100">Tahsan</span>
                        </div>

                        <div class="w-[20%] text-center">
                            
                                <span class="bg-slate-800 text-slate-400 px-2 py-0.5 rounded-md font-bold text-[10px] uppercase">
                                    VS
                                </span>
                            
                        </div>

                        <div class="w-[40%] truncate text-left pl-2">
                            <span class="font-semibold text-slate-100">Olderback</span>
                        </div>
                    </div>

                    
                </div><div class="bg-slate-900/80 border border-slate-800 p-3 rounded-xl hover:border-slate-700/80 transition-all">
                    <div class="flex items-center justify-between text-[11px] text-slate-400 mb-2">
                        <span class="font-semibold text-slate-500">Match 3</span>
                        <div class="flex items-center gap-1.5">
                            <i class="fa-regular fa-clock"></i>
                            <span>Kick-off: <strong class="text-indigo-400 font-medium">8:15 PM</strong></span>
                        </div>
                    </div>

                    <div class="flex items-center justify-between text-xs">
                        <div class="w-[40%] truncate text-right pr-2">
                            <span class="font-semibold text-slate-100">Ashraf</span>
                        </div>

                        <div class="w-[20%] text-center">
                            
                                <span class="bg-slate-800 text-slate-400 px-2 py-0.5 rounded-md font-bold text-[10px] uppercase">
                                    VS
                                </span>
                            
                        </div>

                        <div class="w-[40%] truncate text-left pl-2">
                            <span class="font-semibold text-slate-100">Comeonbro</span>
                        </div>
                    </div>

                    
                </div><div class="bg-slate-900/80 border border-slate-800 p-3 rounded-xl hover:border-slate-700/80 transition-all">
                    <div class="flex items-center justify-between text-[11px] text-slate-400 mb-2">
                        <span class="font-semibold text-slate-500">Match 4</span>
                        <div class="flex items-center gap-1.5">
                            <i class="fa-regular fa-clock"></i>
                            <span>Kick-off: <strong class="text-indigo-400 font-medium">3:45 PM</strong></span>
                        </div>
                    </div>

                    <div class="flex items-center justify-between text-xs">
                        <div class="w-[40%] truncate text-right pr-2">
                            <span class="font-semibold text-slate-100">Amith</span>
                        </div>

                        <div class="w-[20%] text-center">
                            
                                <span class="bg-slate-800 text-slate-400 px-2 py-0.5 rounded-md font-bold text-[10px] uppercase">
                                    VS
                                </span>
                            
                        </div>

                        <div class="w-[40%] truncate text-left pl-2">
                            <span class="font-semibold text-slate-100">pichi</span>
                        </div>
                    </div>

                    
                </div></div>
            </div>
        </div>

        <!-- Submit Results Feed Area -->
        <div class="grid grid-cols-1 lg:grid-cols-3 gap-6">
            
            <!-- Match Feed / History Center -->
            <div class="lg:col-span-2 bg-slate-900/60 border border-slate-800/80 rounded-2xl shadow-xl overflow-hidden flex flex-col">
                <div class="p-4 border-b border-slate-800/80 bg-slate-900/40 flex justify-between items-center">
                    <h3 class="font-bold text-slate-200 flex items-center gap-2 text-sm">
                        <i class="fa-regular fa-clock text-indigo-400"></i> Match History (Played)
                    </h3>
                    <span id="match-count" class="text-xs bg-slate-800 text-slate-300 px-2.5 py-1 rounded-full font-medium">0 played</span>
                </div>

                <div id="match-feed-container" class="p-4 space-y-3 max-h-[350px] overflow-y-auto custom-scrollbar">
                    <div class="text-center py-8 text-slate-500 text-xs">
                        <i class="fa-solid fa-calendar-xmark text-lg mb-1 block opacity-60"></i>
                        No matches played yet.
                    </div>
                </div>
                
                <div id="admin-clear-btn-container" class="hidden p-3 bg-slate-950/40 border-t border-slate-800/50">
                    <button id="reset-tournament-btn" class="w-full py-1.5 bg-red-500/10 hover:bg-red-500/20 text-red-400 border border-red-500/20 rounded-xl text-xs font-semibold flex items-center justify-center gap-1.5 transition-colors">
                        <i class="fa-solid fa-trash-can"></i> Reset All Data
                    </button>
                </div>
            </div>

            <!-- Admin Match Result Entry Form -->
            <div class="space-y-6">
                <div id="admin-match-form-card" class="hidden bg-gradient-to-br from-slate-900 to-slate-950 border-2 border-dashed border-emerald-500/30 p-5 rounded-2xl shadow-2xl space-y-4">
                    <div class="flex justify-between items-center border-b border-slate-800 pb-3">
                        <h3 class="font-bold text-emerald-400 text-sm tracking-wide uppercase flex items-center gap-2">
                            <i class="fa-solid fa-circle-plus"></i> Submit Match Result
                        </h3>
                        <span class="text-[10px] bg-emerald-500/10 text-emerald-400 px-2 py-0.5 rounded-full font-semibold">Admin Panel</span>
                    </div>
                    
                    <form id="match-form" class="space-y-4">
                        <div class="grid grid-cols-2 gap-3">
                            <!-- Team A Selector -->
                            <div class="space-y-1">
                                <label class="text-[11px] font-semibold text-slate-400 uppercase">Home Team</label>
                                <select id="home-team-select" class="w-full bg-slate-800 border border-slate-700 text-slate-100 rounded-xl px-3 py-2 text-xs focus:ring-2 focus:ring-emerald-500 focus:outline-none" required=""><option value="">Choose team...</option><option value="team-8">Amith</option><option value="team-7">Ashraf</option><option value="team-6">Comeonbro</option><option value="team-5">Olderback</option><option value="team-3">pichi</option><option value="team-2">Rejuwan</option><option value="team-4">Tahsan</option><option value="team-1">Touhid</option></select>
                            </div>
                            <!-- Team B Selector -->
                            <div class="space-y-1">
                                <label class="text-[11px] font-semibold text-slate-400 uppercase">Away Team</label>
                                <select id="away-team-select" class="w-full bg-slate-800 border border-slate-700 text-slate-100 rounded-xl px-3 py-2 text-xs focus:ring-2 focus:ring-emerald-500 focus:outline-none" required=""><option value="">Choose team...</option><option value="team-8">Amith</option><option value="team-7">Ashraf</option><option value="team-6">Comeonbro</option><option value="team-5">Olderback</option><option value="team-3">pichi</option><option value="team-2">Rejuwan</option><option value="team-4">Tahsan</option><option value="team-1">Touhid</option></select>
                            </div>
                        </div>

                        <div class="grid grid-cols-2 gap-3">
                            <!-- Score A -->
                            <div class="space-y-1">
                                <label class="text-[11px] font-semibold text-slate-400 uppercase">Home Score</label>
                                <input type="number" id="home-score-input" min="0" placeholder="0" class="w-full bg-slate-800 border border-slate-700 text-slate-100 rounded-xl px-3 py-2 text-center text-sm focus:ring-2 focus:ring-emerald-500 focus:outline-none" required="">
                            </div>
                            <!-- Score B -->
                            <div class="space-y-1">
                                <label class="text-[11px] font-semibold text-slate-400 uppercase">Away Score</label>
                                <input type="number" id="away-score-input" min="0" placeholder="0" class="w-full bg-slate-800 border border-slate-700 text-slate-100 rounded-xl px-3 py-2 text-center text-sm focus:ring-2 focus:ring-emerald-500 focus:outline-none" required="">
                            </div>
                        </div>

                        <div class="pt-2">
                            <button type="submit" class="w-full py-2.5 bg-emerald-500 hover:bg-emerald-400 active:scale-95 text-slate-950 font-bold text-xs uppercase tracking-wider rounded-xl shadow-lg shadow-emerald-500/20 transition-all flex items-center justify-center gap-2">
                                <i class="fa-solid fa-circle-check"></i> Post Match Result
                            </button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </main>

    <!-- Admin Authentication Modal (HINT REMOVED) -->
    <div id="admin-modal" class="fixed inset-0 bg-slate-950/85 backdrop-blur-sm z-50 flex items-center justify-center p-4 hidden transition-opacity duration-300">
        <div class="bg-slate-900 border border-slate-800 rounded-2xl max-w-sm w-full p-6 shadow-2xl relative space-y-5 animate-scale-up">
            <button id="close-modal-btn" class="absolute top-4 right-4 text-slate-400 hover:text-slate-100 transition-colors">
                <i class="fa-solid fa-xmark text-lg"></i>
            </button>
            
            <div class="text-center space-y-2">
                <div class="mx-auto w-12 h-12 bg-amber-500/10 text-amber-500 rounded-full flex items-center justify-center text-xl mb-3 border border-amber-500/20">
                    <i class="fa-solid fa-shield-halved"></i>
                </div>
                <h3 class="text-lg font-bold text-slate-100">Unlock Admin Access</h3>
                <p class="text-xs text-slate-400">Only Touhid should modify league results and team standing points.</p>
            </div>

            <div class="space-y-3">
                <div>
                    <label class="text-[10px] font-bold text-slate-400 uppercase tracking-wider block mb-1">Enter Secret Code</label>
                    <input type="password" id="passcode-input" placeholder="••••••••" class="w-full bg-slate-800 border border-slate-700 text-slate-100 rounded-xl px-4 py-2.5 text-center font-mono text-lg tracking-widest focus:ring-2 focus:ring-emerald-500 focus:outline-none">
                </div>
                
                <div class="flex flex-col gap-1.5">
                    <button id="submit-passcode-btn" class="w-full py-2.5 bg-emerald-500 hover:bg-emerald-400 text-slate-950 font-bold text-sm rounded-xl shadow-lg shadow-emerald-500/10 active:scale-95 transition-all">
                        Verify Code
                    </button>
                </div>
            </div>
        </div>
    </div>

    <!-- Quick Edit Team Modal -->
    <div id="edit-team-modal" class="fixed inset-0 bg-slate-950/85 backdrop-blur-sm z-50 flex items-center justify-center p-4 hidden">
        <div class="bg-slate-900 border border-slate-800 rounded-2xl max-w-md w-full p-6 shadow-2xl relative space-y-4">
            <button id="close-edit-modal-btn" class="absolute top-4 right-4 text-slate-400 hover:text-slate-100 transition-colors">
                <i class="fa-solid fa-xmark text-lg"></i>
            </button>
            
            <div class="border-b border-slate-800 pb-2">
                <h3 class="text-base font-bold text-emerald-400">Directly Edit Standings</h3>
                <p class="text-xs text-slate-400">Manual override for team: <span id="edit-team-title" class="font-bold text-slate-100"></span></p>
            </div>

            <form id="edit-team-form" class="space-y-4">
                <input type="hidden" id="edit-team-id">
                <div class="grid grid-cols-3 gap-3">
                    <div class="space-y-1">
                        <label class="text-[10px] font-semibold text-slate-400 uppercase">Played (P)</label>
                        <input type="number" id="edit-p" min="0" class="w-full bg-slate-800 border border-slate-700 text-slate-100 rounded-lg p-2 text-sm text-center">
                    </div>
                    <div class="space-y-1">
                        <label class="text-[10px] font-semibold text-slate-400 uppercase">Won (W)</label>
                        <input type="number" id="edit-w" min="0" class="w-full bg-slate-800 border border-slate-700 text-slate-100 rounded-lg p-2 text-sm text-center">
                    </div>
                    <div class="space-y-1">
                        <label class="text-[10px] font-semibold text-slate-400 uppercase">Drawn (D)</label>
                        <input type="number" id="edit-d" min="0" class="w-full bg-slate-800 border border-slate-700 text-slate-100 rounded-lg p-2 text-sm text-center">
                    </div>
                </div>

                <div class="grid grid-cols-3 gap-3">
                    <div class="space-y-1">
                        <label class="text-[10px] font-semibold text-slate-400 uppercase">Lost (L)</label>
                        <input type="number" id="edit-l" min="0" class="w-full bg-slate-800 border border-slate-700 text-slate-100 rounded-lg p-2 text-sm text-center">
                    </div>
                    <div class="space-y-1">
                        <label class="text-[10px] font-semibold text-slate-400 uppercase">Goals For (GF)</label>
                        <input type="number" id="edit-gf" min="0" class="w-full bg-slate-800 border border-slate-700 text-slate-100 rounded-lg p-2 text-sm text-center">
                    </div>
                    <div class="space-y-1">
                        <label class="text-[10px] font-semibold text-slate-400 uppercase">Goals Against (GA)</label>
                        <input type="number" id="edit-ga" min="0" class="w-full bg-slate-800 border border-slate-700 text-slate-100 rounded-lg p-2 text-sm text-center">
                    </div>
                </div>

                <div class="bg-slate-950/60 p-3 rounded-xl border border-slate-800 space-y-1">
                    <div class="flex justify-between text-xs">
                        <span class="text-slate-400">Calculated GD (Goal Diff):</span>
                        <span id="calculated-gd" class="font-bold text-slate-200">0</span>
                    </div>
                    <div class="flex justify-between text-xs">
                        <span class="text-slate-400">Calculated PTS (Points):</span>
                        <span id="calculated-pts" class="font-bold text-emerald-400">0</span>
                    </div>
                </div>

                <button type="submit" class="w-full py-2.5 bg-emerald-500 hover:bg-emerald-400 text-slate-950 font-bold text-sm rounded-xl">
                    Save Changes
                </button>
            </form>
        </div>
    </div>

    <!-- Custom Reset Confirmation Modal -->
    <div id="reset-confirm-modal" class="fixed inset-0 bg-slate-950/85 backdrop-blur-sm z-50 flex items-center justify-center p-4 hidden">
        <div class="bg-slate-900 border border-slate-800 rounded-2xl max-w-sm w-full p-6 shadow-2xl relative space-y-5 animate-scale-up">
            <div class="text-center space-y-2">
                <div class="mx-auto w-12 h-12 bg-red-500/10 text-red-500 rounded-full flex items-center justify-center text-xl mb-3 border border-red-500/20">
                    <i class="fa-solid fa-triangle-exclamation"></i>
                </div>
                <h3 class="text-lg font-bold text-slate-100">Reset All Data?</h3>
                <p class="text-xs text-slate-400 leading-relaxed">This will permanently delete your entire match history log and set every team statistic back to absolute zero. This action cannot be undone.</p>
            </div>
            
            <div class="flex gap-3 pt-1">
                <button id="cancel-reset-btn" class="flex-1 py-2.5 bg-slate-800 hover:bg-slate-700 text-slate-300 font-bold text-xs uppercase tracking-wide rounded-xl border border-slate-700 transition-all">
                    Cancel
                </button>
                <button id="confirm-reset-btn" class="flex-1 py-2.5 bg-red-500 hover:bg-red-600 text-white font-bold text-xs uppercase tracking-wide rounded-xl shadow-lg shadow-red-500/15 active:scale-95 transition-all">
                    Yes, Reset
                </button>
            </div>
        </div>
    </div>

    <!-- Alert System / Toast Notification Area -->
    <div id="toast-container" class="fixed bottom-5 right-5 z-50 flex flex-col gap-2 pointer-events-none max-w-sm w-full"></div>

    <!-- Firebase SDK Imports via Modules -->
    <script type="module">
        import { initializeApp } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-app.js";
        import { getAuth, signInWithCustomToken, signInAnonymously, onAuthStateChanged } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-auth.js";
        import { getFirestore, doc, setDoc, getDoc, collection, onSnapshot, updateDoc, writeBatch } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-firestore.js";

        // Global state and constants (UPDATED SECURE CODE)
        const DEFAULT_PASSCODE = "Touhid4865";
        let currentPasscode = DEFAULT_PASSCODE;
        let isAdmin = false;
        let teamsData = [];
        let matchesData = [];
        let isCloudSynced = false;
        let activeRound = 1;
        let teamFilter = "all";

        // BRAND NEW MATCHDAY SCHEDULE (Rounds 1-7, 8-14 repeat reversed)
        const SEASON_SCHEDULE = {
            1: [
                { home: "team-1", away: "team-2" }, // Touhid Vs Rejuwan
                { home: "team-4", away: "team-5" }, // Tahsan Vs Olderback
                { home: "team-7", away: "team-6" }, // Ashraf Vs Comeonbro
                { home: "team-8", away: "team-3" }  // Amith Vs Pichi
            ],
            2: [
                { home: "team-1", away: "team-5" }, // Touhid Vs Olderback
                { home: "team-8", away: "team-6" }, // Amith vs Comeonbro
                { home: "team-4", away: "team-7" }, // Tahsan Vs Ashraf
                { home: "team-2", away: "team-3" }  // Rejuwan Vs Pichi
            ],
            3: [
                { home: "team-1", away: "team-4" }, // Touhid Vs Tahsan
                { home: "team-8", away: "team-2" }, // Amith Vs Rejuwan
                { home: "team-6", away: "team-5" }, // Comeonbro vs Olderback
                { home: "team-7", away: "team-3" }  // Ashraf Vs Pichi
            ],
            4: [
                { home: "team-1", away: "team-8" }, // Touhid Vs Amith
                { home: "team-6", away: "team-2" }, // Comeonbro Vs Rejuwan
                { home: "team-4", away: "team-7" }, // Tahsan Vs Ashraf
                { home: "team-5", away: "team-3" }  // Olderback Vs Pichi
            ],
            5: [
                { home: "team-1", away: "team-3" }, // Touhid Vs Pichi
                { home: "team-8", away: "team-4" }, // Amith Vs Tahsan
                { home: "team-7", away: "team-2" }, // Ashraf vs Rejuwan
                { home: "team-6", away: "team-5" }  // Comeonbro vs Olderback
            ],
            6: [
                { home: "team-1", away: "team-6" }, // Touhid Vs Comeonbro
                { home: "team-8", away: "team-5" }, // Amith vs Olderback
                { home: "team-7", away: "team-3" }, // Ashraf Vs Pichi
                { home: "team-4", away: "team-2" }  // Tahsan vs Rejuwan
            ],
            7: [
                { home: "team-1", away: "team-7" }, // Touhid Vs Ashraf
                { home: "team-3", away: "team-8" }, // Pichi Vs Amith
                { home: "team-6", away: "team-2" }, // Comeonbro vs Rejuwan
                { home: "team-4", away: "team-5" }  // Tahsan Vs Olderback
            ],
            // NEXT 7 MATCHDAYS: Swapped Home/Away
            8: [
                { home: "team-2", away: "team-1" }, 
                { home: "team-5", away: "team-4" }, 
                { home: "team-6", away: "team-7" }, 
                { home: "team-3", away: "team-8" }  
            ],
            9: [
                { home: "team-5", away: "team-1" }, 
                { home: "team-6", away: "team-8" }, 
                { home: "team-7", away: "team-4" }, 
                { home: "team-3", away: "team-2" }  
            ],
            10: [
                { home: "team-4", away: "team-1" }, 
                { home: "team-2", away: "team-8" }, 
                { home: "team-5", away: "team-6" }, 
                { home: "team-3", away: "team-7" }  
            ],
            11: [
                { home: "team-8", away: "team-1" }, 
                { home: "team-2", away: "team-6" }, 
                { home: "team-7", away: "team-4" }, 
                { home: "team-3", away: "team-5" }  
            ],
            12: [
                { home: "team-3", away: "team-1" }, 
                { home: "team-4", away: "team-8" }, 
                { home: "team-2", away: "team-7" }, 
                { home: "team-5", away: "team-6" }  
            ],
            13: [
                { home: "team-6", away: "team-1" }, 
                { home: "team-5", away: "team-8" }, 
                { home: "team-3", away: "team-7" }, 
                { home: "team-2", away: "team-4" }  
            ],
            14: [
                { home: "team-7", away: "team-1" }, 
                { home: "team-8", away: "team-3" }, 
                { home: "team-2", away: "team-6" }, 
                { home: "team-5", away: "team-4" }  
            ]
        };

        // Complete 8 Squad Roster
        const INITIAL_TEAMS = [
            { id: "team-1", name: "Touhid", played: 0, won: 0, drawn: 0, lost: 0, gf: 0, ga: 0, gd: 0, pts: 0 },
            { id: "team-2", name: "Rejuwan", played: 0, won: 0, drawn: 0, lost: 0, gf: 0, ga: 0, gd: 0, pts: 0 },
            { id: "team-3", name: "pichi", played: 0, won: 0, drawn: 0, lost: 0, gf: 0, ga: 0, gd: 0, pts: 0 },
            { id: "team-4", name: "Tahsan", played: 0, won: 0, drawn: 0, lost: 0, gf: 0, ga: 0, gd: 0, pts: 0 },
            { id: "team-5", name: "Olderback", played: 0, won: 0, drawn: 0, lost: 0, gf: 0, ga: 0, gd: 0, pts: 0 },
            { id: "team-6", name: "Comeonbro", played: 0, won: 0, drawn: 0, lost: 0, gf: 0, ga: 0, gd: 0, pts: 0 },
            { id: "team-7", name: "Ashraf", played: 0, won: 0, drawn: 0, lost: 0, gf: 0, ga: 0, gd: 0, pts: 0 },
            { id: "team-8", name: "Amith", played: 0, won: 0, drawn: 0, lost: 0, gf: 0, ga: 0, gd: 0, pts: 0 }
        ];

        const getDisplayTeamName = (teamId) => {
            const team = INITIAL_TEAMS.find(t => t.id === teamId);
            return team ? team.name : "Unknown";
        };

        const MATCH_HOURS = ["1:30 PM", "3:45 PM", "6:00 PM", "8:15 PM", "10:30 PM"];

        const appId = typeof __app_id !== 'undefined' ? __app_id : 'live-tournament-system';
        let firebaseConfig = null;
        if (typeof __firebase_config !== 'undefined') {
            try {
                firebaseConfig = JSON.parse(__firebase_config);
            } catch(e) {
                console.warn("Could not parse Firebase Config:", e);
            }
        }

        let db = null;
        let auth = null;
        let user = null;

        if (firebaseConfig) {
            try {
                const app = initializeApp(firebaseConfig);
                auth = getAuth(app);
                db = getFirestore(app);
            } catch (err) {
                console.error("Firebase startup error:", err);
            }
        }

        const initAuthentication = async () => {
            if (!auth) {
                updateSyncIndicator(false, "Offline / Local Mode");
                loadLocalData();
                return;
            }

            try {
                if (typeof __initial_auth_token !== 'undefined' && __initial_auth_token) {
                    await signInWithCustomToken(auth, __initial_auth_token);
                } else {
                    await signInAnonymously(auth);
                }
            } catch (err) {
                console.error("Auth Sign-In Error. Switching to Offline mode.", err);
                updateSyncIndicator(false, "Offline mode");
                loadLocalData();
            }
        };

        const getDocRef = (collectionName, docId) => {
            if (!db) return null;
            return doc(db, 'artifacts', appId, 'public', 'data', collectionName, docId);
        };

        const showToast = (message, type = "success") => {
            const container = document.getElementById("toast-container");
            const toast = document.createElement("div");
            toast.className = `p-4 rounded-xl shadow-xl flex items-center justify-between space-x-3 pointer-events-auto transition-all transform duration-300 translate-y-2 opacity-0 ${
                type === 'success' ? 'bg-emerald-950 border border-emerald-500/20 text-emerald-300' : 
                type === 'error' ? 'bg-red-950 border border-red-500/20 text-red-300' : 
                'bg-slate-800 border border-slate-700 text-slate-300'
            }`;

            let icon = '<i class="fa-solid fa-circle-check"></i>';
            if (type === 'error') icon = '<i class="fa-solid fa-triangle-exclamation"></i>';
            if (type === 'info') icon = '<i class="fa-solid fa-circle-info"></i>';

            toast.innerHTML = `
                <div class="flex items-center space-x-2 text-xs font-semibold">
                    ${icon}
                    <span>${message}</span>
                </div>
            `;
            container.appendChild(toast);

            setTimeout(() => {
                toast.classList.remove("translate-y-2", "opacity-0");
            }, 50);

            setTimeout(() => {
                toast.classList.add("opacity-0", "translate-y-1");
                setTimeout(() => toast.remove(), 300);
            }, 3000);
        };

        const updateSyncIndicator = (synced, text) => {
            isCloudSynced = synced;
            const dot = document.getElementById("sync-status-dot");
            const label = document.getElementById("sync-status-text");
            if (synced) {
                dot.className = "w-2.5 h-2.5 rounded-full bg-emerald-500 shadow-md shadow-emerald-500/50";
                label.textContent = text || "Live Syncing with Firestore";
            } else {
                dot.className = "w-2.5 h-2.5 rounded-full bg-amber-500 shadow-md shadow-amber-500/50 animate-pulse";
                label.textContent = text || "Local Backup Mode";
            }
        };

        const loadLocalData = () => {
            try {
                const savedTeams = localStorage.getItem(`${appId}_teams`);
                const savedMatches = localStorage.getItem(`${appId}_matches`);
                const savedPasscode = localStorage.getItem(`${appId}_passcode`);

                teamsData = savedTeams ? JSON.parse(savedTeams) : INITIAL_TEAMS.map(team => ({ ...team }));
                matchesData = savedMatches ? JSON.parse(savedMatches) : [];
                currentPasscode = savedPasscode || DEFAULT_PASSCODE;

                renderUI();
            } catch (err) {
                teamsData = INITIAL_TEAMS.map(team => ({ ...team }));
                matchesData = [];
                renderUI();
            }
        };

        const saveLocalBackup = () => {
            try {
                localStorage.setItem(`${appId}_teams`, JSON.stringify(teamsData));
                localStorage.setItem(`${appId}_matches`, JSON.stringify(matchesData));
                localStorage.setItem(`${appId}_passcode`, currentPasscode);
            } catch (err) {
                console.error("Fail backup save", err);
            }
        };

        const startLiveSync = () => {
            if (!db || !user) {
                updateSyncIndicator(false, "Connected Offline");
                return;
            }

            updateSyncIndicator(true, "Connecting Cloud database...");

            const teamsRef = getDocRef("tournament_info", "league_table");
            const matchesRef = getDocRef("tournament_info", "match_history");
            const metaRef = getDocRef("tournament_info", "metadata");

            onSnapshot(teamsRef, (docSnap) => {
                if (docSnap.exists()) {
                    teamsData = docSnap.data().teams || [];
                    renderUI();
                    updateSyncIndicator(true, "Live - Synced with Cloud");
                } else {
                    saveChangesToDb(INITIAL_TEAMS.map(team => ({ ...team })), matchesData);
                }
            }, (error) => {
                console.error("Teams listener error. Falling back.", error);
                loadLocalData();
            });

            onSnapshot(matchesRef, (docSnap) => {
                if (docSnap.exists()) {
                    matchesData = docSnap.data().matches || [];
                    renderUI();
                }
            }, (error) => {
                console.error("Matches listener error", error);
            });

            onSnapshot(metaRef, (docSnap) => {
                if (docSnap.exists()) {
                    currentPasscode = docSnap.data().passcode || DEFAULT_PASSCODE;
                }
            }, (error) => {
                console.error("Passcode fetch error", error);
            });
        };

        const saveChangesToDb = async (newTeams, newMatches) => {
            teamsData = newTeams;
            matchesData = newMatches;
            saveLocalBackup();

            if (!db || !user) {
                renderUI();
                return true;
            }

            try {
                const batch = writeBatch(db);
                const teamsDocRef = getDocRef("tournament_info", "league_table");
                const matchesDocRef = getDocRef("tournament_info", "match_history");
                const metaDocRef = getDocRef("tournament_info", "metadata");

                batch.set(teamsDocRef, { teams: newTeams }, { merge: true });
                batch.set(matchesDocRef, { matches: newMatches }, { merge: true });
                batch.set(metaDocRef, { passcode: currentPasscode }, { merge: true });

                await batch.commit();
                return true;
            } catch (err) {
                console.error("Cloud synchronization failed:", err);
                showToast("Saved locally. Connection issues.", "error");
                return false;
            }
        };

        const sortTeams = (teams) => {
            return [...teams].sort((a, b) => {
                if (b.pts !== a.pts) return b.pts - a.pts;
                if (b.gd !== a.gd) return b.gd - a.gd;
                if (b.gf !== a.gf) return b.gf - a.gf;
                return a.name.localeCompare(b.name);
            });
        };

        const getRandomTime = (round, index) => {
            const seed = (round * 7) + (index * 13);
            const hour = MATCH_HOURS[seed % MATCH_HOURS.length];
            return hour;
        };

        const handleShareWebsite = () => {
            const shareTitle = "FC Elite Clash Result and Fixture";
            const shareText = "Keep track of the real-time matches, scores, and live standings on the FC Elite Clash portal!";
            const shareUrl = window.location.href;

            if (navigator.share) {
                navigator.share({
                    title: shareTitle,
                    text: shareText,
                    url: shareUrl
                }).then(() => {
                    showToast("Successfully shared!", "success");
                }).catch((err) => {
                    copyUrlToClipboard(shareUrl);
                });
            } else {
                copyUrlToClipboard(shareUrl);
            }
        };

        // UNIQUE OWN-SOURCE CODE COPIER (USER REQUESTED FOR DIRECT FILE SAVE)
        const handleCopySelfSourceCode = () => {
            try {
                // Fetch current entire HTML contents
                const rawHTMLCode = "<!DOCTYPE html>\n" + document.documentElement.outerHTML;
                
                // Copy strictly using commended execCommand utility for frame safety
                const tempText = document.createElement("textarea");
                tempText.value = rawHTMLCode;
                document.body.appendChild(tempText);
                tempText.select();
                const copySuccess = document.execCommand("copy");
                document.body.removeChild(tempText);

                if (copySuccess) {
                    showToast("Website code successfully copied! Apnar phone/PC clipboard-e paste korar jonno ready.", "success");
                } else {
                    showToast("Automatically copy korte parini. Manual browser features check korun.", "error");
                }
            } catch (err) {
                console.error(err);
                showToast("Code copying failed. Phone permissions dynamic check korun.", "error");
            }
        };

        const copyUrlToClipboard = (text) => {
            try {
                const tempTextArea = document.createElement("textarea");
                tempTextArea.value = text;
                document.body.appendChild(tempTextArea);
                tempTextArea.select();
                const successful = document.execCommand("copy");
                document.body.removeChild(tempTextArea);
                
                if (successful) {
                    showToast("Link copied to clipboard! Share it with your friends.", "success");
                } else {
                    showToast("Failed to copy link automatically.", "error");
                }
            } catch (err) {
                showToast("Sharing failed. Please copy the URL from browser bar.", "error");
            }
        };

        const renderFixtures = () => {
            const container = document.getElementById("fixtures-container");
            container.innerHTML = "";

            const roundMatchups = SEASON_SCHEDULE[activeRound] || [];
            
            let filteredMatchups = roundMatchups;
            if (teamFilter !== "all") {
                filteredMatchups = roundMatchups.filter(m => m.home === teamFilter || m.away === teamFilter);
            }

            if (filteredMatchups.length === 0) {
                container.innerHTML = `
                    <div class="text-center py-12 text-slate-500 text-xs">
                        <i class="fa-solid fa-ban text-lg mb-1 block"></i>
                        No matches scheduled for this team in Round ${activeRound}.
                    </div>
                `;
                return;
            }

            filteredMatchups.forEach((matchup, idx) => {
                const homeName = getDisplayTeamName(matchup.home);
                const awayName = getDisplayTeamName(matchup.away);
                const matchTime = getRandomTime(activeRound, idx);

                const playedMatch = matchesData.find(m => 
                    (m.homeId === matchup.home && m.awayId === matchup.away) || 
                    (m.homeId === matchup.away && m.awayId === matchup.home)
                );

                const div = document.createElement("div");
                div.className = "bg-slate-900/80 border border-slate-800 p-3 rounded-xl hover:border-slate-700/80 transition-all";
                
                div.innerHTML = `
                    <div class="flex items-center justify-between text-[11px] text-slate-400 mb-2">
                        <span class="font-semibold text-slate-500">Match ${idx + 1}</span>
                        <div class="flex items-center gap-1.5">
                            <i class="fa-regular fa-clock"></i>
                            <span>Kick-off: <strong class="text-indigo-400 font-medium">${matchTime}</strong></span>
                        </div>
                    </div>

                    <div class="flex items-center justify-between text-xs">
                        <div class="w-[40%] truncate text-right pr-2">
                            <span class="font-semibold text-slate-100">${escapeHTML(homeName)}</span>
                        </div>

                        <div class="w-[20%] text-center">
                            ${playedMatch ? `
                                <span class="bg-emerald-500/10 border border-emerald-500/30 text-emerald-400 px-2 py-0.5 rounded-md font-bold text-[11px]">
                                    ${playedMatch.homeScore} - ${playedMatch.awayScore}
                                </span>
                            ` : `
                                <span class="bg-slate-800 text-slate-400 px-2 py-0.5 rounded-md font-bold text-[10px] uppercase">
                                    VS
                                </span>
                            `}
                        </div>

                        <div class="w-[40%] truncate text-left pl-2">
                            <span class="font-semibold text-slate-100">${escapeHTML(awayName)}</span>
                        </div>
                    </div>

                    ${isAdmin && !playedMatch ? `
                        <div class="mt-2.5 pt-2 border-t border-slate-800/60 flex justify-end">
                            <button onclick="window.preloadMatchForm('${matchup.home}', '${matchup.away}')" class="px-2.5 py-1 bg-emerald-500/10 hover:bg-emerald-500/20 text-emerald-400 text-[11px] font-bold rounded-md transition-all flex items-center gap-1">
                                <i class="fa-solid fa-clipboard-check"></i> Post Result
                            </button>
                        </div>
                    ` : ''}
                `;
                container.appendChild(div);
            });
        };

        const renderUI = () => {
            const sortedTeams = sortTeams(teamsData);
            const tableBody = document.getElementById("league-table-body");
            tableBody.innerHTML = "";

            if (sortedTeams.length === 0) {
                tableBody.innerHTML = `<tr><td colspan="9" class="py-10 text-center text-slate-500">No teams added.</td></tr>`;
                return;
            }

            sortedTeams.forEach((team, index) => {
                const tr = document.createElement("tr");
                const isLeader = index === 0;
                
                let posBadgeClass = "text-slate-400";
                if (index === 0) posBadgeClass = "bg-amber-500/10 text-amber-500 font-extrabold ring-1 ring-amber-500/20";
                else if (index === 1) posBadgeClass = "bg-slate-300/10 text-slate-300 font-bold ring-1 ring-slate-300/20";
                else if (index === 2) posBadgeClass = "bg-amber-700/10 text-amber-600 font-bold ring-1 ring-amber-700/20";

                tr.className = `hover:bg-slate-800/40 transition-colors ${isLeader ? 'bg-amber-500/5' : ''}`;
                tr.innerHTML = `
                    <td class="py-3 px-4 text-center">
                        <span class="inline-flex items-center justify-center w-7 h-7 rounded-lg text-xs ${posBadgeClass}">
                            ${index + 1}
                        </span>
                    </td>
                    <td class="py-3 px-4 font-semibold text-slate-100">
                        <div class="flex items-center space-x-2">
                            <span>${escapeHTML(team.name)}</span>
                            ${isLeader ? '<i class="fa-solid fa-crown text-amber-500 text-xs animate-bounce"></i>' : ''}
                        </div>
                    </td>
                    <td class="py-3 px-3 text-center text-slate-300 font-medium">${team.played}</td>
                    <td class="py-3 px-3 text-center text-emerald-400/90 font-medium">${team.won}</td>
                    <td class="py-3 px-3 text-center text-slate-400 font-medium">${team.drawn}</td>
                    <td class="py-3 px-3 text-center text-rose-400/90 font-medium">${team.lost}</td>
                    <td class="py-3 px-3 text-center font-bold ${team.gd > 0 ? 'text-emerald-500' : team.gd < 0 ? 'text-rose-500' : 'text-slate-400'}">
                        ${team.gd > 0 ? '+' : ''}${team.gd}
                    </td>
                    <td class="py-3 px-4 text-center font-black text-slate-100 bg-slate-800/10 text-base">${team.pts}</td>
                    <td class="py-3 px-4 text-center admin-actions ${isAdmin ? '' : 'hidden'}">
                        <button onclick="window.openEditModal('${team.id}')" class="p-1.5 bg-slate-800 hover:bg-slate-700 text-slate-300 rounded-lg hover:text-emerald-400 active:scale-95 transition-all text-xs border border-slate-700">
                            <i class="fa-regular fa-pen-to-square"></i> Edit
                        </button>
                    </td>
                `;
                tableBody.appendChild(tr);
            });

            const homeSelect = document.getElementById("home-team-select");
            const awaySelect = document.getElementById("away-team-select");
            const currentHomeSelection = homeSelect.value;
            const currentAwaySelection = awaySelect.value;

            const dropdownHtml = `<option value="">Choose team...</option>` + 
                sortedTeams.map(t => `<option value="${t.id}">${escapeHTML(t.name)}</option>`).join("");
            
            homeSelect.innerHTML = dropdownHtml;
            awaySelect.innerHTML = dropdownHtml;

            if (currentHomeSelection) homeSelect.value = currentHomeSelection;
            if (currentAwaySelection) awaySelect.value = currentAwaySelection;

            renderMatches();
            renderFixtures();
            updateDashboardStats(sortedTeams);
        };

        const renderMatches = () => {
            const feedContainer = document.getElementById("match-feed-container");
            const matchCountLabel = document.getElementById("match-count");
            
            if (matchesData.length === 0) {
                matchCountLabel.textContent = "0 played";
                feedContainer.innerHTML = `
                    <div class="text-center py-8 text-slate-500 text-xs">
                        <i class="fa-solid fa-calendar-xmark text-lg mb-1 block opacity-60"></i>
                        No matches played yet.
                    </div>
                `;
                return;
            }

            matchCountLabel.textContent = `${matchesData.length} played`;
            feedContainer.innerHTML = "";

            [...matchesData].reverse().forEach((match) => {
                const homeWinner = match.homeScore > match.awayScore;
                const awayWinner = match.awayScore > match.homeScore;
                
                const matchCard = document.createElement("div");
                matchCard.className = "bg-slate-900 border border-slate-800 p-3.5 rounded-xl hover:border-slate-700 transition-all flex flex-col space-y-2 relative group";
                matchCard.innerHTML = `
                    <div class="flex items-center justify-between text-xs">
                        <span class="text-slate-500 font-medium">${match.date || "Match Day"}</span>
                        ${isAdmin ? `
                            <button onclick="window.deleteMatch('${match.matchId}')" class="opacity-0 group-hover:opacity-100 text-red-400 hover:text-red-300 text-[10px] font-bold transition-all px-1.5 py-0.5 rounded bg-red-500/10 border border-red-500/20">
                                <i class="fa-regular fa-trash-can"></i> Delete
                            </button>
                        ` : ''}
                    </div>

                    <div class="grid grid-cols-5 items-center justify-items-center">
                        <div class="col-span-2 text-right w-full truncate pr-1">
                            <span class="text-xs md:text-sm ${homeWinner ? 'font-bold text-emerald-400' : 'text-slate-300'}">
                                ${escapeHTML(match.homeName)}
                            </span>
                        </div>
                        
                        <div class="col-span-1 bg-slate-950 border border-slate-800 px-2.5 py-1 rounded-lg text-center font-bold text-xs md:text-sm font-mono text-slate-100 flex items-center justify-center gap-1.5 shadow-inner">
                            <span class="${homeWinner ? 'text-emerald-400' : 'text-slate-300'}">${match.homeScore}</span>
                            <span class="text-slate-600">-</span>
                            <span class="${awayWinner ? 'text-emerald-400' : 'text-slate-300'}">${match.awayScore}</span>
                        </div>

                        <div class="col-span-2 text-left w-full truncate pl-1">
                            <span class="text-xs md:text-sm ${awayWinner ? 'font-bold text-emerald-400' : 'text-slate-300'}">
                                ${escapeHTML(match.awayName)}
                            </span>
                        </div>
                    </div>
                `;
                feedContainer.appendChild(matchCard);
            });
        };

        const updateDashboardStats = (sortedTeams) => {
            document.getElementById("stat-total-teams").textContent = sortedTeams.length;
            const totalMatches = matchesData.length;
            document.getElementById("stat-matches-played").textContent = totalMatches;

            let totalGoals = 0;
            matchesData.forEach(m => {
                totalGoals += (parseInt(m.homeScore) || 0) + (parseInt(m.awayScore) || 0);
            });
            document.getElementById("stat-total-goals").textContent = totalGoals;

            if (sortedTeams.length > 0) {
                document.getElementById("stat-leader").textContent = sortedTeams[0].name;
            } else {
                document.getElementById("stat-leader").textContent = "N/A";
            }
        };

        const escapeHTML = (string) => {
            const temp = document.createElement('div');
            temp.textContent = string;
            return temp.innerHTML;
        };

        window.preloadMatchForm = (homeId, awayId) => {
            if (!isAdmin) return;
            document.getElementById("home-team-select").value = homeId;
            document.getElementById("away-team-select").value = awayId;
            document.getElementById("home-score-input").value = "";
            document.getElementById("away-score-input").value = "";
            
            document.getElementById("admin-match-form-card").scrollIntoView({ behavior: 'smooth' });
            showToast("Pre-selected fixture matchups. Enter score below.", "info");
        };

        const toggleAdminMode = () => {
            if (isAdmin) {
                isAdmin = false;
                document.getElementById("admin-btn-text").textContent = "Admin Mode";
                document.getElementById("admin-toggle-btn").className = "px-4 py-2 bg-slate-800 hover:bg-slate-700 active:scale-95 transition-all text-xs md:text-sm font-semibold rounded-xl border border-slate-700 flex items-center gap-2";
                document.getElementById("admin-icon").className = "fa-solid fa-lock text-amber-500";
                
                document.getElementById("admin-indicator").classList.add("hidden");
                document.getElementById("admin-match-form-card").classList.add("hidden");
                document.getElementById("admin-clear-btn-container").classList.add("hidden");
                
                const actionCols = document.querySelectorAll(".admin-actions");
                actionCols.forEach(col => col.classList.add("hidden"));
                
                showToast("Logged out of Admin mode", "info");
                renderUI();
            } else {
                document.getElementById("admin-modal").classList.remove("hidden");
                document.getElementById("passcode-input").focus();
            }
        };

        const submitPasscode = () => {
            const input = document.getElementById("passcode-input");
            const value = input.value.trim();

            if (value === currentPasscode) {
                isAdmin = true;
                
                document.getElementById("admin-btn-text").textContent = "Exit Admin";
                document.getElementById("admin-toggle-btn").className = "px-4 py-2 bg-emerald-500/10 hover:bg-emerald-500/20 active:scale-95 transition-all text-xs md:text-sm font-semibold rounded-xl border border-emerald-500/30 text-emerald-400 flex items-center gap-2";
                document.getElementById("admin-icon").className = "fa-solid fa-lock-open text-emerald-400 animate-bounce";
                
                document.getElementById("admin-indicator").classList.remove("hidden");
                document.getElementById("admin-match-form-card").classList.remove("hidden");
                document.getElementById("admin-clear-btn-container").classList.remove("hidden");
                
                const actionCols = document.querySelectorAll(".admin-actions");
                actionCols.forEach(col => col.classList.remove("hidden"));

                input.value = "";
                document.getElementById("admin-modal").classList.add("hidden");
                showToast("Admin access authenticated successfully", "success");
                renderUI();
            } else {
                showToast("Invalid secret passcode. Please try again.", "error");
                input.value = "";
                input.focus();
            }
        };

        const handleMatchSubmission = async (e) => {
            e.preventDefault();
            if (!isAdmin) return;

            const homeId = document.getElementById("home-team-select").value;
            const awayId = document.getElementById("away-team-select").value;
            const homeScore = parseInt(document.getElementById("home-score-input").value);
            const awayScore = parseInt(document.getElementById("away-score-input").value);

            if (!homeId || !awayId) {
                showToast("Please choose two teams", "error");
                return;
            }

            if (homeId === awayId) {
                showToast("A team cannot play against itself", "error");
                return;
            }

            if (isNaN(homeScore) || isNaN(awayScore) || homeScore < 0 || awayScore < 0) {
                showToast("Please enter correct integer scores", "error");
                return;
            }

            const updatedTeams = JSON.parse(JSON.stringify(teamsData));
            const homeTeam = updatedTeams.find(t => t.id === homeId);
            const awayTeam = updatedTeams.find(t => t.id === awayId);

            if (!homeTeam || !awayTeam) {
                showToast("Error locating selected teams", "error");
                return;
            }

            homeTeam.played += 1;
            awayTeam.played += 1;
            homeTeam.gf += homeScore;
            awayTeam.gf += awayScore;
            homeTeam.ga += awayScore;
            awayTeam.ga += homeScore;

            if (homeScore > awayScore) {
                homeTeam.won += 1;
                homeTeam.pts += 3;
                awayTeam.lost += 1;
            } else if (awayScore > homeScore) {
                awayTeam.won += 1;
                awayTeam.pts += 3;
                homeTeam.lost += 1;
            } else {
                homeTeam.drawn += 1;
                homeTeam.pts += 1;
                awayTeam.drawn += 1;
                awayTeam.pts += 1;
            }

            homeTeam.gd = homeTeam.gf - homeTeam.ga;
            awayTeam.gd = awayTeam.gf - awayTeam.ga;

            const newMatch = {
                matchId: 'match_' + Date.now(),
                homeId,
                homeName: homeTeam.name,
                awayId,
                awayName: awayTeam.name,
                homeScore,
                awayScore,
                date: new Date().toLocaleDateString(undefined, { month: 'short', day: 'numeric', hour: '2-digit', minute: '2-digit' })
            };

            const updatedMatches = [...matchesData, newMatch];

            const success = await saveChangesToDb(updatedTeams, updatedMatches);
            if (success) {
                showToast(`Saved match: ${homeTeam.name} vs ${awayTeam.name}`, "success");
                document.getElementById("match-form").reset();
            }
        };

        window.deleteMatch = async (matchId) => {
            if (!isAdmin) return;

            const matchObj = matchesData.find(m => m.matchId === matchId);
            if (!matchObj) return;

            const updatedTeams = JSON.parse(JSON.stringify(teamsData));
            const homeTeam = updatedTeams.find(t => t.id === matchObj.homeId);
            const awayTeam = updatedTeams.find(t => t.id === matchObj.awayId);

            if (homeTeam && awayTeam) {
                homeTeam.played = Math.max(0, homeTeam.played - 1);
                awayTeam.played = Math.max(0, awayTeam.played - 1);
                homeTeam.gf = Math.max(0, homeTeam.gf - matchObj.homeScore);
                awayTeam.gf = Math.max(0, awayTeam.gf - matchObj.awayScore);
                homeTeam.ga = Math.max(0, homeTeam.ga - matchObj.awayScore);
                awayTeam.ga = Math.max(0, awayTeam.ga - matchObj.homeScore);

                if (matchObj.homeScore > matchObj.awayScore) {
                    homeTeam.won = Math.max(0, homeTeam.won - 1);
                    homeTeam.pts = Math.max(0, homeTeam.pts - 3);
                    awayTeam.lost = Math.max(0, awayTeam.lost - 1);
                } else if (matchObj.awayScore > matchObj.homeScore) {
                    awayTeam.won = Math.max(0, awayTeam.won - 1);
                    awayTeam.pts = Math.max(0, awayTeam.pts - 3);
                    homeTeam.lost = Math.max(0, homeTeam.lost - 1);
                } else {
                    homeTeam.drawn = Math.max(0, homeTeam.drawn - 1);
                    homeTeam.pts = Math.max(0, homeTeam.pts - 1);
                    awayTeam.drawn = Math.max(0, awayTeam.drawn - 1);
                    awayTeam.pts = Math.max(0, awayTeam.pts - 1);
                }

                homeTeam.gd = homeTeam.gf - homeTeam.ga;
                awayTeam.gd = awayTeam.gf - awayTeam.ga;
            }

            const updatedMatches = matchesData.filter(m => m.matchId !== matchId);

            const success = await saveChangesToDb(updatedTeams, updatedMatches);
            if (success) {
                showToast("Match deleted & standings updated", "info");
            }
        };

        window.openEditModal = (teamId) => {
            const team = teamsData.find(t => t.id === teamId);
            if (!team) return;

            document.getElementById("edit-team-id").value = team.id;
            document.getElementById("edit-team-title").textContent = team.name;
            
            document.getElementById("edit-p").value = team.played;
            document.getElementById("edit-w").value = team.won;
            document.getElementById("edit-d").value = team.drawn;
            document.getElementById("edit-l").value = team.lost;
            document.getElementById("edit-gf").value = team.gf;
            document.getElementById("edit-ga").value = team.ga;

            calculateModalRealtime();
            document.getElementById("edit-team-modal").classList.remove("hidden");
        };

        const calculateModalRealtime = () => {
            const w = parseInt(document.getElementById("edit-w").value) || 0;
            const d = parseInt(document.getElementById("edit-d").value) || 0;
            const gf = parseInt(document.getElementById("edit-gf").value) || 0;
            const ga = parseInt(document.getElementById("edit-ga").value) || 0;

            const calculatedGD = gf - ga;
            const calculatedPTS = (w * 3) + (d * 1);

            document.getElementById("calculated-gd").textContent = (calculatedGD > 0 ? "+" : "") + calculatedGD;
            document.getElementById("calculated-pts").textContent = calculatedPTS;
        };

        const handleEditTeamFormSubmit = async (e) => {
            e.preventDefault();
            if (!isAdmin) return;

            const id = document.getElementById("edit-team-id").value;
            const updatedTeams = JSON.parse(JSON.stringify(teamsData));
            const team = updatedTeams.find(t => t.id === id);

            if (!team) return;

            team.played = parseInt(document.getElementById("edit-p").value) || 0;
            team.won = parseInt(document.getElementById("edit-w").value) || 0;
            team.drawn = parseInt(document.getElementById("edit-d").value) || 0;
            team.lost = parseInt(document.getElementById("edit-l").value) || 0;
            team.gf = parseInt(document.getElementById("edit-gf").value) || 0;
            team.ga = parseInt(document.getElementById("edit-ga").value) || 0;
            
            team.gd = team.gf - team.ga;
            team.pts = (team.won * 3) + (team.drawn * 1);

            const success = await saveChangesToDb(updatedTeams, matchesData);
            if (success) {
                showToast(`Manually modified ${team.name}'s stats`, "success");
                document.getElementById("edit-team-modal").classList.add("hidden");
            }
        };

        const openResetConfirmation = () => {
            if (!isAdmin) return;
            document.getElementById("reset-confirm-modal").classList.remove("hidden");
        };

        const closeResetConfirmation = () => {
            document.getElementById("reset-confirm-modal").classList.add("hidden");
        };

        const executeResetAllData = async () => {
            if (!isAdmin) return;
            
            const cleanTeams = INITIAL_TEAMS.map(team => ({
                id: team.id,
                name: team.name,
                played: 0,
                won: 0,
                drawn: 0,
                lost: 0,
                gf: 0,
                ga: 0,
                gd: 0,
                pts: 0
            }));
            
            const cleanMatches = [];

            const success = await saveChangesToDb(cleanTeams, cleanMatches);
            if (success) {
                showToast("Tournament standings & matches have been fully cleared.", "info");
                closeResetConfirmation();
            } else {
                showToast("Error executing reset, please try again.", "error");
            }
        };

        document.addEventListener("DOMContentLoaded", () => {
            const roundSelect = document.getElementById("round-select");
            roundSelect.innerHTML = Array.from({ length: 14 }, (_, i) => i + 1)
                .map(r => `<option value="${r}">Round ${r}</option>`).join("");

            const filterTeamSelect = document.getElementById("filter-team-select");
            INITIAL_TEAMS.forEach(t => {
                const opt = document.createElement("option");
                opt.value = t.id;
                opt.textContent = t.name;
                filterTeamSelect.appendChild(opt);
            });

            loadLocalData();

            roundSelect.addEventListener("change", (e) => {
                activeRound = parseInt(e.target.value) || 1;
                renderFixtures();
            });

            filterTeamSelect.addEventListener("change", (e) => {
                teamFilter = e.target.value;
                renderFixtures();
            });

            // Action Listeners
            document.getElementById("copy-source-btn").addEventListener("click", handleCopySelfSourceCode);
            document.getElementById("share-btn").addEventListener("click", handleShareWebsite);
            document.getElementById("admin-toggle-btn").addEventListener("click", toggleAdminMode);
            document.getElementById("close-modal-btn").addEventListener("click", () => {
                document.getElementById("admin-modal").classList.add("hidden");
            });
            document.getElementById("submit-passcode-btn").addEventListener("click", submitPasscode);
            document.getElementById("passcode-input").addEventListener("keypress", (e) => {
                if (e.key === "Enter") submitPasscode();
            });

            document.getElementById("match-form").addEventListener("submit", handleMatchSubmission);

            document.getElementById("close-edit-modal-btn").addEventListener("click", () => {
                document.getElementById("edit-team-modal").classList.add("hidden");
            });
            
            const editFormInputs = ["edit-w", "edit-d", "edit-gf", "edit-ga"];
            editFormInputs.forEach(id => {
                document.getElementById(id).addEventListener("input", calculateModalRealtime);
            });
            
            document.getElementById("edit-team-form").addEventListener("submit", handleEditTeamFormSubmit);
            
            document.getElementById("reset-tournament-btn").addEventListener("click", openResetConfirmation);
            document.getElementById("cancel-reset-btn").addEventListener("click", closeResetConfirmation);
            document.getElementById("confirm-reset-btn").addEventListener("click", executeResetAllData);

            initAuthentication().then(() => {
                onAuthStateChanged(auth, (usr) => {
                    user = usr;
                    if (usr) {
                        startLiveSync();
                    } else {
                        updateSyncIndicator(false, "Offline / Guest");
                    }
                });
            });
        });
    </script>

<iframe ng-non-bindable="" frameborder="0" hspace="0" marginheight="0" marginwidth="0" scrolling="no" tabindex="-1" vspace="0" width="100%" aria-hidden="true" id="I0_1779706345576" name="I0_1779706345576" src="https://bard-frontend.firebaseapp.com/__/auth/iframe?apiKey=AIzaSyCqyCcs2R2e7AegGjvFAwG98wlamtbHvZY&amp;appName=%5BDEFAULT%5D&amp;v=11.6.1&amp;eid=p&amp;usegapi=1&amp;jsh=m%3B%2F_%2Fscs%2Fabc-static%2F_%2Fjs%2Fk%3Dgapi.lb.en.ch0Jz-JlMrQ.O%2Fd%3D1%2Frs%3DAHpOoo_YD4KoV8fTh_kLhktsiThAm3yJ5A%2Fm%3D__features__#id=I0_1779706345576&amp;_gfid=I0_1779706345576&amp;parent=blob%3A%2F%2F&amp;pfname=&amp;rpctoken=25262660" style="position: absolute; top: -100px; width: 1px; height: 1px;"></iframe></body></html>
// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyBBPoHCXUX9D3lnwzESgdNW2XqZP9aRNZU",
  authDomain: "fc-elite-clash.firebaseapp.com",
  databaseURL: "https://fc-elite-clash-default-rtdb.asia-southeast1.firebasedatabase.app",
  projectId: "fc-elite-clash",
  storageBucket: "fc-elite-clash.firebasestorage.app",
  messagingSenderId: "712557131555",
  appId: "1:712557131555:web:26229cae1fb30b8f3b3e96",
  measurementId: "G-8CZD15P4D8"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);

