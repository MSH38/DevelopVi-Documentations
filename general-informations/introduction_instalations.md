window.addEventListener('DOMContentLoaded',function(){var v=archive\_analytics.values;v.service='wb';v.server\_name='wwwb-app215.us.archive.org';v.server\_ms=375;archive\_analytics.send\_pageview({});}); window.RufflePlayer=window.RufflePlayer||{};window.RufflePlayer.config={"autoplay":"on","unmuteOverlay":"hidden"}; \_\_wm.init("https://web.archive.org/web"); \_\_wm.wombat("https://developvideploy.com/documentation/wpcloud-deploy/introduction-to-wpcloud-deploy/","20231216194429","https://web.archive.org/","web","/\_static/", "1702755869");      Introduction, Installation & Quick Start Guide - DevelopVIDeploy                                 window.\_wpemojiSettings = {"baseUrl":"https:\\/\\/web.archive.org\\/web\\/20231216194429\\/https:\\/\\/s.w.org\\/images\\/core\\/emoji\\/14.0.0\\/72x72\\/","ext":".png","svgUrl":"https:\\/\\/web.archive.org\\/web\\/20231216194429\\/https:\\/\\/s.w.org\\/images\\/core\\/emoji\\/14.0.0\\/svg\\/","svgExt":".svg","source":{"concatemoji":"https:\\/\\/web.archive.org\\/web\\/20231216194429\\/https:\\/\\/developvideploy.com\\/wp-includes\\/js\\/wp-emoji-release.min.js?ver=6.4.2"}}; /\*! This file is auto-generated \*/ !function(i,n){var o,s,e;function c(e){try{var t={supportTests:e,timestamp:(new Date).valueOf()};sessionStorage.setItem(o,JSON.stringify(t))}catch(e){}}function p(e,t,n){e.clearRect(0,0,e.canvas.width,e.canvas.height),e.fillText(t,0,0);var t=new Uint32Array(e.getImageData(0,0,e.canvas.width,e.canvas.height).data),r=(e.clearRect(0,0,e.canvas.width,e.canvas.height),e.fillText(n,0,0),new Uint32Array(e.getImageData(0,0,e.canvas.width,e.canvas.height).data));return t.every(function(e,t){return e===r\[t\]})}function u(e,t,n){switch(t){case"flag":return n(e,"\\ud83c\\udff3\\ufe0f\\u200d\\u26a7\\ufe0f","\\ud83c\\udff3\\ufe0f\\u200b\\u26a7\\ufe0f")?!1:!n(e,"\\ud83c\\uddfa\\ud83c\\uddf3","\\ud83c\\uddfa\\u200b\\ud83c\\uddf3")&&!n(e,"\\ud83c\\udff4\\udb40\\udc67\\udb40\\udc62\\udb40\\udc65\\udb40\\udc6e\\udb40\\udc67\\udb40\\udc7f","\\ud83c\\udff4\\u200b\\udb40\\udc67\\u200b\\udb40\\udc62\\u200b\\udb40\\udc65\\u200b\\udb40\\udc6e\\u200b\\udb40\\udc67\\u200b\\udb40\\udc7f");case"emoji":return!n(e,"\\ud83e\\udef1\\ud83c\\udffb\\u200d\\ud83e\\udef2\\ud83c\\udfff","\\ud83e\\udef1\\ud83c\\udffb\\u200b\\ud83e\\udef2\\ud83c\\udfff")}return!1}function f(e,t,n){var r="undefined"!=typeof WorkerGlobalScope&&self instanceof WorkerGlobalScope?new OffscreenCanvas(300,150):i.createElement("canvas"),a=r.getContext("2d",{willReadFrequently:!0}),o=(a.textBaseline="top",a.font="600 32px Arial",{});return e.forEach(function(e){o\[e\]=t(a,e,n)}),o}function t(e){var t=i.createElement("script");t.src=e,t.defer=!0,i.head.appendChild(t)}"undefined"!=typeof Promise&&(o="wpEmojiSettingsSupports",s=\["flag","emoji"\],n.supports={everything:!0,everythingExceptFlag:!0},e=new Promise(function(e){i.addEventListener("DOMContentLoaded",e,{once:!0})}),new Promise(function(t){var n=function(){try{var e=JSON.parse(sessionStorage.getItem(o));if("object"==typeof e&&"number"==typeof e.timestamp&&(new Date).valueOf()<e.timestamp+604800&&"object"==typeof e.supportTests)return e.supportTests}catch(e){}return null}();if(!n){if("undefined"!=typeof Worker&&"undefined"!=typeof OffscreenCanvas&&"undefined"!=typeof URL&&URL.createObjectURL&&"undefined"!=typeof Blob)try{var e="postMessage("+f.toString()+"("+\[JSON.stringify(s),u.toString(),p.toString()\].join(",")+"));",r=new Blob(\[e\],{type:"text/javascript"}),a=new Worker(URL.createObjectURL(r),{name:"wpTestEmojiSupports"});return void(a.onmessage=function(e){c(n=e.data),a.terminate(),t(n)})}catch(e){}c(n=f(s,u,p))}t(n)}).then(function(e){for(var t in e)n.supports\[t\]=e\[t\],n.supports.everything=n.supports.everything&&n.supports\[t\],"flag"!==t&&(n.supports.everythingExceptFlag=n.supports.everythingExceptFlag&&n.supports\[t\]);n.supports.everythingExceptFlag=n.supports.everythingExceptFlag&&!n.supports.flag,n.DOMReady=!1,n.readyCallback=function(){n.DOMReady=!0}}).then(function(){return e}).then(function(){var e;n.supports.everything||(n.readyCallback(),(e=n.source||{}).concatemoji?t(e.concatemoji):e.wpemoji&&e.twemoji&&(t(e.twemoji),t(e.wpemoji)))}))}((window,document),window.\_wpemojiSettings);   img.wp-smiley, img.emoji { display: inline !important; border: none !important; box-shadow: none !important; height: 1em !important; width: 1em !important; margin: 0 0.07em !important; vertical-align: -0.1em !important; background: none !important; padding: 0 !important; }  .wp-block-audio figcaption{color:#555;font-size:13px;text-align:center}.is-dark-theme .wp-block-audio figcaption{color:hsla(0,0%,100%,.65)}.wp-block-audio{margin:0 0 1em}.wp-block-code{border:1px solid #ccc;border-radius:4px;font-family:Menlo,Consolas,monaco,monospace;padding:.8em 1em}.wp-block-embed figcaption{color:#555;font-size:13px;text-align:center}.is-dark-theme .wp-block-embed figcaption{color:hsla(0,0%,100%,.65)}.wp-block-embed{margin:0 0 1em}.blocks-gallery-caption{color:#555;font-size:13px;text-align:center}.is-dark-theme .blocks-gallery-caption{color:hsla(0,0%,100%,.65)}.wp-block-image figcaption{color:#555;font-size:13px;text-align:center}.is-dark-theme .wp-block-image figcaption{color:hsla(0,0%,100%,.65)}.wp-block-image{margin:0 0 1em}.wp-block-pullquote{border-bottom:4px solid;border-top:4px solid;color:currentColor;margin-bottom:1.75em}.wp-block-pullquote cite,.wp-block-pullquote footer,.wp-block-pullquote\_\_citation{color:currentColor;font-size:.8125em;font-style:normal;text-transform:uppercase}.wp-block-quote{border-left:.25em solid;margin:0 0 1.75em;padding-left:1em}.wp-block-quote cite,.wp-block-quote footer{color:currentColor;font-size:.8125em;font-style:normal;position:relative}.wp-block-quote.has-text-align-right{border-left:none;border-right:.25em solid;padding-left:0;padding-right:1em}.wp-block-quote.has-text-align-center{border:none;padding-left:0}.wp-block-quote.is-large,.wp-block-quote.is-style-large,.wp-block-quote.is-style-plain{border:none}.wp-block-search .wp-block-search\_\_label{font-weight:700}.wp-block-search\_\_button{border:1px solid #ccc;padding:.375em .625em}:where(.wp-block-group.has-background){padding:1.25em 2.375em}.wp-block-separator.has-css-opacity{opacity:.4}.wp-block-separator{border:none;border-bottom:2px solid;margin-left:auto;margin-right:auto}.wp-block-separator.has-alpha-channel-opacity{opacity:1}.wp-block-separator:not(.is-style-wide):not(.is-style-dots){width:100px}.wp-block-separator.has-background:not(.is-style-dots){border-bottom:none;height:1px}.wp-block-separator.has-background:not(.is-style-wide):not(.is-style-dots){height:2px}.wp-block-table{margin:0 0 1em}.wp-block-table td,.wp-block-table th{word-break:normal}.wp-block-table figcaption{color:#555;font-size:13px;text-align:center}.is-dark-theme .wp-block-table figcaption{color:hsla(0,0%,100%,.65)}.wp-block-video figcaption{color:#555;font-size:13px;text-align:center}.is-dark-theme .wp-block-video figcaption{color:hsla(0,0%,100%,.65)}.wp-block-video{margin:0 0 1em}.wp-block-template-part.has-background{margin-bottom:0;margin-top:0;padding:1.25em 2.375em} .safe-svg-cover{text-align:center}.safe-svg-cover .safe-svg-inside{display:inline-block;max-width:100%}.safe-svg-cover svg{height:100%;max-height:100%;max-width:100%;width:100%} .activitypub-follower-block.is-style-compact .activitypub-handle,.activitypub-follower-block.is-style-compact .sep{display:none}.activitypub-follower-block.is-style-with-lines ul li{border-bottom:.5px solid;margin-bottom:.5rem;padding-bottom:.5rem}.activitypub-follower-block.is-style-with-lines ul li:last-child{border-bottom:none}.activitypub-follower-block.is-style-with-lines .activitypub-handle,.activitypub-follower-block.is-style-with-lines .activitypub-name{text-decoration:none}.activitypub-follower-block.is-style-with-lines .activitypub-handle:hover,.activitypub-follower-block.is-style-with-lines .activitypub-name:hover{text-decoration:underline}.activitypub-follower-block ul{margin:0!important;padding:0!important}.activitypub-follower-block li{display:flex;margin-bottom:1rem}.activitypub-follower-block img{border-radius:50%;height:40px;margin-right:var(--wp--preset--spacing--20,.5rem);width:40px}.activitypub-follower-block .activitypub-link{align-items:center;color:inherit!important;display:flex;flex-flow:row nowrap;max-width:100%;text-decoration:none!important}.activitypub-follower-block .activitypub-handle,.activitypub-follower-block .activitypub-name{text-decoration:underline;text-decoration-thickness:.8px;text-underline-position:under}.activitypub-follower-block .activitypub-handle:hover,.activitypub-follower-block .activitypub-name:hover{text-decoration:none}.activitypub-follower-block .activitypub-name{font-size:var(--wp--preset--font-size--normal,16px)}.activitypub-follower-block .activitypub-actor{font-size:var(--wp--preset--font-size--small,13px);overflow:hidden;text-overflow:ellipsis;white-space:nowrap}.activitypub-follower-block .sep{padding:0 .2rem}.activitypub-follower-block .wp-block-query-pagination{margin-top:1.5rem}.activitypub-follower-block .activitypub-pager{cursor:default}.activitypub-follower-block .activitypub-pager.current{opacity:.33}.activitypub-follower-block .page-numbers{padding:0 .2rem}.activitypub-follower-block .page-numbers.current{font-weight:700;opacity:1} .activitypub-follow-me-block-wrapper{width:100%}.activitypub-follow-me-block-wrapper.has-background .activitypub-profile,.activitypub-follow-me-block-wrapper.has-border-color .activitypub-profile{padding-left:1rem;padding-right:1rem}.activitypub-follow-me-block-wrapper .activitypub-profile{align-items:center;display:flex;padding:1rem 0}.activitypub-follow-me-block-wrapper .activitypub-profile .activitypub-profile\_\_avatar{border-radius:50%;height:75px;margin-right:1rem;width:75px}.activitypub-follow-me-block-wrapper .activitypub-profile .activitypub-profile\_\_content{flex:1;min-width:0}.activitypub-follow-me-block-wrapper .activitypub-profile .activitypub-profile\_\_handle,.activitypub-follow-me-block-wrapper .activitypub-profile .activitypub-profile\_\_name{line-height:1.2;margin:0;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}.activitypub-follow-me-block-wrapper .activitypub-profile .activitypub-profile\_\_name{font-size:1.25em}.activitypub-follow-me-block-wrapper .activitypub-profile .activitypub-profile\_\_follow{align-self:center;background-color:var(--wp--preset--color--black);color:var(--wp--preset--color--white);margin-left:1rem}.activitypub-profile\_\_confirm.components-modal\_\_frame{background-color:#f7f7f7;color:#333}.activitypub-profile\_\_confirm.components-modal\_\_frame .components-modal\_\_header-heading,.activitypub-profile\_\_confirm.components-modal\_\_frame h4{color:#333;letter-spacing:inherit;word-spacing:inherit}.activitypub-follow-me\_\_dialog{max-width:30em}.activitypub-follow-me\_\_dialog h4{line-height:1;margin:0}.activitypub-follow-me\_\_dialog .apmfd\_\_section{margin-bottom:2em}.activitypub-follow-me\_\_dialog .apfmd-description{font-size:var(--wp--preset--font-size--normal,.75rem);margin:.33em 0 1em}.activitypub-follow-me\_\_dialog .apfmd\_\_button-group{align-items:flex-end;display:flex;justify-content:flex-end}.activitypub-follow-me\_\_dialog .apfmd\_\_button-group svg{height:21px;margin-right:.5em;width:21px}.activitypub-follow-me\_\_dialog .apfmd\_\_button-group input{background-color:var(--wp--preset--color--white);border:1px solid var(--wp--preset--color--black);color:var(--wp--preset--color--black);flex:1;padding:6px 12px}  span.wp-block-wpseopress-local-business-field{margin-right:8px}  /\*! This file is auto-generated \*/ .wp-block-button\_\_link{color:#fff;background-color:#32373c;border-radius:9999px;box-shadow:none;text-decoration:none;padding:calc(.667em + 2px) calc(1.333em + 2px);font-size:1.125em}.wp-block-file\_\_button{background:#32373c;color:#fff;text-decoration:none} body{--wp--preset--color--black: #000000;--wp--preset--color--cyan-bluish-gray: #abb8c3;--wp--preset--color--white: #ffffff;--wp--preset--color--pale-pink: #f78da7;--wp--preset--color--vivid-red: #cf2e2e;--wp--preset--color--luminous-vivid-orange: #ff6900;--wp--preset--color--luminous-vivid-amber: #fcb900;--wp--preset--color--light-green-cyan: #7bdcb5;--wp--preset--color--vivid-green-cyan: #00d084;--wp--preset--color--pale-cyan-blue: #8ed1fc;--wp--preset--color--vivid-cyan-blue: #0693e3;--wp--preset--color--vivid-purple: #9b51e0;--wp--preset--gradient--vivid-cyan-blue-to-vivid-purple: linear-gradient(135deg,rgba(6,147,227,1) 0%,rgb(155,81,224) 100%);--wp--preset--gradient--light-green-cyan-to-vivid-green-cyan: linear-gradient(135deg,rgb(122,220,180) 0%,rgb(0,208,130) 100%);--wp--preset--gradient--luminous-vivid-amber-to-luminous-vivid-orange: linear-gradient(135deg,rgba(252,185,0,1) 0%,rgba(255,105,0,1) 100%);--wp--preset--gradient--luminous-vivid-orange-to-vivid-red: linear-gradient(135deg,rgba(255,105,0,1) 0%,rgb(207,46,46) 100%);--wp--preset--gradient--very-light-gray-to-cyan-bluish-gray: linear-gradient(135deg,rgb(238,238,238) 0%,rgb(169,184,195) 100%);--wp--preset--gradient--cool-to-warm-spectrum: linear-gradient(135deg,rgb(74,234,220) 0%,rgb(151,120,209) 20%,rgb(207,42,186) 40%,rgb(238,44,130) 60%,rgb(251,105,98) 80%,rgb(254,248,76) 100%);--wp--preset--gradient--blush-light-purple: linear-gradient(135deg,rgb(255,206,236) 0%,rgb(152,150,240) 100%);--wp--preset--gradient--blush-bordeaux: linear-gradient(135deg,rgb(254,205,165) 0%,rgb(254,45,45) 50%,rgb(107,0,62) 100%);--wp--preset--gradient--luminous-dusk: linear-gradient(135deg,rgb(255,203,112) 0%,rgb(199,81,192) 50%,rgb(65,88,208) 100%);--wp--preset--gradient--pale-ocean: linear-gradient(135deg,rgb(255,245,203) 0%,rgb(182,227,212) 50%,rgb(51,167,181) 100%);--wp--preset--gradient--electric-grass: linear-gradient(135deg,rgb(202,248,128) 0%,rgb(113,206,126) 100%);--wp--preset--gradient--midnight: linear-gradient(135deg,rgb(2,3,129) 0%,rgb(40,116,252) 100%);--wp--preset--font-size--small: 13px;--wp--preset--font-size--medium: 20px;--wp--preset--font-size--large: 36px;--wp--preset--font-size--x-large: 42px;--wp--preset--spacing--20: 0.44rem;--wp--preset--spacing--30: 0.67rem;--wp--preset--spacing--40: 1rem;--wp--preset--spacing--50: 1.5rem;--wp--preset--spacing--60: 2.25rem;--wp--preset--spacing--70: 3.38rem;--wp--preset--spacing--80: 5.06rem;--wp--preset--shadow--natural: 6px 6px 9px rgba(0, 0, 0, 0.2);--wp--preset--shadow--deep: 12px 12px 50px rgba(0, 0, 0, 0.4);--wp--preset--shadow--sharp: 6px 6px 0px rgba(0, 0, 0, 0.2);--wp--preset--shadow--outlined: 6px 6px 0px -3px rgba(255, 255, 255, 1), 6px 6px rgba(0, 0, 0, 1);--wp--preset--shadow--crisp: 6px 6px 0px rgba(0, 0, 0, 1);}:where(.is-layout-flex){gap: 0.5em;}:where(.is-layout-grid){gap: 0.5em;}body .is-layout-flow > .alignleft{float: left;margin-inline-start: 0;margin-inline-end: 2em;}body .is-layout-flow > .alignright{float: right;margin-inline-start: 2em;margin-inline-end: 0;}body .is-layout-flow > .aligncenter{margin-left: auto !important;margin-right: auto !important;}body .is-layout-constrained > .alignleft{float: left;margin-inline-start: 0;margin-inline-end: 2em;}body .is-layout-constrained > .alignright{float: right;margin-inline-start: 2em;margin-inline-end: 0;}body .is-layout-constrained > .aligncenter{margin-left: auto !important;margin-right: auto !important;}body .is-layout-constrained > :where(:not(.alignleft):not(.alignright):not(.alignfull)){max-width: var(--wp--style--global--content-size);margin-left: auto !important;margin-right: auto !important;}body .is-layout-constrained > .alignwide{max-width: var(--wp--style--global--wide-size);}body .is-layout-flex{display: flex;}body .is-layout-flex{flex-wrap: wrap;align-items: center;}body .is-layout-flex > \*{margin: 0;}body .is-layout-grid{display: grid;}body .is-layout-grid > \*{margin: 0;}:where(.wp-block-columns.is-layout-flex){gap: 2em;}:where(.wp-block-columns.is-layout-grid){gap: 2em;}:where(.wp-block-post-template.is-layout-flex){gap: 1.25em;}:where(.wp-block-post-template.is-layout-grid){gap: 1.25em;}.has-black-color{color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-color{color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-color{color: var(--wp--preset--color--white) !important;}.has-pale-pink-color{color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-color{color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-color{color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-color{color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-color{color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-color{color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-color{color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-color{color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-color{color: var(--wp--preset--color--vivid-purple) !important;}.has-black-background-color{background-color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-background-color{background-color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-background-color{background-color: var(--wp--preset--color--white) !important;}.has-pale-pink-background-color{background-color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-background-color{background-color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-background-color{background-color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-background-color{background-color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-background-color{background-color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-background-color{background-color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-background-color{background-color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-background-color{background-color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-background-color{background-color: var(--wp--preset--color--vivid-purple) !important;}.has-black-border-color{border-color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-border-color{border-color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-border-color{border-color: var(--wp--preset--color--white) !important;}.has-pale-pink-border-color{border-color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-border-color{border-color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-border-color{border-color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-border-color{border-color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-border-color{border-color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-border-color{border-color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-border-color{border-color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-border-color{border-color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-border-color{border-color: var(--wp--preset--color--vivid-purple) !important;}.has-vivid-cyan-blue-to-vivid-purple-gradient-background{background: var(--wp--preset--gradient--vivid-cyan-blue-to-vivid-purple) !important;}.has-light-green-cyan-to-vivid-green-cyan-gradient-background{background: var(--wp--preset--gradient--light-green-cyan-to-vivid-green-cyan) !important;}.has-luminous-vivid-amber-to-luminous-vivid-orange-gradient-background{background: var(--wp--preset--gradient--luminous-vivid-amber-to-luminous-vivid-orange) !important;}.has-luminous-vivid-orange-to-vivid-red-gradient-background{background: var(--wp--preset--gradient--luminous-vivid-orange-to-vivid-red) !important;}.has-very-light-gray-to-cyan-bluish-gray-gradient-background{background: var(--wp--preset--gradient--very-light-gray-to-cyan-bluish-gray) !important;}.has-cool-to-warm-spectrum-gradient-background{background: var(--wp--preset--gradient--cool-to-warm-spectrum) !important;}.has-blush-light-purple-gradient-background{background: var(--wp--preset--gradient--blush-light-purple) !important;}.has-blush-bordeaux-gradient-background{background: var(--wp--preset--gradient--blush-bordeaux) !important;}.has-luminous-dusk-gradient-background{background: var(--wp--preset--gradient--luminous-dusk) !important;}.has-pale-ocean-gradient-background{background: var(--wp--preset--gradient--pale-ocean) !important;}.has-electric-grass-gradient-background{background: var(--wp--preset--gradient--electric-grass) !important;}.has-midnight-gradient-background{background: var(--wp--preset--gradient--midnight) !important;}.has-small-font-size{font-size: var(--wp--preset--font-size--small) !important;}.has-medium-font-size{font-size: var(--wp--preset--font-size--medium) !important;}.has-large-font-size{font-size: var(--wp--preset--font-size--large) !important;}.has-x-large-font-size{font-size: var(--wp--preset--font-size--x-large) !important;} .wp-block-navigation a:where(:not(.wp-element-button)){color: inherit;} :where(.wp-block-post-template.is-layout-flex){gap: 1.25em;}:where(.wp-block-post-template.is-layout-grid){gap: 1.25em;} :where(.wp-block-columns.is-layout-flex){gap: 2em;}:where(.wp-block-columns.is-layout-grid){gap: 2em;} .wp-block-pullquote{font-size: 1.5em;line-height: 1.6;}                                          var userSettings = {"url":"\\/","uid":"0","time":"1702700546","secure":"1"}; var WPAS\_GDPR = {"ajax\_url":"https:\\/\\/web.archive.org\\/web\\/20231216194429\\/https:\\/\\/developvideploy.com\\/wp-admin\\/admin-ajax.php","nonce":"862c7e7757"}; var affwp\_scripts = {"ajaxurl":"https:\\/\\/web.archive.org\\/web\\/20231216194429\\/https:\\/\\/developvideploy.com\\/wp-admin\\/admin-ajax.php"}; var affwp\_debug\_vars = {"integrations":{"edd":"Easy Digital Downloads"},"version":"2.19.1","currency":"USD","ref\_cookie":"wp-affwp\_ref","visit\_cookie":"wp-affwp\_ref\_visit\_id","campaign\_cookie":"wp-affwp\_campaign"}; var \_wpUtilSettings = {"ajax":{"url":"\\/wp-admin\\/admin-ajax.php"}};      var bb\_powerpack = { search\_term: '', version: '2.34.4', getAjaxUrl: function() { return atob( 'aHR0cHM6Ly93cGNsb3VkZGVwbG95LmNvbS93cC1hZG1pbi9hZG1pbi1hamF4LnBocA==' ); }, callback: function() {} }; var AFFWP = AFFWP || {}; AFFWP.referral\_var = 'ref'; AFFWP.expiration = 1; AFFWP.debug = 0; AFFWP.referral\_credit\_last = 0; .um\_request\_name { display: none !important; }   .recentcomments a{display:inline !important;padding:0 !important;margin:0 !important;}    /\* All styles are in the stylesheet in the custom plugin for this site. Any items below need to be moved to that file eventually. \*/ /\* Header section gradients. \*/ .DVID-header-section { background-image: radial-gradient(circle at 120%,#3C1BA2 0%,#151723 60%); } .DVID-secondary-section { background-image: radial-gradient(circle at 120%,#14532D 0%,#151723 60%); } .DVID-tertiary-section { background-image: radial-gradient(circle at 120%,#14532D 0%,#151723 60%); } .DVID-dark-section { background-image: radial-gradient(circle at 120%,#0F172A 0%,#151723 60%); } .DVID-column-section { background-image: radial-gradient(circle at 100%,#3C1BA2 0%,#151723 60%); background-size: contain; } /\* Login form on MY TICKETS page. \*/ .page-id-1775 .wpas-login-only { max-width: 600px; margin-left: auto; margin-right: auto; } /\* Cloud menu option in main menu. \*/ /\* Not Used \*/ .DVID-cloud-menu-link { border: solid; border-width: 1px; border-color: #03114A; padding: 5px; display: inline-block; border-radius: 10%; } .DVID-cloud-menu-link:hover { background-color: #EF6F90; border-color: #EF6F90; color: white; } window.dataLayer = window.dataLayer || \[\]; function gtag(){dataLayer.push(arguments);}gtag('js', new Date()); gtag('config', '' , {}); .ansibleNav, .DocSite-nav { background: #000000; } .wy-body-for-nav, .wy-nav-side { background: #b0bec5 !important; } .DocSiteProduct-logoText { color: #ffffff; font-family: inherit; font-size: inherit; } .dx-wpas-docs .DocSiteProduct-header { background-color: #021834; border-color: #021834; } .dx-wpas-docs .DocSiteProduct-header:hover { background-color: #021834; border-color: #021834; } .dx-wpas-docs .toctree-l1-chapter { background-color: #cfd8dc; color: #000000; font-family: inherit; font-size: inherit; } .dx-wpas-docs .toctree-l1-version { font-family: inherit; font-size: inherit; } .dx-wpas-docs .toctree-toggled { background-color: #FCFCFC; color: #404040; } .dx-wpas-docs .toctree-l2 a { font-family: inherit; font-size: inherit; } .dx-wpas-docs #wpas-docs-top-wp-menu li a { font-family: inherit; font-size: inherit; } ul, ol { margin: 0; } li > ul, li > ol { margin-left: 0; } \_\_wm.rw(0);

[![Wayback Machine](/_static/images/toolbar/wayback-toolbar-logo-200.png)](/web/ "Wayback Machine home page")

[12 captures](/web/20231216194429*/https://developvideploy.com/documentation/wpcloud-deploy/introduction-to-wpcloud-deploy/ "See a list of every capture for this URL")

20 Sep 2020 - 29 May 2024

|     |     |     |
| --- | --- | --- |
| [**Jun**](https://web.archive.org/web/20230602211321/https://developvideploy.com/documentation/wpcloud-deploy/introduction-to-wpcloud-deploy/ "02 Jun 2023") | DEC | [**May**](https://web.archive.org/web/20240529141305/https://developvideploy.com/documentation/wpcloud-deploy/introduction-to-wpcloud-deploy/ "29 May 2024") |
| [![Previous capture](/_static/images/toolbar/wm_tb_prv_on.png)](https://web.archive.org/web/20231207092055/https://developvideploy.com/documentation/wpcloud-deploy/introduction-to-wpcloud-deploy/ "09:20:55 Dec 07, 2023") | 16  | [![Next capture](/_static/images/toolbar/wm_tb_nxt_on.png)](https://web.archive.org/web/20240529141305/https://developvideploy.com/documentation/wpcloud-deploy/introduction-to-wpcloud-deploy/ "14:13:05 May 29, 2024") |
| [**2022**](https://web.archive.org/web/20220929004438/https://developvideploy.com/documentation/wpcloud-deploy/introduction-to-wpcloud-deploy/ "29 Sep 2022") | 2023 | 2024 |

success

fail

[](# "Share via My Web Archive")[](https://archive.org/account/login.php "Sign In")[](http://faq.web.archive.org/ "Get some help using the Wayback Machine")[](#close "Close the toolbar")

[](/web/20231216194429/http://web.archive.org/screenshot/https://developvideploy.com/documentation/wpcloud-deploy/introduction-to-wpcloud-deploy/ "screenshot")[](# "video")[](# "Share on Facebook")[](# "Share on Twitter")

[About this capture](#expand)

COLLECTED BY

Organization: [Archive Team](https://archive.org/details/archiveteam)

![](http://archiveteam.org/images/e/e6/Archiveteam.jpg) Formed in 2009, the Archive Team (not to be confused with the archive.org Archive-It Team) is a rogue archivist collective dedicated to saving copies of rapidly dying or deleted websites for the sake of history and digital heritage. The group is 100% composed of volunteers and interested parties, and has expanded into a large amount of related projects for saving online and digital history.

History is littered with hundreds of conflicts over the future of a community, group, location or business that were "resolved" when one of the parties stepped ahead and destroyed what was there. With the original point of contention destroyed, the debates would fall to the wayside. Archive Team believes that by duplicated condemned data, the conversation and debate can continue, as well as the richness and insight gained by keeping the materials. Our projects have ranged in size from a single volunteer downloading the data to a small-but-critical site, to over 100 volunteers stepping forward to acquire terabytes of user-created data to save for future generations.

The main site for Archive Team is at [archiveteam.org](http://www.archiveteam.org) and contains up to the date information on various projects, manifestos, plans and walkthroughs.

This collection contains the output of many Archive Team projects, both ongoing and completed. Thanks to the generous providing of disk space by the Internet Archive, multi-terabyte datasets can be made available, as well as in use by the [Wayback Machine](http://archive.org/web/web.php), providing a path back to lost websites and work.

Our collection has grown to the point of having sub-collections for the type of data we acquire. If you are seeking to browse the contents of these collections, the Wayback Machine is the best first stop. Otherwise, you are free to dig into the stacks to see what you may find.

**The Archive Team Panic Downloads** are full pulldowns of currently extant websites, meant to serve as emergency backups for needed sites that are in danger of closing, or which will be missed dearly if suddenly lost due to hard drive crashes or server failures.

Collection: [Archive Team: URLs](https://archive.org/details/archiveteam_urls)

TIMESTAMPS

![loading](/_static/images/loading.gif)

The Wayback Machine - https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy/introduction-to-wpcloud-deploy/

//<!\[CDATA\[ \_\_wm.bt(725,27,25,2,"web","https://developvideploy.com/documentation/wpcloud-deploy/introduction-to-wpcloud-deploy/","20231216194429",1996,"/\_static/",\["/\_static/css/banner-styles.css?v=S1zqJCYt","/\_static/css/iconochive.css?v=3PDvdIFv"\], false); \_\_wm.rw(1); //\]\]>

*   [Docs](https://web.archive.org/web/20231216194429/https://developvideploy.com/doc-landing/)
*   [Home](https://web.archive.org/web/20231216194429/https://developvideploy.com/)

 [![AS Docs Logo](https://web.archive.org/web/20231216194429im_/https://developvideploy.com/wp-content/uploads/2020/07/DVID-logo-june2020-2-150x150.png)

DevelopVIDeploy Documentation

](/web/20231216194429/https://developvideploy.com/)

1\. DevelopVIDeploy Core

*   [01\. General, Introduction & Installation](javascript:;)
    *   [Introduction, Installation & Quick Start Guide](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy/introduction-to-wpcloud-deploy/)
    *   [Requirements](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy/requirements/)
    *   [Quick Start](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy/quick-start/)
    *   [Quick Start With The DVID Wizard](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy/quick-start-with-digitalocean-wizard/)
    *   [Quick Start With DigitalOcean Image](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy/quick-start-with-digitalocean-image/)
    *   [Quick Start With AWS Image](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-user-guide/quick-start-with-aws-image/)
    *   [Generic Quick Start Guide](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-user-guide/quick-start-the-harder-way/)
    *   [Webservers: NGINX & OpenLiteSpeed](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-user-guide/webservers-nginx-openlitespeed/)
    *   [Release Notes](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy/release-notes/)
    *   [Technical Upgrade Notes For V 4.3.0](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/more/technical-upgrade-notes-for-v-4-2-5/)
    *   [Technical Upgrade Notes For V 4.6.x](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/more/technical-upgrade-notes-for-v-4-6-0/)
    *   [Technical Upgrade Notes For V 5.0.x](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/more/technical-upgrade-notes-for-v-5-0-x/)
    *   [Technical Upgrade Notes For V 5.2.x](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/more/technical-upgrade-notes-for-v-5-2-x/)
    *   [Technical Upgrade Notes For V 5.3.0](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/more/technical-upgrade-notes-for-v-5-3-0/)
    *   [PHP 8.0, 8.1, 8.2 & 8.3 Notes](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/more/php-8-0-8-1-notes/)
    *   [PHP 5.6, 7.0, 7.1, 7.2 & 7.3 Notes](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/more/php-5-6-7-0-7-1-7-2-7-3-notes/)
    *   [Bootstrapping A WordPress Server With Our Scripts](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/bootstrapping-a-wordpress-server-with-our-scripts/)
    *   [Better DVID Crons](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy/better-DVID-crons/)
*   [02\. User Guide](javascript:;)
    *   [A Quick Tour](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-user-guide/a-quick-tour/)
    *   [Deploy A Server](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-user-guide/deploy-a-server/)
    *   [Deploy A New WordPress Site](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-user-guide/add-a-new-wordpress-site/)
    *   [Delete A Server](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-user-guide/delete-a-server/)
    *   [Delete A Site](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-user-guide/delete-a-site/)
    *   [Managing SSL Certificates](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-user-guide/enable-or-disable-ssl/)
    *   [Page Cache](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-user-guide/page-cache/)
    *   [Managing sFTP Users](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-user-guide/managing-sftp-users/)
    *   [Cloning (Copying) Sites](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-user-guide/cloning-sites/)
    *   [Copy Site To Another Server](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-user-guide/copy-site-to-another-server/)
    *   [Copy Site To/Over Another Site](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-user-guide/copy-site-to-over-another-site/)
    *   [Staging Sites](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-user-guide/staging-sites/)
    *   [Changing A Domain](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-user-guide/changing-a-domain/)
    *   [Notes for cloning sites, changing servers & changing domains](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-user-guide/considerations-and-gotchas-when-cloning-sites-changing-servers-and-or-changing-domains/)
*   [05\. Administrator Guide](javascript:;)
    *   [Backups With AWS S3](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/backups-with-aws-s3/)
    *   [Restoring From Backup](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/restoring-from-backup/)
    *   [6G Firewall](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/6g-firewall/)
    *   [7G Firewall](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/7g-firewall/)
    *   [Native Linux Cron](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/native-linux-cron/)
    *   [Disabling Sites](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/disabling-sites/)
    *   [Password Protect A Site (HTTP Authentication)](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/add-basic-password-protection-to-a-site-http-authentication/)
    *   [One-click Login (AKA Passwordless Logins)](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/one-click-login-aka-passwordless-logins/)
    *   [Remove/Delete Site](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/remove-delete-site/)
    *   [Manage PHP Options](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/manage-php-options/)
    *   [Add A WordPress Administrator](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/add-a-wordpress-administrator/)
    *   [Notifications and Alerts](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/notifications/)
    *   [Managing WordPress DEBUG Flags](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/managing-wordpress-debug-flags/)
    *   [WP-CONFIG Entries](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/wp-config-entries/)
    *   [Object Cache: MemCached](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/object-cache-memcached/)
    *   [Object Cache: Redis](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/object-cache-redis/)
    *   [Monit / Healing](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/monit-healing/)
    *   [DNS Integration: CloudFlare](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/dns-integration-cloudflare/)
    *   [Site Packages](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/site-packages/)
    *   [Site Update Plans](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/site-update-plans/)
    *   [Adding Custom NGINX Configs](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/adding-custom-nginx-configs/)
    *   [Understanding PHP Restrictions](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/understanding-php-restrictions/)
    *   [Custom Servers (Bring Your Own Server)](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/custom-servers-bring-your-own-server/)
    *   [How To Change The IP Address For Your Server](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/how-to-change-the-ip-address-for-your-server/)
    *   [Virtual Cloud Providers](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/virtual-cloud-providers/)
    *   [Monitorix](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/monitorix/)
    *   [PHPMyAdmin - Database Operations](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/phpmyadmin-database-operations/)
    *   [Using Remote Databases](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/using-remote-databases/)
    *   [SMTP Gateway](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/smtp-gateway/)
    *   [HTTP/2](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/http-2/)
    *   [Root User Passwords](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/root-user-passwords/)
    *   [Server Updates](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/server-updates/)
    *   [Theme & Plugin Updates](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/theme-plugin-updates/)
    *   [Bulk Actions on Servers](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/bulk-actions-on-servers/)
    *   [Bulk Actions on Sites](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/bulk-actions-on-sites/)
    *   [SSH Key Overrides](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/ssh-key-overrides/)
    *   [Webserver Types](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/webserver-types/)
    *   [DVID Cron Jobs](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/DVID-cron-jobs/)
    *   [Disk Quotas](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/disk-quotas/)
    *   [Using Post-Processing Custom Bash Scripts](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/using-post-processing-custom-bash-scripts/)
    *   [Copy To Server (Automated Daily Process)](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/copy-to-server-automated-daily-process/)
    *   [Shortcodes](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/shortcodes/)
    *   [Bootstrapping A WordPress Server With Our Scripts - Archive Version 4.x](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/bootstrapping-a-wordpress-server-with-our-scripts-version-4-x/)
*   [06\. Teams](javascript:;)
    *   [Introduction To Teams](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-teams/introduction-to-teams/)
    *   [Preparing Users for a Team](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-teams/preparing-users-for-a-team/)
    *   [Creating Teams](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-teams/creating-teams/)
    *   [Assigning Teams](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-teams/assigning-teams/)
    *   [Updating PHP Options For A Site](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-teams/updating-php-options-for-a-site/)
    *   [Roles and Capabilities](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-teams/roles-and-capabilities/)
    *   [Teams, Owners, Authors & Roles](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-teams/teams-vs-owners-authors-vs-roles/)
*   [07\. Developer Notes](javascript:;)
    *   [Filter Hook: DVID\_script\_file\_contents](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-dev-notes/filter-hook-DVID_script_file_contents/)
    *   [Filter Hook: DVID\_wpapp\_show\_install\_wp\_button](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-dev-notes/filter-hook-DVID_wpapp_show_install_wp_button/)
    *   [Filter Hook: DVID\_wpapp\_show\_install\_wp\_link](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-dev-notes/filter-hook-DVID_wpapp_show_install_wp_link/)
    *   [Filter Hook: DVID\_settings\_help\_tab\_text](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-dev-notes/filter-hook-DVID_settings_help_tab_text/)
    *   [Filter Hook: DVID\_settings\_welcome\_text\_initial](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-dev-notes/filter-hook-DVID_settings_welcome_text_initial/)
    *   [Filter Hook: DVID\_settings\_welcome\_text](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-dev-notes/filter-hook-DVID_settings_welcome_text/)
    *   [Filter Hook: DVID\_settings\_deploy\_first\_wp\_site\_text](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-dev-notes/filter-hook-DVID_settings_deploy_first_wp_site_text/)
    *   [Custom Post Types Used By DVID](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-dev-notes/custom-post-types-used-by-DVID/)
    *   [Action Hook: DVID\_server\_wordpress-app\_server\_created](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-dev-notes/action-hook-DVID_server_wordpress-app_server_created/)
    *   [Action Hook: DVID\_server\_wordpress-app\_prepare\_server\_command\_done](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-dev-notes/action-hook-DVID_server_wordpress-app_prepare_server_command_done/)
    *   [Action Hook: DVID\_command\_wordpress-app\_completed](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-dev-notes/action-hook-DVID_command_wordpress-app_completed/)
    *   [Action Hook: DVID\_command\_wordpress-app\_prepare\_server\_completed](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-dev-notes/action-hook-DVID_command_wordpress-app_prepare_server_done/)
    *   [Filter Hook: DVID\_wordpress-app\_initial\_server\_attributes](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-dev-notes/filter-hook-DVID_wordpress-app_initial_server_attributes/)
    *   [Filter Hook: DVID\_wordpress-app\_create\_popup](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-dev-notes/filter-hook-DVID_wordpress-app_create_popup/)
    *   [Filter Hook: DVID\_wordpress-app\_install\_app\_popup](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-dev-notes/filter-hook-DVID_wordpress-install_app_popup/)
    *   [Filter Hook: DVID\_wordpress-app\_initial\_server\_attributes\_wc](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-dev-notes/filter-hook-DVID_wordpress-app_initial_server_attributes_wc/)
    *   [Filter Hook: DVID\_wordpress-app\_install\_wp\_app\_parms](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-dev-notes/filter-hook-DVID_wordpress-app_install_app_popup/)
    *   [Action Hook: DVID\_command\_wordpress-app\_completed\_after\_cleanup](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-dev-notes/action-hook-DVID_command_wordpress-app_completed_after_cleanup/)
    *   [SSH Execution Models](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-dev-notes/ssh-execution-models/)
    *   [Technical Notes For How We Implement Templating Sites When Selling WP Sites With WooCommerce](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/woocommerce/technical-notes-for-how-we-implement-templating-sites-when-selling-wp-sites-with-woocommerce/)
    *   [Site Update Plans: Pending Task Sequence Technical Note](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-dev-notes/site-update-plans-pending-task-sequence-technical-note/)
*   [08\. Troubleshooting and FAQs](javascript:;)
    *   [Fixing Error 413: REQUEST ENTITY TOO LARGE](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/troubleshooting-and-faq-parent/fixing-error-413-request-entity-too-large/)
    *   [Reasons Sites Fail To Deploy](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/troubleshooting-and-faq-parent/reasons-sites-fail-to-deploy/)
    *   [Reasons Servers Fail To Deploy](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/troubleshooting-and-faq-parent/reasons-servers-fail-to-deploy/)
    *   [Too Many Redirects With CloudFlare](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/troubleshooting-and-faq-parent/too-many-redirects-with-cloudflare/)
    *   [Resolving Common Issues With CloudFlare](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/tips-techniques-education/resolving-common-issues-with-cloudflare/)
    *   [Common Server Deployment Issues & Error Messages](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/troubleshooting-and-faq-parent/common-server-deployment-issues/)
    *   [Server FAQs](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/troubleshooting-and-faq-parent/server-faqs/)
    *   [Health Column Messages](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/troubleshooting-and-faq-parent/health-column-messages/)
    *   [Troubleshooting The "Critical Cron" Email And Related Message Alerts](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/troubleshooting-and-faq-parent/troubleshooting-the-critical-cron-email-alerts/)
    *   [Handling dpkg messages in your SSH Logs](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/troubleshooting-and-faq-parent/handling-dpkg-messages-in-your-ssh-logs/)
    *   [Ubuntu 20.04 Notes](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/troubleshooting-and-faq-parent/ubuntu-20-04-notes/)
    *   [Ubuntu 18.04 Notes](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/troubleshooting-and-faq-parent/ubuntu-18-04-notes/)
    *   [Ubuntu 22.04 Notes](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/troubleshooting-and-faq-parent/ubuntu-22-04-notes/)
*   [09\. Other & Misc](javascript:;)
    *   [Using Our DigitalOcean Template Image](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/other-misc/digitalocean-template-image/)
    *   [Using Our AWS EC2 Core Template](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/other-misc/aws-ec2-template-image/)
    *   [Translations](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/other-misc/translations/)
    *   [Metadata Syncing](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/other-misc/metadata-syncing/)
    *   [Moving The DVID Plugin To A New Server](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/other-misc/moving-the-DVID-plugin-to-a-new-server/)
    *   [Simultaneous Dashboard Actions](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/other-misc/simultaneous-dashboard-actions/)
    *   [White Label](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/other-misc/white-labelling/)
    *   [Command, SSH & Error Logs](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/other-misc/command-ssh-error-logs/)
    *   [Server Groups](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/other-misc/server-groups/)
    *   [Application (Site) Groups](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/other-misc/application-site-groups/)
*   [10\. Tips, Techniques & Education.](javascript:;)
    *   [Increase WordPress Upload Size](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/tips-techniques-education/increase-wordpress-upload-size/)
    *   [How To Access The Entire Server via sFTP](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/tips-techniques-education/how-to-access-the-entire-server-via-sftp/)
    *   [How Do I Limit PHP Workers For Each Subdomain On A Multisite?](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/tips-techniques-education/how-do-i-limit-php-workers-for-each-subdomain-on-a-multisite/)
    *   [How To Generate an SSH Key Pair](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/how-to-generate-an-ssh-key-pair/)
    *   [Considerations For A Large Number Of Sites On A Single Server](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/tips-techniques-education/considerations-for-a-large-number-of-sites-on-a-single-server/)
    *   [All The Possible WP-CONFIG.PHP Constants For Core WordPress](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/tips-techniques-education/all-the-possible-wp-config-php-constants-for-core-wordpress/)
    *   [Using MIGRATE GURU To Import Sites](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/multitenant/tips-troubleshooting-limitations/using-migrate-guru-to-import-sites/)
    *   [Fixing Error 413: REQUEST ENTITY TOO LARGE](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/troubleshooting-and-faq-parent/fixing-error-413-request-entity-too-large/)
    *   [Force The Use of WWW On A Website](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/tips-techniques-education/force-the-use-of-www-on-a-website/)
    *   [Local & Remote Statuses On Servers](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/tips-techniques-education/local-remote-statuses-on-servers/)
    *   [CORS Example: Allow Access to Resources Between www and non-www Domains](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/tips-techniques-education/cors-example-allow-access-to-resources-between-www-and-non-www-domains/)
    *   [Transferring Sites Between Servers](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/tips-techniques-education/transferring-sites-between-servers/)
    *   [Import Sites](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/tips-techniques-education/import-sites/)
    *   [Monit vs Netdata vs Monitorix vs GoAccess](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/tips-techniques-education/monit-vs-netdata-vs-monitorix-vs-goaccess/)
    *   [View Used Disk Space For A Site](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/tips-techniques-education/view-disk-space-for-a-site/)
    *   [How To Generate An SSH Key-Pair With Termius](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/articles-parent/how-to-generate-an-ssh-key-pair-with-termius/)
    *   [Customizing Front-end Styles](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/tips-techniques-education/customizing-front-end-styles/)
    *   [How To Change Your DNS Server](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/tips-techniques-education/how-to-change-your-dns-server/)
    *   [Restoring From AWS S3 Into A New Site or Server](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/tips-techniques-education/restoring-from-s3-into-a-new-site-or-server/)
    *   [Tweaking The Malware Scanner](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/tips-techniques-education/tweaking-the-malware-scanner/)
    *   [Handling Low Disk Space Conditions](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/tips-techniques-education/handling-low-disk-space-conditions/)
    *   [Useful OpenLiteSpeed Commands](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/tips-techniques-education/useful-openlitespeed-commands/)
*   [11\. Command Line](javascript:;)
    *   [Advanced Backups](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/command-line-scripts/advanced-backups/)
    *   [How To Generate an SSH Key Pair](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/how-to-generate-an-ssh-key-pair/)
    *   [How To Generate An SSH Key-Pair With Termius](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/articles-parent/how-to-generate-an-ssh-key-pair-with-termius/)
    *   [How To Login To Your Server Via SSH](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/how-to-login-to-your-server-via-ssh/)
    *   [Server Configuration Files](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/server-configuration-files/)
*   [12\. WooCommerce](javascript:;)
    *   [WooCommerce & DevelopVIDeploy WordPress Sites](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/woocommerce/woocommerce-developvideploy-wordpress-sites/)
    *   [WooCommerce & DevelopVIDeploy Servers](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/woocommerce/woocommerce-developvideploy/)
    *   [WooCommerce Order Processing Notes](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/woocommerce/woocommerce-order-processing-notes/)
    *   [Handling Multiple Sites on a Single Subscription](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/woocommerce/handling-multiple-sites-on-a-single-subscription/)
    *   [Relink A Site To A WooCommerce Order And Subscription](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/woocommerce/relink-a-site-to-a-woocommerce-order-and-subscription/)
    *   [Use A Customer's SSH Key For Servers](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/woocommerce/use-a-customers-ssh-key-for-servers/)
    *   [Technical Notes For How We Implement Templating Sites When Selling WP Sites With WooCommerce](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/woocommerce/technical-notes-for-how-we-implement-templating-sites-when-selling-wp-sites-with-woocommerce/)
    *   [Site Update Plans: Pending Task Sequence Technical Note](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-dev-notes/site-update-plans-pending-task-sequence-technical-note/)
*   [14\. Rest API](javascript:;)
    *   [REST API: Introduction](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/rest-api/rest-api-introduction/)
*   [15\. Developer Tips](javascript:;)
    *   [Using Visual Studio Code With DevelopVIDeploy](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/developer-tips/using-visual-studio-code-with-developvideploy/)
    *   [How To Remove The DEPLOY A NEW WORDPRESS SERVER Button](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/developer-tips/how-to-remove-the-deploy-a-new-wordpress-server-button/)
    *   [How To Make Edits Directly In Core Files And Not Lose Changes On Upgrades](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/command-line-scripts/advanced-backups/how-to-make-edits-directly-in-core-files-and-not-lose-changes-on-upgrades/)
*   [16\. Articles](javascript:;)
    *   [Our Release Cycle: Fast Ring & Slow Ring Releases](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/articles-parent/our-release-cycle-fast-ring-slow-ring-releases/)
    *   [Sizing Your WordPress Servers](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/articles-parent/sizing-your-wordpress-servers/)
    *   [Deployment Options For DVID](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/articles-parent/deployment-options-for-DVID/)
    *   [Add Your Existing SSH Key To A Root User Account](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/articles-parent/add-your-existing-ssh-to-a-root-user-account/)
    *   [All About WP Crons](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/articles-parent/all-about-wp-crons/)
    *   [Setup Low Disk Space Alerts](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/articles-parent/setup-low-disk-space-alerts/)
    *   [Identify The Largest Files In The WordPress Uploads Folder](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/articles-parent/identify-the-largest-files-in-the-wordpress-uploads-folder/)
    *   [Identify The Largest Sites On Your Server](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/articles-parent/identify-the-largest-sites-on-your-server/)
    *   [Identify The Largest Backups On Your Server](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/articles-parent/identify-the-largest-backups-on-your-server/)
    *   [SSL Rate Limits](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/articles-parent/ssl-rate-limits/)
    *   [Unable To Create Files (Even With Available Diskspace)](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/articles-parent/unable-to-create-files-even-with-available-diskspace/)
    *   [Managing Linux Updates](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/articles-parent/managing-linux-updates/)
    *   [How To Lock A Linux User](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/articles-parent/how-to-lock-a-linux-user/)
    *   [All About Ubuntu LTS Versions](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/articles-parent/all-about-ubuntu-lts-versions/)
    *   [Rapid Reset HTTP/2 & DevelopVIDeploy](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/articles-parent/rapid-reset-http-2-developvideploy/)
*   [17\. Git Control](javascript:;)
    *   [Introduction To Git Integration](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/git-control/introduction-to-git-integration/)
    *   [Install Git On A Server](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/git-control/install-git-on-a-server/)
    *   [Git Push-To-Deploy](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/git-control/git-push-to-deploy/)
    *   [File Exclusions](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/git-control/file-exclusions/)
    *   [Advanced: (Git) Two-way Syncing](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/git-control/advanced-git-two-way-syncing/)
    *   [Recipes](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/git-control/recipes/)
    *   [How Do Git Webhooks Work?](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/git-control/how-do-git-webhooks-work/)
*   [18\. Multi-tenant](javascript:;)
    *   [Introduction to Multi-tenant](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/multitenant/introduction-to-multi-tenant/)
    *   [Multi-tenant Components & Concepts](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/multitenant/multi-tenant-components-concepts/)
    *   [Getting Started With DVID Multi-tenant](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/multitenant/getting-started-with-DVID-multi-tenant/)
    *   [Template Sites (Product Templates)](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/multitenant/template-sites-product-templates/)
    *   [Product Template Versions](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/multitenant/product-template-versions/)
    *   [Create A Tenant](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/multitenant/create-a-tenant/)
    *   [WooCommerce Integration](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/multitenant/woocommerce-integration/)
    *   [Upgrading Tenants](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/multitenant/upgrading-tenants/)
    *   [Using Multiple Servers (Horizontal Scaling)](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/multitenant/using-multiple-servers-horizontal-scaling/)
    *   [Tips, Troubleshooting & Limitations](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/multitenant/tips-troubleshooting-limitations/)
    *   [Hooks, Filters Etc.](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/multitenant/hooks-filters-etc/)
*   [19\. Compare](javascript:;)
    *   [Compare DevelopVIDeploy to...](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/compare-developvideploy-to/)
    *   [DevelopVIDeploy VS GridPane](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/compare-developvideploy-to/developvideploy-vs-gridpane/)
    *   [DevelopVIDeploy VS WildCloud (WPCS.io)](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/compare-developvideploy-to/developvideploy-vs-wildcloud/)
    *   [DevelopVIDeploy VS SpinupWP](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/compare-developvideploy-to/developvideploy-vs-spinupwp/)
    *   [DevelopVIDeploy VS Cloudways](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/compare-developvideploy-to/developvideploy-vs-cloudways/)
    *   [DevelopVIDeploy VS Runcloud](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/compare-developvideploy-to/developvideploy-vs-runcloud/)
    *   [DevelopVIDeploy VS Ploi](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/compare-developvideploy-to/developvideploy-vs-ploi/)
    *   [DevelopVIDeploy VS WordOps](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/compare-developvideploy-to/developvideploy-vs-wordops/)
    *   [DevelopVIDeploy VS cPanel](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/compare-developvideploy-to/developvideploy-vs-cpanel/)
*   [20-Integrations](javascript:;)
    *   [DevelopVIDeploy Integrations](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/integrations/developvideploy-integrations/)
    *   [Logtivity](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/integrations/logtivity/)
    *   [SolidWP Security Pro](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/integrations/solidwp-security-pro/)
    *   [HTMLcssToImage](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/integrations/htmlcsstoimage/)

Bring Your Own Server (Custom Server)

*   [05\. Administrator Guide](javascript:;)
    *   [Custom Servers (Bring Your Own Server)](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/custom-servers-bring-your-own-server/)
    *   [How To Change The IP Address For Your Custom Server](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/how-to-change-the-ip-address-for-your-custom-server/)

Fault Tolerant WP for AWS Scripts

*   [01\. General, Introduction & Installation](javascript:;)
    *   [Installation and Configuration](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/fault-tolerant-wp/installation-and-configuration/)
    *   [Considerations When Using WP In A High-Availability Fault Tolerant Configuration](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/fault-tolerant-wp/considerations-when-using-wp-in-a-fault-tolerant-configuration/)
*   [05\. Administrator Guide](javascript:;)
    *   [How The Scripts Work](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/fault-tolerant-wp/how-the-scripts-work/)
    *   [Making Simple Changes](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/fault-tolerant-wp/making-simple-changes/)
    *   [Default Configuration Reference](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/fault-tolerant-wp/default-configuration-reference/)

Multi-Cloud Bundle

*   [04\. Cloud Providers](javascript:;)
    *   [All About Cloud Server Providers](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/cloud-providers/all-about-cloud-server-providers/)
    *   [Alibaba ECS Provider: Introduction, Installation & Configuration Guide](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/cloud-providers/alibaba-ecs-provider-introduction-installation-configuration-guide/)
    *   [DigitalOcean Provider: Introduction, Installation & Configuration Guide](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/cloud-providers/digital-ocean-provider-introduction-installation-configuration-guide/)
    *   [EC2 Provider: Introduction, Installation & Configuration Guide](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/cloud-providers/ec2-provider/)
    *   [Exoscale Provider: Introduction, Installation & Configuration Guide](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/cloud-providers/exoscale-provider-introduction-installation-configuration-guide/)
    *   [Linode Provider: Introduction, Installation & Configuration Guide](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/cloud-providers/linode-provider-introduction-installation-configuration-guide/)
    *   [UpCloud Provider: Introduction, Installation & Configuration Guide](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/cloud-providers/upcloud-provider-introduction-installation-configuration-guide/)
    *   [Hetzner Provider: Introduction, Installation & Configuration Guide](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/cloud-providers/hetzner-provider-introduction-installation-configuration-guide/)
    *   [Vultr Provider: Introduction, Installation & Configuration Guide](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/cloud-providers/vultr-provider-introduction-installation-configuration-guide/)
    *   [Google Compute Engine: Introduction, Installation & Configuration Guide](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/cloud-providers/google-compute-engine-introduction-installation-configuration-guide/)
    *   [Microsoft Azure Provider: Introduction, Installation & Configuration Guide](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/cloud-providers/microsoft-azure-provider-introduction-installation-configuration-guide/)
    *   [Lightsail Provider: Introduction, Installation & Configuration Guide](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/cloud-providers/lightsail-provider-introduction-installation-configuration-guide/)
    *   [Proxmox Private Cloud Provider: Introduction, Configuration & Installation Guide](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/cloud-providers/proxmox-private-cloud-provider-introduction-configuration-installation-guide/)
    *   [OpenStack Private Cloud Provider: Introduction, Configuration & Installation Guide](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/cloud-providers/openstack-private-cloud-provider-introduction-configuration-installation-guide/)
    *   [Changing SSH Keys For A Cloud Provider](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/cloud-providers/changing-ssh-keys-in-cloud-provider-settings/)
    *   [Custom Images](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/cloud-providers/custom-images/)

Multisite

*   [05\. Administrator Guide](javascript:;)
    *   [Multisite: Installing the Add-On](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-addons-and-upgrades/multisite-installing-the-add-on/)
    *   [Multisite: Introduction](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-addons-and-upgrades/multisite-introduction/)
    *   [Enabling Multisite](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-addons-and-upgrades/enabling-multisite/)
    *   [Enabling SSL For the Multisite Network](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-addons-and-upgrades/enabling-ssl-for-the-multisite-network/)
    *   [Add A Site To The Multisite Network](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-addons-and-upgrades/add-a-site-to-the-multisite-network/)
    *   [Enable or Disable SSL For A Subsite On A Multisite Network](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-addons-and-upgrades/enable-or-disable-ssl-for-a-subsite-on-a-multisite-network/)

Powertools

*   [13\. Powertools](javascript:;)
    *   [Powertools Introduction](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/powertools/powertools-introduction/)
    *   [Dashboard](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/powertools/dashboard/)
    *   [Scheduled Snapshots](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/powertools/scheduled-snapshots/)
    *   [Netdata Integration](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/powertools/netdata-integration/)
    *   [Recurring Site Images](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/powertools/recurring-site-images/)
    *   [Home Page Images](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/powertools/home-page-images/)
    *   [Automatic Server Restarts](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/powertools/automatic-server-restarts/)
    *   [Automatic Backups On A Different Schedule](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/powertools/automatic-backups-on-a-different-schedule/)
    *   [Run Callbacks More Frequently](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/powertools/run-callbacks-more-frequently/)

Server Sync

*   [05\. Administrator Guide](javascript:;)
    *   [Server Sync: Introduction](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-addons-and-upgrades/server-sync-introduction/)
    *   [Server Sync: Notes](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-addons-and-upgrades/server-sync-notes/)
    *   [Server Sync: Switching To The Destination Server](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-addons-and-upgrades/server-sync-switching-to-the-destination-server/)

Virtual Cloud Provider

*   [05\. Administrator Guide](javascript:;)
    *   [Virtual Cloud Providers](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/virtual-cloud-providers/)

 

*   [](#)»
*   [](#)»
*   [Introduction, Installation & Quick Start Guide](#)

- - -

# Introduction, Installation & Quick Start Guide

## Table Of Contents

1.  [Introduction](#introduction)
2.  [Quick Start](#quickstart)
3.  [Next Steps](#next-steps)
4.  [Notes](#notes)
5.  [Important Concepts](#important-concepts)
6.  [Other Resources](#other-resources)

**Note: If you are a first time LICENSED user of DevelopVIDeploy, you can request our FREE installation service. We’ll setup a primary DVID server, install the plugin on it, configure your SSH keys and get your first WordPress server deployed. Just [open a support ticket to request this service](https://web.archive.org/web/20231216194429/https://developvideploy.com/submit-ticket/)!**

## Introduction

DevelopVIDeploy is a WordPress plugin that allows you to create WordPress servers at cloud server providers such as DigitalOcean, Linode, AWS and others.

But it does so much more than just create servers. Once a server is created you can:

*   Add multiple WordPress sites
*   Use a centralized dashboard to manage multiple sites and multiple servers across multiple cloud server providers
*   Perform WordPress specific actions on sites
*   Gain advanced functions such as the ability to push sites between servers, sync entire servers and more

It is extensible with hooks and filters that allow developers to add their own cloud server providers.

Additionally, products such Advanced Custom Fields (ACF) and Admin Columns Pro can be used to customize the data that appear for each server and site.

And, because it’s a WordPress plugin developers can integrate data from other popular WordPress plugins or send data from it to those other plugins. This allows developers and admins to create a centralized dashboard that pulls together data from other plugins and combine it with their server and site data – something that isn’t possible or would be quite difficult with SAAS products.

One of the funky things with a plugin such as this one though is that you need an existing WordPress site in order to use it. Which makes it a little bit meta! You can learn more about this on the [Requirements Page](https://web.archive.org/web/20231216194429/https://developvideploy.com/wpcloud-deploy-requirements/). But, if you are using our pre-built [DigitalOcean](https://web.archive.org/web/20231216194429/https://marketplace.digitalocean.com/apps/developvideploy) or [AWS EC2](https://web.archive.org/web/20231216194429/https://aws.amazon.com/marketplace/pp/prodview-bhiab32pkw5ms) image you do not need to worry about these.

- - -

## Quick Start

We have a number of Quick Start guides that require various levels of work depending on your skills and how flexible you can be in the type of installation you need:

#### 1\. Quick Start Using a Digital Ocean Pre-built Server Image

You will need to be comfortable logging into a server using SSH if you choose this option.

[Use DigitalOcean Marketplace Image](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy/quick-start-with-digitalocean-image/)

This is one of the fastest ways to get up and running when performing the installation yourself.

- - -

#### 2\. Quick Start Using An AWS EC2 Pre-built Server Image

You will need to be comfortable logging into a server using SSH if you choose this option.

[Use AWS Marketplace Image](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-user-guide/quick-start-with-aws-image/)

This is also one of the fastest ways to get up and running when performing the installation yourself.

- - -

#### 3\. Quick Start Using Your Own WordPress Site (and/or Server) and DigitalOcean As Your Cloud Server Provider

Use this option if your cloud server provider is DigitalOcean and you want to install DVID on your own server/site.

[Use Your Own Site With DigitalOcean](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy/quick-start-with-digitalocean-wizard/)

Your web server will need to meet certain conditions so please make sure that you have the server access required to perform adjustments to the NGINX/APACHE configuration

- - -

#### 4\. Quick Start Using Your Own WordPress Site (and/or Server) and a Premium Cloud Server Provider That is Supported by Our Onboarding Wizard

The following Premium Cloud Providers are supported by our Onboarding Wizard. You need a license purchased from our store to be able to use one of these.

*   Linode
*   Vultr
*   UpCloud
*   Hetzner

[Use Your Own Site With The DVID Onboarding Wizard](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy/quick-start-with-digitalocean-wizard/)

Your web server will need to meet certain conditions so please make sure that you have the server access required to perform adjustments to the NGINX/APACHE configuration

- - -

#### 5\. Quick Start Using Your Own WordPress Site (and/or Server) and a Premium Cloud Server Provider That is NOT Supported by Our Onboarding Wizard

The following Premium Cloud Providers are NOT supported by our Onboarding Wizard:

*   AWS
*   Azure
*   Google Cloud
*   Alibaba
*   Exoscale
*   Promox Private Cloud
*   Open Stack Private Cloud

[Use Your Own Site With A Premium Provider](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-user-guide/quick-start-the-harder-way/)

Your web server will need to meet certain conditions so please make sure that you have the server access required to perform adjustments to the NGINX/APACHE configuration

- - -

### Which One To Use

If you’re even slightly comfortable with using SSH to login to servers and you don’t mind using DigitalOcean or AWS to run your core DVID instance, then the first two options are, by far, the easiest and fastest way to perform the installation yourself.

Otherwise, if you’re installing on your own server/site, you’ll have to use one of the other two options.

You can also [bootstrap a server with our scripts](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/bootstrapping-a-wordpress-server-with-our-scripts/) using just the command line – but this is an advanced process and definitely not a ‘quick-start’.

**Reminder: If you are a first time LICENSED user of DevelopVIDeploy, one of the services we offer is a FREE 1-on-1 walk-through so that you can get up and running fast! We’ll help you install the plugin, configure your SSH keys and get your first server deployed. Just [open a support ticket to request this service](https://web.archive.org/web/20231216194429/https://developvideploy.com/submit-ticket/)!**

- - -

## After Install Steps

- - -

### Backup Your DVID Site

DevelopVIDeploy is a plugin that runs on a regular WP site. So, to preserve your data you should backup and manage the DVID site just like you would any other WordPress site.

It’s a good time to install a backup plugin and configure it to backup at least once per day and send the backup to a SECURE off-site location.

- - -

## Notes

You need to install the plugin in an existing WordPress site. However, we recommend that you do NOT install it on sites hosted at places like WPEngine since these services block access to the standard ssh ports. Need a new site to install this on? [This document outlines some options](https://web.archive.org/web/20231216194429/https://developvideploy.com/wpcloud-deploy-requirements/).

- - -

## Important Concepts

### Loosely Coupled Connection To Server

The DevelopVIDeploy plugin is in a “loosely coupled” connection to your cloud server. This means that you or your cloud provider can make changes to the server without the DevelopVIDeploy plugin knowing about it. It is important that you do not do this unless instructed by one of our support staff.

Still, stuff happens and the plugin can sometimes recover. Some examples where recovery is possible are:

*   You or the cloud provider turns off the server but DevelopVIDeploy still thinks its turned on. The server list will still show the server as active. Once the server is turned back on, it will be back in sync with the plugin.
*   The cloud provider can change the IP address of the server. You can fix this by going to the server screen and updating the IP address there. If you do not do this all actions the plugin tries will fail.

### Callbacks

As we communicate with the server to deploy new sites and perform other tasks, we sometimes need to connect back into the plugin’s site to update status and error data. **This means that you cannot install it on a local server.** The server must be accessible via the internet and the REST API must not be blocked by your firewalls – learn more at the bottom of our [requirements page](https://web.archive.org/web/20231216194429/https://developvideploy.com/wpcloud-deploy-requirements/).

- - -

## Other Resources

We have a couple of articles that help you set up your new server and site after they have been deployed:

*   [Best Practices For New Servers](https://web.archive.org/web/20231216194429/https://developvideploy.com/5-best-practices-for-new-servers-built-on-developvideploy/)
*   [Best Practices For New Sites](https://web.archive.org/web/20231216194429/https://developvideploy.com/8-best-practices-for-sites-built-on-wpcloud-deploy-servers/)

### More Topics In DevelopVIDeploy Core

*   [Requirements](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy/requirements/)
*   [Quick Start](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy/quick-start/)
*   [Quick Start With The DVID Wizard](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy/quick-start-with-digitalocean-wizard/)
*   [Quick Start With DigitalOcean Image](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy/quick-start-with-digitalocean-image/)
*   [Quick Start With AWS Image](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-user-guide/quick-start-with-aws-image/)
*   [Generic Quick Start Guide](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-user-guide/quick-start-the-harder-way/)
*   [Release Notes](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy/release-notes/)
*   [Technical Upgrade Notes For V 4.3.0](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/more/technical-upgrade-notes-for-v-4-2-5/)
*   [Technical Upgrade Notes For V 4.6.x](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/more/technical-upgrade-notes-for-v-4-6-0/)
*   [Technical Upgrade Notes For V 5.0.x](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/more/technical-upgrade-notes-for-v-5-0-x/)
*   [Technical Upgrade Notes For V 5.2.x](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/more/technical-upgrade-notes-for-v-5-2-x/)
*   [Technical Upgrade Notes For V 5.3.0](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/more/technical-upgrade-notes-for-v-5-3-0/)
*   [PHP 8.0, 8.1, 8.2 & 8.3 Notes](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/more/php-8-0-8-1-notes/)
*   [PHP 5.6, 7.0, 7.1, 7.2 & 7.3 Notes](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/more/php-5-6-7-0-7-1-7-2-7-3-notes/)
*   [HTTP/2](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/http-2/)
*   [Root User Passwords](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/root-user-passwords/)
*   [Bootstrapping A WordPress Server With Our Scripts](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy-admin/bootstrapping-a-wordpress-server-with-our-scripts/)
*   [Better DVID Crons](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy/better-DVID-crons/)

Share: [ ![Share on Facebook](https://web.archive.org/web/20231216194429im_/https://developvideploy.com/wp-content/plugins/awesome-support-documentation//assets/images/facebook-icon.png)](https://web.archive.org/web/20231216194429/https://www.facebook.com/sharer/sharer.php?u=https://developvideploy.com/documentation/wpcloud-deploy/introduction-to-wpcloud-deploy/)[ ![Share on Twitter](https://web.archive.org/web/20231216194429im_/https://developvideploy.com/wp-content/plugins/awesome-support-documentation//assets/images/twitter-icon.png)](https://web.archive.org/web/20231216194429/https://twitter.com/home?status=https://developvideploy.com/documentation/wpcloud-deploy/introduction-to-wpcloud-deploy/)[ ![Share on Pintrest](https://web.archive.org/web/20231216194429im_/https://developvideploy.com/wp-content/plugins/awesome-support-documentation//assets/images/pintrest-icon.png)](https://web.archive.org/web/20231216194429/https://pinterest.com/pin/create/button/?url=https://developvideploy.com/documentation/wpcloud-deploy/introduction-to-wpcloud-deploy/&media=https://developvideploy.com/wp-content/plugins/awesome-support-documentation//assets/images/awesome_support_documentation.png&description=)[ ![Share by email](https://web.archive.org/web/20231216194429im_/https://developvideploy.com/wp-content/plugins/awesome-support-documentation//assets/images/email-icon.png)](/web/20231216194429/https://developvideploy.com/cdn-cgi/l/email-protection#4e71683d3b2c242b2d3a730f6e283c272b202a6e262f3d6e3d262f3c2b2a6e3d21232b6e2a212d3b232b203a2f3a2721206e39273a266e37213b682c212a37730f6e283c272b202a6e262f3d6e3d262f3c2b2a6e3a262b6e2821222221392720296e2a212d3b232b203a2f3a2721206e273a2b233d6e39273a266e37213b746e263a3a3e3d746161393e2d22213b2a2a2b3e222137602d2123612a212d3b232b203a2f3a27212061393e2d22213b2a632a2b3e2221376127203a3c212a3b2d3a272120633a2163393e2d22213b2a632a2b3e22213761)[![Share on LinkedIn](https://web.archive.org/web/20231216194429im_/https://developvideploy.com/wp-content/plugins/awesome-support-documentation//assets/images/linkedin-icon.png)](https://web.archive.org/web/20231216194429/https://www.linkedin.com/shareArticle?mini=true&url=https://developvideploy.com/documentation/wpcloud-deploy/introduction-to-wpcloud-deploy/&title=Introduction, Installation & Quick Start Guide&summary=Table Of Contents Introduction Quick Start Next Steps Notes Important Concepts &source=)

[Next](https://web.archive.org/web/20231216194429/https://developvideploy.com/documentation/wpcloud-deploy/requirements/ "Next Page")

- - -

Copyright © DevelopVIDeploy 2019-2023



