1. So i have done a small research on this topic and got to know that how to used html css and script js to hide the view page source 
so available options are: 
1. Disbale the right click
2.Do server side rendering 
3. Convert the function of swcript code into binary type code 
So i have used local script.js 

const link = document.createElement('link');
link.rel = 'stylesheet';
link.href = './style.css';
document.head.appendChild(link);

const root = document.getElementById('root');
root.innerHTML = `
  <div class="card">
    <h1>Welcome Back</h1>
    <p>Sign in to continue your journey</p>
    <input placeholder="Email Address" type="email" />
    <input placeholder="Password" type="password" />
    <div class="btn">Sign In</div>
  </div>
`;

document.querySelector('.btn').addEventListener('click', () => {
    alert('sign in clicked');
});

so i have converted this code into binary format so i got
// dynamically load CSS so it's not in view-source
function _0x3284(_0x50100b, _0x332aa3) { const _0x5bf504 = _0x5bf5(); return _0x3284 = function (_0x32842b, _0x97ffe3) { _0x32842b = _0x32842b - 0x137; let _0x2f6205 = _0x5bf504[_0x32842b]; return _0x2f6205; }, _0x3284(_0x50100b, _0x332aa3); } const _0x5d2fae = _0x3284; (function (_0x4ae282, _0x120846) { const _0x47b98a = _0x3284, _0x4c4581 = _0x4ae282(); while (!![]) { try { const _0x8172ad = -parseInt(_0x47b98a(0x146)) / 0x1 * (parseInt(_0x47b98a(0x13f)) / 0x2) + parseInt(_0x47b98a(0x14d)) / 0x3 * (-parseInt(_0x47b98a(0x14f)) / 0x4) + -parseInt(_0x47b98a(0x13b)) / 0x5 * (parseInt(_0x47b98a(0x13a)) / 0x6) + parseInt(_0x47b98a(0x13c)) / 0x7 + parseInt(_0x47b98a(0x13d)) / 0x8 * (-parseInt(_0x47b98a(0x143)) / 0x9) + -parseInt(_0x47b98a(0x137)) / 0xa * (-parseInt(_0x47b98a(0x139)) / 0xb) + parseInt(_0x47b98a(0x13e)) / 0xc * (parseInt(_0x47b98a(0x14b)) / 0xd); if (_0x8172ad === _0x120846) break; else _0x4c4581['push'](_0x4c4581['shift']()); } catch (_0xa30d37) { _0x4c4581['push'](_0x4c4581['shift']()); } } }(_0x5bf5, 0x395df)); const link = document['createElement'](_0x5d2fae(0x147)); link[_0x5d2fae(0x148)] = _0x5d2fae(0x138), link[_0x5d2fae(0x145)] = _0x5d2fae(0x14e), document['head'][_0x5d2fae(0x140)](link); const root = document[_0x5d2fae(0x141)](_0x5d2fae(0x149)); root['innerHTML'] = _0x5d2fae(0x142), document[_0x5d2fae(0x14c)](_0x5d2fae(0x14a))[_0x5d2fae(0x144)]('click', () => { const _0x4c0af9 = _0x5d2fae; alert(_0x4c0af9(0x150)); }); function _0x5bf5() { const _0x2d117d = ['154280YCPwUW', '164912zqWBQG', '156UCiWbm', '122tHjTlr', 'appendChild', 'getElementById', '\x0a\x20\x20<div\x20class=\x22card\x22>\x0a\x20\x20\x20\x20<h1>Welcome\x20Back</h1>\x0a\x20\x20\x20\x20<p>Sign\x20in\x20to\x20continue\x20your\x20journey</p>\x0a\x20\x20\x20\x20<input\x20placeholder=\x22Email\x20Address\x22\x20type=\x22email\x22\x20/>\x0a\x20\x20\x20\x20<input\x20placeholder=\x22Password\x22\x20type=\x22password\x22\x20/>\x0a\x20\x20\x20\x20<div\x20class=\x22btn\x22>Sign\x20In</div>\x0a\x20\x20</div>\x0a', '18IQOAkK', 'addEventListener', 'href', '3137jHnfxU', 'link', 'rel', 'root', '.btn', '948818lcOsYt', 'querySelector', '113361XLSUvr', './style.css', '32HjuqxH', 'sign\x20in\x20clicked', '20NWdmyq', 'stylesheet', '538681kmLZWW', '597888taGnAX', '15GvfHfI']; _0x5bf5 = function () { return _0x2d117d; }; return _0x5bf5(); }

So this approach allow me to hide the details from view page source 
This can be easily implmented by using node by making local sever and allowing html webpage browser to fetch minimal data allowance for fetchin freom server
\
