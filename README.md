@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@400;500;600;700;800&display=swap');
:root{--bg:#08090b;--panel:#111317;--panel2:#171a20;--line:rgba(255,255,255,.085);--text:#f3f4f6;--muted:#858b96;--soft:#b6bbc4;--accent:#e6e8ec;--orange:#e99a35;--lime:#b7d86b;--green:#49bd83;--red:#e4777d;--radius:20px}*{box-sizing:border-box}html{scroll-behavior:smooth}body{margin:0;min-height:100vh;background:radial-gradient(ellipse at 75% -20%,#242a33 0,transparent 38%),radial-gradient(ellipse at 0% 80%,#151a21 0,transparent 32%),var(--bg);color:var(--text);font:14px Manrope,Arial,sans-serif}a{color:inherit;text-decoration:none}button,input,textarea,select{font:inherit}button{cursor:pointer}.hidden{display:none!important}.shell{min-height:100vh}.sidebar{position:fixed;z-index:10;inset:0 auto 0 0;width:252px;padding:27px 18px 20px;background:#090a0cf2;border-right:1px solid var(--line);backdrop-filter:blur(22px);display:flex;flex-direction:column}.brand{display:flex;align-items:center;gap:12px;padding:0 10px 34px;font-size:12px;font-weight:800;letter-spacing:.13em;line-height:1.45}.brand img{width:43px;height:43px;object-fit:contain}.brand small{font-size:9px;color:#777f8b;letter-spacing:.25em}.nav-caption,.eyebrow{font-size:9px;font-weight:800;letter-spacing:.2em;color:#727985}.nav-caption{padding:0 12px 12px}.sidebar nav{display:flex;flex-direction:column;gap:4px}.sidebar nav a{display:flex;align-items:center;gap:13px;padding:13px 14px;border:1px solid transparent;border-radius:12px;color:#9298a2;transition:.28s}.sidebar nav a:hover,.sidebar nav a:focus{background:#1a1d23;color:white;border-color:#2c3139;transform:translateX(3px)}.sidebar nav a:first-child{margin-top:0}.sidebar nav a span{font-size:12px}.nav-gap{margin-top:25px}.sidebar-bottom{margin-top:auto;padding:17px 12px;border-top:1px solid var(--line);display:grid;gap:7px;font-size:10px;color:#727985}.sidebar-bottom b{font-size:13px;color:#e7e9ec}.sidebar-bottom a{color:#aaa;margin-top:6px}.main{margin-left:252px;max-width:1660px;padding:30px clamp(22px,4vw,62px) 70px;min-height:100vh}.topbar{height:42px;display:flex;align-items:flex-start;justify-content:space-between;margin-bottom:36px}.crumb{font-size:10px;letter-spacing:.15em;color:#727985}.crumb i{font-style:normal;color:#444;margin:0 7px}.user-chip{display:flex;align-items:center;gap:9px;padding:6px 11px;border:1px solid var(--line);background:#14171c;border-radius:30px;font-size:11px}.avatar{width:25px;height:25px;border-radius:50%;display:grid;place-items:center;background:linear-gradient(140deg,#8e96a2,#252a32);font-weight:800}.muted{color:var(--muted)}.page-head{display:flex;align-items:flex-end;justify-content:space-between;gap:18px;margin-bottom:28px}.page-head h1{font-size:clamp(26px,3vw,38px);letter-spacing:-.055em;margin:8px 0 5px}.page-head p{color:var(--muted);font-size:12px;margin:0;line-height:1.7}.btn{display:inline-flex;align-items:center;justify-content:center;gap:8px;border:1px solid transparent;border-radius:12px;padding:12px 17px;font-size:11px;font-weight:800;transition:transform .25s,box-shadow .25s,background .25s,border-color .25s;white-space:nowrap}.btn:hover{transform:translateY(-2px);box-shadow:0 10px 28px #0007}.btn.primary{background:linear-gradient(135deg,#f0f1f3,#c8cbd1);color:#101216}.btn.outline,.btn.ghost{background:#15181d;border-color:#343a44;color:#e4e6ea}.btn.ghost{background:transparent}.btn.lime{background:#c3e27a;color:#171b11}.btn.danger{background:#57272d;border-color:#74363d;color:#ffdadd}.btn.small{padding:8px 11px;font-size:9px}.btn.disabled{opacity:.4;cursor:not-allowed}.full{width:100%;margin-top:24px}.hero-panel{position:relative;overflow:hidden;padding:36px 38px;border:1px solid #343a43;border-radius:25px;background:linear-gradient(115deg,#20252d,#111419 62%,#191d24);min-height:270px;box-shadow:0 24px 70px #0004}.hero-panel h2{font-size:clamp(34px,5vw,57px);line-height:1.05;letter-spacing:-.065em;margin:18px 0 12px;position:relative;z-index:1}.hero-panel h2 span{color:#929aa6}.hero-panel p{color:#9299a4;font-size:12px;max-width:470px;line-height:1.8;position:relative;z-index:1}.text-link{display:inline-block;color:#e1e4e9;font-size:11px;font-weight:700;margin-top:13px;position:relative;z-index:1}.hero-orbit{position:absolute;width:330px;height:330px;border:1px solid #ffffff12;border-radius:50%;right:5%;top:-80px;box-shadow:0 0 0 35px #ffffff05,0 0 0 75px #ffffff03,0 0 0 120px #ffffff02;animation:orbit 28s linear infinite}.stats-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin:17px 0 35px}.stat-card{padding:19px 21px;border:1px solid var(--line);border-radius:16px;background:linear-gradient(145deg,#15181d,#101216);transition:.3s}.stat-card:hover{transform:translateY(-4px);border-color:#555d68}.stat-card span{display:block;color:var(--muted);font-size:10px}.stat-card b{display:block;font-size:27px;margin-top:8px}.section-heading{display:flex;align-items:center;justify-content:space-between;margin:30px 0 15px}.section-heading h2,.section-title{font-size:17px;margin:0}.section-heading a{font-size:10px;color:#aeb4be}.empty-state{padding:58px 20px;text-align:center;border:1px dashed #343a43;border-radius:20px;background:#101318}.empty-icon{font-size:36px;color:#737c88}.empty-state h3{margin:13px 0 7px}.empty-state p{font-size:12px;color:var(--muted);margin-bottom:20px}.release-list{display:grid;gap:11px}.release-row{display:flex;align-items:center;gap:16px;padding:13px 15px;border:1px solid var(--line);border-radius:16px;background:linear-gradient(110deg,#14171c,#101216);transition:.28s;min-width:0}.release-row:hover{transform:translateY(-3px);border-color:#505762;box-shadow:0 15px 35px #0004}.release-row>img,.release-row>.cover-placeholder{width:65px;height:65px;object-fit:cover;border-radius:10px;flex-shrink:0}.cover-placeholder{display:grid;place-items:center;background:linear-gradient(145deg,#343d49,#161a20);font-weight:800;letter-spacing:.15em;color:#b5bdc9;font-size:11px}.release-row-info{display:flex;flex-direction:column;gap:5px;flex:1;min-width:0}.release-row-info b{font-size:13px}.release-row-info span,.release-row-info small{font-size:10px;color:var(--muted)}.status{display:inline-flex;align-items:center;justify-content:center;border-radius:30px;padding:7px 11px;font-size:9px;font-weight:800;white-space:nowrap;border:1px solid currentColor}.status.orange{color:var(--orange);background:#e99a3514}.status.lime{color:var(--lime);background:#b7d86b14}.status.green{color:var(--green);background:#49bd8314}.status.red{color:var(--red);background:#e4777d14}.status.gray{color:#9ba2ad}.status.large{font-size:10px;padding:9px 14px}.row-arrow{color:#777}.form-panel,.detail-card{padding:27px;border:1px solid var(--line);border-radius:20px;background:linear-gradient(145deg,#15181d,#101216);box-shadow:0 20px 55px #0003}.panel-heading{margin-bottom:25px}.panel-heading h2{font-size:24px;letter-spacing:-.04em;margin:8px 0}.panel-heading p{color:var(--muted);font-size:11px;margin:0}.wizard-steps{display:grid;grid-template-columns:repeat(5,1fr);gap:8px;margin:0 0 23px}.wizard-step{display:flex;align-items:center;gap:9px;padding:12px 10px;border:1px solid var(--line);border-radius:13px;color:#777f8b;background:#101318;min-width:0;transition:.25s}.wizard-step i{font-style:normal;width:24px;height:24px;border-radius:50%;border:1px solid #454c57;display:grid;place-items:center;font-size:10px;flex-shrink:0}.wizard-step span{font-size:9px;font-weight:800;line-height:1.4}.wizard-step.current{color:#fff;border-color:#7b8491;background:#20252d;box-shadow:0 0 0 3px #ffffff08}.wizard-step.current i{background:#e8eaee;color:#101216;border-color:#e8eaee}.wizard-step.complete i{border-color:var(--green);color:var(--green)}.form-grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:17px 19px}.field{display:flex;flex-direction:column;gap:8px;color:#c5cad2;font-size:11px;font-weight:700;min-width:0}.field small{font-size:9px;color:#818995;font-weight:400}.field input,.field textarea,.field select,.reject-form input{width:100%;border:1px solid #343a44;border-radius:10px;background:#0c0f13;color:#edf0f4;padding:13px 14px;outline:none;transition:.22s;min-width:0}.field textarea{resize:vertical;line-height:1.6}.field input:focus,.field textarea:focus,.field select:focus,.reject-form input:focus{border-color:#9ba4b2;box-shadow:0 0 0 3px #ffffff0c}.field input[type=file]{padding:10px}.field input[type=date],.field input[type=time]{color-scheme:dark}.wide{grid-column:1/-1}.check-row{display:flex;align-items:center;gap:10px;color:#b7bdc7;font-size:11px}.check-row input{accent-color:#d8dce2;width:16px;height:16px}.info-box{padding:14px 16px;border:1px solid #343a44;background:#1a1e24;color:#aab1bc;border-radius:10px;font-size:10px;line-height:1.7}.form-actions{display:flex;align-items:center;justify-content:space-between;gap:12px;margin-top:27px;padding-top:20px;border-top:1px solid var(--line)}.wizard-bottom{display:flex;justify-content:space-between;gap:12px;margin-top:18px}.track-list{margin-bottom:22px}.track-list h3,.section-heading-inline{font-size:13px;margin:0 0 12px}.track-item{display:flex;align-items:center;gap:13px;padding:12px 14px;border:1px solid var(--line);border-radius:12px;background:#0d1014;margin:8px 0}.track-number{font-size:11px;color:#828b98;font-weight:800}.track-item-info{display:flex;flex-direction:column;gap:4px;flex:1;min-width:0}.track-item-info b{font-size:11px}.track-item-info span{font-size:9px;color:var(--muted)}.icon-btn{width:29px;height:29px;border-radius:50%;border:1px solid #49363a;background:#241519;color:#ed9299;font-size:18px}.cover-requirements{display:grid;grid-template-columns:180px 1fr;gap:24px;margin:22px 0}.cover-preview{aspect-ratio:1;border:1px dashed #505865;border-radius:14px;background:#0c0f13;display:grid;place-items:center;overflow:hidden;color:#7d8794;text-align:center;letter-spacing:.2em;font-weight:800}.cover-preview img{width:100%;height:100%;object-fit:cover}.cover-preview small{font-size:8px}.cover-requirements h3{font-size:13px;margin:2px 0 10px}.cover-requirements ul{padding-left:17px;color:#aeb5bf;font-size:10px;line-height:2}.preview-release{display:grid;grid-template-columns:190px 1fr;gap:24px;padding:16px;border:1px solid var(--line);border-radius:16px;background:#0d1014}.preview-release>img,.preview-release>.cover-placeholder{width:100%;aspect-ratio:1;object-fit:cover;border-radius:11px}.preview-release h2{font-size:26px;margin:10px 0 5px}.preview-release p{color:#aeb5bf;font-size:12px}.preview-meta{display:grid;grid-template-columns:repeat(2,1fr);gap:11px;margin-top:20px}.preview-meta span{font-size:9px;color:#818995}.preview-meta b{display:block;color:#e3e6eb;font-size:10px;margin-top:4px}.alert{padding:13px 15px;border-radius:11px;font-size:11px;margin:15px 0}.alert.error{background:#351b20;border:1px solid #71343d;color:#ffb5ba}.alert.success{background:#172b20;border:1px solid #326847;color:#a5e6bd}.detail-layout{display:grid;grid-template-columns:220px 1fr;gap:18px;margin-bottom:20px}.detail-cover{width:100%;aspect-ratio:1;object-fit:cover;border-radius:15px;border:1px solid var(--line)}.detail-card h3{margin:0 0 12px;font-size:14px}.profile-row{display:flex;justify-content:space-between;gap:20px;padding:13px 0;border-bottom:1px solid var(--line);font-size:11px}.profile-row:last-child{border:0}.profile-row span{color:var(--muted)}.profile-row b{font-weight:600;text-align:right}.section-title{margin:30px 0 13px}.timeline{border-left:1px solid #3d4652;margin:15px 0 0 8px;padding-left:22px}.timeline-item{position:relative;padding:0 0 20px}.timeline-item>i{position:absolute;left:-27px;top:2px;width:9px;height:9px;border-radius:50%;background:#b7d86b;box-shadow:0 0 0 4px #b7d86b18}.timeline-item div{display:grid;gap:5px}.timeline-item b{font-size:11px}.timeline-item span,.timeline-item small{font-size:10px;color:var(--muted)}.filter-tabs{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:18px}.filter-tabs a{padding:9px 12px;border:1px solid var(--line);border-radius:30px;color:#9ba2ad;font-size:10px}.filter-tabs a.active{background:#e8eaee;color:#11151a;border-color:#e8eaee;font-weight:800}.admin-row{flex-wrap:wrap}.admin-actions{display:flex;gap:7px;align-items:center}.admin-actions form{margin:0}.reject-form{display:flex;gap:8px;width:100%;padding:12px;border-top:1px solid var(--line)}.reject-form input{flex:1}.toast{position:fixed;top:16px;right:20px;z-index:100;padding:13px 18px;border-radius:12px;background:#1c3426;border:1px solid #3b7652;color:#b5ebc8;box-shadow:0 15px 45px #0008;animation:toastIn .4s both;font-size:11px}.toast.error{background:#381d22;border-color:#783b44;color:#ffc1c5}.auth-wrap{min-height:100vh;display:grid;place-items:center;padding:24px}.auth-card{width:min(440px,100%);padding:38px;border:1px solid #343a44;border-radius:24px;background:linear-gradient(145deg,#191d23,#0d1014);box-shadow:0 30px 100px #0009;animation:rise .7s both}.auth-brand{padding:0;margin-bottom:40px}.auth-card h1{font-size:30px;letter-spacing:-.05em;margin:10px 0}.auth-card>.muted{font-size:11px;line-height:1.7;margin-bottom:24px}.auth-card .field{margin:17px 0}.auth-foot{font-size:10px;color:var(--muted);text-align:center;margin:22px 0 0}.auth-foot a{color:#f0f2f5;font-weight:700}.auth-card .alert{margin:15px 0}.nav-caption{white-space:nowrap}
@keyframes rise{from{opacity:0;transform:translateY(16px)}to{opacity:1;transform:translateY(0)}}@keyframes orbit{to{transform:rotate(360deg)}}@keyframes toastIn{from{opacity:0;transform:translateY(-12px)}to{opacity:1;transform:translateY(0)}}
@media(max-width:1050px){.sidebar{width:218px}.main{margin-left:218px;padding:25px 22px 55px}.wizard-step{flex-direction:column;text-align:center}.wizard-step span{font-size:8px}}
@media(max-width:700px){.sidebar{inset:auto 0 0;width:100%;height:66px;padding:6px 8px;border:0;border-top:1px solid var(--line);background:#090a0cf7}.sidebar .brand,.sidebar .nav-caption,.sidebar-bottom{display:none}.sidebar nav{height:100%;display:flex;flex-direction:row;justify-content:space-around;align-items:center}.sidebar nav a{flex:1;justify-content:center;padding:8px 3px;font-size:16px}.sidebar nav a span{font-size:8px}.main{margin:0;padding:19px 14px 95px}.topbar{margin-bottom:22px}.user-chip{font-size:9px}.page-head{align-items:flex-start;flex-direction:column}.page-head .btn{align-self:flex-start}.hero-panel{padding:27px 22px;min-height:250px}.hero-orbit{right:-170px}.stats-grid{gap:7px}.stat-card{padding:13px 11px}.stat-card span{font-size:8px}.stat-card b{font-size:21px}.wizard-steps{gap:4px}.wizard-step{padding:8px 3px;border-radius:9px;gap:5px}.wizard-step i{width:20px;height:20px}.wizard-step span{font-size:7px}.form-panel{padding:18px 14px}.form-grid{grid-template-columns:1fr;gap:14px}.wide{grid-column:auto}.form-actions,.wizard-bottom{flex-wrap:wrap}.form-actions>*{flex:1}.cover-requirements{grid-template-columns:105px 1fr;gap:14px}.preview-release{grid-template-columns:100px 1fr;gap:13px;padding:10px}.preview-release h2{font-size:18px}.preview-meta{grid-template-columns:1fr}.release-row{gap:9px;padding:10px}.release-row>img,.release-row>.cover-placeholder{width:48px;height:48px}.release-row-info b{font-size:11px}.status{font-size:7px;padding:6px 7px}.detail-layout{grid-template-columns:110px 1fr;gap:10px}.detail-card{padding:14px}.profile-row{font-size:9px;gap:8px}.admin-actions{width:100%;justify-content:flex-end}.auth-card{padding:28px 22px}.toast{left:12px;right:12px;top:10px;text-align:center}}
.user-row .avatar{width:42px;height:42px;flex-shrink:0}.user-row small{font-size:9px;color:#7f8792;font-weight:500}.user-actions{display:flex;align-items:center;gap:6px}.user-actions select{max-width:135px;border:1px solid #343a44;border-radius:9px;background:#0c0f13;color:#dce0e6;padding:9px 8px;font-size:9px}
@media(max-width:700px){.user-actions{width:100%;flex-wrap:wrap}.user-actions select{flex:1;max-width:none}}

/* PMD ORIGINAL APPROVED VISUAL BASELINE — neutral black / graphite, matching supplied index.html */
:root{--bg:#080808;--panel:#111111;--panel2:#171717;--line:rgba(255,255,255,.09);--text:#f5f5f5;--muted:#888888;--soft:#b6b6b6;--accent:#d7d7d7;--radius:20px}
body{background:radial-gradient(ellipse at 75% -15%,#262626 0,transparent 38%),var(--bg);color:var(--text)}
.sidebar{background:#090909ef;border-right-color:var(--line)}
.sidebar nav a{color:#888;background:transparent}
.sidebar nav a:hover,.sidebar nav a:focus,.sidebar nav a.active{background:#1a1a1a;color:#fff;border-color:#292929}
.sidebar-bottom b{color:#ddd}
.user-chip{background:#151515;border-color:var(--line)}
.avatar{background:linear-gradient(135deg,#777,#222)}
.btn.primary{background:#f2f2f2;color:#090909}
.btn.primary:hover{background:#fff;box-shadow:0 10px 30px #fff2}
.btn.outline,.btn.ghost{background:#151515;border-color:#333;color:#e4e4e4}
.btn.ghost{background:transparent}
.hero-panel{border-color:#333;background:linear-gradient(120deg,#1e1e1e,#101010 65%,#181818)}
.hero-panel h2 span{color:#929292}
.stat-card{background:linear-gradient(145deg,#151515,#101010)}
.stat-card:hover,.release-row:hover{border-color:#555}
.empty-state{border-color:#333;background:#101010}
.release-row{background:linear-gradient(110deg,#141414,#101010)}
.cover-placeholder{background:linear-gradient(145deg,#343434,#161616);color:#b5b5b5}
.form-panel,.detail-card{background:linear-gradient(145deg,#151515,#101010)}
.wizard-step{background:#101010;color:#777;border-color:var(--line)}
.wizard-step.current{color:#fff;border-color:#777;background:#202020;box-shadow:0 0 0 3px #ffffff08}
.wizard-step.current i{background:#e8e8e8;color:#101010;border-color:#e8e8e8}
.field input,.field textarea,.field select,.reject-form input,.user-actions select{background:#090909;border-color:#303030;color:#f5f5f5}
.field input:focus,.field textarea:focus,.field select:focus,.reject-form input:focus{border-color:#aaa;box-shadow:0 0 0 4px #ffffff10}
.info-box{background:#1a1a1a;border-color:#333;color:#aaa}
.track-item{background:#0d0d0d}
.cover-preview{background:#0c0c0c;border-color:#505050}
.preview-release{background:#0d0d0d}
.filter-tabs a{color:#999}
.filter-tabs a.active{background:#e8e8e8;color:#111;border-color:#e8e8e8}
.auth-card{background:linear-gradient(145deg,#191919,#0d0d0d);border-color:#343434}
.auth-foot a{color:#f0f0f0}

/* Consistent motion language across every page, tab, card and control */
html{scroll-behavior:smooth}
button,a,.btn,.sidebar nav a,.filter-tabs a,.wizard-step,.release-row,.stat-card,.form-panel,.detail-card,.hero-panel,.user-chip,.field input,.field textarea,.field select,.cover-preview,.track-item,.profile-row{transition:color .28s ease,background .28s ease,border-color .28s ease,box-shadow .32s ease,transform .32s cubic-bezier(.2,.75,.25,1),opacity .28s ease}
.page.active{animation:pageReveal .55s cubic-bezier(.2,.75,.25,1) both}
.page.active .page-head,.page.active .hero-panel,.page.active .form-panel,.page.active .detail-card,.page.active .release-row,.page.active .stat-card{animation:cardReveal .55s cubic-bezier(.2,.75,.25,1) both}
.page.active .stat-card:nth-child(2),.page.active .release-row:nth-child(2){animation-delay:.06s}
.page.active .stat-card:nth-child(3),.page.active .release-row:nth-child(3){animation-delay:.12s}
.sidebar nav a.active{box-shadow:inset 2px 0 #e5e5e5}
.wizard-step:hover:not(.disabled){transform:translateY(-2px);border-color:#777}
.filter-tabs a:hover{transform:translateY(-2px);border-color:#777;color:#fff}
.btn:active,button:active{transform:scale(.975)}
.field input:focus,.field textarea:focus,.field select:focus{transform:translateY(-1px)}
.cover-preview img{animation:coverAppear .55s ease both}
.toast{animation:toastIn .4s cubic-bezier(.2,.75,.25,1) both}
@keyframes pageReveal{from{opacity:0;transform:translateY(12px);filter:blur(3px)}to{opacity:1;transform:translateY(0);filter:blur(0)}}
@keyframes cardReveal{from{opacity:0;transform:translateY(14px)}to{opacity:1;transform:translateY(0)}}
@keyframes coverAppear{from{opacity:0;transform:scale(1.04)}to{opacity:1;transform:scale(1)}}
@media(prefers-reduced-motion:reduce){*,*::before,*::after{scroll-behavior:auto!important;animation-duration:.01ms!important;animation-iteration-count:1!important;transition-duration:.01ms!important}}


/* Release wizard refinements: keep the approved graphite PMD visual language */
.field-head{display:flex;align-items:center;justify-content:space-between;gap:12px;min-height:16px}
.field-head>span{color:#c5cad2}
.field-head small{font-size:9px;color:#858b95;font-weight:400;text-align:right}
.text-action{border:1px solid #414141;border-radius:9px;background:linear-gradient(145deg,#202020,#111);color:#ededed;padding:8px 11px;font-size:10px;font-weight:700;cursor:pointer;transition:.25s}
.text-action:hover{background:#292929;border-color:#777;transform:translateY(-1px);box-shadow:0 8px 20px #0006}
.artist-picker-list{display:grid;gap:9px}
.artist-pick-row{display:grid;grid-template-columns:minmax(0,1.3fr) minmax(0,.9fr) 30px;gap:9px;align-items:center;animation:cardReveal .28s ease both}
.artist-pick-row select,.multi-select{width:100%;min-width:0;border:1px solid #343434;border-radius:10px;background:rgba(18,18,18,.88);backdrop-filter:blur(14px);-webkit-backdrop-filter:blur(14px);color:#f3f3f3;padding:12px 13px;outline:0;transition:.25s}
.artist-pick-row select:focus,.multi-select:focus{border-color:#aaa;box-shadow:0 0 0 3px #fff1}
.artist-pick-row option,.multi-select option{background:#171717;color:#eee}
.artist-picker-list+.field-note,.field>small{line-height:1.5}
.track-empty-state{display:grid;justify-items:center;gap:15px;text-align:center;padding:36px 18px;margin:14px 0 22px;border:1px dashed #444;border-radius:16px;background:linear-gradient(145deg,#151515,#0d0d0d);animation:cardReveal .35s ease both}
.track-empty-state p{max-width:420px;margin:0;color:#a4a4a4;font-size:12px;line-height:1.7}
.track-counter{float:right;color:#888;font-size:10px;font-weight:500}
.track-limit-note{padding:15px;border:1px solid #444;border-radius:12px;color:#aaa;background:#141414;font-size:11px}
.is-hidden{display:none!important}
.file-picker{position:relative;display:flex;align-items:center;gap:12px;min-height:48px;padding:7px 10px;border:1px solid #343434;border-radius:11px;background:linear-gradient(145deg,#121212,#090909);overflow:hidden;transition:.25s}
.file-picker:hover{border-color:#777;box-shadow:0 8px 25px #0005}
.file-picker input[type=file]{position:absolute!important;inset:0;width:100%!important;height:100%;opacity:0;cursor:pointer;z-index:2;padding:0!important}
.file-picker-button{display:inline-flex;align-items:center;justify-content:center;padding:9px 13px;border:1px solid #555;border-radius:8px;background:#242424;color:#f3f3f3;font-size:10px;font-weight:800;white-space:nowrap;transition:.25s}
.file-picker:hover .file-picker-button{background:#303030;border-color:#888;transform:translateY(-1px)}
.file-picker-name{min-width:0;overflow:hidden;text-overflow:ellipsis;white-space:nowrap;color:#898989;font-size:10px}
.cover-preview{position:relative}
.cover-preview img{display:block}
.distribution-check{align-self:center;min-height:46px;padding:11px 13px;border:1px solid #303030;border-radius:11px;background:#101010;line-height:1.5}
.check-row input[type=checkbox]{appearance:none;-webkit-appearance:none;position:relative;flex:0 0 18px;width:18px;height:18px;margin:0;border:1px solid #666;border-radius:5px;background:#101010;cursor:pointer;transition:background .22s,border-color .22s,transform .22s,box-shadow .22s}
.check-row input[type=checkbox]:hover{border-color:#bbb;box-shadow:0 0 0 3px #fff1}
.check-row input[type=checkbox]:checked{background:#eee;border-color:#eee;transform:scale(1.04)}
.check-row input[type=checkbox]:checked:after{content:"";position:absolute;left:5px;top:1px;width:5px;height:10px;border:solid #111;border-width:0 2px 2px 0;transform:rotate(45deg);animation:checkPop .2s ease both}
@keyframes checkPop{from{opacity:0;transform:rotate(45deg) scale(.4)}to{opacity:1;transform:rotate(45deg) scale(1)}}
.field input[type=file]:not(.file-picker input){cursor:pointer}
.field select{appearance:none;-webkit-appearance:none;padding-right:38px;background-image:linear-gradient(45deg,transparent 50%,#aaa 50%),linear-gradient(135deg,#aaa 50%,transparent 50%);background-position:calc(100% - 17px) 50%,calc(100% - 12px) 50%;background-size:5px 5px,5px 5px;background-repeat:no-repeat}
.field select option{background:#171717;color:#eee}
.modal-backdrop{position:fixed;inset:0;z-index:1000;display:grid;place-items:center;padding:20px;background:rgba(0,0,0,.72);backdrop-filter:blur(9px);-webkit-backdrop-filter:blur(9px);opacity:0;visibility:hidden;transition:opacity .25s,visibility .25s}
.modal-backdrop.open{opacity:1;visibility:visible}
.site-modal{position:relative;width:min(470px,100%);padding:29px;border:1px solid #444;border-radius:20px;background:linear-gradient(145deg,#1b1b1b,#0b0b0b);box-shadow:0 28px 90px #000b;transform:translateY(15px) scale(.98);opacity:0;transition:transform .3s cubic-bezier(.2,.75,.25,1),opacity .3s}
.modal-backdrop.open .site-modal{transform:translateY(0) scale(1);opacity:1}
.site-modal h2{margin:10px 0;font-size:23px;letter-spacing:-.04em}
.site-modal p{margin:0 0 20px;color:#999;font-size:11px;line-height:1.7}
.site-modal .field{margin:18px 0}
.modal-close{position:absolute;right:16px;top:14px;width:30px;height:30px;border:1px solid #444;border-radius:50%;background:#171717;color:#ccc;font-size:19px;cursor:pointer;transition:.2s}
.modal-close:hover{background:#292929;color:white;transform:rotate(90deg)}
.modal-submit{width:100%;margin-top:5px}
.saved-chip-list{display:flex;flex-wrap:wrap;gap:7px;margin-top:17px;padding-top:15px;border-top:1px solid #303030}
.saved-chip-list span{padding:7px 10px;border:1px solid #3b3b3b;border-radius:20px;background:#161616;color:#bbb;font-size:9px}
.modal-actions{display:flex;justify-content:flex-end;gap:9px;margin-top:24px}
.toast{max-width:min(460px,calc(100vw - 30px))}
@media(max-width:700px){.artist-pick-row{grid-template-columns:1fr 1fr 28px}.site-modal{padding:24px 19px}.field-head{align-items:flex-start}.field-head small{max-width:55%}.track-empty-state{padding:27px 14px}.distribution-check{min-height:0}.file-picker{gap:8px}.file-picker-button{padding:9px 10px}}

/* Glass dropdowns shared across every portal tab */
.glass-select{position:relative;width:100%;min-width:0}
.glass-select>select{position:absolute!important;width:1px!important;height:1px!important;opacity:0!important;pointer-events:none!important;left:0;bottom:0}
.glass-select-trigger{width:100%;display:flex;align-items:center;justify-content:space-between;gap:12px;text-align:left;padding:13px 42px 13px 14px;border:1px solid #ffffff22;border-radius:11px;background:rgba(20,24,31,.58);color:#edf0f4;backdrop-filter:blur(18px);-webkit-backdrop-filter:blur(18px);position:relative;transition:.2s}
.glass-select-trigger:after{content:"";position:absolute;right:16px;width:7px;height:7px;border-right:1.5px solid #aeb7c4;border-bottom:1.5px solid #aeb7c4;transform:rotate(45deg) translateY(-2px)}
.glass-select-trigger:hover,.glass-select-trigger[aria-expanded=true]{border-color:#aeb8c888;background:rgba(39,45,56,.76);box-shadow:0 0 0 3px #ffffff0b}
.glass-select-trigger.placeholder{color:#8993a1}
.glass-select-menu{display:none;position:absolute;z-index:60;top:calc(100% + 8px);left:0;right:0;max-height:260px;overflow:auto;padding:6px;border:1px solid #ffffff24;border-radius:13px;background:rgba(15,18,24,.78);backdrop-filter:blur(24px) saturate(145%);-webkit-backdrop-filter:blur(24px) saturate(145%);box-shadow:0 18px 50px #0009}
.glass-select-menu.open{display:grid;gap:3px;animation:glassDrop .16s ease-out}
.glass-select-option{width:100%;border:0;border-radius:8px;background:transparent;color:#dce1e9;text-align:left;padding:10px 11px;font-size:11px;cursor:pointer}
.glass-select-option:hover{background:#ffffff16;color:#fff}
@keyframes glassDrop{from{opacity:0;transform:translateY(-5px)}to{opacity:1;transform:translateY(0)}}
.track-item .edit-track{flex-shrink:0}
.saved-chip-list>span{display:inline-flex;align-items:center;gap:7px}
.chip-delete{display:inline-flex;margin:0}
.chip-delete button{border:0;background:transparent;color:#f19aa0;font-size:16px;line-height:1;padding:0 2px}
@media(max-width:650px){.glass-select-menu{max-height:210px}.track-item{flex-wrap:wrap}.track-item .edit-track{margin-left:auto}}

/* Global glass dropdown layering: menus live in body, never clipped by cards or wizard panels. */
.glass-select{position:relative;isolation:auto;z-index:auto;width:100%;min-width:0}
.glass-select:has(.glass-select-trigger[aria-expanded="true"]){z-index:2147482000}
.glass-select>select{position:absolute!important;width:1px!important;height:1px!important;opacity:0!important;pointer-events:none!important;left:0;bottom:0}
.glass-select-menu{display:none;position:fixed!important;z-index:2147483000!important;max-height:260px;overflow:auto;padding:6px;border:1px solid rgba(255,255,255,.22);border-radius:13px;background:rgba(15,18,24,.75)!important;backdrop-filter:blur(22px) saturate(145%);-webkit-backdrop-filter:blur(22px) saturate(145%);box-shadow:0 18px 50px #000b}
.glass-select-menu.open{display:grid;gap:3px;animation:glassDrop .16s ease-out}
.glass-select-option.selected{background:rgba(255,255,255,.13);color:#fff}
.artist-pick-row{position:relative;z-index:auto}
.modal-backdrop{z-index:2147483500}

/* Cover validation modal: same dark glass language as the release wizard. */
.error-modal{position:relative;overflow:hidden;text-align:center;border-color:rgba(255,110,120,.35);box-shadow:0 30px 100px rgba(0,0,0,.7),0 0 55px rgba(220,65,80,.12)}
.error-modal:before{content:"";position:absolute;inset:-45%;pointer-events:none;background:radial-gradient(circle at 50% 35%,rgba(220,65,80,.16),transparent 48%);animation:errorGlow 3.8s ease-in-out infinite alternate}
.error-modal>*{position:relative}
.error-modal-icon{width:48px;height:48px;margin:0 auto 15px;border-radius:50%;display:grid;place-items:center;background:rgba(225,67,81,.14);border:1px solid rgba(255,120,130,.45);color:#ff9da5;font-size:25px;font-weight:800;box-shadow:0 0 28px rgba(225,67,81,.18);animation:errorPulse 1.8s ease-in-out infinite}
.error-modal p{color:#c4c9d1;line-height:1.65}
@keyframes errorGlow{from{opacity:.45;transform:scale(.96)}to{opacity:1;transform:scale(1.04)}}
@keyframes errorPulse{0%,100%{box-shadow:0 0 0 0 rgba(225,67,81,.18)}50%{box-shadow:0 0 0 10px rgba(225,67,81,0)}}

/* Polished songwriter chips and animated track participant rows */
.writer-chip-picker{display:flex;flex-wrap:wrap;gap:9px;padding:13px;border:1px solid #343a44;border-radius:13px;background:linear-gradient(145deg,rgba(24,27,32,.88),rgba(12,15,19,.88));backdrop-filter:blur(16px);-webkit-backdrop-filter:blur(16px);min-height:54px}
.writer-choice{position:relative;display:inline-flex;align-items:center;cursor:pointer;animation:cardReveal .28s ease both}
.writer-choice input{position:absolute;opacity:0;pointer-events:none}
.writer-choice span{display:inline-flex;align-items:center;gap:8px;padding:9px 13px;border:1px solid #414852;border-radius:999px;background:rgba(255,255,255,.035);color:#bfc5ce;font-size:10px;transition:all .22s ease}
.writer-choice span:before{content:'+';font-size:13px;color:#858e9a}
.writer-choice input:checked+span{background:rgba(215,222,231,.13);border-color:#aab3bf;color:#fff;box-shadow:0 0 0 3px rgba(255,255,255,.035)}
.writer-choice input:checked+span:before{content:'✓';color:#c8e5b0}
.artist-picker-list{display:grid;gap:9px}
.artist-pick-row{display:grid;grid-template-columns:minmax(0,1.5fr) minmax(0,1fr) 29px;gap:9px;align-items:center}
.artist-pick-row select{min-width:0;width:100%;border:1px solid #343a44;border-radius:10px;background:rgba(18,18,18,.88);color:#f3f3f3;padding:12px 13px}
.artist-pick-row .remove-artist{grid-column:auto}
.row-enter{animation:cardReveal .28s ease both}
.error-modal{animation:errorModalIn .42s cubic-bezier(.2,.75,.25,1) both}
@keyframes errorModalIn{from{opacity:0;transform:translateY(18px) scale(.96);filter:blur(5px)}to{opacity:1;transform:translateY(0) scale(1);filter:blur(0)}}
@media(max-width:600px){.artist-pick-row{grid-template-columns:1fr 1fr 29px}.writer-chip-picker{gap:7px}}
/* V3.2 track participant and metadata refinements */
.participant-actions{display:flex;align-items:center;gap:16px;flex-wrap:wrap}
.track-item-info .track-extra{display:block;color:#9aa2ad;font-size:9px;line-height:1.6;margin-top:2px;overflow-wrap:anywhere}
.track-item-info small{font-size:9px;color:#9aa2ad;line-height:1.6}
@media(max-width:600px){.participant-actions{gap:10px}.track-item{align-items:flex-start;flex-wrap:wrap}.track-item-info{flex-basis:calc(100% - 45px)}}

/* PMD listening analytics — same graphite surfaces, restrained lime accent. */
.stats-source-form{flex:0 0 100%;grid-column:1/-1;width:100%;padding:15px 17px;margin:0 0 4px 74px;max-width:calc(100% - 74px);border:1px solid var(--line);border-radius:14px;background:rgba(12,14,18,.72);display:grid;gap:9px;animation:statsReveal .45s ease both}.stats-source-fields{display:grid;grid-template-columns:minmax(220px,1.5fr) minmax(150px,.7fr) auto;align-items:end;gap:10px}.stats-source-fields label,.stats-toolbar label{display:grid;gap:7px;color:var(--muted);font-size:10px;font-weight:700}.stats-source-fields input,.stats-toolbar select{width:100%;min-width:0;padding:10px 12px;border:1px solid #303640;border-radius:10px;background:#111419;color:var(--text);outline:none;transition:border-color .25s,box-shadow .25s}.stats-source-fields input:focus,.stats-toolbar select:focus{border-color:#899b61;box-shadow:0 0 0 3px #b7d86b18}.stats-source-note{color:#777f89;font-size:9px}.stats-toolbar{display:flex;align-items:end;justify-content:space-between;gap:16px;margin:0 0 18px}.stats-toolbar label{width:min(460px,100%)}.stats-toolbar select{appearance:auto;font-size:12px}.stats-live-dot{display:inline-flex;align-items:center;gap:8px;color:#a9c978;font-size:10px}.stats-live-dot:before{content:"";width:7px;height:7px;border-radius:50%;background:#b7d86b;box-shadow:0 0 12px #b7d86b88;animation:statsPulse 2s infinite}.stats-kpis{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:13px;margin-bottom:18px}.stats-kpis .stat-card{min-height:126px;display:flex;flex-direction:column;align-items:flex-start;gap:8px}.stats-kpis .stat-card b{font-size:clamp(26px,3vw,36px);letter-spacing:-.06em;font-variant-numeric:tabular-nums}.stats-kpis .stat-card small{color:var(--muted);font-size:9px}.chart-panel{padding:25px 26px 20px;border:1px solid #2b3038;border-radius:20px;background:linear-gradient(145deg,#171a20,#101216 75%);box-shadow:0 20px 55px #0003;animation:statsReveal .65s .08s both}.chart-head{display:flex;justify-content:space-between;align-items:flex-start;gap:15px;margin-bottom:22px}.chart-head h2{font-size:20px;letter-spacing:-.04em;margin:8px 0 5px}.chart-head p{margin:0;color:var(--muted);font-size:10px}.chart-period{padding:7px 10px;border:1px solid var(--line);border-radius:8px;color:#aeb4bd;font-size:9px;letter-spacing:.12em}.chart-plot{display:grid;grid-template-columns:48px minmax(0,1fr);gap:10px}.chart-y-labels{display:flex;flex-direction:column;justify-content:space-between;padding:3px 0 23px;color:#6f7782;font-size:9px;font-variant-numeric:tabular-nums}.chart-canvas-wrap{min-width:0;position:relative;background:repeating-linear-gradient(to bottom,transparent 0,transparent 63px,#ffffff0b 64px,#ffffff0b 65px)}.listens-chart{display:block;width:100%;height:260px;overflow:visible}.chart-area{fill:url(#chartFill);opacity:0;animation:chartAreaIn 1s .3s ease forwards}.chart-line{fill:none;stroke:#c3e27a;stroke-width:3;stroke-linecap:round;stroke-linejoin:round;stroke-dasharray:1400;stroke-dashoffset:1400;animation:chartDraw 1.8s .15s cubic-bezier(.2,.7,.2,1) forwards;filter:drop-shadow(0 0 6px #c3e27a33)}.chart-point{fill:#d9f39a;stroke:#171a20;stroke-width:2;opacity:0;animation:pointIn .35s ease forwards;animation-delay:calc(.25s + var(--i,0)*.025s)}.chart-x-labels{display:flex;justify-content:space-between;padding-top:9px;color:#737b86;font-size:9px}.chart-empty{min-height:210px;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;border:1px dashed #343a43;border-radius:14px;background:#0c0e1266}.chart-empty>span,.stats-empty .empty-icon{font-size:34px;color:#b7d86b}.chart-empty b{margin:10px 0 5px;font-size:13px}.chart-empty p,.stats-empty p{max-width:430px;color:var(--muted);font-size:11px;line-height:1.7}.stats-footnote{margin-top:14px;padding:12px 15px;border-left:2px solid #657849;background:#151912;color:#939b8a;font-size:10px;line-height:1.7;border-radius:0 9px 9px 0}.stats-empty{padding:55px 20px}.stats-empty .btn{margin-top:10px}@keyframes statsReveal{from{opacity:0;transform:translateY(12px)}to{opacity:1;transform:translateY(0)}}@keyframes statsPulse{50%{opacity:.45;box-shadow:0 0 3px #b7d86b33}}@keyframes chartDraw{to{stroke-dashoffset:0}}@keyframes chartAreaIn{to{opacity:1}}@keyframes pointIn{to{opacity:1;transform:scale(1)}}
@media(max-width:900px){.stats-source-form{margin-left:0;max-width:100%}.stats-source-fields{grid-template-columns:1fr 1fr}.stats-source-fields button{grid-column:1/-1}.stats-kpis{grid-template-columns:1fr 1fr}.stats-kpis .stat-card:last-child{grid-column:1/-1}}
@media(max-width:600px){.stats-toolbar{align-items:stretch;flex-direction:column}.stats-kpis{grid-template-columns:1fr}.stats-kpis .stat-card:last-child{grid-column:auto}.stats-source-fields{grid-template-columns:1fr}.stats-source-fields button{grid-column:auto}.chart-panel{padding:19px 14px}.chart-head h2{font-size:17px}.listens-chart{height:205px}.chart-plot{grid-template-columns:36px minmax(0,1fr)}}
@media(prefers-reduced-motion:reduce){.stats-source-form,.chart-panel,.chart-area,.chart-line,.chart-point,.stats-live-dot:before{animation:none!important}.chart-line{stroke-dashoffset:0}.chart-area,.chart-point{opacity:1}}
/* VK auto-statistics source form */
.stats-source-fields-auto{grid-template-columns:minmax(240px,1fr) auto;max-width:100%}
.stats-source-fields-auto button{min-height:39px}
.stats-source-note b{color:#dce9bd;font-variant-numeric:tabular-nums}
.stats-warning{border-left-color:#e99a35;background:#1b1711;color:#c4aa86}
@media(max-width:900px){.stats-source-fields-auto{grid-template-columns:1fr}.stats-source-fields-auto button{grid-column:auto}}

/* =========================================
   PMD — L-SHAPED FLOATING GLASS HEADER
========================================= */

/* Рабочая область */
.main {
    position: relative;
    min-width: 0;
    padding-top: 100px;
}

/* Стеклянная верхняя полоса */
.main > .topbar {
    position: fixed !important;

    top: 0;
    left: 252px;
    right: 0;

    width: auto;
    max-width: none;
    height: 76px;
    min-height: 76px;

    z-index: 9999;

    display: flex;
    align-items: center;
    justify-content: space-between;

    padding: 0 clamp(22px, 4vw, 62px);

    /* Никакой отдельной карточки */
    background: rgba(8, 8, 8, 0.48);
    border: 0;
    border-bottom: 1px solid rgba(255,255,255,0.045);
    border-radius: 0;

    /* Эффект стекла */
    backdrop-filter: blur(28px) saturate(120%);
    -webkit-backdrop-filter: blur(28px) saturate(120%);

    box-shadow: none;

    transform: none;
}

/* Лёгкое затемнение сверху */
.main > .topbar::before {
    content: "";
    position: absolute;
    inset: 0;
    pointer-events: none;
    background: linear-gradient(
        180deg,
        rgba(0,0,0,0.24),
        rgba(0,0,0,0.04)
    );
    z-index: -1;
}

/* Левая часть */
.main > .topbar .crumb {
    white-space: nowrap;
    flex-shrink: 0;
    position: relative;
    z-index: 1;
}

/* Правая часть */
.main > .topbar .user-chip {
    position: relative;
    z-index: 1;
    display: flex;
    align-items: center;
    justify-content: flex-end;
    white-space: nowrap;
    flex-shrink: 0;

    /* Убираем собственную заливку */
    background: transparent;
    border-color: transparent;
}

/* Боковое меню остаётся поверх фона */
.sidebar {
    z-index: 10000;
}

/* Уведомления поверх шапки */
.notifications-widget {
    z-index: 10001;
}

/* Планшеты */
@media (min-width: 701px) and (max-width: 1050px) {
    .main > .topbar {
        left: 218px;
        padding-left: 22px;
        padding-right: 22px;
    }

    .main {
        padding-top: 94px;
    }
}

/* Телефоны: меню снизу, шапка на всю ширину */
@media (max-width: 700px) {
    .main {
        margin: 0;
        padding-top: 78px;
    }

    .main > .topbar {
        left: 0;
        right: 0;
        top: 0;
        height: 62px;
        min-height: 62px;

        padding: 0 15px;

        background: rgba(8,8,8,0.58);
        backdrop-filter: blur(24px);
        -webkit-backdrop-filter: blur(24px);
    }

    .main > .topbar .crumb {
        font-size: 9px;
    }

    .main > .topbar .user-chip {
        font-size: 10px;
        gap: 6px;
    }

    .main > .topbar .user-chip .muted {
        display: none;
    }
}

/* Уважение настройки уменьшения анимации */
@media (prefers-reduced-motion: reduce) {
    .main > .topbar {
        transition: none !important;
    }
}

/* =========================================
   PMD GLOBAL PREMIUM SELECTS
========================================= */

:root {
    --pmd-select-bg: #11160f;
    --pmd-select-bg-hover: #192117;
    --pmd-select-border: rgba(195,226,122,.19);
    --pmd-select-accent: #c8f477;
    --pmd-select-text: #edf4e6;
    --pmd-select-muted: #929b89;
}

/* Основной select */

select,
select:not([multiple]) {
    appearance: none;
    -webkit-appearance: none;
    -moz-appearance: none;

    min-height: 46px;
    padding: 0 46px 0 16px;

    color: var(--pmd-select-text);
    background-color: var(--pmd-select-bg);

    background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='18' height='18' viewBox='0 0 24 24' fill='none' stroke='%23c8f477' stroke-width='2' stroke-linecap='round' stroke-linejoin='round'%3E%3Cpath d='m6 9 6 6 6-6'/%3E%3C/svg%3E");
    background-repeat: no-repeat;
    background-position: right 15px center;
    background-size: 17px;

    border: 1px solid var(--pmd-select-border);
    border-radius: 12px;

    font: inherit;
    font-size: 13px;
    font-weight: 600;

    outline: none;
    cursor: pointer;

    transition:
        background-color .25s ease,
        border-color .25s ease,
        box-shadow .25s ease,
        transform .25s ease;
}

select:hover {
    background-color: var(--pmd-select-bg-hover);
    border-color: rgba(195,226,122,.42);
}

select:focus {
    border-color: var(--pmd-select-accent);
    box-shadow:
        0 0 0 3px rgba(195,226,122,.09),
        0 0 24px rgba(195,226,122,.08);
}

select:disabled {
    opacity: .4;
    cursor: not-allowed;
    filter: grayscale(1);
}

/* Варианты внутри списка */

select option {
    color: var(--pmd-select-text);
    background: #11160f;
    padding: 12px;
    font-weight: 500;
}

select option:checked {
    color: #c8f477;
    background: #26351c;
    font-weight: 700;
}

select optgroup {
    color: #c8f477;
    background: #11160f;
    font-weight: 700;
}

/* Select с несколькими вариантами */

select[multiple] {
    appearance: auto;
    -webkit-appearance: auto;
    background-image: none;
    padding: 10px;
    min-height: 110px;
}

select[multiple] option {
    padding: 9px 10px;
    border-radius: 6px;
}

/* Обёртки select */

select,
.form-control select,
.form-group select,
.field select,
.input-group select {
    max-width: 100%;
}

/* Светящиеся поля выбора */

.stats-toolbar select {
    border-color: rgba(195,226,122,.22);
    background-color: rgba(7,10,8,.92);
}

/* Убираем стандартное оформление старых браузеров */

select::-ms-expand {
    display: none;
}

/* Адаптация */

@media(max-width:600px) {
    select,
    select:not([multiple]) {
        min-height: 44px;
        font-size: 12px;
        border-radius: 11px;
    }
}

@media(prefers-reduced-motion:reduce) {
    select {
        transition: none !important;
    }
}

/* =====================================================
   PMD — FINAL GLASS SELECT STYLE
   Перекрывает старое оформление без удаления CSS
===================================================== */

.glass-select {
    position: relative !important;
    isolation: auto !important;
    z-index: auto !important;
    width: 100% !important;
    min-width: 0 !important;
}

.glass-select:has(.glass-select-trigger[aria-expanded="true"]) {
    z-index: 2147482000 !important;
}

.glass-select > select {
    position: absolute !important;
    width: 1px !important;
    height: 1px !important;
    opacity: 0 !important;
    pointer-events: none !important;
    left: 0 !important;
    bottom: 0 !important;
}

/* Кнопка */
.glass-select-trigger {
    width: 100% !important;
    min-height: 50px !important;
    display: flex !important;
    align-items: center !important;
    justify-content: space-between !important;
    gap: 14px !important;
    padding: 13px 46px 13px 16px !important;

    position: relative !important;
    overflow: hidden !important;

    border: 1px solid rgba(255,255,255,.10) !important;
    border-radius: 13px !important;

    background: linear-gradient(
        135deg,
        rgba(35,39,43,.94),
        rgba(15,18,20,.96)
    ) !important;

    color: #f3f5f4 !important;
    font: inherit !important;
    font-size: 14px !important;
    font-weight: 500 !important;
    text-align: left !important;

    backdrop-filter: blur(22px) !important;
    -webkit-backdrop-filter: blur(22px) !important;

    cursor: pointer !important;

    box-shadow: inset 0 1px 0 rgba(255,255,255,.035) !important;

    transition:
        border-color .25s ease,
        background .25s ease,
        box-shadow .25s ease,
        transform .25s ease !important;
}

/* Стрелка */
.glass-select-trigger::after {
    content: "" !important;
    position: absolute !important;
    right: 19px !important;
    top: 50% !important;

    width: 8px !important;
    height: 8px !important;

    border: 0 !important;
    border-right: 1.5px solid #a9b4ad !important;
    border-bottom: 1.5px solid #a9b4ad !important;

    transform: translateY(-70%) rotate(45deg) !important;

    transition:
        transform .25s ease,
        border-color .25s ease !important;
}

.glass-select-trigger:hover {
    border-color: rgba(190,255,70,.38) !important;
    background: rgba(35,42,31,.85) !important;
    box-shadow: 0 0 20px rgba(180,255,50,.08) !important;
}

.glass-select-trigger[aria-expanded="true"] {
    border-color: rgba(190,255,70,.65) !important;

    background: linear-gradient(
        135deg,
        rgba(35,48,27,.94),
        rgba(15,22,15,.98)
    ) !important;

    box-shadow:
        0 0 0 3px rgba(190,255,70,.07),
        0 0 24px rgba(190,255,70,.12) !important;
}

.glass-select-trigger[aria-expanded="true"]::after {
    border-color: #c5ff63 !important;
    transform: translateY(-25%) rotate(225deg) !important;
}

.glass-select-trigger.placeholder {
    color: #818b85 !important;
}

/* Выпадающее меню */
.glass-select-menu {
    display: none !important;

    position: fixed !important;
    z-index: 2147483000 !important;

    max-height: 260px !important;
    overflow-y: auto !important;
    overscroll-behavior: contain !important;

    padding: 7px !important;

    border: 1px solid rgba(190,255,70,.20) !important;
    border-radius: 15px !important;

    background: linear-gradient(
        145deg,
        rgba(25,29,27,.98),
        rgba(10,13,12,.99)
    ) !important;

    backdrop-filter: blur(28px) !important;
    -webkit-backdrop-filter: blur(28px) !important;

    box-shadow:
        0 18px 55px rgba(0,0,0,.65),
        0 0 25px rgba(190,255,70,.07),
        inset 0 1px 0 rgba(255,255,255,.05) !important;

    scrollbar-width: thin !important;
    scrollbar-color: rgba(190,255,70,.35) transparent !important;
}

.glass-select-menu.open {
    display: grid !important;
    gap: 4px !important;
    animation: pmdGlassDropdownOpen .2s cubic-bezier(.2,.8,.2,1) !important;
}

@keyframes pmdGlassDropdownOpen {
    from {
        opacity: 0;
        transform: translateY(-7px) scale(.985);
    }
    to {
        opacity: 1;
        transform: translateY(0) scale(1);
    }
}

/* Пункты */
.glass-select-option {
    width: 100% !important;
    min-height: 40px !important;

    display: flex !important;
    align-items: center !important;

    padding: 10px 12px !important;

    border: 1px solid transparent !important;
    border-radius: 9px !important;

    background: transparent !important;

    color: #cbd2ce !important;
    font: inherit !important;
    font-size: 13px !important;
    font-weight: 450 !important;
    text-align: left !important;

    cursor: pointer !important;

    transition:
        color .18s ease,
        background .18s ease,
        border-color .18s ease,
        padding-left .18s ease !important;
}

.glass-select-option:hover {
    padding-left: 16px !important;
    color: #d8ff91 !important;
    background: rgba(190,255,70,.09) !important;
    border-color: rgba(190,255,70,.12) !important;
}

.glass-select-option.selected {
    color: #d5ff8a !important;

    background: linear-gradient(
        90deg,
        rgba(190,255,70,.15),
        rgba(190,255,70,.045)
    ) !important;

    border-color: rgba(190,255,70,.18) !important;
    font-weight: 600 !important;
}

/* Скроллбар */
.glass-select-menu::-webkit-scrollbar {
    width: 5px !important;
}

.glass-select-menu::-webkit-scrollbar-track {
    background: transparent !important;
}

.glass-select-menu::-webkit-scrollbar-thumb {
    background: rgba(190,255,70,.3) !important;
    border-radius: 10px !important;
}

.glass-select-menu::-webkit-scrollbar-thumb:hover {
    background: rgba(190,255,70,.6) !important;
}

/* Фокус */
.glass-select-trigger:focus-visible,
.glass-select-option:focus-visible {
    outline: 2px solid rgba(190,255,70,.75) !important;
    outline-offset: 3px !important;
}

/* Мобильные устройства */
@media (max-width: 600px) {
    .glass-select-trigger {
        min-height: 48px !important;
        font-size: 13px !important;
    }

    .glass-select-menu {
        max-height: 230px !important;
    }

    .glass-select-option {
        min-height: 42px !important;
    }
}

/* Отключение анимации по настройкам устройства */
@media (prefers-reduced-motion: reduce) {
    .glass-select-trigger,
    .glass-select-option,
    .glass-select-menu {
        animation: none !important;
        transition: none !important;
    }
}

/* PMD — DARK DEFAULT DROPDOWN */

.glass-select-trigger,
.glass-select-trigger:hover {
    background: linear-gradient(
        135deg,
        rgba(13,16,15,.98),
        rgba(8,10,9,.99)
    ) !important;

    border-color: rgba(255,255,255,.09) !important;

    color: #f2f5f1 !important;

    box-shadow: inset 0 1px 0 rgba(255,255,255,.025) !important;
}

/* Лаймовый акцент только при наведении */
.glass-select-trigger:hover {
    border-color: rgba(190,255,70,.38) !important;
    box-shadow:
        0 0 18px rgba(190,255,70,.07),
        inset 0 1px 0 rgba(255,255,255,.025) !important;
}

/* Открытый список */
.glass-select-trigger[aria-expanded="true"] {
    background: linear-gradient(
        135deg,
        rgba(17,24,13,.99),
        rgba(8,12,8,.99)
    ) !important;

    border-color: rgba(190,255,70,.55) !important;

    box-shadow:
        0 0 0 3px rgba(190,255,70,.055),
        0 0 20px rgba(190,255,70,.09) !important;
}

/* Текст */
.glass-select-trigger.placeholder {
    color: #858d87 !important;
}

/* Само выпадающее меню */
.glass-select-menu {
    background: linear-gradient(
        145deg,
        rgba(12,15,14,.99),
        rgba(6,8,7,.99)
    ) !important;

    border-color: rgba(255,255,255,.11) !important;
}
/* =========================================
   PMD — FULL WIDTH WORKSPACE FIX
========================================= */

.main {
    width: auto !important;
    max-width: none !important;
    min-width: 0 !important;
}

/* На широких экранах используем всю ширину */
.pmd-releases {
    width: 100% !important;
    max-width: none !important;
    min-width: 0 !important;
}

/* Сетка релизов */
.pmd-release-list {
    width: 100% !important;
    max-width: none !important;
    grid-template-columns: repeat(6, minmax(0, 1fr));
}

/* Планшеты и небольшие ноутбуки */
@media (max-width: 1399px) {
    .pmd-release-list {
        grid-template-columns: repeat(5, minmax(0, 1fr));
    }
}

@media (max-width: 1150px) {
    .pmd-release-list {
        grid-template-columns: repeat(4, minmax(0, 1fr));
    }
}

@media (max-width: 900px) {
    .pmd-release-list {
        grid-template-columns: repeat(3, minmax(0, 1fr));
    }
}

@media (max-width: 650px) {
    .pmd-release-list {
        grid-template-columns: repeat(2, minmax(0, 1fr));
    }
}

/* Не даём карточкам и содержимому раздвигать страницу */
.pmd-release-card {
    min-width: 0;
}

.pmd-release-info,
.pmd-release-card-bottom {
    min-width: 0;
}

/* На очень узких телефонах */
@media (max-width: 350px) {
    .pmd-release-list {
        gap: 8px;
    }
}
/* =========================================================
   PMD — MOBILE INTERFACE
   Финальный слой адаптации для телефонов и планшетов
========================================================= */

/* Базовая защита от горизонтальной прокрутки */
html {
    width: 100%;
    min-height: 100%;
    overflow-x: clip;
    -webkit-text-size-adjust: 100%;
}

body {
    width: 100%;
    min-width: 320px;
    min-height: 100vh;
    overflow-x: clip;
}

*,
*::before,
*::after {
    box-sizing: border-box;
}

img,
video,
iframe,
svg {
    max-width: 100%;
}

input,
select,
textarea,
button {
    max-width: 100%;
    font: inherit;
}

.main,
.shell,
.pmd-releases,
.pmd-release-list,
.pmd-release-card,
.pmd-release-info {
    min-width: 0;
}

/* Планшеты */
@media (max-width: 900px) {
    .main {
        width: 100% !important;
        max-width: 100% !important;
        min-width: 0 !important;
    }

    .pmd-release-list {
        grid-template-columns: repeat(3, minmax(0, 1fr)) !important;
    }

    .grid,
    .stats-grid,
    .statistics-grid {
        grid-template-columns: repeat(2, minmax(0, 1fr));
    }

    table {
        min-width: 600px;
    }

    .table-wrapper,
    .table-responsive,
    .table-scroll {
        width: 100%;
        max-width: 100%;
        overflow-x: auto;
        -webkit-overflow-scrolling: touch;
    }
}

/* Телефоны */
@media (max-width: 650px) {
    html,
    body {
        overflow-x: clip !important;
    }

    body {
        padding-bottom: env(safe-area-inset-bottom);
    }

    /* Основная рабочая область */
    .shell {
        display: block !important;
        width: 100% !important;
        min-height: 100vh;
    }

    .main {
        width: 100% !important;
        max-width: none !important;
        min-width: 0 !important;
        margin: 0 !important;
        padding: 82px 14px calc(100px + env(safe-area-inset-bottom)) !important;
    }

    /* Верхняя панель */
    .topbar {
        position: fixed !important;
        top: 0 !important;
        left: 0 !important;
        right: 0 !important;
        z-index: 1000 !important;

        width: 100% !important;
        min-width: 0 !important;
        margin: 0 !important;

        padding:
            max(10px, env(safe-area-inset-top))
            14px
            10px !important;

        border-radius: 0 0 16px 16px !important;

        background: rgba(9, 11, 10, .92) !important;
        backdrop-filter: blur(22px);
        -webkit-backdrop-filter: blur(22px);
    }

    .topbar > * {
        min-width: 0;
    }

    .user-chip {
        max-width: 100%;
        min-width: 0;
    }

    .user-chip span {
        overflow: hidden;
        text-overflow: ellipsis;
        white-space: nowrap;
    }

    /* Нижняя навигация */
    .sidebar {
        position: fixed !important;
        top: auto !important;
        right: 0 !important;
        bottom: 0 !important;
        left: 0 !important;

        z-index: 1100 !important;

        display: block !important;
        width: 100% !important;
        height: auto !important;
        min-height: 0 !important;
        max-height: none !important;

        margin: 0 !important;
        padding: 8px 0 calc(8px + env(safe-area-inset-bottom)) !important;

        overflow: hidden !important;

        border: 0 !important;
        border-top: 1px solid rgba(255,255,255,.09) !important;
        border-radius: 17px 17px 0 0 !important;

        background: rgba(10, 12, 11, .96) !important;
        backdrop-filter: blur(26px);
        -webkit-backdrop-filter: blur(26px);

        box-shadow: 0 -10px 35px rgba(0,0,0,.35) !important;
    }

    .sidebar .brand,
    .sidebar .nav-caption,
    .sidebar .sidebar-bottom {
        display: none !important;
    }

    .sidebar nav,
    .sidebar .pmd-nav {
        display: flex !important;
        flex-direction: row !important;
        align-items: stretch !important;
        justify-content: flex-start !important;

        width: 100% !important;
        max-width: 100% !important;
        min-width: 0 !important;

        gap: 5px !important;
        margin: 0 !important;
        padding: 0 9px !important;

        overflow-x: auto !important;
        overflow-y: hidden !important;

        scrollbar-width: none !important;
        -webkit-overflow-scrolling: touch;
    }

    .sidebar nav::-webkit-scrollbar,
    .sidebar .pmd-nav::-webkit-scrollbar {
        display: none !important;
    }

    .sidebar nav a,
    .sidebar .pmd-nav a {
        display: flex !important;
        flex: 0 0 76px !important;
        flex-direction: column !important;
        align-items: center !important;
        justify-content: center !important;

        min-width: 76px !important;
        min-height: 54px !important;

        gap: 5px !important;
        margin: 0 !important;
        padding: 7px 4px !important;

        border: 1px solid transparent !important;
        border-radius: 12px !important;

        background: transparent !important;

        color: #929b95 !important;
        font-size: 10px !important;
        line-height: 1.15 !important;
        text-align: center !important;
        text-decoration: none !important;

        white-space: normal !important;
        overflow: hidden !important;
    }

    .sidebar nav a.active,
    .sidebar .pmd-nav a.active {
        color: #d5ff8a !important;
        border-color: rgba(190,255,70,.13) !important;
        background: rgba(190,255,70,.075) !important;
    }

    .sidebar nav a svg,
    .sidebar .pmd-nav a svg,
    .sidebar nav a i,
    .sidebar .pmd-nav a i {
        flex: 0 0 auto;
        width: 19px !important;
        height: 19px !important;
    }

    .sidebar nav a span,
    .sidebar .pmd-nav a span {
        display: block !important;
        max-width: 100%;
        overflow: hidden;
        text-overflow: ellipsis;
        white-space: nowrap;
    }

    /* Заголовки страниц */
    h1 {
        font-size: clamp(22px, 6vw, 29px) !important;
        line-height: 1.2 !important;
        overflow-wrap: anywhere;
    }

    h2 {
        font-size: clamp(18px, 5vw, 23px) !important;
        line-height: 1.25 !important;
    }

    h3 {
        font-size: 16px !important;
        line-height: 1.3 !important;
    }

    /* Контейнеры и карточки */
    .card,
    .panel,
    .glass-card,
    .stat-card,
    .pmd-card {
        min-width: 0 !important;
        max-width: 100% !important;
        padding: 15px !important;
        border-radius: 15px !important;
    }

    .pmd-release-list {
        display: grid !important;
        grid-template-columns: repeat(2, minmax(0, 1fr)) !important;
        gap: 11px !important;
        width: 100% !important;
    }

    .pmd-release-card {
        min-width: 0 !important;
        width: 100% !important;
    }

    .pmd-release-info,
    .pmd-release-card-bottom {
        min-width: 0 !important;
        overflow-wrap: anywhere;
    }

    /* Формы */
    form {
        min-width: 0;
        max-width: 100%;
    }

    input:not([type="checkbox"]):not([type="radio"]),
    select,
    textarea {
        width: 100% !important;
        min-width: 0 !important;
        max-width: 100% !important;
        font-size: 16px !important;
    }

    textarea {
        min-height: 110px;
    }

    label {
        max-width: 100%;
        overflow-wrap: anywhere;
    }

    .form-row,
    .form-group,
    .form-grid,
    .form-actions {
        min-width: 0;
        max-width: 100%;
    }

    .form-grid {
        grid-template-columns: minmax(0, 1fr) !important;
    }

    /* Кнопки */
    button,
    .btn,
    .button {
        min-height: 43px;
        max-width: 100%;
    }

    .btn-group,
    .button-group,
    .actions,
    .form-actions {
        display: flex;
        flex-wrap: wrap;
        gap: 8px;
        min-width: 0;
    }

    /* Таблицы */
    .table-wrapper,
    .table-responsive,
    .table-scroll {
        width: 100% !important;
        max-width: 100% !important;
        overflow-x: auto !important;
        -webkit-overflow-scrolling: touch;
    }

    table {
        min-width: 580px;
        font-size: 12px;
    }

    th,
    td {
        padding: 9px 10px !important;
        white-space: nowrap;
    }

    /* Статистика и графики */
    .stats-grid,
    .statistics-grid,
    .dashboard-grid,
    .charts-grid {
        grid-template-columns: repeat(2, minmax(0, 1fr)) !important;
        gap: 10px !important;
    }

    .chart-container,
    .chart-wrapper,
    .analytics-chart {
        width: 100% !important;
        max-width: 100% !important;
        min-width: 0 !important;
        overflow: hidden !important;
    }

    canvas,
    .chart-container canvas,
    .chart-wrapper canvas {
        max-width: 100% !important;
    }

    /* Модальные окна */
    .modal,
    .modal-dialog,
    .modal-content {
        max-width: calc(100vw - 24px) !important;
    }

    .modal {
        padding: 12px !important;
    }

    .modal-content {
        width: 100% !important;
        max-height: calc(100dvh - 30px) !important;
        overflow-y: auto !important;
        border-radius: 17px !important;
    }

    /* Выпадающие списки */
    .glass-select {
        width: 100% !important;
        min-width: 0 !important;
    }

    .glass-select-trigger {
        min-height: 48px !important;
        padding: 12px 42px 12px 13px !important;
        font-size: 14px !important;
    }

    .glass-select-menu {
        max-width: calc(100vw - 24px) !important;
        max-height: min(230px, 40dvh) !important;
    }

    .glass-select-option {
        min-height: 44px !important;
        font-size: 14px !important;
    }

    /* Длинные названия и технические строки */
    .release-title,
    .track-title,
    .artist-name,
    .user-name,
    .file-name,
    .text-content {
        min-width: 0;
        overflow-wrap: anywhere;
        word-break: break-word;
    }

    /* Изображения обложек */
    .cover,
    .release-cover,
    .pmd-release-cover {
        max-width: 100%;
        overflow: hidden;
    }

    .cover img,
    .release-cover img,
    .pmd-release-cover img {
        display: block;
        width: 100%;
        height: 100%;
        object-fit: cover;
    }
}

/* Очень узкие телефоны */
@media (max-width: 380px) {
    .main {
        padding-right: 10px !important;
        padding-left: 10px !important;
    }

    .pmd-release-list {
        gap: 8px !important;
    }

    .sidebar nav,
    .sidebar .pmd-nav {
        gap: 2px !important;
        padding-right: 5px !important;
        padding-left: 5px !important;
    }

    .sidebar nav a,
    .sidebar .pmd-nav a {
        flex-basis: 68px !important;
        min-width: 68px !important;
        font-size: 9px !important;
    }

    .stats-grid,
    .statistics-grid,
    .dashboard-grid,
    .charts-grid {
        gap: 7px !important;
    }
}

/* Уменьшение анимаций по настройкам устройства */
@media (prefers-reduced-motion: reduce) {
    *,
    *::before,
    *::after {
        scroll-behavior: auto !important;
        animation-duration: .01ms !important;
        animation-iteration-count: 1 !important;
        transition-duration: .01ms !important;
    }
}

/* =========================================================
   PMD — UNIFIED RESPONSIVE LAYER
   Единственная финальная адаптация интерфейса
========================================================= */

@media (max-width: 700px) {
    html,
    body {
        width: 100%;
        max-width: 100%;
        overflow-x: hidden !important;
    }

    body {
        min-width: 320px;
        -webkit-text-size-adjust: 100%;
    }

    .shell {
        display: block !important;
        width: 100% !important;
        max-width: 100% !important;
        min-width: 0 !important;
        overflow-x: clip !important;
    }

    .main {
        display: block !important;
        width: 100% !important;
        max-width: 100% !important;
        min-width: 0 !important;
        margin: 0 !important;
        padding: 78px 14px calc(88px + env(safe-area-inset-bottom)) !important;
        overflow-x: clip !important;
    }

    /* Верхняя панель: раздел слева, уведомления и профиль справа */
    .main > .topbar {
        position: fixed !important;
        inset: 0 0 auto 0 !important;
        z-index: 12000 !important;
        display: flex !important;
        flex-direction: row !important;
        align-items: center !important;
        justify-content: flex-start !important;
        flex-wrap: nowrap !important;
        gap: 8px !important;
        width: 100% !important;
        max-width: 100vw !important;
        min-width: 0 !important;
        height: 62px !important;
        min-height: 62px !important;
        margin: 0 !important;
        padding: max(8px, env(safe-area-inset-top)) 10px 8px !important;
        box-sizing: border-box !important;
    }

    .main > .topbar > .crumb {
        flex: 1 1 auto !important;
        min-width: 0 !important;
        overflow: hidden !important;
        white-space: nowrap !important;
        text-overflow: ellipsis !important;
        font-size: 9px !important;
    }

    .main > .topbar > .global-notification-area {
        display: flex !important;
        order: 2 !important;
        flex: 0 0 auto !important;
        align-items: center !important;
        justify-content: center !important;
        gap: 4px !important;
        margin: 0 !important;
        padding: 0 !important;
        z-index: 12002 !important;
    }

    .global-notification-button,
    .global-sound-toggle {
        width: 32px !important;
        height: 32px !important;
        min-width: 32px !important;
    }

    .main > .topbar > .user-chip {
        display: flex !important;
        order: 3 !important;
        flex: 0 0 auto !important;
        align-items: center !important;
        gap: 5px !important;
        min-width: 0 !important;
        max-width: 34vw !important;
        margin: 0 !important;
        padding: 0 !important;
        overflow: hidden !important;
        white-space: nowrap !important;
        text-overflow: ellipsis !important;
        font-size: 10px !important;
    }

    .main > .topbar > .user-chip .muted {
        display: none !important;
    }

    .main > .topbar > .user-chip .avatar {
        flex: 0 0 30px !important;
        width: 30px !important;
        height: 30px !important;
    }

    /* Уведомления открываются относительно окна, а не узкого topbar */
    .global-notification-dropdown {
        position: fixed !important;
        top: calc(62px + env(safe-area-inset-top)) !important;
        right: 8px !important;
        left: auto !important;
        width: min(370px, calc(100vw - 16px)) !important;
        max-width: calc(100vw - 16px) !important;
        max-height: min(65vh, 520px) !important;
        z-index: 12010 !important;
    }

    /* Нижняя навигация. Ссылки всегда помещаются в одну строку. */
    .sidebar {
        position: fixed !important;
        inset: auto 0 0 0 !important;
        display: flex !important;
        flex-direction: row !important;
        align-items: center !important;
        justify-content: stretch !important;
        width: 100% !important;
        max-width: 100vw !important;
        min-width: 0 !important;
        height: auto !important;
        min-height: 60px !important;
        margin: 0 !important;
        padding: 5px 3px calc(5px + env(safe-area-inset-bottom)) !important;
        box-sizing: border-box !important;
        overflow: hidden !important;
        z-index: 11000 !important;
        transform: none !important;
        border-radius: 0 !important;
    }

    .sidebar > .brand,
    .sidebar > .nav-caption {
        display: none !important;
    }

    .sidebar nav,
    .sidebar .pmd-nav {
        display: flex !important;
        flex: 1 1 auto !important;
        flex-direction: row !important;
        flex-wrap: nowrap !important;
        align-items: center !important;
        justify-content: space-between !important;
        width: auto !important;
        max-width: 100% !important;
        min-width: 0 !important;
        gap: 0 !important;
        margin: 0 !important;
        padding: 0 !important;
        overflow: hidden !important;
        transform: none !important;
    }

    .sidebar nav a,
    .sidebar .pmd-nav a {
        display: flex !important;
        flex: 1 1 0 !important;
        width: 0 !important;
        min-width: 0 !important;
        max-width: none !important;
        min-height: 48px !important;
        margin: 0 !important;
        padding: 5px 0 !important;
        flex-direction: column !important;
        align-items: center !important;
        justify-content: center !important;
        gap: 0 !important;
        overflow: hidden !important;
        border-radius: 9px !important;
        transform: none !important;
        box-sizing: border-box !important;
    }

    .sidebar nav a span,
    .sidebar .pmd-nav a span {
        display: none !important;
    }

    .sidebar nav a svg,
    .sidebar nav a .pmd-nav-icon,
    .sidebar .pmd-nav a svg,
    .sidebar .pmd-nav a .pmd-nav-icon {
        display: block !important;
        width: 21px !important;
        height: 21px !important;
        min-width: 21px !important;
        max-width: 21px !important;
        flex: 0 0 21px !important;
    }

    .sidebar nav a.active {
        box-shadow: inset 0 -2px 0 #c5d99a !important;
        background: rgba(197,217,154,.10) !important;
    }

    /* Не теряем мобильный доступ к выходу / входу */
    .sidebar > .sidebar-bottom {
        display: contents !important;
    }

    .sidebar > .sidebar-bottom > span,
    .sidebar > .sidebar-bottom > b {
        display: none !important;
    }

    .sidebar > .sidebar-bottom > a {
        display: flex !important;
        flex: 0 0 38px !important;
        width: 38px !important;
        min-width: 38px !important;
        height: 48px !important;
        margin: 0 !important;
        padding: 5px 0 !important;
        align-items: center !important;
        justify-content: center !important;
        overflow: hidden !important;
        border-radius: 9px !important;
    }

    .sidebar > .sidebar-bottom > a span {
        display: none !important;
    }

    .sidebar > .sidebar-bottom > a svg {
        width: 20px !important;
        height: 20px !important;
    }

    /* Заголовки страниц */
    .page-head,
    .pmd-admin-head,
    .pmd-releases-header,
    .pmd-users-head,
    .chart-heading,
    .chart-head,
    .rv-section-heading,
    .section-heading-inline {
        max-width: 100% !important;
        min-width: 0 !important;
        flex-wrap: wrap !important;
        gap: 10px !important;
    }

    .page-head h1,
    .page-head h2,
    .pmd-admin-head h1,
    .pmd-releases-heading,
    .pmd-users-head h1,
    .chart-heading h1 {
        max-width: 100% !important;
        overflow-wrap: anywhere !important;
        font-size: clamp(20px, 6vw, 28px) !important;
        line-height: 1.15 !important;
    }

    /* Карточки, KPI и сетки */
    .pmd-dash-stats,
    .pmd-stats-grid,
    .pmd-data-grid,
    .pmd-codes-grid,
    .stats-grid,
    .statistics-grid,
    .dashboard-grid,
    .charts-grid,
    .stats-kpis,
    .stats-charts-grid,
    .yandex-metrics,
    .pmd-grid {
        grid-template-columns: repeat(2, minmax(0, 1fr)) !important;
        width: 100% !important;
        max-width: 100% !important;
        min-width: 0 !important;
        gap: 10px !important;
    }

    .pmd-release-list,
    .pmd-release-grid {
        grid-template-columns: repeat(2, minmax(0, 1fr)) !important;
        width: 100% !important;
        max-width: 100% !important;
        gap: 10px !important;
    }

    .pmd-users-list,
    .pmd-admin,
    .pmd-profile,
    .release-wizard,
    .stats-page,
    .pmd-dashboard,
    .release-view,
    .pmd-releases {
        width: 100% !important;
        max-width: 100% !important;
        min-width: 0 !important;
    }

    .pmd-card,
    .pmd-release-card,
    .pmd-user-card,
    .pmd-account-card,
    .pmd-panel,
    .chart-panel,
    .rv-card,
    .form-panel,
    .pmd-dash-hero {
        min-width: 0 !important;
        max-width: 100% !important;
        overflow-wrap: anywhere !important;
    }

    /* Формы: одна колонка, удобные поля и кнопки */
    .pmd-form-grid,
    .form-grid,
    .pmd-required-box {
        grid-template-columns: minmax(0, 1fr) !important;
        width: 100% !important;
        min-width: 0 !important;
    }

    .field,
    .pmd-field,
    .pmd-codes-field,
    .form-panel,
    .field input,
    .field select,
    .field textarea,
    .pmd-field input,
    .pmd-field select,
    .pmd-field textarea {
        min-width: 0 !important;
        max-width: 100% !important;
    }

    input,
    select,
    textarea,
    button {
        max-width: 100%;
        font-size: 16px;
    }

    input,
    select,
    textarea {
        min-height: 44px;
    }

    button,
    .btn,
    .pmd-dash-button {
        min-height: 42px;
        touch-action: manipulation;
    }

    /* Таблицы прокручиваются внутри себя, не растягивая весь экран */
    .table-wrapper,
    .table-responsive,
    .table-scroll,
    .pmd-table-wrap {
        display: block !important;
        width: 100% !important;
        max-width: 100% !important;
        overflow-x: auto !important;
        overflow-y: hidden !important;
        -webkit-overflow-scrolling: touch;
    }

    .main table {
        max-width: 100% !important;
    }

    .main > table,
    .main .pmd-admin table,
    .main .pmd-users table {
        display: block !important;
        width: 100% !important;
        overflow-x: auto !important;
        -webkit-overflow-scrolling: touch;
    }

    /* Чарты и SVG-графики */
    .stats-chart,
    .stats-chart-body,
    .stats-chart-main,
    .stats-chart-svg,
    .chart-panel,
    .chart-page,
    .ranking,
    .pmd-dash-hero-art {
        max-width: 100% !important;
        min-width: 0 !important;
    }

    .stats-chart-svg {
        width: 100% !important;
        height: auto !important;
    }

    /* Модальные окна и выпадающие панели */
    .pmd-modal,
    .pmd-modal-backdrop,
    .pmd-confirm-modal,
    .pmd-confirm-backdrop,
    .site-modal,
    .modal-backdrop,
    .pmd-avatar-modal,
    .pmd-achievement-modal {
        max-width: 100vw !important;
    }

    .pmd-modal-dialog,
    .pmd-confirm-dialog,
    .pmd-avatar-window,
    .pmd-achievement-window,
    .site-modal > div {
        width: calc(100vw - 24px) !important;
        max-width: 520px !important;
        max-height: calc(100dvh - 24px) !important;
        overflow-y: auto !important;
        -webkit-overflow-scrolling: touch;
    }

    /* Текст и длинные значения */
    .pmd-data-value,
    .pmd-user-email,
    .pmd-file-link,
    .rv-track-file,
    .rv-track-code,
    code,
    pre {
        overflow-wrap: anywhere !important;
        word-break: break-word !important;
    }

    pre {
        max-width: 100% !important;
        overflow-x: auto !important;
    }

    /* Не даём декоративным элементам создавать горизонтальный скролл */
    img,
    video,
    iframe,
    canvas,
    svg {
        max-width: 100%;
    }

    .pmd-filters,
    .pmd-search,
    .pmd-pagination,
    .pmd-card-actions,
    .form-actions,
    .wizard-bottom,
    .pmd-avatar-actions,
    .modal-actions,
    .rv-history-controls {
        display: flex !important;
        flex-wrap: wrap !important;
        gap: 8px !important;
        max-width: 100% !important;
    }

    .auth-wrap {
        width: 100% !important;
        max-width: 100% !important;
        min-height: 100vh;
        padding: 20px 12px !important;
        box-sizing: border-box !important;
    }

    .auth-card {
        width: 100% !important;
        max-width: 460px !important;
        min-width: 0 !important;
        margin-right: auto !important;
        margin-left: auto !important;
        padding: 24px 18px !important;
    }

    .artist-pick-row {
        grid-template-columns: minmax(0, 1fr) minmax(0, 1fr) 28px !important;
    }

    .pmd-user-actions,
    .pmd-user-identity,
    .pmd-release-card-bottom,
    .pmd-dash-footer,
    .rv-track-list,
    .rv-info-row {
        min-width: 0 !important;
        flex-wrap: wrap !important;
    }

}

@media (max-width: 380px) {
    .main {
        padding-right: 10px !important;
        padding-left: 10px !important;
    }

    .main > .topbar {
        gap: 5px !important;
        padding-right: 7px !important;
        padding-left: 7px !important;
    }

    .main > .topbar > .user-chip {
        max-width: 30vw !important;
        font-size: 9px !important;
    }

    .global-notification-button,
    .global-sound-toggle {
        width: 29px !important;
        height: 29px !important;
        min-width: 29px !important;
    }

    .sidebar {
        padding-right: 2px !important;
        padding-left: 2px !important;
    }

    .sidebar > .sidebar-bottom > a {
        flex-basis: 32px !important;
        width: 32px !important;
        min-width: 32px !important;
    }

    .pmd-dash-stats,
    .pmd-stats-grid,
    .stats-grid,
    .statistics-grid,
    .stats-kpis,
    .stats-charts-grid,
    .yandex-metrics {
        gap: 7px !important;
    }
}

@media (prefers-reduced-motion: reduce) {
    .pmd-achievement-overlay *,
    .pmd-achievement-overlay,
    .sidebar nav a,
    .sidebar nav a *,
    .global-notification-dropdown {
        animation-duration: .01ms !important;
        animation-iteration-count: 1 !important;
        transition-duration: .01ms !important;
    }
}

/* =========================================
   SWEETMEAK — ЕДИНЫЙ СТИЛЬ СКРОЛЛБАРОВ
   ========================================= */

/* Firefox и браузеры на базе Chromium */
* {
    scrollbar-width: thin;
    scrollbar-color: #526b35 #10140f;
}

/* Размер полос прокрутки */
::-webkit-scrollbar {
    width: 10px;
    height: 10px;
}

/* Дорожка */
::-webkit-scrollbar-track {
    background: linear-gradient(
        180deg,
        #0c100c 0%,
        #141a12 50%,
        #0c100c 100%
    );
    border-radius: 20px;
    border: 1px solid rgba(150, 190, 90, 0.07);
}

/* Сам ползунок */
::-webkit-scrollbar-thumb {
    background: linear-gradient(
        180deg,
        #829d4c 0%,
        #526d32 45%,
        #344a25 100%
    );
    border-radius: 20px;
    border: 2px solid #10140f;
    min-height: 35px;
    transition:
        background 0.25s ease,
        box-shadow 0.25s ease,
        border-color 0.25s ease;
}

/* Наведение */
::-webkit-scrollbar-thumb:hover {
    background: linear-gradient(
        180deg,
        #c1f36b 0%,
        #8fce45 50%,
        #639b32 100%
    );
    border-color: #192313;
    box-shadow:
        0 0 5px rgba(174, 239, 91, 0.55),
        0 0 12px rgba(151, 220, 67, 0.35),
        inset 0 0 4px rgba(255, 255, 255, 0.2);
    animation: sweetmeak-scroll-glow 1.5s ease-in-out infinite alternate;
}

/* Ненавязчивое свечение */
@keyframes sweetmeak-scroll-glow {
    from {
        filter: brightness(1);
    }
    to {
        filter: brightness(1.25);
    }
}

/* Угол пересечения вертикальной и горизонтальной полос */
::-webkit-scrollbar-corner {
    background: #0c100c;
}

/* Кнопки прокрутки в браузерах, которые их показывают */
::-webkit-scrollbar-button {
    background: #141a12;
    width: 10px;
    height: 10px;
}

/* Ползунок при нажатии */
::-webkit-scrollbar-thumb:active {
    background: #c1f36b;
    box-shadow: 0 0 14px rgba(174, 239, 91, 0.65);
}

/* Одинаковый размер кнопок звука и уведомлений */
@media (max-width: 700px) {
    #globalNotificationSoundToggle.global-sound-toggle {
        width: 32px !important;
        height: 32px !important;
        min-width: 32px !important;
        min-height: 32px !important;
        max-width: 32px !important;
        max-height: 32px !important;
        flex: 0 0 32px !important;

        padding: 0 !important;
        margin: 0 !important;
        border-radius: 50% !important;

        display: inline-flex !important;
        align-items: center !important;
        justify-content: center !important;
        box-sizing: border-box !important;
    }

    #globalNotificationSoundToggle.global-sound-toggle svg {
        width: 17px !important;
        height: 17px !important;
        flex: 0 0 17px !important;
    }
}
/* =========================================================
   PMD GLOBAL THEME — graphite glass + restrained lime
   Дополнительный слой для существующего assets/app.css.
   Не заменяет исходные стили компонентов и разметку.
   ========================================================= */

:root {
  --pmd-bg: #080909;
  --pmd-glass: rgba(13, 15, 14, .76);
  --pmd-glass-strong: rgba(10, 12, 11, .88);
  --pmd-glass-border: rgba(255, 255, 255, .085);
  --pmd-lime: #c3e27a;
  --pmd-lime-soft: rgba(195, 226, 122, .12);
  --pmd-text: #f2f4f1;
  --pmd-muted: #969d96;
}

html {
  min-height: 100%;
  scroll-behavior: smooth;
  scrollbar-width: thin;
  scrollbar-color: rgba(195, 226, 122, .38) rgba(8, 10, 9, .65);
}

body {
  min-height: 100vh;
  color: var(--pmd-text);
  background: var(--pmd-bg) !important;
  position: relative;
  isolation: isolate;
}

/* Размытый и приглушённый фон: изображение остаётся атмосферой,
   но больше не отвлекает от текста и элементов интерфейса. */
body::before {
  content: "";
  position: fixed;
  inset: -24px;
  z-index: -1;
  pointer-events: none;
  background: url("https://i.ibb.co/mVqsL1qq/PMD.png") center / cover no-repeat;
  filter: blur(18px) brightness(.58);
  transform: scale(1.035);
}

body::after {
  content: "";
  position: fixed;
  inset: 0;
  z-index: -1;
  pointer-events: none;
  background: linear-gradient(180deg, rgba(5, 7, 6, .36), rgba(5, 7, 6, .58));
}

/* Общие стеклянные поверхности */
.sidebar,
.topbar,
.form-panel,
.detail-card,
.stat-card,
.chart-panel,
.hero-panel,
.auth-card,
.site-modal,
.modal-backdrop,
.empty-state,
.chart-empty,
.release-row,
.track-item,
.preview-release,
.info-box,
.stats-source-form,
.stats-footnote {
  -webkit-backdrop-filter: blur(22px) saturate(115%);
  backdrop-filter: blur(22px) saturate(115%);
}

.sidebar {
  background: rgba(7, 9, 8, .76) !important;
  border-right: 1px solid rgba(255, 255, 255, .07) !important;
}

.topbar {
  background: rgba(7, 9, 8, .68) !important;
  border-color: rgba(255, 255, 255, .065) !important;
}

.form-panel,
.detail-card,
.chart-panel,
.auth-card,
.site-modal {
  background: linear-gradient(145deg, rgba(24, 27, 25, .84), rgba(8, 10, 9, .88)) !important;
  border-color: var(--pmd-glass-border) !important;
  box-shadow: 0 22px 65px rgba(0, 0, 0, .32), inset 0 1px 0 rgba(255, 255, 255, .025);
}

.stat-card,
.release-row,
.track-item,
.preview-release,
.empty-state,
.chart-empty,
.stats-source-form {
  background: linear-gradient(145deg, rgba(22, 25, 23, .78), rgba(9, 11, 10, .84)) !important;
  border-color: var(--pmd-glass-border) !important;
}

.hero-panel {
  background: linear-gradient(115deg, rgba(31, 36, 32, .88), rgba(10, 13, 11, .88) 68%, rgba(22, 27, 21, .86)) !important;
  border-color: rgba(195, 226, 122, .16) !important;
}

/* Активные элементы и лаймовые акценты */
.sidebar nav a.active,
.sidebar nav a[aria-current="page"] {
  color: #dcf5ad !important;
  background: rgba(195, 226, 122, .09) !important;
  border-color: rgba(195, 226, 122, .16) !important;
  box-shadow: inset 2px 0 var(--pmd-lime), 0 0 22px rgba(195, 226, 122, .045);
}

.sidebar nav a:hover,
.filter-tabs a:hover,
.release-row:hover,
.stat-card:hover {
  border-color: rgba(195, 226, 122, .28) !important;
}

.btn.lime,
.stats-live-dot,
.stats-source-note b {
  color: #e6f7c7 !important;
}

.btn.lime {
  background: linear-gradient(135deg, #c9e98a, #a9ce62) !important;
  border-color: rgba(220, 250, 170, .3) !important;
  color: #151b10 !important;
  box-shadow: 0 7px 24px rgba(175, 218, 99, .12);
}

.btn.lime:hover {
  box-shadow: 0 10px 30px rgba(175, 218, 99, .2);
}

.btn.primary {
  background: linear-gradient(135deg, #f0f2ed, #c9cec5) !important;
  color: #10130f !important;
}

/* Поля, выпадающие списки и фокус */
.field input,
.field textarea,
.field select,
.reject-form input,
.user-actions select,
.stats-source-fields input,
.stats-toolbar select,
.glass-select-trigger {
  background-color: rgba(8, 11, 9, .82) !important;
  color: var(--pmd-text) !important;
  border-color: rgba(255, 255, 255, .11) !important;
}

.field input:focus,
.field textarea:focus,
.field select:focus,
.reject-form input:focus,
.stats-source-fields input:focus,
.stats-toolbar select:focus,
.glass-select-trigger:focus-visible {
  border-color: rgba(195, 226, 122, .58) !important;
  box-shadow: 0 0 0 3px rgba(195, 226, 122, .09), 0 0 22px rgba(195, 226, 122, .055) !important;
}

input::placeholder,
textarea::placeholder {
  color: #737b74 !important;
}

/* Ссылки и небольшие состояния */
a { text-underline-offset: 3px; }
.text-link,
.section-heading a,
.auth-foot a {
  transition: color .22s ease, text-shadow .22s ease;
}
.text-link:hover,
.section-heading a:hover,
.auth-foot a:hover {
  color: #d7f39b !important;
  text-shadow: 0 0 16px rgba(195, 226, 122, .2);
}

.status.lime {
  color: #d5f29b !important;
  background: rgba(195, 226, 122, .09) !important;
}

.timeline-item > i {
  background: var(--pmd-lime) !important;
  box-shadow: 0 0 0 4px rgba(195, 226, 122, .13), 0 0 16px rgba(195, 226, 122, .22) !important;
}

/* Единый аккуратный скроллбар */
* {
  scrollbar-width: thin;
  scrollbar-color: rgba(195, 226, 122, .32) rgba(8, 10, 9, .35);
}

*::-webkit-scrollbar { width: 8px; height: 8px; }
*::-webkit-scrollbar-track {
  background: rgba(8, 10, 9, .42);
  border-radius: 20px;
}
*::-webkit-scrollbar-thumb {
  background: linear-gradient(180deg, rgba(195, 226, 122, .42), rgba(133, 160, 83, .28));
  border: 2px solid rgba(8, 10, 9, .55);
  border-radius: 20px;
}
*::-webkit-scrollbar-thumb:hover {
  background: rgba(195, 226, 122, .68);
}

/* Сдержанные анимации без резких вспышек */
.btn,
.sidebar nav a,
.stat-card,
.release-row,
.form-panel,
.detail-card,
.field input,
.field textarea,
.field select,
.glass-select-trigger,
.glass-select-option {
  transition: color .24s ease, background .24s ease, border-color .24s ease,
    box-shadow .28s ease, transform .28s cubic-bezier(.2, .75, .25, 1);
}

@media (max-width: 700px) {
  body::before { background-attachment: scroll; filter: blur(16px) brightness(.56); }
  .sidebar {
    background: rgba(7, 9, 8, .94) !important;
    border-top: 1px solid rgba(195, 226, 122, .12) !important;
  }
  .topbar { background: rgba(7, 9, 8, .88) !important; }
}

@media (prefers-reduced-motion: reduce) {
  *, *::before, *::after {
    scroll-behavior: auto !important;
    animation-duration: .01ms !important;
    animation-iteration-count: 1 !important;
    transition-duration: .01ms !important;
  }
}/* PMD — стеклянные выдвижные уведомления */

.toast {
    position: fixed !important;
    top: 84px !important;
    right: 3px !important;
    left: auto !important;
    z-index: 20000 !important;

    width: min(370px, calc(100vw - 24px));
    padding: 14px 19px;

    color: rgba(240, 243, 241, .92);
    background: rgba(35, 37, 36, .68);

    border: 1px solid rgba(210, 220, 214, .13);
    border-radius: 13px;

    backdrop-filter: blur(24px) saturate(115%);
    -webkit-backdrop-filter: blur(24px) saturate(115%);

    box-shadow:
        0 8px 30px rgba(0, 0, 0, .20),
        0 0 18px rgba(180, 195, 185, .035),
        inset 0 1px 0 rgba(255, 255, 255, .045);

    animation: pmdToastSlide 5s ease-in-out both !important;
    will-change: transform, opacity;
    overflow: hidden;
}

.toast.success {
    color: rgba(222, 239, 226, .92);
    border-color: rgba(135, 180, 145, .17);
    background: rgba(34, 40, 36, .70);
}

.toast.error {
    color: rgba(239, 222, 222, .92);
    border-color: rgba(185, 135, 135, .18);
    background: rgba(43, 36, 37, .72);
}

/* Выезд справа, остановка и возвращение */
@keyframes pmdToastSlide {
    0% {
        opacity: 0;
        transform: translateX(calc(100% + 15px));
        filter: blur(6px);
    }

    12% {
        opacity: 1;
        transform: translateX(0);
        filter: blur(0);
    }

    82% {
        opacity: 1;
        transform: translateX(0);
        filter: blur(0);
    }

    100% {
        opacity: 0;
        transform: translateX(calc(100% + 15px));
        filter: blur(6px);
    }
}

/* Телефоны */
@media (max-width: 700px) {
    .toast {
        top: 84px !important;
        right: 3px !important;
        left: 3px !important;
        width: auto;
    }
}
