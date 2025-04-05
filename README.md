<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:css='false' b:defaultwidgetversion='2' b:layoutsVersion='3' b:responsive='true' b:templateVersion='1.0.0' expr:class='data:blog.languageDirection' expr:dir='data:blog.languageDirection' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
  <head>
<b:if cond='data:blog.pageType in {&quot;index&quot;} and data:blog.homepageUrl == data:blog.url'>
	<title><data:blog.pageTitle/> - <data:view.description.escaped/></title>
<b:else/>
<b:if cond='data:blog.pageType in {&quot;item&quot;,&quot;static_page&quot;}'>
	<title><data:blog.pageName/> - <data:blog.title/></title>
<b:else/>
<b:if cond='data:blog.pageType in {&quot;index&quot;} and data:blog.pageName == &quot;&quot;'>
	<title>All Posts - <data:blog.title/></title>
<b:else/>
<b:if cond='data:blog.pageType in {&quot;error_page&quot;}'>
	<title>Page Not Found - <data:blog.title/></title>
<b:else/>
	<title><data:blog.pageName/> - <data:blog.title/></title>
</b:if>
</b:if>
</b:if>
</b:if>
    <meta content='width=device-width, initial-scale=1' name='viewport'/>
    <b:include data='blog' name='all-head-content'/>
    <b:skin><![CDATA[
/*Developer: Pro Templates*/
@import url(https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.6.3/css/font-awesome.min.css);.owl-carousel{display:none;width:100%;-webkit-tap-highlight-color:transparent;position:relative;z-index:1}.owl-carousel .owl-stage{position:relative;-ms-touch-action:pan-Y;touch-action:manipulation;-moz-backface-visibility:hidden}.owl-carousel .owl-stage:after{content:".";display:block;clear:both;visibility:hidden;line-height:0;height:0}.owl-carousel .owl-stage-outer{position:relative;overflow:hidden;-webkit-transform:translateZ(0)}.owl-carousel .owl-item{-webkit-backface-visibility:hidden;-moz-backface-visibility:hidden;-ms-backface-visibility:hidden;-webkit-transform:translateZ(0);-moz-transform:translateZ(0);-ms-transform:translateZ(0)}.owl-carousel .owl-item{position:relative;min-height:1px;float:left;-webkit-backface-visibility:hidden;-webkit-tap-highlight-color:transparent;-webkit-touch-callout:none}.owl-carousel .owl-item img{display:block;width:100%}.owl-carousel .owl-dot,.owl-carousel .owl-nav .owl-next,.owl-carousel .owl-nav .owl-prev{cursor:pointer;cursor:hand;-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none}.owl-carousel.owl-loaded{display:block}.main_content{word-break:break-word;font-size:18px;line-height:28px;padding:25px}.single_head{background-image:url(https://lh3.googleusercontent.com/-pPNQPYAJQNk/YfDzcvN8vWI/AAAAAAAAA_8/XaF5CvmjZaYfGpb7QnTp1uDn5r2bOT90wCNcBGAsYHQ/s16000/image.png);padding:80px 0}.main_slider{background-image:url(https://lh3.googleusercontent.com/-l1P4_bBkPLk/YfFUv6lHDZI/AAAAAAAABAM/OiSBmh7XoQ4tRX69uPl6zxFZuRZVWLgDwCNcBGAsYHQ/s16000/image.png)}.single_head .image{width:45%;position:relative;border-radius:10px}.single_head .content{width:45%}.single_head .content span.cat a{display:initial;font-size:14px;padding:0 20px;background-color:#6c75ff;color:#fff;border-radius:20px;width:85px;text-align:center}.single_head .content h1 a{display:block;color:#fff;font-size:30px;line-height:40px;font-weight:700;margin-top:20px}.single_head .content .author_dtails{display:-webkit-box;display:-ms-flexbox;display:flex;color:#fff;-webkit-box-align:center;-ms-flex-align:center;align-items:center}.single_head .content .author_dtails .auth_img{padding-right:15px}.single_head .content .author_dtails .auth_img img{width:60px;height:60px;border:7px solid #fff;border-radius:50%}.single_head .content .author_dtails .auth_desc h4{margin:0;line-height:0}.single_head .content .author_dtails .auth_desc a{font-size:18px;line-height:28px}.single_head .content .author_dtails a{color:#fff}.single_head .content ul.post_infos{padding:0;margin:0;margin-top:30px;display:-webkit-box;display:-ms-flexbox;display:flex;position:relative;list-style-type:none;-webkit-box-pack:justify;-ms-flex-pack:justify;justify-content:space-between;width:200px}.single_head .content ul.post_infos li a{color:#fff;font-size:14px}.single_head .image .fold{position:absolute;top:-10px;right:30px}.image img.fold{width:auto}.single_head .image img.main_img{border-radius:5px;width:100%;max-height:300px}#comments .continue{display:none}span.search-label:after,span.search-label:before,span.search-query:after,span.search-query:before{content:'"'}.queryEmpty{background:#fff;width:100%;box-shadow:0 1px 3px rgb(0 0 0 / 12%),0 1px 2px rgb(0 0 0 / 24%);padding:20px;margin:auto}.sidebar .FeaturedPost .entry-image-wrap{position:relative;float:left;width:100%;height:170px;z-index:1;overflow:hidden;display:flex;flex-direction:column;margin:10px 0 0}.sidebar .widget-content.featured-post{display:grid}.sidebar .FeaturedPost h2 a{font-weight:600;font-size:20px;color:#3e3e3e}.cloud-label-widget-content a.label-name{background-color:#6c75ff;color:#fff;padding:5px 15px;border-radius:15px;overflow:hidden;text-overflow:ellipsis;white-space:nowrap;margin-top:0}.cloud-label-widget-content span.label-count{margin:3px;background:#8a2be2;border-radius:50%;padding:10px;font-weight:500}.sidebar .widget.ContactForm form{display:flex;flex-wrap:wrap;font-size:15px}.sidebar input.contact-form-name{width:100%;margin-bottom:10px}.sidebar input.contact-form-email{width:100%;margin-bottom:10px}.sidebar textarea.contact-form-email-message{width:100%;border-color:#ccc;border-radius:5px;resize:vertical}.sidebar input.contact-form-button-submit{width:100%;background:#7243e9;color:#fff;margin-top:10px;padding:8px;cursor:pointer}.sidebar input.contact-form-button-submit:hover{background:#4e11e7}p.contact-form-error-message-with-border{display:flex;width:100%;color:#df4848;margin:12px 0}p.contact-form-error-message-with-border img{cursor:pointer}.sidebar .widget.Profile img.profile-img{float:left}.sidebar .widget.Profile .profile-info{display:block}.sidebar .widget.Profile .widget-content.individual{display:flex}.sidebar .widget.Profile dd.profile-textblock{margin:0;font-size:15px;padding:5px 0}.sidebar .widget.Profile dl.profile-datablock{margin:0;padding:0 10px}.sidebar .widget.Profile a.profile-link{padding:0 10px;color:#3e3e3e;font-size:14px}.sidebar .widget.Profile a.profile-link.g-profile{padding:0;font-weight:600;font-size:20px;color:#3e3e3e}.sidebar .widget.Profile dd.profile-data.location{margin:0;font-size:15px}.sidebar-posts .post-item{width:100%;display:flex;flex-wrap:wrap;padding:0;margin:20px 0 0}.sidebar-posts .entry-image-wrap{position:relative;width:90px;height:62px;overflow:hidden;z-index:1;margin:0 12px 0 0}.entry-thumb{display:block;position:relative;width:100%;height:100%;background-size:cover;background-position:center center;background-repeat:no-repeat;z-index:1;transition:opacity .35s ease,filter 0s ease}.sidebar-posts .post-item .entry-header{flex:1}.sidebar-posts .entry-title{font-size:15px;margin:0;line-height:18px}.sidebar-posts .entry-title a{color:#3e3e3e}#comments{clear:both;margin-top:10px;margin-bottom:0;font-family:Arial;line-height:18px;font-size:13px}#comments .comments-content{margin-bottom:16px;font-weight:400;text-align:left}#comments .comment .comment-actions a,#comments .comment .continue a{display:inline-block;margin:0 0 10px 10px;padding:0 15px;color:#fff!important;text-align:center;text-decoration:none;background:#7243e9;border:1px solid #9976f1;border-radius:2px;height:26px;line-height:28px;font-weight:400;cursor:pointer}#comments .comments-content .comment-thread ol{list-style-type:none;padding:0}#comments .comments-content .inline-thread{padding:0}#comments .comments-content .comment-thread{margin:8px 0}#comments .comments-content .comment-thread:empty{display:none}.comment-replies{margin-top:1em;margin-left:40px;background:#fff0}#comments .comments-content .comment{margin-bottom:0;padding-bottom:0}#comments .comments-content .comment:first-child{padding-top:16px}#comments .comments-content .comment:last-child{border-bottom:0;padding-bottom:0}#comments .comments-content .comment-body{position:relative}#comments .comments-content .user{font-style:normal}#comments .comments-content .user a{color:#3e3e3e;font-weight:600;font-size:17px;text-decoration:none}#comments .comments-content .icon.blog-author{width:18px;height:18px;display:inline-block;margin:0 0 -4px 6px}#comments .comments-content .datetime a{color:#666;font-size:12px;float:right;text-decoration:none}.comment-content{margin:0 0 8px;padding:5px 5px;font-family:'Hind Siliguri'}.comment-header{font-size:18px;padding:5px}#comments .comments-content .owner-actions{position:absolute;right:0;top:0}#comments .comments-replybox{border:none;height:230px;width:100%}#comments .comment-replybox-thread{margin-top:0}#comments .comment-replybox-single{margin-top:5px;margin-left:48px}#comments .comments-content .loadmore a{display:block;padding:10px 16px;text-align:center}#comments .thread-toggle{cursor:pointer;display:inline-block}#comments .comments-content .loadmore.hidden{cursor:pointer;max-height:3em;margin-top:0;display:none}#comments .comments-content .loadmore.loaded{max-height:0;opacity:0;overflow:hidden}#comments .thread-chrome.thread-collapsed{display:none}#comments .thread-toggle{display:inline-block}#comments .thread-toggle .thread-arrow{display:inline-block;height:6px;width:7px;overflow:visible;margin:.3em;padding-right:4px}#comments .thread-expanded .thread-arrow{background:url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAc AAAAHCAYAAADEUlfTAAAAG0lEQVR42mNgwAfKy8v/48I4FeA0AacVDFQBAP9wJkE/KhUMAAAAAElFTkSuQmCC") no-repeat scroll 0 0 transparent}#comments .thread-collapsed .thread-arrow{background:url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAA AcAAAAHCAYAAADEUlfTAAAAJUlEQVR42mNgAILy8vL/DLgASBKnApgkVgXIkhgKiNKJ005s4gDLbCZBiSxfygAAAAB JRU5ErkJggg==") no-repeat scroll 0 0 transparent}.avatar-image-container{float:left;vertical-align:middle;overflow:hidden;width:65px!important;height:51px!important;max-width:65px!important;max-height:51px!important;z-index:111;position:relative;margin:10px 0 0 10px}#comments .avatar-image-container img{padding:2px;width:50px!important;height:50px!important;max-width:50px!important;max-height:50px!important;border-radius:50%}#comments .comment-block{position:relative;border:5px solid #fff;background:#fff;box-shadow:0 1px 3px rgb(0 0 0 / 12%),0 1px 2px rgb(0 0 0 / 24%)}@media screen and (max-device-width:480px){#comments .comments-content .comment-replies{margin-left:0}}li.comment div.comment-replies ol li.comment div.comment-block{background-color:#d8f0fa!important;border-color:#d8f0fa!important}.comment-thread.inline-thread.hidden{display:none}#comments .comment-replybox-single iframe,#comments .comment-replybox-thread iframe,.comment-form iframe{margin-bottom:10px;box-shadow:0 1px 3px rgb(0 0 0 / 12%),0 1px 2px rgb(0 0 0 / 24%)}#top-continue a.comment-reply{color:#666;font-size:16px;margin:15px 0;font-weight:600;text-transform:capitalize;display:block}.item-control{display:none}span.datetime.secondary-text{display:flex}.sidebar .ReportAbuse h3{text-align:center}.sidebar .ReportAbuse h3 a{color:#3e3e3e}.post-views.entry-meta>span{margin-right:0!important;font:16px/1}*{outline:0}a,article,aside,body,div,footer,form,h2,h3,h6,header,html,i,img,li,nav,p,section,span,ul{margin:0;padding:0;border:0;font-size:100%;font:inherit;vertical-align:baseline;-webkit-box-sizing:border-box;box-sizing:border-box}article,aside,footer,header,nav,section{display:block}body{line-height:1}ul{list-style:none}a{text-decoration:none;display:block}html{font-family:sans-serif;-ms-text-size-adjust:100%;-webkit-text-size-adjust:100%}body{margin:0}a{background-color:transparent}a:active,a:hover{outline-width:0}img{border-style:none;display:block;height:auto}button,input{font:inherit}button,input{overflow:visible}button,input{margin:0}button{text-transform:none}[type=submit],button{cursor:pointer}[type=submit],button{-webkit-appearance:button}button::-moz-focus-inner,input::-moz-focus-inner{border:0;padding:0}button:-moz-focusring,input:-moz-focusring{outline:0 dotted ButtonText}[type=search]{-webkit-appearance:textfield}.recent_posts .mid.has_sidebar{-ms-flex-wrap:wrap;flex-wrap:wrap}input{padding:5px 10px;border:1px solid #ccc;border-radius:5px}body{font-family:Hind Siliguri,sans-serif}.trickbd-notification>a,a.notification{position:relative}.trickbd-like-count.liked a{color:#6c75ff!important}*{word-wrap:break-word}.search_login .search_login{position:relative}ul.mob_prfile{display:none;width:130px;position:absolute;right:-55px;top:58px;background:#fff;list-style-type:none;margin:0;padding:0;border:1px solid #ccc;text-align:center;border-bottom:none}ul.mob_prfile li{border-bottom:1px solid #ccc}ul.mob_prfile li a{font-size:16px;padding:15px 10px;color:#555}ul.page-numbers{padding:0;list-style-type:none;margin:30px 0;display:-webkit-box;display:-ms-flexbox;display:flex}ul.page-numbers li{display:inline-block;margin-right:5px}ul.page-numbers li a,ul.page-numbers li span{color:#3e3e3e;background-color:#fff;height:35px;width:35px;-webkit-box-shadow:0 0 50px #eee;box-shadow:0 0 50px #eee;text-align:center;padding-top:10px;font-size:14px;font-weight:600;display:block}.post-views{display:inline-block}.user img.avatar{border-radius:50%}ul{margin:0 1em;padding-left:40px}ul{list-style-type:disc}h2,h3,h6,p,ul{margin:5px 0}h2,h3,h6{color:#333;margin:10px 0}h2{font-weight:700}h2{font-size:24px;line-height:30px}h3{font-size:22px;line-height:38px}h6{font-size:16px;line-height:22px}.naaai{display:none}.cats ul li a,.col_2 article,.featured_post .box ul,.featured_post .mid,.has_sidebar,.m_menu ul,.main_slider .slide,.sp_flex,footer .foo_bottom .mid,footer .foo_top .mid,header .mid{display:-moz-flex;display:-ms-flex;display:-o-flex;display:-webkit-box;display:-ms-flexbox;display:flex;-webkit-box-pack:justify;-ms-flex-pack:justify;justify-content:space-between;-webkit-box-align:center;-ms-flex-align:center;align-items:center}img{max-width:100%;-o-object-fit:cover;object-fit:cover}a{display:inline-block}.p_title{font-weight:600;font-size:19px;line-height:25px;margin:0}.p_title a{color:#3e3e3e}.h_middle{font-size:36px;color:#000;text-align:center;padding:50px 0;font-weight:700}.desc{color:#555;font-size:13px;line-height:20px;word-spacing:3px}footer .foo_top .mid .b4 ul li{margin-bottom:15px}footer .foo_top .mid .b4 ul li a:before{font-family:FontAwesome;font-size:14px;width:35px;color:#fff;height:35px;padding:10px;text-align:center;margin-right:15px}footer .foo_top .mid .b4 ul li:first-child a:before{content:"\f09a";background:#3a599d;padding:10px 12px}footer .foo_top .mid .b4 ul li:nth-child(2) a:before{content:"\f099";background:#00aeef}footer .foo_top .mid .b4 ul li:nth-child(3) a:before{content:"\f0e1";background:#0e7bbb}.cats ul li a{color:#3e3e3e;font-size:15px;margin-bottom:15px;font-weight:600}.cats ul img{width:20px;margin-right:10px}.sidebar .cats{background-color:#fff;-webkit-box-shadow:0 0 50px #eee;box-shadow:0 0 50px #eee;-webkit-box-shadow:0 1px 3px rgba(0,0,0,.12),0 1px 2px rgba(0,0,0,.24);box-shadow:0 1px 3px rgba(0,0,0,.12),0 1px 2px rgba(0,0,0,.24);padding:8%;margin:6% 0}.sidebar .cats h3{color:#3e3e3e;font-size:22px;font-weight:600;margin-bottom:20px}a.scroll_top{background:#7446e8;font-size:45px;text-align:center;color:#fff;padding:5px 10px;position:fixed;bottom:3%;right:2%;border-radius:5px;cursor:pointer;z-index:9999999999;display:none}a.scroll_top:hover{background:#6436d8}a,a:focus,a:hover{text-decoration:none}a.more{text-align:center;font-size:17px;padding:15px 0;border-radius:3px;margin-top:30px;display:block;width:125px}.mid{width:90%;margin:auto}header{position:relative}header .mid{background:#fff}.search_login,header .mid>a{display:none}.logo img{display:block;width:130px;height:auto}.m_menu ul{margin:0;padding:0;list-style:none}.m_menu ul li{-webkit-transition:.2s;transition:.2s}.m_menu ul li a{display:block;color:#ababab;padding:30px 15px;font-size:14px;font-weight:700}.m_menu ul li .sub_posts{-webkit-box-pack:center;-ms-flex-pack:center;justify-content:center;display:none;position:absolute;background-color:#555;right:0;left:0;padding:0;width:100%;z-index:333;padding-top:20px}.m_menu ul li .sub_posts article{padding:0 10px}.m_menu ul li .sub_posts article .image a{padding:0}.m_menu ul li .sub_posts article img{width:100%;height:160px}.m_menu ul li .sub_posts article h3 a{font-size:20px;line-height:30px;font-weight:600;color:#ddd;padding:20px 0;-webkit-transition:.2s;transition:.2s}.m_menu ul li .sub_posts article h3 a:hover{color:#fff}.m_menu ul li .sub_posts article:first-child{padding-left:0}.m_menu ul li .sub_posts article:last-child{padding-right:0}.m_menu ul li:hover>a{text-decoration:none;color:#000}.m_menu ul li:hover .sub_posts{display:-webkit-box;display:-ms-flexbox;display:flex}.m_menu ul li.login>a{background-color:#7243e9;color:#fff;padding:10px 20px;margin:20px 10px;border-radius:3px;-webkit-filter:drop-shadow(0 0 15px #999);filter:drop-shadow(0 0 15px #999)}.m_menu ul li.login>a:hover{background-color:#6334e0;color:#fff;-webkit-transition:.5s;transition:.5s}.m_menu ul li.search a{font-size:20px;padding:27px 15px}.m_menu ul li.search input{display:none;width:50%;padding:10px 2%;border:1px solid #aaa;border-radius:5px;position:absolute;z-index:222;font-size:15px;color:#555;top:100%;right:5%}.m_menu ul ul.sub-menu{position:absolute;z-index:222;display:none;background-color:#fff;border-top:1px solid #333;padding:0;margin:0}.m_menu ul ul.sub-menu a{color:#444;border:1px solid #ccc;border-top:none;font-size:12px}.m_menu ul ul.sub-menu ul.sub-menu{border-top:1px solid #ccc;top:0;right:100%}.m_menu ul ul.sub-menu li a{text-align:center;padding:15px 10px;min-width:200px;-webkit-transition:.2s;transition:.2s}.m_menu ul ul.sub-menu li:hover>a{color:#000}.m_menu ul li:hover>ul.sub-menu{display:block}.m_menu ul li.menu-item-has-children{position:relative}.m_menu ul li.arrow_mega>a:after,.m_menu ul li.menu-item-has-children>a:after{font:normal normal normal 14px/1 FontAwesome;font-size:inherit;text-rendering:auto;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale;content:"\F107";margin-left:5px}.main_slider{background-size:100% 100%;background-position:50%;position:relative}.main_slider .slide{padding:80px 0}.main_slider .slide .sl_text{width:45%}.main_slider .slide .sl_text h6{position:relative}.main_slider .slide .sl_text h6 a{display:initial;font-size:16px;padding:0 20px;background-color:#00aeff;color:#fff;border-radius:20px;width:100px;text-align:center}.main_slider .slide .sl_text h6 span.triangle{position:absolute;border-left:0 solid transparent;border-right:13px solid transparent;border-top:13px solid #00aeff;top:19px;left:7px}.main_slider .slide .sl_text h3{margin-top:30px}.main_slider .slide .sl_text h3 a{display:block;color:#fff;font-size:30px;line-height:40px;font-weight:700}.main_slider .slide .sl_text p{color:#ccc;font-size:16px;line-height:22px;margin:15px 0}.main_slider .slide .sl_text a.more{color:#000;background-color:#fff}.main_slider .slide .sl_img{width:45%}.main_slider .slide .sl_img img{border-radius:5px;width:100%;max-height:360px;-o-object-fit:cover;object-fit:cover}.main_slider a.down{position:absolute;display:block;left:0;right:0;margin:auto;bottom:-23px;width:45px;height:45px;border-radius:50%;text-align:center;background-color:#fff;color:#000;font-size:18px;-webkit-box-shadow:0 5px 20px #ccc;box-shadow:0 5px 20px #ccc;z-index:2222}.main_slider a.down i.fa{margin-top:14px}.featured_post{padding:50px 0}.featured_post .mid{width:80%;-webkit-box-align:initial;-ms-flex-align:initial;align-items:initial}.featured_post .box{width:32%;-webkit-box-shadow:0 0 50px #ccc;box-shadow:0 0 50px #ccc;-webkit-box-shadow:0 1px 3px rgba(0,0,0,.12),0 1px 2px rgba(0,0,0,.24);box-shadow:0 1px 3px rgba(0,0,0,.12),0 1px 2px rgba(0,0,0,.24);position:relative;display:-webkit-box;display:-ms-flexbox;display:flex;-webkit-box-orient:vertical;-webkit-box-direction:normal;-ms-flex-direction:column;flex-direction:column;padding:0}.featured_post .box ul{list-style:none;padding:15px 5%;text-align:center;background-color:#f6f8fa;width:100%;margin-top:auto;margin-bottom:0}.featured_post .box ul li:nth-child(5){display:-webkit-box;display:-ms-flexbox;display:flex;position:absolute;top:20px;right:20px}.featured_post .box ul li:nth-child(5) a{background-color:rgba(0,0,0,.6);color:#fff;text-align:center;padding:5px 10px;border-radius:20px;font-size:13px}.featured_post .box ul li:nth-child(2){display:-webkit-box;display:-ms-flexbox;display:flex;-webkit-box-align:center;-ms-flex-align:center;align-items:center}.featured_post .box ul li:nth-child(2) a.user{margin-right:5px}.featured_post .box ul li:nth-child(2) a[rel=author]{max-width:120px;overflow:hidden;text-overflow:ellipsis;white-space:nowrap;text-align:left}.featured_post .box ul li.cat{display:none}.featured_post .box ul li a{color:#9f9f9f;font-size:12px}.featured_post .box ul li a i{margin-right:5px}.featured_post .box ul li a i.fa-calendar{margin-right:2px}.featured_post .box .image{position:relative;width:100%;height:200px}.featured_post .box .image img{width:100%;height:200px}.featured_post .box .image .cat a{display:block;font-size:16px;padding:7px 15px;border-radius:20px;-webkit-box-shadow:0 7px 20px #ccc;box-shadow:0 7px 20px #ccc;background-color:#fff;position:absolute;left:5%;bottom:-14px;color:#727272;text-align:center}.featured_post .box .f_content{height:100%;min-height:0;display:-webkit-box;display:-ms-flexbox;display:flex;-webkit-box-orient:vertical;-webkit-box-direction:normal;-ms-flex-direction:column;flex-direction:column}.featured_post .box h3{margin:15px 5%;margin-top:35px}.featured_post .box p{margin:15px 5%;margin-bottom:0}article ul li a.user img{height:20px;width:20px}.home_featured.featured_post .box .image img{height:200px}.recent_posts{background-color:#f0f8fb;padding:30px 0;border-top:1px solid #eee}.has_sidebar{-webkit-box-align:initial;-ms-flex-align:initial;align-items:initial}.col_2{width:68%}.col_2 article{margin-bottom:2%;padding:2%;background-color:#fff;-webkit-box-align:initial;-ms-flex-align:initial;align-items:initial;-webkit-box-shadow:0 0 50px #ddd;box-shadow:0 0 50px #ddd;-webkit-box-shadow:0 1px 3px rgba(0,0,0,.12),0 1px 2px rgba(0,0,0,.24);box-shadow:0 1px 3px rgba(0,0,0,.12),0 1px 2px rgba(0,0,0,.24)}.col_2 article .image{width:26%}.col_2 article .image img{width:100%;max-height:200px}.sidebar{width:30%}footer ul{margin:0;padding:0;list-style-type:none}footer .foo_top{background-color:#111;padding:80px 0;position:relative}footer .foo_top .mid{-webkit-box-align:initial;-ms-flex-align:initial;align-items:initial}footer .foo_top h2{color:#fff;font-size:22px;font-weight:700;margin-bottom:30px}footer .foo_top .mid .b1 ul li:first-child a,footer .foo_top .mid .b4 ul li:first-child a{padding-top:0}footer .foo_top .mid .b1 ul li a,footer .foo_top .mid .b4 ul li a{font-size:16px;line-height:22px;font-weight:600;color:#aeaeae;padding:3px 0}footer .foo_top .mid .b2{padding:0 3%}footer .foo_top .mid .b2 ul li{padding-bottom:15px}footer .foo_top .mid .b2 ul li h3{font-size:16px;line-height:22px;font-weight:600;text-transform:capitalize}footer .foo_top .mid .b2 ul li h3 a{color:#aeaeae}footer .foo_top .mid .b2 ul li p{font-size:14px;margin-bottom:5px}footer .foo_top .mid .b2 ul li p a{display:inline-block;-webkit-transition:.2s;transition:.2s}footer .foo_top .mid .b2 ul li:first-child p,footer .foo_top .mid .b2 ul li:first-child p a,footer .foo_top .mid .b2 ul li:first-child p a:hover{color:#6c75ff}footer .foo_top .mid .b2 ul li:nth-child(2) p,footer .foo_top .mid .b2 ul li:nth-child(2) p a,footer .foo_top .mid .b2 ul li:nth-child(2) p a:hover{color:#de8f12}footer .foo_top .mid .b2 ul li:nth-child(3) p,footer .foo_top .mid .b2 ul li:nth-child(3) p a,footer .foo_top .mid .b2 ul li:nth-child(3) p a:hover{color:#19b394}footer .foo_top .email{position:absolute;left:0;right:0;bottom:-30px;margin:auto;display:-webkit-box;display:-ms-flexbox;display:flex;-webkit-box-pack:center;-ms-flex-pack:center;justify-content:center;width:33%}footer .foo_top .email input{background-color:#7243e9;border:1px solid #7243e9;width:100%;font-size:16px;font-family:sans-serif;padding:20px 30px;border-radius:100px;color:#ccc}footer .foo_top .email input::-webkit-input-placeholder{color:#ccc}footer .foo_top .email input:-ms-input-placeholder,footer .foo_top .email input::-ms-input-placeholder{color:#ccc}footer .foo_top .email input::placeholder{color:#ccc}footer .foo_top .email input:focus{border:1px solid #7243e9;border-radius:100px}footer .foo_top .email button{position:absolute;height:100%;right:0;width:20%;border:1px solid #7243e9;border-radius:0 100px 100px 0;background-color:#7243e9;color:#fff}footer .foo_top .email button i{font-size:20px}footer .foo_bottom{background-color:#181818;padding:40px 0;padding-top:70px}footer .foo_bottom .m_menu ul li:hover>a{color:#fff}.full_post_area{background-color:#f0f8fb;padding:30px 0}.BlogSearch,.search_aside{position:relative;-webkit-box-shadow:0 0 50px #eee;box-shadow:0 0 50px #eee;-webkit-box-shadow:0 1px 3px rgba(0,0,0,.12),0 1px 2px rgba(0,0,0,.24);box-shadow:0 1px 3px rgba(0,0,0,.12),0 1px 2px rgba(0,0,0,.24);margin-bottom:6%}.BlogSearch button{position:absolute;top:0;right:0;height:100%;width:15%;color:#7243e9;background-color:#fff;border:1px solid #fff;font-size:20px}.BlogSearch .search-input input[type=search]::-webkit-input-placeholder{color:#ccc}.BlogSearch .search-input input[type=search]:-ms-input-placeholder,.BlogSearch input[type=search]::-ms-input-placeholder{color:#ccc}.BlogSearch .search-input input[type=search]::placeholder{color:#ccc}.BlogSearch .search-input input[type=search]{width:100%;padding:15px;border:1px solid #fff;color:#aaa}.full_post_area .col_2 .featured_post{padding:0;display:-webkit-box;display:-ms-flexbox;display:flex;-webkit-box-pack:justify;-ms-flex-pack:justify;justify-content:space-between;-ms-flex-wrap:wrap;flex-wrap:wrap}.full_post_area .col_2 .featured_post .box{width:49%}.full_post_area .col_2 .featured_post .box .f_content{height:100%}.comments_count_filter h3{color:#666;font-size:16px;font-weight:600;margin-right:30px;line-height:26px}.sidebar div.widget{background:#fff;width:100%;box-shadow:0 1px 3px rgb(0 0 0 / 12%),0 1px 2px rgb(0 0 0 / 24%);padding:20px;margin-bottom:6%}.sidebar div.BlogSearch{padding:0}.sidebar .widget h3.title{color:#3e3e3e;font-weight:600;font-size:22px;margin-bottom:20px}.sidebar .Label ul,.sidebar .PageList ul{margin:0;padding:0;list-style-type:none}.sidebar .LinkList ul{margin:0;padding:0 18px;list-style-type:square}.sidebar .Label ul li a,.sidebar .LinkList ul li a,.sidebar .PageList ul li a{display:block;color:#3e3e3e;font-size:15px;margin-bottom:15px;font-weight:600}.sidebar .Label ul li:before{content:'\f0ca';font-family:FontAwesome;font-size:13px;color:#6c75ff;margin-right:8px;float:left}.list-label-widget-content span.label-count{float:right}@media (max-width:1330px){.featured_post .mid .box ul li a i{margin-right:2px}}@media (max-width:1280px){.mid{width:90%}.featured_post .mid .box ul li a i{margin-right:2px}}@media (max-width:1260px){.main_slider .slide .sl_img{width:46%}}@media (max-width:1160px){header .mid{width:90%}.featured_post .mid .box ul{padding:15px 3%}}@media (max-width:1100px){.featured_post .mid{width:95%}.main_slider .slide .sl_text{width:48%}.main_slider .slide .sl_text h3{margin-top:25px}.main_slider .slide .sl_text p{margin:10px 0}a.more{margin-top:20px}.featured_post .mid{width:760px!important;-ms-flex-wrap:wrap;flex-wrap:wrap;-webkit-box-pack:justify;-ms-flex-pack:justify;justify-content:space-between}.featured_post .mid .box:last-child{margin:auto;margin-top:20px}.featured_post .mid .box{width:370px}.featured_post .box p{margin-bottom:10px}}@media (max-width:1060px){.sidebar .widget h3.title{text-align:center}.m_menu ul li a,.m_menu ul li.search a{padding-left:10px;padding-right:10px}.logo img{width:100px}.has_sidebar{-webkit-box-orient:vertical;-webkit-box-direction:normal;-ms-flex-direction:column;flex-direction:column;-webkit-box-align:center;-ms-flex-align:center;align-items:center;width:95%}.col_2{width:95%}.col_2 article .image{width:26%}.ad_sec{display:none}.sidebar{width:95%}.sidebar .cats{width:32%;margin-top:70px}.sidebar .cats{padding:20px 15px;display:-webkit-box;display:-ms-flexbox;display:flex;-webkit-box-orient:vertical;-webkit-box-direction:normal;-ms-flex-direction:column;flex-direction:column;-webkit-box-align:center;-ms-flex-align:center;align-items:center;padding-top:30px}.sidebar{margin-top:20px}}@media (max-width:1030px){.main_slider .slide .sl_text{width:51%}.main_slider .slide .sl_text h3 a{font-size:27px;line-height:37px}.main_slider .slide .sl_text{width:46%}.main_slider .slide .sl_img{width:50%}.col_2 article .image{width:27%}}@media (max-width:1010px){.featured_post .mid .box ul li a{font-size:13px}.featured_post .mid .box ul li:nth-child(2) a{max-width:100px}}@media (max-width:980px){.full_post_area .sidebar .BlogSearch{position:relative}.full_post_area .sidebar .BlogSearch{width:100%}}@media (max-width:980px) and (min-width:525px){.sidebar{-webkit-box-orient:vertical;-webkit-box-direction:normal;-ms-flex-direction:column;flex-direction:column;-webkit-box-align:center;-ms-flex-align:center;align-items:center}.full_post_area .sidebar .BlogSearch button{width:10%}.foo_top .mid:after{content:"";display:block;clear:both}}@media (max-width:930px){.m_menu ul li a,.m_menu ul li.search a{padding-left:7px;padding-right:7px}.m_menu ul li a{font-size:13px}.m_menu ul li.search a{font-size:17px}.sidebar .cats ul img{margin-right:5px}footer .foo_top .email{width:45%}}@media (max-width:850px){div.comments-area.block_comment{width:760px;margin:auto}.featured_post .mid .box ul li a i.fa-calendar{display:none}.full_post_area .col_2 .featured_post{-webkit-box-pack:justify;-ms-flex-pack:justify;justify-content:space-between}.full_post_area .col_2 .featured_post,.full_post_area .col_2 ul.page-numbers{width:760px;margin:auto}.full_post_area .col_2 .featured_post .box{width:370px}.sidebar{width:760px;margin:auto;margin-top:20px}.queryEmpty{width:760px}.has_sidebar{width:100%}footer{margin-top:-20px}}@media (max-width:815px){header .mid.scroll_funcs{top:-120px!important}.single_head .mid.sp_flex{-webkit-box-orient:vertical;-webkit-box-direction:normal;-ms-flex-direction:column;flex-direction:column}.single_head .content{width:100%;text-align:center;margin-top:30px}.single_head .content .author_dtails{-webkit-box-pack:center;-ms-flex-pack:center;justify-content:center;-webkit-box-align:center;-ms-flex-align:center;align-items:center}.single_head .content ul.post_infos{margin:auto;margin-top:30px;justify-content:center}.single_head .content ul.post_infos li a{padding:0 10px}.full_post_area{padding:80px 0}div#main-nav{position:absolute}header .m_menu.menu_showw>ul{left:0}a.scroll_top{font-size:40px;padding:0 5px;background-color:rgba(100,54,216,.7);right:5%}.main_slider .slider .mid{width:100%}.main_slider .slider{background:rgba(0,0,0,.6)}.main_slider{margin-top:63px}.main_slider .slide{position:relative;-webkit-box-pack:center;-ms-flex-pack:center;justify-content:center}.main_slider .slide .sl_text a.more{padding:12px 0;font-size:16px;width:110px}.main_slider .slide .sl_text{width:80%}.main_slider .slide .sl_text h3{margin-top:30px}.main_slider .slide .sl_text p{margin:15px 0}.main_slider .slide .sl_img{width:90%;position:absolute;opacity:.2;z-index:-111;top:0;left:0;right:0;margin:auto;display:-webkit-box;display:-ms-flexbox;display:flex;-webkit-box-align:center;-ms-flex-align:center;align-items:center;height:100%}.main_slider .slide .sl_text h3 a{font-size:30px;line-height:40px}header .mid{width:100%;padding:2px 5%;border-bottom:2px solid #030303;-webkit-transition:.2s;transition:.2s;z-index:5555555;position:fixed;left:0;right:0;top:0}header .mid .search_login{display:-moz-flex;display:-ms-flex;display:-o-flex;display:-webkit-box;display:-ms-flexbox;display:flex;-webkit-box-pack:justify;-ms-flex-pack:justify;justify-content:space-between;-webkit-box-align:center;-ms-flex-align:center;align-items:center;max-width:200px}header .mid .search_login>a{padding:15px 10px;font-size:20px;color:#555}.mob_search{display:none;position:absolute;-webkit-box-align:initial;-ms-flex-align:initial;align-items:initial;width:100%;margin:auto;left:0;right:0;top:100%;margin-top:2px}.mob_search input::-webkit-input-placeholder{padding:8px 0;font-size:20px;color:#555;width:100%;display:-webkit-box;display:flex;-webkit-box-align:center;align-items:center;vertical-align:middle}.mob_search input:-ms-input-placeholder,.mob_search input::-ms-input-placeholder{padding:8px 0;font-size:20px;color:#555;width:100%;display:-ms-flexbox;display:flex;-ms-flex-align:center;align-items:center;vertical-align:middle}.mob_search input::placeholder{padding:8px 0;font-size:20px;color:#555;width:100%;display:-webkit-box;display:-ms-flexbox;display:flex;-webkit-box-align:center;-ms-flex-align:center;align-items:center;vertical-align:middle}.mob_search input{padding:17px 30px;border:1px solid #ccc;z-index:222;font-size:20px;color:#555;width:100%}.mob_search button{font-size:20px;background-color:#7243e9;border:1px solid #7243e9;padding:0 30px;border-radius:5px;color:#eee}header .mid .logo a{padding:15px 5px}header .mid .naaai{display:block}header .mid>a{display:block;padding:18px 10px;font-size:20px;color:#555}header .m_menu ul li.login,header .m_menu ul li.search{display:none}header .m_menu{position:absolute}header .m_menu>ul{-webkit-transition:.2s;transition:.2s;position:fixed;background-color:#fff;z-index:5555555;left:-80%;width:75%;top:63px;max-height:4000px;overflow-x:scroll;display:block;height:100%;padding-bottom:63px;border-right:1px solid #ccc}header .m_menu ul li{border-bottom:1px solid #ccc}header .m_menu ul li a{font-size:18px;padding:20px 10px;color:#555;border-left:1px solid #ccc;margin-left:50px}.m_menu ul li.arrow_mega>a:after,header .m_menu ul li.menu-item-has-children>a:after{content:""}.m_menu ul li:hover>ul.sub-menu,header .m_menu ul li:hover .sub_posts{display:none}header .m_menu ul ul.sub-menu{position:relative;border:none;-webkit-transition:.2s;transition:.2s}header .m_menu ul li.menu-item-has-children>ul.sub-menu{display:block!important;height:0;overflow:hidden}header .m_menu ul li.menu-item-has-children>i.naaai{position:absolute;height:50px;display:block;width:50px;left:0;top:0;display:-webkit-box;display:-ms-flexbox;display:flex;-webkit-box-pack:center;-ms-flex-pack:center;justify-content:center;-webkit-box-align:center;-ms-flex-align:center;align-items:center;cursor:pointer}header .m_menu ul ul li.menu-item-has-children>i.naaai{width:60px}header .m_menu ul ul.sub-menu li a{font-size:18px;padding:20px 10px;font-weight:600;margin-left:60px}header .m_menu ul ul.sub-menu a{border:none;border-left:1px solid #ccc}header .m_menu ul ul.sub-menu ul.sub-menu{left:0!important;border-top:none}header .m_menu ul ul.sub-menu ul li a{margin-left:70px}.featured_post .mid .box ul li a i.fa-calendar{display:inline}.foo_bottom .m_menu{display:none}.h_middle{font-size:30px;padding:30px 0}.col_2{width:100%}.col_2 article{position:relative}.queryEmpty,.sidebar{width:660px}footer .foo_bottom .mid{-webkit-box-pack:center;-ms-flex-pack:center;justify-content:center}footer .foo_top .email{width:55%}.featured_post .mid,.full_post_area .col_2 .featured_post{width:660px!important}.full_post_area .col_2 ul.page-numbers{width:660px;margin:auto}.featured_post .mid .box,.full_post_area .col_2 .featured_post .box{width:320px}.featured_post .box .image img{height:172px}.featured_post .box p{margin-bottom:-10px;margin-top:0}.featured_post.home_featured .box p{margin:15px 5%;margin-bottom:10px;margin-top:0}.menu-item-has-children{position:relative}footer .foo_top .mid{-webkit-box-orient:vertical;-webkit-box-direction:normal;-ms-flex-direction:column;flex-direction:column;-webkit-box-align:center;-ms-flex-align:center;align-items:center}footer .foo_top .mid .box{width:80%;margin-bottom:40px;padding-left:0;padding-right:0}footer .foo_top .mid .b1{-webkit-box-ordinal-group:4;-ms-flex-order:3;order:3}footer .foo_top .mid .b2{-webkit-box-ordinal-group:2;-ms-flex-order:1;order:1}footer .foo_top .mid .b4{-webkit-box-ordinal-group:3;-ms-flex-order:2;order:2}footer .foo_top h2{text-align:center;margin-bottom:20px}footer .foo_top .mid .b2 ul li{padding-bottom:20px}.m_menu ul li.trickbd-notification{display:none}.ar-flex{display:-moz-flex;display:-ms-flex;display:-o-flex;display:-webkit-box;display:-ms-flexbox;display:flex;width:95%}}@media (max-width:760px){.main_slider .slide{padding:7% 0}}@media (max-width:680px){.featured_post .mid,.full_post_area .col_2 .featured_post{width:590px!important}div.comments-area.block_comment{width:590px;margin:auto}.full_post_area .col_2 ul.page-numbers,.queryEmpty,.sidebar{width:590px}.featured_post .mid .box,.full_post_area .col_2 .featured_post .box{width:290px}.full_post_area .col_2 .featured_post .box{margin-bottom:10px}.featured_post .mid .box:last-child{margin-top:10px}.featured_post .box .image img{height:156px}.featured_post .box ul li:nth-child(2) a[rel=author]{max-width:70px}.featured_post .box ul li:nth-child(3){display:-webkit-box;display:-ms-flexbox;display:flex}.featured_post .box ul li:nth-child(3) a{max-width:130px;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}.featured_post .box p{margin-bottom:-30px}}@media (max-width:645px){.main_slider .slide .sl_img{width:100%}.featured_post .mid .box ul li a{font-size:14px}}@media (max-width:620px){.single_head .content h1 a{font-size:26px;line-height:36px}div.comments-area.block_comment{width:550px;margin:auto}.featured_post .mid,.full_post_area .col_2 .featured_post{width:550px!important}.full_post_area .col_2 ul.page-numbers,.queryEmpty,.sidebar{width:550px}.featured_post .mid .box,.full_post_area .col_2 .featured_post .box{width:270px}.featured_post .box .image img{height:145px}.featured_post .box p{margin-bottom:-45px}}@media (max-width:565px){.single_head .image{width:65%}.col_2 article.art-item,div.comments-area.block_comment{width:95%;margin:auto}.main_slider .slide .sl_img{width:95%}.main_slider .slide{padding:40px 0}footer .foo_top .email{width:75%}.featured_post .mid,.full_post_area .col_2 .featured_post{width:100%!important;-webkit-box-orient:vertical;-webkit-box-direction:normal;-ms-flex-direction:column;flex-direction:column;-webkit-box-align:center;-ms-flex-align:center;align-items:center}.featured_post .mid .box:last-child{margin:0}.featured_post .box .image img{height:200px}.featured_post .mid .box,.full_post_area .col_2 .featured_post .box,.full_post_area .col_2 ul.page-numbers,.queryEmpty,.sidebar{width:95%;margin:auto;margin-bottom:20px}.featured_post .box p{margin-bottom:10px}}@media (max-width:524px){.main_content{padding:15px}ul.mob_prfile{top:60px}.featured_post{padding:30px 0}header .m_menu.menu_showw>ul{left:0}header .m_menu>ul{left:-85%;width:80%}header .mid>a{padding:20px 15px;font-size:16px}header .mid .search_login>a{padding:20px 10px;font-size:16px}.main_slider .slide{padding:30px 0}.main_slider .slide .sl_img{width:100%}.main_slider .slide .sl_text h3{margin-top:20px}.main_slider .slide .sl_text h3 a{font-size:22px;line-height:30px;font-weight:800}.main_slider .slide .sl_text p{margin:10px 0}.main_slider .slide .sl_text a.more{margin-top:15px}.col_2,.featured_post .mid .box .f_content,.featured_post .mid .box .image{width:100%}.col_2 article{display:block;padding-bottom:0;min-height:180px;margin:10px}.col_2 article .image{width:33%;float:left;display:block;margin-right:10px;margin-bottom:5px}.sidebar{-webkit-box-orient:vertical;-webkit-box-direction:normal;-ms-flex-direction:column;flex-direction:column;-webkit-box-align:center;-ms-flex-align:center;align-items:center}.sidebar .cats{width:100%}.sidebar .cats{margin:20px 0}a.more{margin-top:0}footer .foo_top{padding:20px 0;padding-top:50px}.featured_post .box ul li a{font-size:14px}.full_post_area .col_2 ul.page-numbers li a{font-size:16px;padding-top:11px;width:35px;height:35px}}@media (max-width:486px){.main_content{padding:10px}.main_slider .slide .sl_text{width:95%}}@media (max-width:450px){.main_slider .slide .sl_img{opacity:.1}.main_slider .slide .sl_text h6 a{font-size:14px}.main_slider .slide .sl_text p{font-size:14px;line-height:20px}.main_slider .slide .sl_text a.more{margin-top:10px;font-size:14px;width:100px}.main_slider .slide{padding:20px 0}header .m_menu>ul{left:-90%;width:85%}footer .foo_top .mid .box{width:90%}}@media (max-width:425px){.mob_search button{padding:0 10px;-webkit-box-flex:1;-ms-flex:1;flex:1}.mob_search input{-webkit-box-flex:4;-ms-flex:4;flex:4;padding:15px 10px}footer .foo_top .mid .box{width:100%;padding-right:0!important;padding-left:0!important}footer .foo_top .email{width:85%}.featured_post .box ul li a i{margin-right:0}}@media (max-width:380px){.featured_post .box .image,.full_post_area .col_2 .featured_post .box .image{height:auto}.featured_post .box .image img,.full_post_area .col_2 .featured_post .box .image img{height:auto;min-height:100px}}@media (max-width:365px){.main_slider .slide .sl_text h3 a{font-size:18px;line-height:26px}.featured_post .box ul li:nth-child(2) a{max-width:100px}}@media (min-width:815px){footer .foo_top .mid .b2{max-width:45%}}@media (min-width:850px){.full_post_area .col_2.posts .featured_post .box{width:auto}.col_2.posts .featured_post .box{-webkit-box-shadow:0 1px 3px rgba(0,0,0,.12),0 1px 2px rgba(0,0,0,.24);box-shadow:0 1px 3px rgba(0,0,0,.12),0 1px 2px rgba(0,0,0,.24);position:static;-webkit-box-orient:initial;-webkit-box-direction:initial;-ms-flex-direction:initial;flex-direction:row;margin-bottom:2%;padding:2%;background-color:#fff;-webkit-box-align:initial;-ms-flex-align:initial;align-items:initial}.col_2.posts .featured_post .box .image{position:static;width:26%;height:auto}.col_2.posts .featured_post .box .image img{width:100%;height:130px}.col_2.posts .featured_post .box .image span.cat{display:none}.col_2.posts .featured_post .box .f_content{height:auto;display:initial;-webkit-box-orient:initial;-webkit-box-direction:initial;-ms-flex-direction:initial;flex-direction:row}.col_2.posts .featured_post .box h3{margin:0;font-size:19px;line-height:25px;font-weight:600}.col_2.posts .featured_post .box p{margin:initial}.full_post_area .col_2.posts .featured_post{display:block}.full_post_area .col_2.posts .featured_post article .image span.cat{display:none}.full_post_area .col_2.posts .featured_post article .f_content{width:72%;position:relative}.full_post_area .col_2.posts .featured_post article .f_content .desc{padding-bottom:30px}.full_post_area .col_2.posts .featured_post article.box ul{display:-webkit-box;display:-ms-flexbox;display:flex;-webkit-box-pack:justify;-ms-flex-pack:justify;justify-content:space-between;position:absolute;right:0;left:0;bottom:0;list-style:none;text-align:center;background-color:#fff;width:100%;padding:0;margin:0}.full_post_area .col_2.posts .featured_post article.box ul li:nth-child(2){display:-webkit-box;display:-ms-flexbox;display:flex;-webkit-box-align:center;-ms-flex-align:center;align-items:center}.full_post_area .col_2.posts .featured_post article.box ul li:nth-child(2) a.user{margin-right:5px}.full_post_area .col_2.posts .featured_post article.box ul li:nth-child(2) a[rel=author]{max-width:120px;overflow:hidden;text-overflow:ellipsis;white-space:nowrap;text-align:left}.full_post_area .col_2.posts .featured_post article.box ul li:nth-child(5){display:initial;position:static}.full_post_area .col_2.posts .featured_post article.box ul li:nth-child(5) a{background-color:initial;color:#9f9f9f;text-align:center;padding:initial;border-radius:initial;font-size:12px}.full_post_area .col_2.posts .featured_post article.box ul li.cat{display:block}.full_post_area .col_2.posts .featured_post article.box ul li.cat a{background-color:#6c75ff;color:#fff;padding:5px 15px;border-radius:15px;overflow:hidden;text-overflow:ellipsis;white-space:nowrap;margin-top:0}.full_post_area .col_2.posts .featured_post article.box ul li a{color:#9f9f9f;font-size:12px}.full_post_area .col_2.posts .featured_post article.box ul li a i{margin-right:5px}.full_post_area .col_2.posts .featured_post article.box ul li a i.fa-calendar{margin-right:2px}}@media (min-width:815px) and (max-width:1060px){.m_menu ul li .sub_posts{padding:0 5%;padding-top:20px}.m_menu ul li .sub_posts article{width:25%}.m_menu ul li .sub_posts article img{height:120px}}@media (min-width:1060px){.mid{width:1020px!important}.m_menu ul li .sub_posts article{width:255px}}@media (min-width:1140px){.featured_post .mid{width:1020px!important}.featured_post .box p{margin-bottom:10px}.mid{width:1100px!important}.m_menu ul li .sub_posts article{width:275px}}@media (min-width:1270px){.featured_post .mid{width:1100px!important}.mid{width:1140px!important}.m_menu ul li .sub_posts article{width:285px}}div#blog-pager .pagecurrent,div#blog-pager a,span.dots{color:#3e3e3e;background:#fff;padding:10px 12px;text-align:center;margin:3px;box-shadow:0 1px 3px rgb(0 0 0 / 12%),0 1px 2px rgb(0 0 0 / 24%)}div#blog-pager{margin:10px;display:flex;justify-content:center;font-weight:500}span.current{color:#3e3e3e;background:#fff;padding:10px 12px;text-align:center;margin:3px}span.pages{color:#3e3e3e;background:#fff;padding:10px 12px;text-align:center;margin:3px}.trickbd-ad{text-align:center}.user img.avatar{font-size:0px}@font-face{font-family:'Hind Siliguri';font-style:normal;font-weight:300;src:url(https://fonts.gstatic.com/s/hindsiliguri/v7/ijwOs5juQtsyLLR5jN4cxBEoRDf40vQVKxGv.woff2) format('woff2');unicode-range:U+0964-0965,U+0981-09FB,U+200C-200D,U+20B9,U+25CC}@font-face{font-family:'Hind Siliguri';font-style:normal;font-weight:300;src:url(https://fonts.gstatic.com/s/hindsiliguri/v7/ijwOs5juQtsyLLR5jN4cxBEoRDf40ugVKxGv.woff2) format('woff2');unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}@font-face{font-family:'Hind Siliguri';font-style:normal;font-weight:300;src:url(https://fonts.gstatic.com/s/hindsiliguri/v7/ijwOs5juQtsyLLR5jN4cxBEoRDf40uYVKw.woff2) format('woff2');unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}@font-face{font-family:'Hind Siliguri';font-style:normal;font-weight:400;src:url(https://fonts.gstatic.com/s/hindsiliguri/v7/ijwTs5juQtsyLLR5jN4cxBEoTI7ax9k0.woff2) format('woff2');unicode-range:U+0964-0965,U+0981-09FB,U+200C-200D,U+20B9,U+25CC}@font-face{font-family:'Hind Siliguri';font-style:normal;font-weight:400;src:url(https://fonts.gstatic.com/s/hindsiliguri/v7/ijwTs5juQtsyLLR5jN4cxBEoTJLax9k0.woff2) format('woff2');unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}@font-face{font-family:'Hind Siliguri';font-style:normal;font-weight:400;src:url(https://fonts.gstatic.com/s/hindsiliguri/v7/ijwTs5juQtsyLLR5jN4cxBEoTJzaxw.woff2) format('woff2');unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}@font-face{font-family:'Hind Siliguri';font-style:normal;font-weight:500;src:url(https://fonts.gstatic.com/s/hindsiliguri/v7/ijwOs5juQtsyLLR5jN4cxBEoRG_50vQVKxGv.woff2) format('woff2');unicode-range:U+0964-0965,U+0981-09FB,U+200C-200D,U+20B9,U+25CC}@font-face{font-family:'Hind Siliguri';font-style:normal;font-weight:500;src:url(https://fonts.gstatic.com/s/hindsiliguri/v7/ijwOs5juQtsyLLR5jN4cxBEoRG_50ugVKxGv.woff2) format('woff2');unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}@font-face{font-family:'Hind Siliguri';font-style:normal;font-weight:500;src:url(https://fonts.gstatic.com/s/hindsiliguri/v7/ijwOs5juQtsyLLR5jN4cxBEoRG_50uYVKw.woff2) format('woff2');unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}@font-face{font-family:'Hind Siliguri';font-style:normal;font-weight:600;src:url(https://fonts.gstatic.com/s/hindsiliguri/v7/ijwOs5juQtsyLLR5jN4cxBEoREP-0vQVKxGv.woff2) format('woff2');unicode-range:U+0964-0965,U+0981-09FB,U+200C-200D,U+20B9,U+25CC}@font-face{font-family:'Hind Siliguri';font-style:normal;font-weight:600;src:url(https://fonts.gstatic.com/s/hindsiliguri/v7/ijwOs5juQtsyLLR5jN4cxBEoREP-0ugVKxGv.woff2) format('woff2');unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}@font-face{font-family:'Hind Siliguri';font-style:normal;font-weight:600;src:url(https://fonts.gstatic.com/s/hindsiliguri/v7/ijwOs5juQtsyLLR5jN4cxBEoREP-0uYVKw.woff2) format('woff2');unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}@font-face{font-family:'Hind Siliguri';font-style:normal;font-weight:700;src:url(https://fonts.gstatic.com/s/hindsiliguri/v7/ijwOs5juQtsyLLR5jN4cxBEoRCf_0vQVKxGv.woff2) format('woff2');unicode-range:U+0964-0965,U+0981-09FB,U+200C-200D,U+20B9,U+25CC}@font-face{font-family:'Hind Siliguri';font-style:normal;font-weight:700;src:url(https://fonts.gstatic.com/s/hindsiliguri/v7/ijwOs5juQtsyLLR5jN4cxBEoRCf_0ugVKxGv.woff2) format('woff2');unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}@font-face{font-family:'Hind Siliguri';font-style:normal;font-weight:700;src:url(https://fonts.gstatic.com/s/hindsiliguri/v7/ijwOs5juQtsyLLR5jN4cxBEoRCf_0uYVKw.woff2) format('woff2');unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}
.widget-content.cloud-label-widget-content {
    display: inline-block;
}
.sidebar div.widget.Blog a.image {
    margin: 10px 0;
    margin-bottom: 30px;
    display: block;
}

.sidebar div.widget.Blog a.image img {
    width: 110px;
    height: 110px;
    border: 10px solid #fff;
    -webkit-box-shadow: 0 0 50px #ccc;
    box-shadow: 0 0 50px #ccc;
    margin: auto;
    border-radius: 50%;
}

.sidebar div.widget.Blog span {
    background-color: #00c828;
    color: #eee;
    font-size: 12px;
    border-radius: 50px;
    padding: 0 10px;
}

.sidebar div.widget.Blog {text-align: center;}

.sidebar div.widget.Blog h3 {
    font-size: 30px;
    font-weight: 700;
    text-align: center;
}

.sidebar div.widget.Blog h3 a {
    font-size: 30px;
    font-weight: 700;
    text-align: center;
    color: #000;
}

.sidebar div.widget.Blog p {
    margin: 25px 0;
    padding-top: 10px;
    font-size: 14px;
    line-height: 24px;
    color: #999;
}
a.scroll_top{background:#7446e8;font-size:45px;text-align:center;color:#fff;padding:5px 10px;position:fixed;bottom:3%;right:2%;border-radius:5px;cursor:pointer;z-index:9999999999;display:none;}
a.scroll_top:hover{background:#6436d8;}
@media (max-width: 1060px) and (min-width: 525px){
.sidebar .Label ul li {
    width: 50%;
    float: left;
    padding: 0 22px;
}
.sidebar .Label .widget-content.list-label-widget-content{
display: flex;
justify-content: center;
}
}
.main_content blockquote {
    margin: 10px;
    border: 2px solid #7446e8;
    border-left-width: 6px;
    padding: 5px;
} .distr{opacity:0}
]]></b:skin>

    <b:if cond='data:view.isLayoutMode'>
<b:template-skin><![CDATA[
body#layout .flex-left{display:flex!important}body#layout .mid{display:flex!important}body#layout .footer-logo,body#layout .footer-nav,body#layout .main-logo,body#layout .main-nav{width:50%}body#layout .mid .footer-center,body#layout .mid .footer-left,body#layout .mid .footer-right{width:33%}body#layout .col_2{width:70%}body#layout:after{content:'Design by ProTemplates';display:block;font-family:Roboto,sans-serif;font-size:14px;color:#555;line-height:1;text-align:center;visibility:visible;padding:20px 0}body#layout .theme-options{display:block!important}
]]></b:template-skin>
</b:if>
<b:defaultmarkups>
  <b:defaultmarkup type='PopularPosts'>
        <b:includable id='main' var='this'>
    <b:include name='widget-title'/>
    <div class='widget-content sidebar-posts'>
      <b:include name='snippetedPosts'/>
    </div>
  </b:includable>

  <b:includable id='snippetedPosts'>
    <div role='feed'>
      <!-- Don't render the post that we're currently already looking at. -->
      <b:loop values='data:posts filter (p =&gt; p.id != data:view.postId)' var='post'>
        <article class='post-item' role='article'>
          <b:include name='snippetedPostContent'/>
        </article>
      </b:loop>
    </div>
  </b:includable>

  <b:includable id='snippetedPostContent'>
    <b:include cond='data:this.postDisplay.showFeaturedImage and data:post.featuredImage' name='snippetedPostThumbnail'/>
    <b:include cond='data:this.postDisplay.showTitle' name='snippetedPostTitle'/>
  </b:includable>

  <b:includable id='snippetedPostThumbnail'>
    <a class='entry-image-wrap' expr:href='data:post.url'>
        <img class='entry-thumb' expr:src='data:post.featuredImage.isYouTube ? resizeImage(data:post.featuredImage.youtubeMaxResDefaultUrl.jsonEscaped, 72, &quot;1:1&quot;) : resizeImage(data:post.featuredImage, 72, &quot;1:1&quot;)'/>
    </a>
  </b:includable>
  
  <b:includable id='snippetedPostTitle'>
    <b:if cond='data:post.title != &quot;&quot;'>
      <div class='entry-header'>
        <h2 class='entry-title'>
          <a expr:href='data:post.url' expr:title='data:post.title'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></a>
        </h2>
      </div>
    </b:if>
  </b:includable>
  </b:defaultmarkup>
    <b:defaultmarkup type='FeaturedPost'>
    <b:includable id='main' var='this'>
      <div class='widget-content featured-post'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='content'/>
        </b:loop>
      </div>
    </b:includable>
    <b:includable id='blogThisShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='bylineByName' var='byline'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='bylineRegion' var='regionItems'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='commentsLink'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='commentsLinkIframe'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='content' var='post'>
        <div class='entry-header'>
          <h2 class='entry-title'><a expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></a></h2>
        </div>
        <b:if cond='data:post.featuredImage'>
          <a class='entry-image-wrap' expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle'><img class='entry-thumb' expr:src='data:post.featuredImage.isYouTube ? data:post.featuredImage.youtubeMaxResDefaultUrl.jsonEscaped : data:post.featuredImage'/></a>
          <b:else/>
          <a class='entry-image-wrap is-image' expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle'><span class='entry-thumb' data-image='https://4.bp.blogspot.com/-oSjP8F09qxo/Wy1J9dp7b0I/AAAAAAAACF0/ggcRfLCFQ9s2SSaeL9BFSE2wyTYzQaTyQCK4BGAYYCw/s35-r/avatar.jpg'/></a>
        </b:if>
    </b:includable>
    <b:includable id='emailPostIcon'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='facebookShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='footerBylines'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='googlePlusShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='headerByline'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='linkShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='otherSharingButton'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='platformShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postAuthor'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postCommentsLink'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postJumpLink' var='post'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postLabels'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postLocation'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postReactions'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postShareButtons'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postTimestamp'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButton'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButtonContent'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButtons'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButtonsMenu'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingPlatformIcon'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPostByline'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPostContent'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPostThumbnail'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPostTitle'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPosts'><b:comment>Replaced</b:comment></b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='BlogSearch'>
    <b:includable id='main'>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <div class='widget-content' role='search'>
        <b:include name='searchForm'/>
      </div>
    </b:includable>
    <b:includable id='searchForm'>
      <form expr:action='data:blog.searchUrl'>
        <b:attr cond='not data:view.isPreview' name='target' value='_top'/>
          <b:include name='urlParamsAsFormInput'/>
            <div class='search-input'>
              <input autocomplete='off' expr:aria-label='data:messages.searchThisBlog' expr:value='data:view.isSearch ? data:view.search.query.escaped : &quot;&quot;' name='q' placeholder='Search' type='search'/>
              <button type='submit'><i class='fa fa-search'/></button>
            </div>
      </form>
    </b:includable>
    <b:includable id='searchSubmit'>
      <input class='search-action' expr:value='data:messages.search.escaped' type='submit'/>
    </b:includable>
  </b:defaultmarkup>
</b:defaultmarkups>
  </head>
  <body>
    
      <div class='theme-options' style='display:none'>
    <b:section class='sora-panel' id='sora-panel' maxwidgets='1' name='Theme Options' showaddelement='no'>
      <b:widget id='LinkList71' locked='true' title='Default Variables' type='LinkList' version='2' visible='true'>
        <b:widget-settings>
          <b:widget-setting name='sorting'>NONE</b:widget-setting>
          <b:widget-setting name='text-1'>perPage</b:widget-setting>
          <b:widget-setting name='link-1'>3</b:widget-setting>
          <b:widget-setting name='text-0'>numPages</b:widget-setting>
          <b:widget-setting name='link-0'>3</b:widget-setting>
        </b:widget-settings>
        <b:includable id='main'>
          <b:include name='content'/>
        </b:includable>
        <b:includable id='content'>
          &lt;script type=&#39;text/javascript&#39;&gt;
          //&lt;![CDATA[
          var perPage = 7,numPages = 3;
          <b:loop values='data:links' var='link'>
            <b:if cond='data:link.name == &quot;perPage&quot;'>
              var perPage = <data:link.target/>;
            </b:if>
            <b:if cond='data:link.name == &quot;numPages&quot;'>
              var numPages = <data:link.target/>;
            </b:if>
          </b:loop>
          //]]&gt;
          &lt;/script&gt;
        </b:includable>
      </b:widget>
    </b:section>
  </div>
    
    
    <header>
    <div class='flex-left mid'>
      <a class='menu_toggle' href='#'><i class='fa fa-bars'/></a>
      <b:section class='main-logo' id='main-logo' maxwidgets='1' name='Header Logo' showaddelement='no'>
        <b:widget id='Header1' locked='true' title='themes (Header)' type='Header' version='2' visible='true'>
          <b:widget-settings>
            <b:widget-setting name='displayUrl'>https://1.bp.blogspot.com/-a5lb98BdL_4/YfGXIdg85mI/AAAAAAAABBk/Y6vmx_UHnnEVlyxGBVoBe5yIbG8QVwfowCNcBGAsYHQ/s150/logo.png</b:widget-setting>
            <b:widget-setting name='displayHeight'>32</b:widget-setting>
            <b:widget-setting name='sectionWidth'>150</b:widget-setting>
            <b:widget-setting name='useImage'>true</b:widget-setting>
            <b:widget-setting name='shrinkToFit'>true</b:widget-setting>
            <b:widget-setting name='imagePlacement'>BEHIND</b:widget-setting>
            <b:widget-setting name='displayWidth'>150</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main' var='this'>
            <b:if cond='data:this.sourceUrl'>
              <div class='logo'>
                <a expr:href='data:blog.homepageUrl.canonical'><img expr:alt='data:this.title' expr:src='data:this.sourceUrl'/></a>
              </div>
              <b:else/>
              <h2><a expr:href='data:blog.homepageUrl.canonical'><data:this.title/></a></h2>
            </b:if>
          </b:includable>
          <b:includable id='behindImageStyle'>
          </b:includable>
          <b:includable id='description'>
          </b:includable>
          <b:includable id='image'>
          </b:includable>
          <b:includable id='title'>
          </b:includable>
        </b:widget>
      </b:section>
      <div class='search_login '>
        <a class='m_search' href='#'><i class='fa fa-search'/></a>
          <div class='mob_search'>
            <form expr:action='data:blog.searchUrl' style='display:contents'>
            <input autocomplete='off' name='q' placeholder='Search' type='search'/>
            <button type='submit'><i class='fa fa-search'/></button>
            </form>
          </div>
      </div>
      <b:section class='main-nav' id='main-nav' maxwidgets='1' name='Main Menu' showaddelement='no'>
        <b:widget id='LinkList1' locked='true' title='' type='LinkList' version='2' visible='true'>
          <b:widget-settings>
            <b:widget-setting name='link-3'>https://trickbd-template.blogspot.com/search/label/Tech%20News</b:widget-setting>
            <b:widget-setting name='sorting'>NONE</b:widget-setting>
            <b:widget-setting name='text-1'>Free Vector</b:widget-setting>
            <b:widget-setting name='link-1'>https://trickbd-template.blogspot.com/search/label/Free%20Vector</b:widget-setting>
            <b:widget-setting name='text-0'>Home</b:widget-setting>
            <b:widget-setting name='link-2'>https://trickbd-template.blogspot.com/search/label/Life%20Style</b:widget-setting>
            <b:widget-setting name='text-3'>Tech News</b:widget-setting>
            <b:widget-setting name='link-0'>/</b:widget-setting>
            <b:widget-setting name='text-2'>Life Style</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main'>
            <b:include name='content'/>
          </b:includable>
          <b:includable id='content'>
            <nav class='m_menu'>
              <ul>
                <b:loop values='data:links' var='link'>
                  <li><a expr:href='data:link.target'><data:link.name/></a></li>
                </b:loop>
                <li class='search'>
                  <a href='#'><i class='fa fa-search'/></a>
                  <form expr:action='data:blog.searchUrl'>
                    <input autocomplete='off' name='q' placeholder='খুঁজুন' type='search' value=''/>
                  </form>
                </li>
              </ul>
            </nav>
          </b:includable>
        </b:widget>
      </b:section>
    </div>
      <a class='scroll_top' href='#' style='display: none;'><i class='fa fa-angle-up'/></a>
    </header>
    
    <b:if cond='data:view.isPost'>
      <b:section id='display_posts' maxwidgets='1' name='Display Posts' showaddelement='yes'>
        <b:widget id='Blog2' locked='true' title='Blog Posts' type='Blog' version='2' visible='true'>
          <b:widget-settings>
            <b:widget-setting name='showDateHeader'>false</b:widget-setting>
            <b:widget-setting name='style.textcolor'>#ffffff</b:widget-setting>
            <b:widget-setting name='showShareButtons'>false</b:widget-setting>
            <b:widget-setting name='showCommentLink'>true</b:widget-setting>
            <b:widget-setting name='style.urlcolor'>#ffffff</b:widget-setting>
            <b:widget-setting name='showAuthor'>true</b:widget-setting>
            <b:widget-setting name='style.linkcolor'>#ffffff</b:widget-setting>
            <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
            <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
            <b:widget-setting name='reactionsLabel'/>
            <b:widget-setting name='showAuthorProfile'>false</b:widget-setting>
            <b:widget-setting name='style.layout'>1x1</b:widget-setting>
            <b:widget-setting name='showLabels'>true</b:widget-setting>
            <b:widget-setting name='showLocation'>true</b:widget-setting>
            <b:widget-setting name='showTimestamp'>true</b:widget-setting>
            <b:widget-setting name='postsPerAd'>1</b:widget-setting>
            <b:widget-setting name='showBacklinks'>false</b:widget-setting>
            <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
            <b:widget-setting name='showInlineAds'>false</b:widget-setting>
            <b:widget-setting name='showReactions'>false</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main' var='this'>
    <b:loop index='i' values='data:posts' var='post'>
<section class='single_head'>
  <div class='mid sp_flex'>
    <div class='image'>
      <img class='main_img' expr:alt='data:post.title' expr:src='data:post.featuredImage'/>
      <img alt='' class='fold' src='https://lh3.googleusercontent.com/-0VN90Al_a9U/YfFTXN02zcI/AAAAAAAABAE/kLSgYbmXC7YlKNXzO-2QQZ9CvmsgQhyfACNcBGAsYHQ/s16000/image.png'/>
    </div>
    <div class='content'>
      <span class='cat'><a expr:href='data:post.labels.first.url' expr:title='&quot;Archive by category &quot; + data:post.labels.first.name' rel='category tag'><data:post.labels.first.name/></a></span>
      <h1><a href='#single_post_content'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></a></h1>
      <div class='author_dtails'>
        <div class='auth_img'>
          <img alt='' class='avatar avatar-150 photo' expr:src='data:post.author.authorPhoto.image ? resizeImage(data:post.author.authorPhoto.image, 150, &quot;1:1&quot;) : &quot;https://4.bp.blogspot.com/-oSjP8F09qxo/Wy1J9dp7b0I/AAAAAAAACF0/ggcRfLCFQ9s2SSaeL9BFSE2wyTYzQaTyQCK4BGAYYCw/s72-c/avatar.jpg&quot;' height='150' loading='lazy' width='150'/> 
        </div>
        <div class='auth_desc'>
          <h4><a expr:href='data:post.author.profileUrl' expr:title='&quot;Posted by &quot;+data:post.author.name' rel='author'><data:post.author.name/></a></h4>
          <ul class='auth_links'/>
        </div>
      </div>
      <ul class='post_infos'>
        <li>
          <a href='#'><i class='fa fa-calendar'/> <data:post.date/></a>
        </li>
        <li>
          <a href='#'><i class='fa fa-comment'/> <data:post.numberOfComments/></a>
        </li>
      </ul>
    </div>
  </div>
</section>
    </b:loop>
</b:includable>
          <b:includable id='aboutPostAuthor'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='addComments'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='blogThisShare'>
  <b:with value='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
          <b:includable id='bylineByName' var='byline'>
  <b:switch var='data:byline.name'>
  <b:case value='share'/>
    <b:include cond='data:post.shareUrl' name='postShareButtons'/>
  <b:case value='comments'/>
    <b:include cond='data:post.allowComments' name='postCommentsLink'/>
  <b:case value='location'/>
    <b:include cond='data:post.location' name='postLocation'/>
  <b:case value='timestamp'/>
    <b:include cond='not data:view.isPage' name='postTimestamp'/>
  <b:case value='author'/>
    <b:include name='postAuthor'/>
  <b:case value='labels'/>
    <b:include cond='data:post.labels' name='postLabels'/>
  <b:case value='icons'/>
    <b:include cond='data:post.emailPostUrl' name='emailPostIcon'/>
  </b:switch>
</b:includable>
          <b:includable id='bylineRegion' var='regionItems'>
  <b:loop values='data:regionItems' var='byline'>
    <b:include data='byline' name='bylineByName'/>
  </b:loop>
</b:includable>
          <b:includable id='commentAuthorAvatar'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='commentDeleteIcon' var='comment'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='commentForm' var='post'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='commentFormIframeSrc' var='post'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='commentItem' var='comment'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='commentList' var='comments'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='commentPicker' var='post'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='comments' var='post'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='commentsLink'>
  <a class='comment-link' expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
    <b:if cond='data:post.numberOfComments &gt; 0'>
      <b:message name='messages.numberOfComments'>
        <b:param expr:value='data:post.numberOfComments' name='numComments'/>
      </b:message>
    <b:else/>
      <data:messages.postAComment/>
    </b:if>
  </a>
</b:includable>
          <b:includable id='commentsLinkIframe'>
  <!-- G+ comments, no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
          <b:includable id='commentsTitle'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='defaultAdUnit'>
  <ins class='adsbygoogle' data-ad-format='auto' expr:data-ad-client='data:adClientId ?: data:blog.adsenseClientId' expr:data-ad-host='data:blog.adsenseHostId' expr:data-analytics-uacct='data:blog.analyticsAccountNumber' expr:style='data:style ?: &quot;display: block;&quot;'/>
  <script>
   (adsbygoogle = window.adsbygoogle || []).push({});
  </script>
</b:includable>
          <b:includable id='emailPostIcon'>
  <span class='byline post-icons'>
    <!-- email post links -->
    <span class='item-action'>
      <a expr:href='data:post.emailPostUrl' expr:title='data:messages.emailPost'>
        <b:include data='{ iconClass: &quot;touch-icon sharing-icon&quot; }' name='emailIcon'/>
      </a>
    </span>
  </span>
</b:includable>
          <b:includable id='facebookShare'>
  <b:with value='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
          <b:includable id='feedLinks'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='feedLinksBody' var='links'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='footerBylines'>
  <b:if cond='data:widgets.Blog.first.footerBylines'>
    <b:loop index='i' values='data:widgets.Blog.first.footerBylines' var='region'>
      <b:if cond='not data:region.items.empty'>
        <div expr:class='&quot;post-footer-line post-footer-line-&quot; + (data:i + 1)'>
          <b:with value='&quot;footer-&quot; + (data:i + 1)' var='regionName'>
            <b:include data='region.items' name='bylineRegion'/>
          </b:with>
        </div>
      </b:if>
    </b:loop>
  </b:if>
</b:includable>
          <b:includable id='googlePlusShare'>
  <div class='goog-inline-block google-plus-share-container'>
    <g:plusone annotation='inline' expr:href='data:originalUrl.canonical.http' size='medium' source='blogger:blog:plusone'/>
  </div>
</b:includable>
          <b:includable id='headerByline'>
  <b:if cond='data:widgets.Blog.first.headerByline'>
    <div class='post-header'>
      <div class='post-header-line-1'>
        <b:with value='&quot;header-1&quot;' var='regionName'>
          <b:include data='data:widgets.Blog.first.headerByline.items' name='bylineRegion'/>
        </b:with>
      </div>
    </div>
  </b:if>
</b:includable>
          <b:includable id='homePageLink'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='iframeComments' var='post'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='inlineAd' var='post'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='linkShare'>
  <b:with value='&quot;window.prompt(\&quot;Copy to clipboard: Ctrl+C, Enter\&quot;, \&quot;&quot; + data:originalUrl + &quot;\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
          <b:includable id='nextPageLink'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='otherSharingButton'>
  <span class='sharing-platform-button sharing-element-other' expr:aria-label='data:messages.shareToOtherApps.escaped' expr:data-url='data:originalUrl' expr:title='data:messages.shareToOtherApps.escaped' role='menuitem' tabindex='-1'>
    <b:with value='{key: &quot;sharingOther&quot;}' var='platform'>
      <b:include name='sharingPlatformIcon'/>
    </b:with>
    <span class='platform-sharing-text'><data:messages.shareOtherApps.escaped/></span>
  </span>
</b:includable>
          <b:includable id='platformShare'>
  <a expr:class='&quot;goog-inline-block sharing-&quot; + data:platform.key' expr:data-url='data:originalUrl' expr:href='data:shareUrl + &quot;&amp;target=&quot; + data:platform.target' expr:onclick='data:onclick ? data:onclick : &quot;&quot;' expr:title='data:platform.shareMessage' target='_blank'>
    <span class='share-button-link-text'>
      <data:platform.shareMessage/>
    </span>
  </a>
</b:includable>
          <b:includable id='post' var='post'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='postAuthor'>
  <span class='byline post-author vcard'>
    <span class='post-author-label'>
      <data:byline.label/>
    </span>
    <span class='fn'>
      <b:if cond='data:post.author.profileUrl'>
        <meta expr:content='data:post.author.profileUrl'/>
        <a class='g-profile' expr:href='data:post.author.profileUrl' rel='author' title='author profile'>
          <span><data:post.author.name/></span>
        </a>
      <b:else/>
        <span><data:post.author.name/></span>
      </b:if>
    </span>
  </span>
</b:includable>
          <b:includable id='postBody' var='post'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='postBodySnippet' var='post'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='postCommentsAndAd' var='post'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='postCommentsLink'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='postFooter' var='post'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='postFooterAuthorProfile' var='post'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='postHeader' var='post'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='postJumpLink' var='post'>
  <div class='jump-link flat-button'>
    <a expr:href='data:post.url fragment &quot;more&quot;' expr:title='data:post.title'>
      <b:eval expr='data:blog.jumpLinkMessage'/>
    </a>
  </div>
</b:includable>
          <b:includable id='postLabels'>
  <span class='byline post-labels'>
    <span class='byline-label'><data:byline.label/></span>
    <b:loop index='i' values='data:post.labels' var='label'>
      <a expr:href='data:label.url' rel='tag'>
        <data:label.name/>
      </a>
    </b:loop>
  </span>
</b:includable>
          <b:includable id='postLocation'>
  <span class='byline post-location'>
    <data:byline.label/>
    <a expr:href='data:post.location.mapsUrl' target='_blank'><data:post.location.name/></a>
  </span>
</b:includable>
          <b:includable id='postMeta' var='post'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='postMetadataJSONImage'>
  &quot;image&quot;: {
    &quot;@type&quot;: &quot;ImageObject&quot;,
    <b:if cond='data:post.featuredImage.isResizable'>
    &quot;url&quot;: &quot;<b:eval expr='resizeImage(data:post.featuredImage, 1200, &quot;1200:630&quot;)'/>&quot;,
    &quot;height&quot;: 630,
    &quot;width&quot;: 1200
    <b:else/>
    &quot;url&quot;: &quot;https://lh3.googleusercontent.com/ULB6iBuCeTVvSjjjU1A-O8e9ZpVba6uvyhtiWRti_rBAs9yMYOFBujxriJRZ-A=w1200&quot;,
    &quot;height&quot;: 348,
    &quot;width&quot;: 1200
    </b:if>
  },
</b:includable>
          <b:includable id='postMetadataJSONPublisher'>
 &quot;publisher&quot;: {
    &quot;@type&quot;: &quot;Organization&quot;,
    &quot;name&quot;: &quot;Blogger&quot;,
    &quot;logo&quot;: {
      &quot;@type&quot;: &quot;ImageObject&quot;,
      &quot;url&quot;: &quot;https://lh3.googleusercontent.com/ULB6iBuCeTVvSjjjU1A-O8e9ZpVba6uvyhtiWRti_rBAs9yMYOFBujxriJRZ-A=h60&quot;,
      &quot;width&quot;: 206,
      &quot;height&quot;: 60
    }
  },
</b:includable>
          <b:includable id='postPagination'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='postReactions'>
  <!-- Reaction feature no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
          <b:includable id='postShareButtons'>
  <div class='byline post-share-buttons goog-inline-block'>
    <b:with value='data:sharingId ?: ((data:widget.instanceId ?: &quot;sharing&quot;) + &quot;-&quot; + (data:regionName ?: &quot;byline&quot;) + &quot;-&quot; + data:post.id)' var='sharingId'>
      <!-- Note: 'sharingButtons' includable is from the default Sharing widget markup. -->
      <b:include data='{                                                sharingId: data:sharingId,                                                originalUrl: data:post.url,                                                platforms: data:this.sharing.platforms,                                                shareUrl: data:post.shareUrl,                                                shareTitle: data:post.title,                                              }' name='sharingButtons'/>
    </b:with>
  </div>
</b:includable>
          <b:includable id='postTimestamp'>
  <span class='byline post-timestamp'>
    <data:byline.label/>
    <b:if cond='data:post.url'>
      <meta expr:content='data:post.url.canonical'/>
      <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'>
        <time class='published' expr:datetime='data:post.date.iso8601' expr:title='data:post.date.iso8601'>
          <data:post.date/>
        </time>
      </a>
    </b:if>
  </span>
</b:includable>
          <b:includable id='postTitle' var='post'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='previousPageLink'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='sharingButton'>
  <span expr:aria-label='data:platform.shareMessage' expr:class='&quot;sharing-platform-button sharing-element-&quot; + data:platform.key' expr:data-href='data:shareUrl + &quot;&amp;target=&quot; + data:platform.target' expr:data-url='data:originalUrl' expr:title='data:platform.shareMessage' role='menuitem' tabindex='-1'>
    <b:include name='sharingPlatformIcon'/>
    <span class='platform-sharing-text'><data:platform.name/></span>
  </span>
</b:includable>
          <b:includable id='sharingButtonContent'>
  <div class='flat-icon-button ripple'>
    <b:include name='shareIcon'/>
  </div>
</b:includable>
          <b:includable id='sharingButtons'>
  <div class='sharing' expr:aria-owns='&quot;sharing-popup-&quot; + data:sharingId' expr:data-title='data:shareTitle'>
    <button class='sharing-button touch-icon-button' expr:aria-controls='&quot;sharing-popup-&quot; + data:sharingId' expr:aria-label='data:messages.share.escaped' expr:id='&quot;sharing-button-&quot; + data:sharingId' role='button'>
      <b:include name='sharingButtonContent'/>
    </button>
    <b:include name='sharingButtonsMenu'/>
  </div>
</b:includable>
          <b:includable id='sharingButtonsMenu'>
  <div class='share-buttons-container'>
    <ul aria-hidden='true' class='share-buttons hidden' expr:aria-label='data:messages.share.escaped' expr:id='&quot;sharing-popup-&quot; + data:sharingId' role='menu'>
      <b:loop values='(data:platforms ?: data:blog.sharing.platforms) filter (p =&gt; p.key not in {&quot;blogThis&quot;})' var='platform'>
        <li>
          <b:include name='sharingButton'/>
        </li>
      </b:loop>
      <li aria-hidden='true' class='hidden'>
        <b:include name='otherSharingButton'/>
      </li>
    </ul>
  </div>
</b:includable>
          <b:includable id='sharingPlatformIcon'>
  <b:include data='{ iconClass: (&quot;touch-icon sharing-&quot; + data:platform.key) }' expr:name='data:platform.key + &quot;Icon&quot;'/>
</b:includable>
          <b:includable id='threadedCommentForm' var='post'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='threadedCommentJs' var='post'><b:comment>Replaced</b:comment></b:includable>
          <b:includable id='threadedComments' var='post'><b:comment>Replaced</b:comment></b:includable>
        </b:widget>
      </b:section>
        
        
    </b:if>
  
  
    <div id='trickbd-app'>
      <b:if cond='data:view.isHomepage'>
        
<b:section id='popular_ar_item' maxwidgets='1' name='Popular Posts' showaddelement='no'>
  <b:widget id='PopularPosts1' locked='true' title='Populer' type='PopularPosts' version='2' visible='true'>
    <b:widget-settings>
      <b:widget-setting name='numItemsToShow'>10</b:widget-setting>
      <b:widget-setting name='showThumbnails'>true</b:widget-setting>
      <b:widget-setting name='showSnippets'>true</b:widget-setting>
      <b:widget-setting name='timeRange'>LAST_MONTH</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main' var='this'>
<section class='main_slider'>
   <div class='slider'>
     <b:loop values='data:posts filter (p =&gt; p.id != data:view.postId)' var='post'>
              <div class='mid'>
         <div class='slide'>
            <div class='sl_text'>
               <h6>
                  <a expr:href='data:post.labels.first.url' expr:title='&quot;Archive by category &quot; + data:post.labels.first.name'><data:post.labels.first.name/></a> <span class='triangle'/>
               </h6>
               <h3>
                  <a expr:href='data:post.url.canonical'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></a>
               </h3>
               <p><b:eval expr='data:post.snippets.long snippet { length: 230 }'/></p>
               <a class='more' expr:href='data:post.url.canonical'>Read More</a>
            </div>
            <div class='sl_img'>
               <img class='' expr:alt='data:post.title ? data:post.title : data:messages.noTitle' expr:src='data:post.featuredImage'/> 
            </div>
         </div>
      </div>
      </b:loop>
   </div>
   <a class='down' href='#scroll_fture'><i class='fa fa-angle-down'/></a>
</section>
    </b:includable>
    <b:includable id='blogThisShare'>
  <b:with value='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
    <b:includable id='bylineByName' var='byline'>
  <b:switch var='data:byline.name'>
  <b:case value='share'/>
    <b:include cond='data:post.shareUrl' name='postShareButtons'/>
  <b:case value='comments'/>
    <b:include cond='data:post.allowComments' name='postCommentsLink'/>
  <b:case value='location'/>
    <b:include cond='data:post.location' name='postLocation'/>
  <b:case value='timestamp'/>
    <b:include cond='not data:view.isPage' name='postTimestamp'/>
  <b:case value='author'/>
    <b:include name='postAuthor'/>
  <b:case value='labels'/>
    <b:include cond='data:post.labels' name='postLabels'/>
  <b:case value='icons'/>
    <b:include cond='data:post.emailPostUrl' name='emailPostIcon'/>
  </b:switch>
</b:includable>
    <b:includable id='bylineRegion' var='regionItems'>
  <b:loop values='data:regionItems' var='byline'>
    <b:include data='byline' name='bylineByName'/>
  </b:loop>
</b:includable>
    <b:includable id='commentsLink'>
  <a class='comment-link' expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
    <b:if cond='data:post.numberOfComments &gt; 0'>
      <b:message name='messages.numberOfComments'>
        <b:param expr:value='data:post.numberOfComments' name='numComments'/>
      </b:message>
    <b:else/>
      <data:messages.postAComment/>
    </b:if>
  </a>
</b:includable>
    <b:includable id='commentsLinkIframe'>
  <!-- G+ comments, no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
    <b:includable id='emailPostIcon'>
  <span class='byline post-icons'>
    <!-- email post links -->
    <span class='item-action'>
      <a expr:href='data:post.emailPostUrl' expr:title='data:messages.emailPost'>
        <b:include data='{ iconClass: &quot;touch-icon sharing-icon&quot; }' name='emailIcon'/>
      </a>
    </span>
  </span>
</b:includable>
    <b:includable id='facebookShare'>
  <b:with value='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
    <b:includable id='footerBylines'>
  <b:if cond='data:widgets.Blog.first.footerBylines'>
    <b:loop index='i' values='data:widgets.Blog.first.footerBylines' var='region'>
      <b:if cond='not data:region.items.empty'>
        <div expr:class='&quot;post-footer-line post-footer-line-&quot; + (data:i + 1)'>
          <b:with value='&quot;footer-&quot; + (data:i + 1)' var='regionName'>
            <b:include data='region.items' name='bylineRegion'/>
          </b:with>
        </div>
      </b:if>
    </b:loop>
  </b:if>
</b:includable>
    <b:includable id='googlePlusShare'>
  <div class='goog-inline-block google-plus-share-container'>
    <g:plusone annotation='inline' expr:href='data:originalUrl.canonical.http' size='medium' source='blogger:blog:plusone'/>
  </div>
</b:includable>
    <b:includable id='headerByline'>
  <b:if cond='data:widgets.Blog.first.headerByline'>
    <div class='post-header'>
      <div class='post-header-line-1'>
        <b:with value='&quot;header-1&quot;' var='regionName'>
          <b:include data='data:widgets.Blog.first.headerByline.items' name='bylineRegion'/>
        </b:with>
      </div>
    </div>
  </b:if>
</b:includable>
    <b:includable id='linkShare'>
  <b:with value='&quot;window.prompt(\&quot;Copy to clipboard: Ctrl+C, Enter\&quot;, \&quot;&quot; + data:originalUrl + &quot;\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
    <b:includable id='otherSharingButton'>
  <span class='sharing-platform-button sharing-element-other' expr:aria-label='data:messages.shareToOtherApps.escaped' expr:data-url='data:originalUrl' expr:title='data:messages.shareToOtherApps.escaped' role='menuitem' tabindex='-1'>
    <b:with value='{key: &quot;sharingOther&quot;}' var='platform'>
      <b:include name='sharingPlatformIcon'/>
    </b:with>
    <span class='platform-sharing-text'><data:messages.shareOtherApps.escaped/></span>
  </span>
</b:includable>
    <b:includable id='platformShare'>
  <a expr:class='&quot;goog-inline-block sharing-&quot; + data:platform.key' expr:data-url='data:originalUrl' expr:href='data:shareUrl + &quot;&amp;target=&quot; + data:platform.target' expr:onclick='data:onclick ? data:onclick : &quot;&quot;' expr:title='data:platform.shareMessage' target='_blank'>
    <span class='share-button-link-text'>
      <data:platform.shareMessage/>
    </span>
  </a>
</b:includable>
    <b:includable id='postAuthor'>
  <span class='byline post-author vcard'>
    <span class='post-author-label'>
      <data:byline.label/>
    </span>
    <span class='fn'>
      <b:if cond='data:post.author.profileUrl'>
        <meta expr:content='data:post.author.profileUrl'/>
        <a class='g-profile' expr:href='data:post.author.profileUrl' rel='author' title='author profile'>
          <span><data:post.author.name/></span>
        </a>
      <b:else/>
        <span><data:post.author.name/></span>
      </b:if>
    </span>
  </span>
</b:includable>
    <b:includable id='postCommentsLink'>
  <span class='byline post-comment-link container'>
    <b:include cond='data:post.commentSource != 1' name='commentsLink'/>
  </span>
</b:includable>
    <b:includable id='postJumpLink' var='post'>
  <div class='jump-link flat-button'>
    <a expr:href='data:post.url fragment &quot;more&quot;' expr:title='data:post.title'>
      <b:eval expr='data:blog.jumpLinkMessage'/>
    </a>
  </div>
</b:includable>
    <b:includable id='postLabels'>
  <span class='byline post-labels'>
    <span class='byline-label'><data:byline.label/></span>
    <b:loop index='i' values='data:post.labels' var='label'>
      <a expr:href='data:label.url' rel='tag'>
        <data:label.name/>
      </a>
    </b:loop>
  </span>
</b:includable>
    <b:includable id='postLocation'>
  <span class='byline post-location'>
    <data:byline.label/>
    <a expr:href='data:post.location.mapsUrl' target='_blank'><data:post.location.name/></a>
  </span>
</b:includable>
    <b:includable id='postReactions'>
  <!-- Reaction feature no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
    <b:includable id='postShareButtons'>
  <div class='byline post-share-buttons goog-inline-block'>
    <b:with value='data:sharingId ?: ((data:widget.instanceId ?: &quot;sharing&quot;) + &quot;-&quot; + (data:regionName ?: &quot;byline&quot;) + &quot;-&quot; + data:post.id)' var='sharingId'>
      <!-- Note: 'sharingButtons' includable is from the default Sharing widget markup. -->
      <b:include data='{                                                sharingId: data:sharingId,                                                originalUrl: data:post.url,                                                platforms: data:this.sharing.platforms,                                                shareUrl: data:post.shareUrl,                                                shareTitle: data:post.title,                                              }' name='sharingButtons'/>
    </b:with>
  </div>
</b:includable>
    <b:includable id='postTimestamp'>
  <span class='byline post-timestamp'>
    <data:byline.label/>
    <b:if cond='data:post.url'>
      <meta expr:content='data:post.url.canonical'/>
      <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'>
        <time class='published' expr:datetime='data:post.date.iso8601' expr:title='data:post.date.iso8601'>
          <data:post.date/>
        </time>
      </a>
    </b:if>
  </span>
</b:includable>
    <b:includable id='sharingButton'>
  <span expr:aria-label='data:platform.shareMessage' expr:class='&quot;sharing-platform-button sharing-element-&quot; + data:platform.key' expr:data-href='data:shareUrl + &quot;&amp;target=&quot; + data:platform.target' expr:data-url='data:originalUrl' expr:title='data:platform.shareMessage' role='menuitem' tabindex='-1'>
    <b:include name='sharingPlatformIcon'/>
    <span class='platform-sharing-text'><data:platform.name/></span>
  </span>
</b:includable>
    <b:includable id='sharingButtonContent'>
  <div class='flat-icon-button ripple'>
    <b:include name='shareIcon'/>
  </div>
</b:includable>
    <b:includable id='sharingButtons'>
  <div class='sharing' expr:aria-owns='&quot;sharing-popup-&quot; + data:sharingId' expr:data-title='data:shareTitle'>
    <button class='sharing-button touch-icon-button' expr:aria-controls='&quot;sharing-popup-&quot; + data:sharingId' expr:aria-label='data:messages.share.escaped' expr:id='&quot;sharing-button-&quot; + data:sharingId' role='button'>
      <b:include name='sharingButtonContent'/>
    </button>
    <b:include name='sharingButtonsMenu'/>
  </div>
</b:includable>
    <b:includable id='sharingButtonsMenu'>
  <div class='share-buttons-container'>
    <ul aria-hidden='true' class='share-buttons hidden' expr:aria-label='data:messages.share.escaped' expr:id='&quot;sharing-popup-&quot; + data:sharingId' role='menu'>
      <b:loop values='(data:platforms ?: data:blog.sharing.platforms) filter (p =&gt; p.key not in {&quot;blogThis&quot;})' var='platform'>
        <li>
          <b:include name='sharingButton'/>
        </li>
      </b:loop>
      <li aria-hidden='true' class='hidden'>
        <b:include name='otherSharingButton'/>
      </li>
    </ul>
  </div>
</b:includable>
    <b:includable id='sharingPlatformIcon'>
  <b:include data='{ iconClass: (&quot;touch-icon sharing-&quot; + data:platform.key) }' expr:name='data:platform.key + &quot;Icon&quot;'/>
</b:includable>
    <b:includable id='snippetedPostByline'>
  <b:with value='(data:widgets first (w =&gt; w.type == &quot;Blog&quot;)).allBylineItems' var='blogBylines'>
    <div class='item-byline'>
      <b:with value='data:blogBylines first (i =&gt; i.name == &quot;author&quot;)' var='byline'>
        <b:include cond='data:byline and data:this.postDisplay.showAuthor' data='post' name='postAuthor'/>
      </b:with>
      <b:with value='data:blogBylines first (i =&gt; i.name == &quot;timestamp&quot;)' var='byline'>
        <b:include cond='data:byline and data:this.postDisplay.showDate' data='post' name='postTimestamp'/>
      </b:with>
    </div>
  </b:with>
</b:includable>
    <b:includable id='snippetedPostContent'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPostThumbnail'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPostTitle'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPosts'><b:comment>Replaced</b:comment></b:includable>
  </b:widget>
</b:section>


        
      </b:if>
        <section class='full_post_area recent_posts'>
          <b:if cond='data:view.isHomepage'>
            <h2 class='h_middle' id='scroll_fture'>Latest Posts</h2>
          </b:if>
          <b:if cond='data:view.isPage'>
            <b:loop values='data:widgets.Blog.first.posts' var='post'>
  				<h2 class='h_middle' id='scroll_fture'><data:post.title/></h2>
			</b:loop>
          </b:if>
          <b:if cond='data:view.isLabelSearch || data:view.isSearch'>
            <h2 class='h_middle' id='scroll_fture'><data:view.search.resultsMessageHtml/></h2>
          </b:if>
            <div class='mid has_sidebar'>
              <b:section class='col_2 posts' id='main_posts' maxwidgets='1' name='Main Posts' showaddelement='no'>
                <b:widget id='Blog1' locked='true' title='Blog Posts' type='Blog' version='2' visible='true'>
                  <b:widget-settings>
                    <b:widget-setting name='commentLabel'>Post a Comment</b:widget-setting>
                    <b:widget-setting name='showShareButtons'>false</b:widget-setting>
                    <b:widget-setting name='authorLabel'>Diposkan oleh</b:widget-setting>
                    <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
                    <b:widget-setting name='timestampLabel'>pada tanggal</b:widget-setting>
                    <b:widget-setting name='reactionsLabel'/>
                    <b:widget-setting name='showAuthorProfile'>false</b:widget-setting>
                    <b:widget-setting name='style.layout'>1x1</b:widget-setting>
                    <b:widget-setting name='showLocation'>false</b:widget-setting>
                    <b:widget-setting name='showTimestamp'>true</b:widget-setting>
                    <b:widget-setting name='postsPerAd'>1</b:widget-setting>
                    <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
                    <b:widget-setting name='showDateHeader'>false</b:widget-setting>
                    <b:widget-setting name='style.textcolor'>#ffffff</b:widget-setting>
                    <b:widget-setting name='showCommentLink'>true</b:widget-setting>
                    <b:widget-setting name='style.urlcolor'>#ffffff</b:widget-setting>
                    <b:widget-setting name='postLocationLabel'>Lokasi:</b:widget-setting>
                    <b:widget-setting name='showAuthor'>true</b:widget-setting>
                    <b:widget-setting name='style.linkcolor'>#ffffff</b:widget-setting>
                    <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
                    <b:widget-setting name='showLabels'>false</b:widget-setting>
                    <b:widget-setting name='postLabelsLabel'>Tags</b:widget-setting>
                    <b:widget-setting name='showBacklinks'>false</b:widget-setting>
                    <b:widget-setting name='showInlineAds'>false</b:widget-setting>
                    <b:widget-setting name='showReactions'>false</b:widget-setting>
                  </b:widget-settings>
                  <b:includable id='main' var='this'>
                    <link href='https://www.priyotrick.com/' rel='dofollow'/>
                    <b:include cond='data:view.isMultipleItems' name='searchMessage'/>
    <div class='featured_post'>
      <b:if cond='data:view.isError'>
        <article class='art-item'>
          <div class='main_content'><h2>404: Page Not Found</h2></div>
        </article>
		</b:if>
      <b:loop index='i' values='data:posts' var='post'>
        <b:include data='post' name='postCommentsAndAd'/>
      </b:loop>
    </div>
    <b:include cond='data:view.isMultipleItems' name='postPagination'/>
  </b:includable>
                  <b:includable id='aboutPostAuthor'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='addComments'>
  <a expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
    <b:message name='messages.postAComment'/>
  </a>
</b:includable>
                  <b:includable id='backlinkDeleteIcon' var='backlink'/>
                  <b:includable id='backlinks' var='post'/>
                  <b:includable id='blogThisShare'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='bylineByName' var='byline'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='bylineRegion' var='regionItems'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <h4 id='comment-post-message'>
        <a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'><data:postCommentMsg/></a></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <h4 id='comment-post-message'><data:postCommentMsg/></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
                  <b:includable id='commentAuthorAvatar'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='commentDeleteIcon' var='comment'>
  <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
    <b:if cond='data:showCmtPopup'>
      <div class='goog-toggle-button'>
        <div class='goog-inline-block comment-action-icon'/>
      </div>
    <b:else/>
      <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:messages.deleteComment'>
        <img src='https://resources.blogblog.com/img/icon_delete13.gif'/>
      </a>
    </b:if>
  </span>
</b:includable>
                  <b:includable id='commentForm' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <h4 id='comment-post-message'><data:messages.postAComment/></h4>
    <b:if cond='data:this.messages.blogComment != &quot;&quot;'>
      <p><data:this.messages.blogComment/></p>
    </b:if>
    <b:include data='post' name='commentFormIframeSrc'/>
    <iframe allowtransparency='allowtransparency' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight ?: &quot;90px&quot;' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
                  <b:includable id='commentFormIframeSrc' var='post'>
    <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
  </b:includable>
                  <b:includable id='commentItem' var='comment'>
  <div class='comment' expr:id='&quot;c&quot; + data:comment.id'>
    <b:include cond='data:blog.enabledCommentProfileImages' name='commentAuthorAvatar'/>

    <div class='comment-block'>
      <div class='comment-author'>
        <b:if cond='data:comment.authorUrl'>
          <b:message name='messages.authorSaidWithLink'>
            <b:param expr:value='data:comment.author' name='authorName'/>
            <b:param expr:value='data:comment.authorUrl' name='authorUrl'/>
          </b:message>
        <b:else/>
          <b:message name='messages.authorSaid'>
            <b:param expr:value='data:comment.author' name='authorName'/>
          </b:message>
        </b:if>
      </div>
      <div expr:class='&quot;comment-body&quot; + (data:comment.isDeleted ? &quot; deleted&quot; : &quot;&quot;)'>
        <data:comment.body/>
      </div>
      <div class='comment-footer'>
        <span class='comment-timestamp'>
          <a expr:href='data:comment.url' title='comment permalink'>
            <data:comment.timestamp/>
          </a>
          <b:include data='comment' name='commentDeleteIcon'/>
        </span>
      </div>
    </div>
  </div>
</b:includable>
                  <b:includable id='commentList' var='comments'>
  <div id='comments-block'>
    <b:loop values='data:comments' var='comment'>
      <b:include data='comment' name='commentItem'/>
    </b:loop>
  </div>
</b:includable>
                  <b:includable id='commentPicker' var='post'>
  <b:if cond='data:post.showThreadedComments'>
    <b:include data='post' name='threadedComments'/>
  <b:else/>
    <b:include data='post' name='comments'/>
  </b:if>
</b:includable>
                  <b:includable id='comment_count_picker' var='post'>
  <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
    <data:post.commentLabelFull/>:
  </a>
</b:includable>
                  <b:includable id='comment_picker' var='post'>
  <b:if cond='data:post.showThreadedComments'>
    <b:include data='post' name='threaded_comments'/>
  <b:else/>
    <b:include data='post' name='comments'/>
  </b:if>
</b:includable>
                  <b:includable id='comments'>
    <div class='comments-area block_comment' id='comments'>
      <b:include data='post' name='threadedComments'/>
    </div>
  </b:includable>
                  <b:includable id='commentsLink'>
  <a class='comment-link' expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
    <b:if cond='data:post.numberOfComments &gt; 0'>
      <b:message name='messages.numberOfComments'>
        <b:param expr:value='data:post.numberOfComments' name='numComments'/>
      </b:message>
    <b:else/>
      <data:messages.postAComment/>
    </b:if>
  </a>
</b:includable>
                  <b:includable id='commentsLinkIframe'>
  <!-- G+ comments, no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
                  <b:includable id='commentsTitle'>
    <b:if cond='data:post.numberOfComments == 0'>
      <b:if cond='data:post.allowNewComments'>
        <div class='comments_count_filter'>
          <h3 class='comment-reply-title' id='reply-title'>Leave a Comment</h3>
        </div>
      </b:if>
      <b:else/>
      <b:if cond='data:post.allowComments'>
      <div class='comments_count_filter'>
        <h3>
        <i class='fa fa-comment-o'/>
        <data:post.numberOfComments/> thoughts on &quot;<span><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></span>&quot; </h3>
      </div>
      </b:if>
    </b:if>
  </b:includable>
                  <b:includable id='defaultAdUnit'>
    <ins class='adsbygoogle' data-ad-format='auto' expr:data-ad-client='data:adClientId ?: data:blog.adsenseClientId' expr:data-ad-host='data:blog.adsenseHostId' expr:data-analytics-uacct='data:blog.analyticsAccountNumber' expr:style='data:style ?: &quot;display: block;&quot;'/>
    <script>
    (adsbygoogle = window.adsbygoogle || []).push({});
    </script>
  </b:includable>
                  <b:includable id='emailPostIcon'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='facebookShare'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='feedLinks'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='feedLinksBody' var='links'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='footerBylines'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='googlePlusShare'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='headerByline'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='homePageLink'>
  <a class='home-link' expr:href='data:blog.homepageUrl'>
    <data:messages.home/>
  </a>
</b:includable>
                  <b:includable id='iframeComments' var='post'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='iframe_comments' var='post'>
  <!-- G+ comments, no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
                  <b:includable id='inlineAd' var='post'>
  <b:if cond='!data:view.isPreview'>
    <b:if cond='data:this.adCode or data:this.adClientId or data:blog.adsenseClientId'>
      <div class='inline-ad'>
        <b:if cond='data:this.adCode != &quot;&quot;'>
          <data:this.adCode/>
          <b:else/>
          <b:include cond='data:this.adClientId or data:blog.adsenseClientId' name='defaultAdUnit'/>
        </b:if>
      </div>
    </b:if>
    <b:else/>
      <div class='inline-ad'>
        <div class='inline-ad-placeholder'>
          <span><b:message name='messages.adsGoHere'/></span>
        </div>
      </div>
  </b:if>
  </b:includable>
                  <b:includable id='linkShare'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='mobile-index-post' var='post'>
  <div class='mobile-date-outer date-outer'>
    <b:if cond='data:post.dateHeader'>
      <div class='date-header'>
        <span><data:post.dateHeader/></span>
      </div>
    </b:if>

    <div class='mobile-post-outer'>
      <a expr:href='data:post.url'>
        <h3 class='mobile-index-title entry-title' itemprop='name'>
          <data:post.title/>
        </h3>

        <div class='mobile-index-arrow'>&amp;rsaquo;</div>

        <div class='mobile-index-contents'>
          <b:if cond='data:post.thumbnailUrl'>
            <div class='mobile-index-thumbnail'>
              <div class='Image'>
                <img expr:src='data:post.thumbnailUrl'/>
              </div>
            </div>
          </b:if>

          <div class='post-body'>
            <b:if cond='data:post.snippet'><data:post.snippet/></b:if>
          </div>
        </div>

        <div style='clear: both;'/>
      </a>

      <div class='mobile-index-comment'>
        <b:include cond='data:blog.pageType != &quot;static_page&quot;                          and data:post.allowComments                          and data:post.numComments != 0' data='post' name='comment_count_picker'/>
      </div>
    </div>
  </div>
</b:includable>
                  <b:includable id='mobile-main' var='top'>
    <!-- posts -->
    <div class='blog-posts hfeed'>

      <b:include data='top' name='status-message'/>

      <b:if cond='data:blog.pageType == &quot;index&quot;'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-index-post'/>
        </b:loop>
      <b:else/>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-post'/>
        </b:loop>
      </b:if>
    </div>

   <b:include name='mobile-nextprev'/>
</b:includable>
                  <b:includable id='mobile-nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <div class='mobile-link-button' id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>&amp;lsaquo;</a>
      </div>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <div class='mobile-link-button' id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>&amp;rsaquo;</a>
      </div>
    </b:if>

    <div class='mobile-link-button' id='blog-pager-home-link'>
    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>
    </div>

    <div class='mobile-desktop-link'>
      <a class='home-link' expr:href='data:desktopLinkUrl'><data:desktopLinkMsg/></a>
    </div>

  </div>
  <div class='clear'/>
</b:includable>
                  <b:includable id='mobile-post' var='post'>
  <div class='date-outer'>
    <b:if cond='data:post.dateHeader'>
      <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
    </b:if>
    <div class='date-posts'>
      <div class='post-outer'>

        <div class='post hentry uncustomized-post-template' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'>
          <b:if cond='data:post.thumbnailUrl'>
            <meta expr:content='data:post.thumbnailUrl' itemprop='image_url'/>
          </b:if>
          <meta expr:content='data:blog.blogId' itemprop='blogId'/>
          <meta expr:content='data:post.id' itemprop='postId'/>

          <a expr:name='data:post.id'/>
          <b:if cond='data:post.title'>
            <h3 class='post-title entry-title' itemprop='name'>
              <b:if cond='data:post.link'>
                <a expr:href='data:post.link'><data:post.title/></a>
              <b:elseif cond='data:post.url and data:blog.url != data:post.url'/>
                <a expr:href='data:post.url'><data:post.title/></a>
              <b:else/>
                <data:post.title/>
              </b:if>
            </h3>
          </b:if>

          <div class='post-header'>
            <div class='post-header-line-1'/>
          </div>

          <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'>
            <data:post.body/>
            <div style='clear: both;'/> <!-- clear for photos floats -->
          </div>

          <div class='post-footer'>
            <div class='post-footer-line post-footer-line-1'>
              <span class='post-author vcard'>
                <b:if cond='data:top.showAuthor'>
                  <b:if cond='data:post.authorProfileUrl'>
                    <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                      <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                      <a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                        <span itemprop='name'><data:post.author/></span>
                      </a>
                    </span>
                  <b:else/>
                    <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                      <span itemprop='name'><data:post.author/></span>
                    </span>
                  </b:if>
                </b:if>
              </span>

              <span class='post-timestamp'>
                <b:if cond='data:top.showTimestamp'>
                  <data:top.timestampLabel/>
                  <b:if cond='data:post.url'>
                    <meta expr:content='data:post.url.canonical' itemprop='url'/>
                    <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
                  </b:if>
                </b:if>
              </span>

              <span class='post-comment-link'>
                <b:include cond='data:blog.pageType not in {&quot;item&quot;,&quot;static_page&quot;}                                  and data:post.allowComments' data='post' name='comment_count_picker'/>
              </span>
            </div>

            <div class='post-footer-line post-footer-line-2'>
              <b:if cond='data:top.showMobileShare'>
                <div class='mobile-link-button goog-inline-block' id='mobile-share-button'>
                  <a href='javascript:void(0);'><data:shareMsg/></a>
                </div>
              </b:if>
            </div>

          </div>
        </div>

        <b:include cond='data:blog.pageType in {&quot;static_page&quot;,&quot;item&quot;}' data='post' name='comment_picker'/>
      </div>
    </div>
  </div>
</b:includable>
                  <b:includable id='multipleitems'>
    <b:include data='post' name='multiviewimage'/>
    <div class='f_content'>
      <b:include data='post' name='multiviewtitle'/>
      <b:include data='post' name='multiviewsnippets'/>
      <b:include data='post' name='multiviewmeta'/>
    </div>
  </b:includable>
                  <b:includable id='multiviewimage'>
    <div class='image'>
      <img expr:alt='data:post.title' expr:src='data:post.featuredImage'/>
      <span class='cat'><a expr:href='data:post.labels.first.url' expr:title='&quot;Archive by category &quot; + data:post.labels.first.name'><data:post.labels.first.name/></a></span>
    </div>
  </b:includable>
                  <b:includable id='multiviewmeta'>
    <ul>
      <li class='cat'>
        <a expr:href='data:post.labels.first.url' expr:title='&quot;Archive by category &quot; + data:post.labels.first.name'><data:post.labels.first.name/></a>
      </li>
      <li>
        <a class='user' expr:href='data:post.author.profileUrl'>
          <img class='avatar avatar-20 photo' expr:alt='data:post.author.name' expr:src='data:post.author.authorPhoto.image ? resizeImage(data:post.author.authorPhoto.image, 72, &quot;1:1&quot;) : &quot;https://4.bp.blogspot.com/-oSjP8F09qxo/Wy1J9dp7b0I/AAAAAAAACF0/ggcRfLCFQ9s2SSaeL9BFSE2wyTYzQaTyQCK4BGAYYCw/s72-c/avatar.jpg&quot;' height='20' width='20'/>
        </a>
        <a expr:href='data:post.author.profileUrl' expr:title='&quot;Posts by &quot;+data:post.author.name' rel='author'><data:post.author.name/></a> 
      </li>
      <li>
        <a expr:href='data:post.url.canonical'>
          <i class='fa fa-calendar'/>
          <data:post.date/>
        </a>
      </li>
      <li>
        <a expr:href='data:post.url.canonical'>
          <i class='fa fa-comment'/>
        </a>
        <a expr:href='data:post.url.canonical'><data:post.numberOfComments/></a>
      </li>
    </ul>
  </b:includable>
                  <b:includable id='multiviewsnippets'>
    <p class='desc'>
      <b:eval expr='data:post.snippets.long snippet { length: 230 }'/>
    </p>
  </b:includable>
                  <b:includable id='multiviewtitle'>
    <h3 class='p_title'>
      <a expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></a>
    </h3>
  </b:includable>
                  <b:includable id='nextPageLink'>
    <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:messages.olderPosts'>
      <data:messages.olderPosts/>
    </a>
  </b:includable>
                  <b:includable id='nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <span id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'><data:newerPageTitle/></a>
      </span>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <span id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'><data:olderPageTitle/></a>
      </span>
    </b:if>

    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>

    <b:if cond='data:mobileLinkUrl'>
      <div class='blog-mobile-link'>
        <a expr:href='data:mobileLinkUrl'><data:mobileLinkMsg/></a>
      </div>
    </b:if>

  </div>
  <div class='clear'/>
</b:includable>
                  <b:includable id='otherSharingButton'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='platformShare'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='post' var='post'>
  <div class='post'>
    <b:include data='post' name='postMeta'/>
    <b:include data='post' name='postTitle'/>
    <b:include name='headerByline'/>
    <b:if cond='data:view.isSingleItem'>
      <b:include data='post' name='postBody'/>
    <b:else/>
      <b:include data='post' name='postBodySnippet'/>
      <b:include data='post' name='postJumpLink'/>
    </b:if>
    <b:include data='post' name='postFooter'/>
  </div>
</b:includable>
                  <b:includable id='postAuthor'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='postBody' var='post'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='postBodySnippet' var='post'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='postCommentsAndAd' var='post'>
    <article>
      <b:class cond='data:view.isMultipleItems' name='box'/>
      <b:class cond='data:view.isSingleItem' name='art-item'/>
      <b:include cond='data:view.isMultipleItems' data='post' name='multipleitems'/>
      <b:include cond='data:view.isSingleItem' data='post' name='singleitem'/>
    </article>
    <b:include cond='data:view.isSingleItem' data='post' name='comments'/>
    <b:include cond='data:view.isMultipleItems and data:post.includeAd' data='post' name='inlineAd'/>
  </b:includable>
                  <b:includable id='postCommentsLink'>
  <b:if cond='data:view.isMultipleItems'>
    <span class='byline post-comment-link container'>
      <b:include cond='data:post.commentSource != 1' name='commentsLink'/>
    </span>
  </b:if>
</b:includable>
                  <b:includable id='postFooter' var='post'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='postFooterAuthorProfile' var='post'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='postHeader' var='post'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='postJumpLink' var='post'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='postLabels'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='postLocation'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='postMeta' var='post'>
  <b:include data='post' name='postMetadataJSON'/>
</b:includable>
                  <b:includable id='postMetadataJSONImage'>
  &quot;image&quot;: {
    &quot;@type&quot;: &quot;ImageObject&quot;,
    <b:if cond='data:post.featuredImage.isResizable'>
    &quot;url&quot;: &quot;<b:eval expr='resizeImage(data:post.featuredImage, 1200, &quot;1200:630&quot;)'/>&quot;,
    &quot;height&quot;: 630,
    &quot;width&quot;: 1200
    <b:else/>
    &quot;url&quot;: &quot;https://lh3.googleusercontent.com/ULB6iBuCeTVvSjjjU1A-O8e9ZpVba6uvyhtiWRti_rBAs9yMYOFBujxriJRZ-A=w1200&quot;,
    &quot;height&quot;: 348,
    &quot;width&quot;: 1200
    </b:if>
  },
</b:includable>
                  <b:includable id='postMetadataJSONPublisher'>
 &quot;publisher&quot;: {
    &quot;@type&quot;: &quot;Organization&quot;,
    &quot;name&quot;: &quot;Blogger&quot;,
    &quot;logo&quot;: {
      &quot;@type&quot;: &quot;ImageObject&quot;,
      &quot;url&quot;: &quot;https://lh3.googleusercontent.com/ULB6iBuCeTVvSjjjU1A-O8e9ZpVba6uvyhtiWRti_rBAs9yMYOFBujxriJRZ-A=h60&quot;,
      &quot;width&quot;: 206,
      &quot;height&quot;: 60
    }
  },
</b:includable>
                  <b:includable id='postPagination'>
     <div class='pagenav' id='blog-pager'>
        <b:include cond='data:newerPageUrl' name='previousPageLink'/>
        <b:include cond='data:olderPageUrl' name='nextPageLink'/>
    </div>
  </b:includable>
                  <b:includable id='postQuickEdit' var='post'>
  <b:if cond='data:post.editUrl'>
    <span expr:class='&quot;item-control &quot; + data:post.adminClass'>
      <a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg'>
        <img alt='' class='icon-action' height='18' src='https://resources.blogblog.com/img/icon18_edit_allbkg.gif' width='18'/>
      </a>
    </span>
  </b:if>
</b:includable>
                  <b:includable id='postReactions'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='postShareButtons'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='postTimestamp'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='postTitle' var='post'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='posttitle'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='previousPageLink'>
    <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:messages.newerPosts'>
      <data:messages.newerPosts/>
    </a>
  </b:includable>
                  <b:includable id='searchMessage'>
              <b:if cond='data:view.isMultipleItems and data:posts.empty'><div class='queryEmpty'><data:messages.noResultsFound/></div></b:if>
            </b:includable>
                  <b:includable id='shareButtons' var='post'>
  <b:if cond='data:top.showEmailButton'><a class='goog-inline-block share-button sb-email' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'><span class='share-button-link-text'><data:top.emailThisMsg/></span></a></b:if><b:if cond='data:top.showBlogThisButton'><a class='goog-inline-block share-button sb-blog' expr:href='data:post.sharePostUrl + &quot;&amp;target=blog&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' expr:title='data:top.blogThisMsg' target='_blank'><span class='share-button-link-text'><data:top.blogThisMsg/></span></a></b:if><b:if cond='data:top.showTwitterButton'><a class='goog-inline-block share-button sb-twitter' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:title='data:top.shareToTwitterMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToTwitterMsg/></span></a></b:if><b:if cond='data:top.showFacebookButton'><a class='goog-inline-block share-button sb-facebook' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToFacebookMsg/></span></a></b:if><b:if cond='data:top.showPinterestButton'><a class='goog-inline-block share-button sb-pinterest' expr:href='data:post.sharePostUrl + &quot;&amp;target=pinterest&quot;' expr:title='data:top.shareToPinterestMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToPinterestMsg/></span></a></b:if>
</b:includable>
                  <b:includable id='sharingButton'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='sharingButtonContent'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='sharingButtons'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='sharingButtonsMenu'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='sharingPlatformIcon'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='singleitem'>
    <div class='main_content'>
      <data:post.body/>
    </div>
  </b:includable>
                  <b:includable id='status-message'>
  <b:if cond='data:navMessage'>
  <div class='status-msg-wrap'>
    <div class='status-msg-body'>
      <data:navMessage/>
    </div>
    <div class='status-msg-border'>
      <div class='status-msg-bg'>
        <div class='status-msg-hidden'><data:navMessage/></div>
      </div>
    </div>
  </div>
  <div style='clear: both;'/>
  </b:if>
</b:includable>
                  <b:includable id='threaded-comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
                  <b:includable id='threadedCommentForm' var='post'>
    <div class='comment-form'>
      <a name='comment-form'/>
      <b:if cond='data:this.messages.blogComment != &quot;&quot;'>
        <p><data:this.messages.blogComment/></p>
      </b:if>
      <b:include data='post' name='commentFormIframeSrc'/>
      <iframe allowtransparency='allowtransparency' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight ?: &quot;90px&quot;' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
      <data:post.cmtfpIframe/>
      <script type='text/javascript'>
        BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
      </script>
    </div>
  </b:includable>
                  <b:includable id='threadedCommentJs' var='post'>
    <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>
    <b:template-script inline='true' name='threaded_comments'/>
    <script type='text/javascript'>
      blogger.widgets.blog.initThreadedComments(
        <data:post.commentJso/>,
        <data:post.commentMsgs/>,
        <data:post.commentConfig/>);
    </script>
  </b:includable>
                  <b:includable id='threadedComments' var='post'>
    <b:class cond='data:post.numberOfComments == &quot;0&quot;' name='no-comments'/>
    <a name='comments'/>
    <b:include name='commentsTitle'/>
    <div class='comments-content'>
      <b:if cond='data:post.embedCommentForm'>
        <b:include data='post' name='threadedCommentJs'/>
      </b:if>
      <div id='comment-holder'>
        <data:post.commentHtml/>
      </div>
    </div>
    <p class='comment-footer'>
      <b:if cond='data:post.allowNewComments'>
        <b:include data='post' name='threadedCommentForm'/>
      </b:if>
    </p>
    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='allowtransparency' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>
  </b:includable>
                  <b:includable id='threaded_comment_js' var='post'>
  <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>

  <script type='text/javascript'>
    (function() {
      var items = <data:post.commentJso/>;
      var msgs = <data:post.commentMsgs/>;
      var config = <data:post.commentConfig/>;

// <![CDATA[
      var cursor = null;
      if (items && items.length > 0) {
        cursor = parseInt(items[items.length - 1].timestamp) + 1;
      }

      var bodyFromEntry = function(entry) {
        var text = (entry &&
                    ((entry.content && entry.content.$t) ||
                     (entry.summary && entry.summary.$t))) ||
            '';
        if (entry && entry.gd$extendedProperty) {
          for (var k in entry.gd$extendedProperty) {
            if (entry.gd$extendedProperty[k].name == 'blogger.contentRemoved') {
              return '<span class="deleted-comment">' + text + '</span>';
            }
          }
        }
        return text;
      }

      var parse = function(data) {
        cursor = null;
        var comments = [];
        if (data && data.feed && data.feed.entry) {
          for (var i = 0, entry; entry = data.feed.entry[i]; i++) {
            var comment = {};
            // comment ID, parsed out of the original id format
            var id = /blog-(\d+).post-(\d+)/.exec(entry.id.$t);
            comment.id = id ? id[2] : null;
            comment.body = bodyFromEntry(entry);
            comment.timestamp = Date.parse(entry.published.$t) + '';
            if (entry.author && entry.author.constructor === Array) {
              var auth = entry.author[0];
              if (auth) {
                comment.author = {
                  name: (auth.name ? auth.name.$t : undefined),
                  profileUrl: (auth.uri ? auth.uri.$t : undefined),
                  avatarUrl: (auth.gd$image ? auth.gd$image.src : undefined)
                };
              }
            }
            if (entry.link) {
              if (entry.link[2]) {
                comment.link = comment.permalink = entry.link[2].href;
              }
              if (entry.link[3]) {
                var pid = /.*comments\/default\/(\d+)\?.*/.exec(entry.link[3].href);
                if (pid && pid[1]) {
                  comment.parentId = pid[1];
                }
              }
            }
            comment.deleteclass = 'item-control blog-admin';
            if (entry.gd$extendedProperty) {
              for (var k in entry.gd$extendedProperty) {
                if (entry.gd$extendedProperty[k].name == 'blogger.itemClass') {
                  comment.deleteclass += ' ' + entry.gd$extendedProperty[k].value;
                } else if (entry.gd$extendedProperty[k].name == 'blogger.displayTime') {
                  comment.displayTime = entry.gd$extendedProperty[k].value;
                }
              }
            }
            comments.push(comment);
          }
        }
        return comments;
      };

      var paginator = function(callback) {
        if (hasMore()) {
          var url = config.feed + '?alt=json&v=2&orderby=published&reverse=false&max-results=50';
          if (cursor) {
            url += '&published-min=' + new Date(cursor).toISOString();
          }
          window.bloggercomments = function(data) {
            var parsed = parse(data);
            cursor = parsed.length < 50 ? null
                : parseInt(parsed[parsed.length - 1].timestamp) + 1
            callback(parsed);
            window.bloggercomments = null;
          }
          url += '&callback=bloggercomments';
          var script = document.createElement('script');
          script.type = 'text/javascript';
          script.src = url;
          document.getElementsByTagName('head')[0].appendChild(script);
        }
      };
      var hasMore = function() {
        return !!cursor;
      };
      var getMeta = function(key, comment) {
        if ('iswriter' == key) {
          var matches = !!comment.author
              && comment.author.name == config.authorName
              && comment.author.profileUrl == config.authorUrl;
          return matches ? 'true' : '';
        } else if ('deletelink' == key) {
          return config.baseUri + '/delete-comment.g?blogID='
               + config.blogId + '&postID=' + comment.id;
        } else if ('deleteclass' == key) {
          return comment.deleteclass;
        }
        return '';
      };

      var replybox = null;
      var replyUrlParts = null;
      var replyParent = undefined;

      var onReply = function(commentId, domId) {
        if (replybox == null) {
          // lazily cache replybox, and adjust to suit this style:
          replybox = document.getElementById('comment-editor');
          if (replybox != null) {
            replybox.height = '250px';
            replybox.style.display = 'block';
            replyUrlParts = replybox.src.split('#');
          }
        }
        if (replybox && (commentId !== replyParent)) {
          replybox.src = '';
          document.getElementById(domId).insertBefore(replybox, null);
          replybox.src = replyUrlParts[0]
              + (commentId ? '&parentID=' + commentId : '')
              + '#' + replyUrlParts[1];
          replyParent = commentId;
        }
      };

      var hash = (window.location.hash || '#').substring(1);
      var startThread, targetComment;
      if (/^comment-form_/.test(hash)) {
        startThread = hash.substring('comment-form_'.length);
      } else if (/^c[0-9]+$/.test(hash)) {
        targetComment = hash.substring(1);
      }

      // Configure commenting API:
      var configJso = {
        'maxDepth': config.maxThreadDepth
      };
      var provider = {
        'id': config.postId,
        'data': items,
        'loadNext': paginator,
        'hasMore': hasMore,
        'getMeta': getMeta,
        'onReply': onReply,
        'rendered': true,
        'initComment': targetComment,
        'initReplyThread': startThread,
        'config': configJso,
        'messages': msgs
      };

      var render = function() {
        if (window.goog && window.goog.comments) {
          var holder = document.getElementById('comment-holder');
          window.goog.comments.render(holder, provider);
        }
      };

      // render now, or queue to render when library loads:
      if (window.goog && window.goog.comments) {
        render();
      } else {
        window.goog = window.goog || {};
        window.goog.comments = window.goog.comments || {};
        window.goog.comments.loadQueue = window.goog.comments.loadQueue || [];
        window.goog.comments.loadQueue.push(render);
      }
    })();
// ]]>
  </script>
</b:includable>
                  <b:includable id='threaded_comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <h4><data:post.commentLabelFull/>:</h4>

    <div class='comments-content'>
      <b:include cond='data:post.embedCommentForm' data='post' name='threaded_comment_js'/>
      <div id='comment-holder'>
         <data:post.commentHtml/>
      </div>
    </div>

    <p class='comment-footer'>
      <b:if cond='data:post.allowNewComments'>
        <b:include data='post' name='threaded-comment-form'/>
      <b:else/>
        <data:post.noNewCommentsText/>
      </b:if>
    </p>

    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
    </div>
    </div>
  </div>
</b:includable>
                </b:widget>
              </b:section>
              <b:section class='sidebar' id='sidebar' name='Sidebar' showaddelement='yes'>
                <b:widget id='BlogSearch1' locked='true' title='Search This Blog' type='BlogSearch' version='2' visible='true'>
                  <b:includable id='main'>
                    <b:include name='content'/>
                  </b:includable>
                  <b:includable id='content'>
                    <div class='widget-content' role='search'>
                      <b:include name='searchForm'/>
                    </div>
                  </b:includable>
                  <b:includable id='searchForm'>
                    <form expr:action='data:blog.searchUrl'>
                      <b:attr cond='not data:view.isPreview' name='target' value='_top'/>
                        <b:include name='urlParamsAsFormInput'/>
                          <div class='search-input'>
                            <input autocomplete='off' expr:aria-label='data:messages.searchThisBlog' expr:value='data:view.isSearch ? data:view.search.query.escaped : &quot;&quot;' name='q' placeholder='খুঁজুন' type='search'/>
                            <button type='submit'><i class='fa fa-search'/></button>
                          </div>
                    </form>
                  </b:includable>
                  <b:includable id='searchSubmit'>
                    <input class='search-action' expr:value='data:messages.search.escaped' type='submit'/>
                  </b:includable>
                </b:widget>
                <b:widget cond='data:view.isPost' id='Blog3' locked='true' title='Blog Posts' type='Blog' version='2' visible='true'>
                  <b:widget-settings>
                    <b:widget-setting name='showDateHeader'>false</b:widget-setting>
                    <b:widget-setting name='style.textcolor'>#ffffff</b:widget-setting>
                    <b:widget-setting name='showShareButtons'>false</b:widget-setting>
                    <b:widget-setting name='showCommentLink'>true</b:widget-setting>
                    <b:widget-setting name='style.urlcolor'>#ffffff</b:widget-setting>
                    <b:widget-setting name='showAuthor'>true</b:widget-setting>
                    <b:widget-setting name='style.linkcolor'>#ffffff</b:widget-setting>
                    <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
                    <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
                    <b:widget-setting name='reactionsLabel'/>
                    <b:widget-setting name='showAuthorProfile'>true</b:widget-setting>
                    <b:widget-setting name='style.layout'>1x1</b:widget-setting>
                    <b:widget-setting name='showLabels'>true</b:widget-setting>
                    <b:widget-setting name='showLocation'>true</b:widget-setting>
                    <b:widget-setting name='showTimestamp'>true</b:widget-setting>
                    <b:widget-setting name='postsPerAd'>1</b:widget-setting>
                    <b:widget-setting name='showBacklinks'>false</b:widget-setting>
                    <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
                    <b:widget-setting name='showInlineAds'>false</b:widget-setting>
                    <b:widget-setting name='showReactions'>false</b:widget-setting>
                  </b:widget-settings>
                  <b:includable id='main' var='this'>
    <b:loop index='i' values='data:posts' var='post'>
      <b:include data='post' name='aboutPostAuthor'/>
    </b:loop>
</b:includable>
                  <b:includable id='aboutPostAuthor'>
<a class='image' expr:href='data:post.author.profileUrl'>
<img class='avatar avatar-150 photo' expr:alt='data:post.author.name' expr:src='data:post.author.authorPhoto.image' height='150' loading='lazy' width='150'/> </a>
<span>Author</span>
<h3><a expr:href='data:post.author.profileUrl' expr:title='&quot;Posted by &quot;+data:post.author.name' rel='author'><data:post.author.name/></a></h3>
<p><data:post.author.aboutMe/></p>
</b:includable>
                  <b:includable id='addComments'>
  <a expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
    <b:message name='messages.postAComment'/>
  </a>
</b:includable>
                  <b:includable id='blogThisShare'>
  <b:with value='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
                  <b:includable id='bylineByName' var='byline'>
  <b:switch var='data:byline.name'>
  <b:case value='share'/>
    <b:include cond='data:post.shareUrl' name='postShareButtons'/>
  <b:case value='comments'/>
    <b:include cond='data:post.allowComments' name='postCommentsLink'/>
  <b:case value='location'/>
    <b:include cond='data:post.location' name='postLocation'/>
  <b:case value='timestamp'/>
    <b:include cond='not data:view.isPage' name='postTimestamp'/>
  <b:case value='author'/>
    <b:include name='postAuthor'/>
  <b:case value='labels'/>
    <b:include cond='data:post.labels' name='postLabels'/>
  <b:case value='icons'/>
    <b:include cond='data:post.emailPostUrl' name='emailPostIcon'/>
  </b:switch>
</b:includable>
                  <b:includable id='bylineRegion' var='regionItems'>
  <b:loop values='data:regionItems' var='byline'>
    <b:include data='byline' name='bylineByName'/>
  </b:loop>
</b:includable>
                  <b:includable id='commentAuthorAvatar'>
  <div class='avatar-image-container'>
    <img class='author-avatar' expr:src='data:comment.authorAvatarSrc' height='35' width='35'/>
  </div>
</b:includable>
                  <b:includable id='commentDeleteIcon' var='comment'>
  <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
    <b:if cond='data:showCmtPopup'>
      <div class='goog-toggle-button'>
        <div class='goog-inline-block comment-action-icon'/>
      </div>
    <b:else/>
      <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:messages.deleteComment'>
        <img src='https://resources.blogblog.com/img/icon_delete13.gif'/>
      </a>
    </b:if>
  </span>
</b:includable>
                  <b:includable id='commentForm' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <h4 id='comment-post-message'><data:messages.postAComment/></h4>
    <b:if cond='data:this.messages.blogComment != &quot;&quot;'>
      <p><data:this.messages.blogComment/></p>
    </b:if>
    <b:include data='post' name='commentFormIframeSrc'/>
    <iframe allowtransparency='allowtransparency' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight ?: &quot;90px&quot;' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
                  <b:includable id='commentFormIframeSrc' var='post'>
  <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
</b:includable>
                  <b:includable id='commentItem' var='comment'>
  <div class='comment' expr:id='&quot;c&quot; + data:comment.id'>
    <b:include cond='data:blog.enabledCommentProfileImages' name='commentAuthorAvatar'/>

    <div class='comment-block'>
      <div class='comment-author'>
        <b:if cond='data:comment.authorUrl'>
          <b:message name='messages.authorSaidWithLink'>
            <b:param expr:value='data:comment.author' name='authorName'/>
            <b:param expr:value='data:comment.authorUrl' name='authorUrl'/>
          </b:message>
        <b:else/>
          <b:message name='messages.authorSaid'>
            <b:param expr:value='data:comment.author' name='authorName'/>
          </b:message>
        </b:if>
      </div>
      <div expr:class='&quot;comment-body&quot; + (data:comment.isDeleted ? &quot; deleted&quot; : &quot;&quot;)'>
        <data:comment.body/>
      </div>
      <div class='comment-footer'>
        <span class='comment-timestamp'>
          <a expr:href='data:comment.url' title='comment permalink'>
            <data:comment.timestamp/>
          </a>
          <b:include data='comment' name='commentDeleteIcon'/>
        </span>
      </div>
    </div>
  </div>
</b:includable>
                  <b:includable id='commentList' var='comments'>
  <div id='comments-block'>
    <b:loop values='data:comments' var='comment'>
      <b:include data='comment' name='commentItem'/>
    </b:loop>
  </div>
</b:includable>
                  <b:includable id='commentPicker' var='post'>
  <b:if cond='data:post.showThreadedComments'>
    <b:include data='post' name='threadedComments'/>
  <b:else/>
    <b:include data='post' name='comments'/>
  </b:if>
</b:includable>
                  <b:includable id='comments' var='post'>
  <section expr:class='&quot;comments&quot; + (data:post.embedCommentForm ? &quot; embed&quot; : &quot;&quot;)' expr:data-num-comments='data:post.numberOfComments' id='comments'>
    <a name='comments'/>
    <b:if cond='data:post.allowComments'>

      <b:include name='commentsTitle'/>

      <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
        <b:include cond='data:post.comments' data='post.comments' name='commentList'/>
      </div>

      <b:if cond='data:post.commentPagingRequired'>
        <div class='paging-control-container'>
          <b:if cond='data:post.hasOlderLinks'>
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
              <data:messages.oldest/>
            </a>
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
              <data:messages.older/>
            </a>
          </b:if>

          <span class='comment-range-text'>
            <data:post.commentRangeText/>
          </span>

          <b:if cond='data:post.hasNewerLinks'>
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
              <data:messages.newer/>
            </a>
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
              <data:messages.newest/>
            </a>
          </b:if>
        </div>
      </b:if>

      <div class='footer'>
        <b:if cond='data:post.embedCommentForm'>
          <b:if cond='data:post.allowNewComments'>
            <b:include data='post' name='commentForm'/>
          <b:else/>
            <data:post.noNewCommentsText/>
          </b:if>
        <b:else/>
          <b:if cond='data:post.allowComments'>
            <b:include data='post' name='addComments'/>
          </b:if>
        </b:if>
      </div>
    </b:if>
    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='allowtransparency' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>
  </section>
</b:includable>
                  <b:includable id='commentsLink'>
  <a class='comment-link' expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
    <b:if cond='data:post.numberOfComments &gt; 0'>
      <b:message name='messages.numberOfComments'>
        <b:param expr:value='data:post.numberOfComments' name='numComments'/>
      </b:message>
    <b:else/>
      <data:messages.postAComment/>
    </b:if>
  </a>
</b:includable>
                  <b:includable id='commentsLinkIframe'>
  <!-- G+ comments, no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
                  <b:includable id='commentsTitle'>
  <h3 class='title'><data:messages.comments/></h3>
</b:includable>
                  <b:includable id='defaultAdUnit'>
  <ins class='adsbygoogle' data-ad-format='auto' expr:data-ad-client='data:adClientId ?: data:blog.adsenseClientId' expr:data-ad-host='data:blog.adsenseHostId' expr:data-analytics-uacct='data:blog.analyticsAccountNumber' expr:style='data:style ?: &quot;display: block;&quot;'/>
  <script>
   (adsbygoogle = window.adsbygoogle || []).push({});
  </script>
</b:includable>
                  <b:includable id='emailPostIcon'>
  <span class='byline post-icons'>
    <!-- email post links -->
    <span class='item-action'>
      <a expr:href='data:post.emailPostUrl' expr:title='data:messages.emailPost'>
        <b:include data='{ iconClass: &quot;touch-icon sharing-icon&quot; }' name='emailIcon'/>
      </a>
    </span>
  </span>
</b:includable>
                  <b:includable id='facebookShare'>
  <b:with value='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
                  <b:includable id='feedLinks'>
  <b:if cond='!data:view.isPost'> <!-- Blog feed links -->
    <b:if cond='data:feedLinks'>
      <div class='blog-feeds'>
        <b:include data='feedLinks' name='feedLinksBody'/>
      </div>
    </b:if>
  <b:else/> <!--Post feed links -->
    <div class='post-feeds'>
      <b:loop values='data:posts' var='post'>
        <b:if cond='data:post.allowComments and data:post.feedLinks'>
          <b:include data='post.feedLinks' name='feedLinksBody'/>
        </b:if>
      </b:loop>
    </div>
  </b:if>
</b:includable>
                  <b:includable id='feedLinksBody' var='links'>
  <div class='feed-links'>
  <data:messages.subscribeTo/>
  <b:loop values='data:links' var='f'>
     <a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'><data:f.name/> (<data:f.feedType/>)</a>
  </b:loop>
  </div>
</b:includable>
                  <b:includable id='footerBylines'>
  <b:if cond='data:widgets.Blog.first.footerBylines'>
    <b:loop index='i' values='data:widgets.Blog.first.footerBylines' var='region'>
      <b:if cond='not data:region.items.empty'>
        <div expr:class='&quot;post-footer-line post-footer-line-&quot; + (data:i + 1)'>
          <b:with value='&quot;footer-&quot; + (data:i + 1)' var='regionName'>
            <b:include data='region.items' name='bylineRegion'/>
          </b:with>
        </div>
      </b:if>
    </b:loop>
  </b:if>
</b:includable>
                  <b:includable id='googlePlusShare'>
  <div class='goog-inline-block google-plus-share-container'>
    <g:plusone annotation='inline' expr:href='data:originalUrl.canonical.http' size='medium' source='blogger:blog:plusone'/>
  </div>
</b:includable>
                  <b:includable id='headerByline'>
  <b:if cond='data:widgets.Blog.first.headerByline'>
    <div class='post-header'>
      <div class='post-header-line-1'>
        <b:with value='&quot;header-1&quot;' var='regionName'>
          <b:include data='data:widgets.Blog.first.headerByline.items' name='bylineRegion'/>
        </b:with>
      </div>
    </div>
  </b:if>
</b:includable>
                  <b:includable id='homePageLink'>
  <a class='home-link' expr:href='data:blog.homepageUrl'>
    <data:messages.home/>
  </a>
</b:includable>
                  <b:includable id='iframeComments' var='post'>
  <!-- G+ comments, no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
                  <b:includable id='inlineAd' var='post'>
  <b:if cond='!data:view.isPreview'>
    <b:if cond='data:this.adCode or data:this.adClientId or data:blog.adsenseClientId'>
      <!-- Ad -->
      <div class='inline-ad'>
        <b:if cond='data:this.adCode != &quot;&quot;'>
          <data:this.adCode/>
        <b:else/>
          <b:include cond='data:this.adClientId or data:blog.adsenseClientId' name='defaultAdUnit'/>
        </b:if>
      </div>
    </b:if>
  <b:else/>
    <div class='inline-ad'>
      <div class='inline-ad-placeholder'>
        <span><b:message name='messages.adsGoHere'/></span>
      </div>
    </div>
  </b:if>
</b:includable>
                  <b:includable id='linkShare'>
  <b:with value='&quot;window.prompt(\&quot;Copy to clipboard: Ctrl+C, Enter\&quot;, \&quot;&quot; + data:originalUrl + &quot;\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
                  <b:includable id='nextPageLink'>
  <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:messages.olderPosts'>
    <data:messages.olderPosts/>
  </a>
</b:includable>
                  <b:includable id='otherSharingButton'>
  <span class='sharing-platform-button sharing-element-other' expr:aria-label='data:messages.shareToOtherApps.escaped' expr:data-url='data:originalUrl' expr:title='data:messages.shareToOtherApps.escaped' role='menuitem' tabindex='-1'>
    <b:with value='{key: &quot;sharingOther&quot;}' var='platform'>
      <b:include name='sharingPlatformIcon'/>
    </b:with>
    <span class='platform-sharing-text'><data:messages.shareOtherApps.escaped/></span>
  </span>
</b:includable>
                  <b:includable id='platformShare'>
  <a expr:class='&quot;goog-inline-block sharing-&quot; + data:platform.key' expr:data-url='data:originalUrl' expr:href='data:shareUrl + &quot;&amp;target=&quot; + data:platform.target' expr:onclick='data:onclick ? data:onclick : &quot;&quot;' expr:title='data:platform.shareMessage' target='_blank'>
    <span class='share-button-link-text'>
      <data:platform.shareMessage/>
    </span>
  </a>
</b:includable>
                  <b:includable id='post' var='post'>
  <div class='post'>
    <b:include data='post' name='postMeta'/>
    <b:include data='post' name='postTitle'/>
    <b:include name='headerByline'/>
    <b:if cond='data:view.isSingleItem'>
      <b:include data='post' name='postBody'/>
    <b:else/>
      <b:include data='post' name='postBodySnippet'/>
      <b:include data='post' name='postJumpLink'/>
    </b:if>
    <b:include data='post' name='postFooter'/>
  </div>
</b:includable>
                  <b:includable id='postAuthor'>
  <span class='byline post-author vcard'>
    <span class='post-author-label'>
      <data:byline.label/>
    </span>
    <span class='fn'>
      <b:if cond='data:post.author.profileUrl'>
        <meta expr:content='data:post.author.profileUrl'/>
        <a class='g-profile' expr:href='data:post.author.profileUrl' rel='author' title='author profile'>
          <span><data:post.author.name/></span>
        </a>
      <b:else/>
        <span><data:post.author.name/></span>
      </b:if>
    </span>
  </span>
</b:includable>
                  <b:includable id='postBody' var='post'>
  <!-- If metaDescription is empty, use the post body as the schema.org description too, for G+/FB snippeting. -->
  <div class='post-body entry-content float-container' expr:id='&quot;post-body-&quot; + data:post.id'>
    <data:post.body/>
  </div>
</b:includable>
                  <b:includable id='postBodySnippet' var='post'>
  <b:include data='post' name='postBody'/>
</b:includable>
                  <b:includable id='postCommentsAndAd' var='post'>
  <article class='post-outer-container'>
    <!-- Post title and body -->
    <div class='post-outer'>
      <b:include data='post' name='post'/>
    </div>

    <!-- Comments -->
    <b:include cond='data:view.isSingleItem' data='post' name='commentPicker'/>

    <!-- Show ad inside post container, after comments, if single item. -->
    <b:include cond='data:view.isSingleItem and data:post.includeAd' data='post' name='inlineAd'/>
  </article>

  <!-- Show ad outside post container (between posts) for feed pages. -->
  <b:include cond='data:view.isMultipleItems and data:post.includeAd' data='post' name='inlineAd'/>
</b:includable>
                  <b:includable id='postCommentsLink'>
  <b:if cond='data:view.isMultipleItems'>
    <span class='byline post-comment-link container'>
      <b:include cond='data:post.commentSource != 1' name='commentsLink'/>
    </span>
  </b:if>
</b:includable>
                  <b:includable id='postFooter' var='post'>
  <div class='post-footer'>
    <b:include name='footerBylines'/>
    <b:include data='post' name='postFooterAuthorProfile'/>
  </div>
</b:includable>
                  <b:includable id='postFooterAuthorProfile' var='post'>
  <b:if cond='data:post.author.aboutMe and data:view.isPost'>
    <div class='author-profile'>
      <b:if cond='data:post.author.authorPhoto.url'>
        <img class='author-image' expr:src='data:post.author.authorPhoto.url' width='50px'/>
        <div class='author-about'>
          <b:include data='post' name='aboutPostAuthor'/>
        </div>
      <b:else/>
        <b:include data='post' name='aboutPostAuthor'/>
      </b:if>
    </div>
  </b:if>
</b:includable>
                  <b:includable id='postHeader' var='post'>
  <b:include name='headerByline'/>
</b:includable>
                  <b:includable id='postJumpLink' var='post'>
  <div class='jump-link flat-button'>
    <a expr:href='data:post.url fragment &quot;more&quot;' expr:title='data:post.title'>
      <b:eval expr='data:blog.jumpLinkMessage'/>
    </a>
  </div>
</b:includable>
                  <b:includable id='postLabels'>
  <span class='byline post-labels'>
    <span class='byline-label'><data:byline.label/></span>
    <b:loop index='i' values='data:post.labels' var='label'>
      <a expr:href='data:label.url' rel='tag'>
        <data:label.name/>
      </a>
    </b:loop>
  </span>
</b:includable>
                  <b:includable id='postLocation'>
  <span class='byline post-location'>
    <data:byline.label/>
    <a expr:href='data:post.location.mapsUrl' target='_blank'><data:post.location.name/></a>
  </span>
</b:includable>
                  <b:includable id='postMeta' var='post'>
  <b:include data='post' name='postMetadataJSON'/>
</b:includable>
                  <b:includable id='postMetadataJSONImage'>
  &quot;image&quot;: {
    &quot;@type&quot;: &quot;ImageObject&quot;,
    <b:if cond='data:post.featuredImage.isResizable'>
    &quot;url&quot;: &quot;<b:eval expr='resizeImage(data:post.featuredImage, 1200, &quot;1200:630&quot;)'/>&quot;,
    &quot;height&quot;: 630,
    &quot;width&quot;: 1200
    <b:else/>
    &quot;url&quot;: &quot;https://lh3.googleusercontent.com/ULB6iBuCeTVvSjjjU1A-O8e9ZpVba6uvyhtiWRti_rBAs9yMYOFBujxriJRZ-A=w1200&quot;,
    &quot;height&quot;: 348,
    &quot;width&quot;: 1200
    </b:if>
  },
</b:includable>
                  <b:includable id='postMetadataJSONPublisher'>
 &quot;publisher&quot;: {
    &quot;@type&quot;: &quot;Organization&quot;,
    &quot;name&quot;: &quot;Blogger&quot;,
    &quot;logo&quot;: {
      &quot;@type&quot;: &quot;ImageObject&quot;,
      &quot;url&quot;: &quot;https://lh3.googleusercontent.com/ULB6iBuCeTVvSjjjU1A-O8e9ZpVba6uvyhtiWRti_rBAs9yMYOFBujxriJRZ-A=h60&quot;,
      &quot;width&quot;: 206,
      &quot;height&quot;: 60
    }
  },
</b:includable>
                  <b:includable id='postPagination'>
  <div class='blog-pager container' id='blog-pager'>
    <b:include cond='data:newerPageUrl' name='previousPageLink'/>
    <b:include cond='data:olderPageUrl' name='nextPageLink'/>
    <b:include cond='data:view.url != data:blog.homepageUrl' name='homePageLink'/>
  </div>
</b:includable>
                  <b:includable id='postReactions'>
  <!-- Reaction feature no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
                  <b:includable id='postShareButtons'>
  <div class='byline post-share-buttons goog-inline-block'>
    <b:with value='data:sharingId ?: ((data:widget.instanceId ?: &quot;sharing&quot;) + &quot;-&quot; + (data:regionName ?: &quot;byline&quot;) + &quot;-&quot; + data:post.id)' var='sharingId'>
      <!-- Note: 'sharingButtons' includable is from the default Sharing widget markup. -->
      <b:include data='{                                                sharingId: data:sharingId,                                                originalUrl: data:post.url,                                                platforms: data:this.sharing.platforms,                                                shareUrl: data:post.shareUrl,                                                shareTitle: data:post.title,                                              }' name='sharingButtons'/>
    </b:with>
  </div>
</b:includable>
                  <b:includable id='postTimestamp'>
  <span class='byline post-timestamp'>
    <data:byline.label/>
    <b:if cond='data:post.url'>
      <meta expr:content='data:post.url.canonical'/>
      <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'>
        <time class='published' expr:datetime='data:post.date.iso8601' expr:title='data:post.date.iso8601'>
          <data:post.date/>
        </time>
      </a>
    </b:if>
  </span>
</b:includable>
                  <b:includable id='postTitle' var='post'>
  <a expr:name='data:post.id'/>
  <b:if cond='data:post.title != &quot;&quot;'>
    <h3 class='post-title entry-title'>
      <b:if cond='data:post.link or (data:post.url and data:view.url != data:post.url)'>
        <a expr:href='data:post.link ?: data:post.url'><data:post.title/></a>
      <b:else/>
        <data:post.title/>
      </b:if>
    </h3>
  </b:if>
</b:includable>
                  <b:includable id='previousPageLink'>
  <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:messages.newerPosts'>
    <data:messages.newerPosts/>
  </a>
</b:includable>
                  <b:includable id='sharingButton'>
  <span expr:aria-label='data:platform.shareMessage' expr:class='&quot;sharing-platform-button sharing-element-&quot; + data:platform.key' expr:data-href='data:shareUrl + &quot;&amp;target=&quot; + data:platform.target' expr:data-url='data:originalUrl' expr:title='data:platform.shareMessage' role='menuitem' tabindex='-1'>
    <b:include name='sharingPlatformIcon'/>
    <span class='platform-sharing-text'><data:platform.name/></span>
  </span>
</b:includable>
                  <b:includable id='sharingButtonContent'>
  <div class='flat-icon-button ripple'>
    <b:include name='shareIcon'/>
  </div>
</b:includable>
                  <b:includable id='sharingButtons'>
  <div class='sharing' expr:aria-owns='&quot;sharing-popup-&quot; + data:sharingId' expr:data-title='data:shareTitle'>
    <button class='sharing-button touch-icon-button' expr:aria-controls='&quot;sharing-popup-&quot; + data:sharingId' expr:aria-label='data:messages.share.escaped' expr:id='&quot;sharing-button-&quot; + data:sharingId' role='button'>
      <b:include name='sharingButtonContent'/>
    </button>
    <b:include name='sharingButtonsMenu'/>
  </div>
</b:includable>
                  <b:includable id='sharingButtonsMenu'>
  <div class='share-buttons-container'>
    <ul aria-hidden='true' class='share-buttons hidden' expr:aria-label='data:messages.share.escaped' expr:id='&quot;sharing-popup-&quot; + data:sharingId' role='menu'>
      <b:loop values='(data:platforms ?: data:blog.sharing.platforms) filter (p =&gt; p.key not in {&quot;blogThis&quot;})' var='platform'>
        <li>
          <b:include name='sharingButton'/>
        </li>
      </b:loop>
      <li aria-hidden='true' class='hidden'>
        <b:include name='otherSharingButton'/>
      </li>
    </ul>
  </div>
</b:includable>
                  <b:includable id='sharingPlatformIcon'>
  <b:include data='{ iconClass: (&quot;touch-icon sharing-&quot; + data:platform.key) }' expr:name='data:platform.key + &quot;Icon&quot;'/>
</b:includable>
                  <b:includable id='threadedCommentForm' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <h4 id='comment-post-message'><data:messages.postAComment/></h4>
    <b:if cond='data:this.messages.blogComment != &quot;&quot;'>
      <p><data:this.messages.blogComment/></p>
    </b:if>
    <b:include data='post' name='commentFormIframeSrc'/>
    <iframe allowtransparency='allowtransparency' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight ?: &quot;90px&quot;' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
                  <b:includable id='threadedCommentJs' var='post'>
  <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>
  <b:template-script inline='true' name='threaded_comments'/>
  <script type='text/javascript'>
    blogger.widgets.blog.initThreadedComments(
        <data:post.commentJso/>,
        <data:post.commentMsgs/>,
        <data:post.commentConfig/>);
  </script>
</b:includable>
                  <b:includable id='threadedComments' var='post'>
  <section class='comments threaded' expr:data-embed='data:post.embedCommentForm' expr:data-num-comments='data:post.numberOfComments' id='comments'>
    <a name='comments'/>

    <b:include name='commentsTitle'/>

    <div class='comments-content'>
      <b:if cond='data:post.embedCommentForm'>
        <b:include data='post' name='threadedCommentJs'/>
      </b:if>
      <div id='comment-holder'>
         <data:post.commentHtml/>
      </div>
    </div>

    <p class='comment-footer'>
      <b:if cond='data:post.allowNewComments'>
        <b:include data='post' name='threadedCommentForm'/>
      <b:else/>
        <data:post.noNewCommentsText/>
      </b:if>
      <b:if cond='data:post.showManageComments'>
        <b:include data='post' name='manageComments'/>
      </b:if>
    </p>

    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='allowtransparency' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>
  </section>
</b:includable>
                </b:widget>
                <b:widget id='FeaturedPost1' locked='false' title='Featured Post' type='FeaturedPost' visible='true'>
                  <b:widget-settings>
                    <b:widget-setting name='showSnippet'>true</b:widget-setting>
                    <b:widget-setting name='showPostTitle'>true</b:widget-setting>
                    <b:widget-setting name='postId'>5036464287564795634</b:widget-setting>
                    <b:widget-setting name='showFirstImage'>true</b:widget-setting>
                    <b:widget-setting name='useMostRecentPost'>false</b:widget-setting>
                  </b:widget-settings>
                  <b:includable id='main' var='this'>
      <div class='widget-content featured-post'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='content'/>
        </b:loop>
      </div>
    </b:includable>
                  <b:includable id='blogThisShare'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='bylineByName' var='byline'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='bylineRegion' var='regionItems'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='commentsLink'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='commentsLinkIframe'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='content' var='post'>
        <div class='entry-header'>
          <h2 class='entry-title'><a expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></a></h2>
        </div>
        <b:if cond='data:post.featuredImage'>
          <a class='entry-image-wrap' expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle'><img class='entry-thumb' expr:src='data:post.featuredImage.isYouTube ? data:post.featuredImage.youtubeMaxResDefaultUrl.jsonEscaped : data:post.featuredImage'/></a>
          <b:else/>
          <a class='entry-image-wrap is-image' expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle'><span class='entry-thumb' data-image='https://4.bp.blogspot.com/-oSjP8F09qxo/Wy1J9dp7b0I/AAAAAAAACF0/ggcRfLCFQ9s2SSaeL9BFSE2wyTYzQaTyQCK4BGAYYCw/s35-r/avatar.jpg'/></a>
        </b:if>
    </b:includable>
                  <b:includable id='emailPostIcon'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='facebookShare'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='footerBylines'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='googlePlusShare'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='headerByline'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='linkShare'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='otherSharingButton'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='platformShare'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='postAuthor'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='postCommentsLink'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='postJumpLink' var='post'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='postLabels'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='postLocation'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='postReactions'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='postShareButtons'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='postTimestamp'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='sharingButton'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='sharingButtonContent'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='sharingButtons'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='sharingButtonsMenu'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='sharingPlatformIcon'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='snippetedPostByline'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='snippetedPostContent'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='snippetedPostThumbnail'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='snippetedPostTitle'><b:comment>Replaced</b:comment></b:includable>
                  <b:includable id='snippetedPosts'><b:comment>Replaced</b:comment></b:includable>
                </b:widget>
                <b:widget id='PopularPosts2' locked='false' title='Popular' type='PopularPosts' version='2' visible='true'>
                  <b:widget-settings>
                    <b:widget-setting name='numItemsToShow'>3</b:widget-setting>
                    <b:widget-setting name='showThumbnails'>true</b:widget-setting>
                    <b:widget-setting name='showSnippets'>true</b:widget-setting>
                    <b:widget-setting name='timeRange'>LAST_YEAR</b:widget-setting>
                  </b:widget-settings>
                  <b:includable id='main' var='this'>
    <b:include name='widget-title'/>
    <div class='widget-content sidebar-posts'>
      <b:include name='snippetedPosts'/>
    </div>
  </b:includable>
                  <b:includable id='blogThisShare'>
  <b:with value='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
                  <b:includable id='bylineByName' var='byline'>
  <b:switch var='data:byline.name'>
  <b:case value='share'/>
    <b:include cond='data:post.shareUrl' name='postShareButtons'/>
  <b:case value='comments'/>
    <b:include cond='data:post.allowComments' name='postCommentsLink'/>
  <b:case value='location'/>
    <b:include cond='data:post.location' name='postLocation'/>
  <b:case value='timestamp'/>
    <b:include cond='not data:view.isPage' name='postTimestamp'/>
  <b:case value='author'/>
    <b:include name='postAuthor'/>
  <b:case value='labels'/>
    <b:include cond='data:post.labels' name='postLabels'/>
  <b:case value='icons'/>
    <b:include cond='data:post.emailPostUrl' name='emailPostIcon'/>
  </b:switch>
</b:includable>
                  <b:includable id='bylineRegion' var='regionItems'>
  <b:loop values='data:regionItems' var='byline'>
    <b:include data='byline' name='bylineByName'/>
  </b:loop>
</b:includable>
                  <b:includable id='commentsLink'>
  <a class='comment-link' expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
    <b:if cond='data:post.numberOfComments &gt; 0'>
      <b:message name='messages.numberOfComments'>
        <b:param expr:value='data:post.numberOfComments' name='numComments'/>
      </b:message>
    <b:else/>
      <data:messages.postAComment/>
    </b:if>
  </a>
</b:includable>
                  <b:includable id='commentsLinkIframe'>
  <!-- G+ comments, no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
                  <b:includable id='emailPostIcon'>
  <span class='byline post-icons'>
    <!-- email post links -->
    <span class='item-action'>
      <a expr:href='data:post.emailPostUrl' expr:title='data:messages.emailPost'>
        <b:include data='{ iconClass: &quot;touch-icon sharing-icon&quot; }' name='emailIcon'/>
      </a>
    </span>
  </span>
</b:includable>
                  <b:includable id='facebookShare'>
  <b:with value='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
                  <b:includable id='footerBylines'>
  <b:if cond='data:widgets.Blog.first.footerBylines'>
    <b:loop index='i' values='data:widgets.Blog.first.footerBylines' var='region'>
      <b:if cond='not data:region.items.empty'>
        <div expr:class='&quot;post-footer-line post-footer-line-&quot; + (data:i + 1)'>
          <b:with value='&quot;footer-&quot; + (data:i + 1)' var='regionName'>
            <b:include data='region.items' name='bylineRegion'/>
          </b:with>
        </div>
      </b:if>
    </b:loop>
  </b:if>
</b:includable>
                  <b:includable id='googlePlusShare'>
  <div class='goog-inline-block google-plus-share-container'>
    <g:plusone annotation='inline' expr:href='data:originalUrl.canonical.http' size='medium' source='blogger:blog:plusone'/>
  </div>
</b:includable>
                  <b:includable id='headerByline'>
  <b:if cond='data:widgets.Blog.first.headerByline'>
    <div class='post-header'>
      <div class='post-header-line-1'>
        <b:with value='&quot;header-1&quot;' var='regionName'>
          <b:include data='data:widgets.Blog.first.headerByline.items' name='bylineRegion'/>
        </b:with>
      </div>
    </div>
  </b:if>
</b:includable>
                  <b:includable id='linkShare'>
  <b:with value='&quot;window.prompt(\&quot;Copy to clipboard: Ctrl+C, Enter\&quot;, \&quot;&quot; + data:originalUrl + &quot;\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
                  <b:includable id='otherSharingButton'>
  <span class='sharing-platform-button sharing-element-other' expr:aria-label='data:messages.shareToOtherApps.escaped' expr:data-url='data:originalUrl' expr:title='data:messages.shareToOtherApps.escaped' role='menuitem' tabindex='-1'>
    <b:with value='{key: &quot;sharingOther&quot;}' var='platform'>
      <b:include name='sharingPlatformIcon'/>
    </b:with>
    <span class='platform-sharing-text'><data:messages.shareOtherApps.escaped/></span>
  </span>
</b:includable>
                  <b:includable id='platformShare'>
  <a expr:class='&quot;goog-inline-block sharing-&quot; + data:platform.key' expr:data-url='data:originalUrl' expr:href='data:shareUrl + &quot;&amp;target=&quot; + data:platform.target' expr:onclick='data:onclick ? data:onclick : &quot;&quot;' expr:title='data:platform.shareMessage' target='_blank'>
    <span class='share-button-link-text'>
      <data:platform.shareMessage/>
    </span>
  </a>
</b:includable>
                  <b:includable id='postAuthor'>
  <span class='byline post-author vcard'>
    <span class='post-author-label'>
      <data:byline.label/>
    </span>
    <span class='fn'>
      <b:if cond='data:post.author.profileUrl'>
        <meta expr:content='data:post.author.profileUrl'/>
        <a class='g-profile' expr:href='data:post.author.profileUrl' rel='author' title='author profile'>
          <span><data:post.author.name/></span>
        </a>
      <b:else/>
        <span><data:post.author.name/></span>
      </b:if>
    </span>
  </span>
</b:includable>
                  <b:includable id='postCommentsLink'>
  <span class='byline post-comment-link container'>
    <b:include cond='data:post.commentSource != 1' name='commentsLink'/>
  </span>
</b:includable>
                  <b:includable id='postJumpLink' var='post'>
  <div class='jump-link flat-button'>
    <a expr:href='data:post.url fragment &quot;more&quot;' expr:title='data:post.title'>
      <b:eval expr='data:blog.jumpLinkMessage'/>
    </a>
  </div>
</b:includable>
                  <b:includable id='postLabels'>
  <span class='byline post-labels'>
    <span class='byline-label'><data:byline.label/></span>
    <b:loop index='i' values='data:post.labels' var='label'>
      <a expr:href='data:label.url' rel='tag'>
        <data:label.name/>
      </a>
    </b:loop>
  </span>
</b:includable>
                  <b:includable id='postLocation'>
  <span class='byline post-location'>
    <data:byline.label/>
    <a expr:href='data:post.location.mapsUrl' target='_blank'><data:post.location.name/></a>
  </span>
</b:includable>
                  <b:includable id='postReactions'>
  <!-- Reaction feature no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
                  <b:includable id='postShareButtons'>
  <div class='byline post-share-buttons goog-inline-block'>
    <b:with value='data:sharingId ?: ((data:widget.instanceId ?: &quot;sharing&quot;) + &quot;-&quot; + (data:regionName ?: &quot;byline&quot;) + &quot;-&quot; + data:post.id)' var='sharingId'>
      <!-- Note: 'sharingButtons' includable is from the default Sharing widget markup. -->
      <b:include data='{                                                sharingId: data:sharingId,                                                originalUrl: data:post.url,                                                platforms: data:this.sharing.platforms,                                                shareUrl: data:post.shareUrl,                                                shareTitle: data:post.title,                                              }' name='sharingButtons'/>
    </b:with>
  </div>
</b:includable>
                  <b:includable id='postTimestamp'>
  <span class='byline post-timestamp'>
    <data:byline.label/>
    <b:if cond='data:post.url'>
      <meta expr:content='data:post.url.canonical'/>
      <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'>
        <time class='published' expr:datetime='data:post.date.iso8601' expr:title='data:post.date.iso8601'>
          <data:post.date/>
        </time>
      </a>
    </b:if>
  </span>
</b:includable>
                  <b:includable id='sharingButton'>
  <span expr:aria-label='data:platform.shareMessage' expr:class='&quot;sharing-platform-button sharing-element-&quot; + data:platform.key' expr:data-href='data:shareUrl + &quot;&amp;target=&quot; + data:platform.target' expr:data-url='data:originalUrl' expr:title='data:platform.shareMessage' role='menuitem' tabindex='-1'>
    <b:include name='sharingPlatformIcon'/>
    <span class='platform-sharing-text'><data:platform.name/></span>
  </span>
</b:includable>
                  <b:includable id='sharingButtonContent'>
  <div class='flat-icon-button ripple'>
    <b:include name='shareIcon'/>
  </div>
</b:includable>
                  <b:includable id='sharingButtons'>
  <div class='sharing' expr:aria-owns='&quot;sharing-popup-&quot; + data:sharingId' expr:data-title='data:shareTitle'>
    <button class='sharing-button touch-icon-button' expr:aria-controls='&quot;sharing-popup-&quot; + data:sharingId' expr:aria-label='data:messages.share.escaped' expr:id='&quot;sharing-button-&quot; + data:sharingId' role='button'>
      <b:include name='sharingButtonContent'/>
    </button>
    <b:include name='sharingButtonsMenu'/>
  </div>
</b:includable>
                  <b:includable id='sharingButtonsMenu'>
  <div class='share-buttons-container'>
    <ul aria-hidden='true' class='share-buttons hidden' expr:aria-label='data:messages.share.escaped' expr:id='&quot;sharing-popup-&quot; + data:sharingId' role='menu'>
      <b:loop values='(data:platforms ?: data:blog.sharing.platforms) filter (p =&gt; p.key not in {&quot;blogThis&quot;})' var='platform'>
        <li>
          <b:include name='sharingButton'/>
        </li>
      </b:loop>
      <li aria-hidden='true' class='hidden'>
        <b:include name='otherSharingButton'/>
      </li>
    </ul>
  </div>
</b:includable>
                  <b:includable id='sharingPlatformIcon'>
  <b:include data='{ iconClass: (&quot;touch-icon sharing-&quot; + data:platform.key) }' expr:name='data:platform.key + &quot;Icon&quot;'/>
</b:includable>
                  <b:includable id='snippetedPostByline'>
  <b:with value='(data:widgets first (w =&gt; w.type == &quot;Blog&quot;)).allBylineItems' var='blogBylines'>
    <div class='item-byline'>
      <b:with value='data:blogBylines first (i =&gt; i.name == &quot;author&quot;)' var='byline'>
        <b:include cond='data:byline and data:this.postDisplay.showAuthor' data='post' name='postAuthor'/>
      </b:with>
      <b:with value='data:blogBylines first (i =&gt; i.name == &quot;timestamp&quot;)' var='byline'>
        <b:include cond='data:byline and data:this.postDisplay.showDate' data='post' name='postTimestamp'/>
      </b:with>
    </div>
  </b:with>
</b:includable>
                  <b:includable id='snippetedPostContent'>
    <b:include cond='data:this.postDisplay.showFeaturedImage and data:post.featuredImage' name='snippetedPostThumbnail'/>
    <b:include cond='data:this.postDisplay.showTitle' name='snippetedPostTitle'/>
  </b:includable>
                  <b:includable id='snippetedPostThumbnail'>
    <a class='entry-image-wrap' expr:href='data:post.url'>
        <img class='entry-thumb' expr:src='data:post.featuredImage.isYouTube ? resizeImage(data:post.featuredImage.youtubeMaxResDefaultUrl.jsonEscaped, 72, &quot;1:1&quot;) : resizeImage(data:post.featuredImage, 72, &quot;1:1&quot;)'/>
    </a>
  </b:includable>
                  <b:includable id='snippetedPostTitle'>
    <b:if cond='data:post.title != &quot;&quot;'>
      <div class='entry-header'>
        <h2 class='entry-title'>
          <a expr:href='data:post.url' expr:title='data:post.title'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></a>
        </h2>
      </div>
    </b:if>
  </b:includable>
                  <b:includable id='snippetedPosts'>
    <div role='feed'>
      <!-- Don't render the post that we're currently already looking at. -->
      <b:loop values='data:posts filter (p =&gt; p.id != data:view.postId)' var='post'>
        <article class='post-item' role='article'>
          <b:include name='snippetedPostContent'/>
        </article>
      </b:loop>
    </div>
  </b:includable>
                </b:widget>
                <b:widget id='Label1' locked='false' title='Labels' type='Label' version='2' visible='true'>
                  <b:widget-settings>
                    <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
                    <b:widget-setting name='display'>LIST</b:widget-setting>
                    <b:widget-setting name='selectedLabelsList'/>
                    <b:widget-setting name='showType'>ALL</b:widget-setting>
                    <b:widget-setting name='showFreqNumbers'>true</b:widget-setting>
                  </b:widget-settings>
                  <b:includable id='main' var='this'>
  <b:include name='widget-title'/>
  <b:include name='content'/>
</b:includable>
                  <b:includable id='cloud'>
  <b:loop values='data:labels' var='label'>
    <span class='label-size'>
      <b:class expr:name='&quot;label-size-&quot; + data:label.cssSize'/>
      <a class='label-name' expr:href='data:label.url'>
        <data:label.name/>
        <b:if cond='data:this.showFreqNumbers'>
          <span class='label-count'><data:label.count/></span>
        </b:if>
      </a>
    </span>
  </b:loop>
</b:includable>
                  <b:includable id='content'>
  <div class='widget-content'>
    <b:class expr:name='data:this.display + &quot;-label-widget-content&quot;'/>
    <b:include cond='data:this.display == &quot;list&quot;' name='list'/>
    <b:include cond='data:this.display == &quot;cloud&quot;' name='cloud'/>
  </div>
</b:includable>
                  <b:includable id='list'>
  <ul>
    <b:loop values='data:labels' var='label'>
      <li>
        <a class='label-name' expr:href='data:label.url'>
          <data:label.name/>
          <b:if cond='data:this.showFreqNumbers'>
            <span class='label-count'><data:label.count/></span>
          </b:if>
        </a>
      </li>
    </b:loop>
  </ul>
</b:includable>
                </b:widget>
              </b:section>
            </div>
        </section>
    </div>
    
    
    <footer>
      <div class='foo_top'>
      <div class='mid'>
      <b:section class='footer-left box b1' id='footer-left' maxwidgets='1' name='Footer Left' showaddelement='no'>
        <b:widget id='LinkList3' locked='true' title='Links' type='LinkList' version='2' visible='true'>
          <b:widget-settings>
            <b:widget-setting name='link-3'>https://trickbd-template.blogspot.com/p/about-us_26.html</b:widget-setting>
            <b:widget-setting name='sorting'>NONE</b:widget-setting>
            <b:widget-setting name='text-1'>Trainer Support</b:widget-setting>
            <b:widget-setting name='link-1'>https://trickbd-template.blogspot.com/p/advertise.html</b:widget-setting>
            <b:widget-setting name='text-0'>Payment Policy</b:widget-setting>
            <b:widget-setting name='link-2'>https://trickbd-template.blogspot.com/p/advertise.html</b:widget-setting>
            <b:widget-setting name='text-3'>About Us</b:widget-setting>
            <b:widget-setting name='link-0'>https://trickbd-template.blogspot.com/p/advertise.html</b:widget-setting>
            <b:widget-setting name='text-2'>Advertise</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main'>
            <b:include name='content'/>
          </b:includable>
          <b:includable id='content'>
            <h2><data:title/></h2>
            <ul>
              <b:loop values='data:links' var='link'>
                <li><a expr:href='data:link.target'><data:link.name/></a></li>
              </b:loop>
            </ul>
          </b:includable>
        </b:widget>
      </b:section>
      <b:section class='footer-center box b2' id='footer-center' maxwidgets='1' name='Footer Center' showaddelement='no'>
        <b:widget id='HTML1' locked='true' title='Posts' type='HTML' version='2' visible='true'>
          <b:widget-settings>
            <b:widget-setting name='content'>&lt;ul id=&quot;commentele&quot;&gt;&lt;/ul&gt;
&lt;script type=&#39;text/javascript&#39;&gt;
//&lt;![CDATA[
var a_rc=3,m_rc=!1,n_rc=!0,o_rc=100;function showrecentcomments(e){for(var r=0;r&lt;a_rc;r++){var n,t=e.feed.entry[r];if(r==e.feed.entry.length)break;for(var a=0;a&lt;t.link.length;a++)if(&quot;alternate&quot;==t.link[a].rel){n=t.link[a].href;break}var l=(n=n.replace(&quot;#&quot;,&quot;#comment-&quot;)).split(&quot;#&quot;),i=(l=l[0]).split(&quot;/&quot;),i=(i=(i=(i=(i=i[5]).split(&quot;.html&quot;))[0]).replace(/-/g,&quot; &quot;)).link(l),l=t.published.$t,l=(l.substring(0,4),l.substring(5,7),l.substring(8,10),new Array,document.createElement(&quot;li&quot;));l.innerHTML=&#39;&lt;p&gt;&lt;a href=&quot;&#39;+n+&#39;&quot;&gt;&#39;+t.author[0].name.$t+&quot;&lt;/a&gt; commented&lt;p&gt;&lt;h3&gt;&quot;+i+&quot;&lt;/h3&gt;&quot;,document.getElementById(&quot;commentele&quot;).appendChild(l)}}
//]]&gt;
&lt;/script&gt;</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main'>
  <div class='widget-content'>
    <h2><data:title/></h2>
    <data:content/>
  </div>
</b:includable>
        </b:widget>
      </b:section>
      <b:section class='footer-right box b4' id='footer-right' maxwidgets='1' name='Footer Right' showaddelement='no'>
        <b:widget id='LinkList4' locked='true' title='Socials' type='LinkList' version='2' visible='true'>
          <b:widget-settings>
            <b:widget-setting name='sorting'>NONE</b:widget-setting>
            <b:widget-setting name='text-1'>Twitter</b:widget-setting>
            <b:widget-setting name='link-1'>#</b:widget-setting>
            <b:widget-setting name='text-0'>Facebook</b:widget-setting>
            <b:widget-setting name='link-2'>javascript:;</b:widget-setting>
            <b:widget-setting name='link-0'>#</b:widget-setting>
            <b:widget-setting name='text-2'>LinkedIn</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main'>
            <b:include name='content'/>
          </b:includable>
          <b:includable id='content'>
            <h2><data:title/></h2>
            <ul>
              <b:loop values='data:links' var='link'>
                <li><a expr:href='data:link.target'><data:link.name/></a></li>
              </b:loop>
            </ul>
          </b:includable>
        </b:widget>
      </b:section>
      </div>
      </div>
     
      <div class='foo_bottom'>
            <div class='flex-left mid'>
              <b:section class='footer-logo' id='footer-logo' maxwidgets='1' name='Footer Logo' showaddelement='no'>
                <b:widget id='Image1' locked='true' title='Liputan9' type='Image' version='2' visible='true'>
                  <b:widget-settings>
                    <b:widget-setting name='displayUrl'>https://1.bp.blogspot.com/-gKk1xg_k-Rc/YfGXTSg0q5I/AAAAAAAABBo/r2TdQkZgi1UVC4a_CuOfSvvdUVSOF-UUgCNcBGAsYHQ/s150/logo.png</b:widget-setting>
                    <b:widget-setting name='displayHeight'>32</b:widget-setting>
                    <b:widget-setting name='sectionWidth'>150</b:widget-setting>
                    <b:widget-setting name='shrinkToFit'>true</b:widget-setting>
                    <b:widget-setting name='displayWidth'>150</b:widget-setting>
                    <b:widget-setting name='link'/>
                    <b:widget-setting name='caption'/>
                  </b:widget-settings>
                  <b:includable id='main'>
                    <b:include name='content'/>
                  </b:includable>
                  <b:includable id='content'>
                    <div class='logo'>
                      <a expr:href='data:blog.homepageUrl.canonical'><img expr:alt='data:title' expr:src='data:sourceUrl'/></a>
                     </div>
                  </b:includable>
                </b:widget>
              </b:section>
              
              <b:section class='footer-nav' id='footer-nav' maxwidgets='1' name='Footer Nav' showaddelement='no'>
                <b:widget id='LinkList2' locked='true' title='Links' type='LinkList' version='2' visible='true'>
                  <b:widget-settings>
                    <b:widget-setting name='link-3'>https://trickbd-template.blogspot.com/p/advertise.html</b:widget-setting>
                    <b:widget-setting name='sorting'>NONE</b:widget-setting>
                    <b:widget-setting name='text-1'>Advertise</b:widget-setting>
                    <b:widget-setting name='link-1'>https://trickbd-template.blogspot.com/p/advertise.html</b:widget-setting>
                    <b:widget-setting name='text-0'>About Us</b:widget-setting>
                    <b:widget-setting name='link-2'>https://trickbd-template.blogspot.com/p/about-us_26.html</b:widget-setting>
                    <b:widget-setting name='text-3'>Advertise</b:widget-setting>
                    <b:widget-setting name='link-0'>https://trickbd-template.blogspot.com/p/about-us_26.html</b:widget-setting>
                    <b:widget-setting name='text-2'>About Us</b:widget-setting>
                  </b:widget-settings>
                  <b:includable id='main'>
                    <b:include name='content'/>
                  </b:includable>
                  <b:includable id='content'>
                    <nav class='m_menu'>
                      <ul class='sub-menu' id='menu-footer-menu'>
                        <b:loop values='data:links' var='link'>
                          <li><a expr:href='data:link.target'><data:link.name/></a></li>
                        </b:loop>
                      </ul>
                    </nav>
                  </b:includable>
                </b:widget>
              </b:section>
              </div> <span class='distr'>Distributed by <a href='https://protemplates.org/'>Protemplates </a></span>
        </div>
      
    </footer>

    <script src='https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js' type='text/javascript'/>
<b:if cond='data:view.isHomepage'>
    <script id='jquery-migrate-js' src='https://cdnjs.cloudflare.com/ajax/libs/jquery-migrate/3.3.2/jquery-migrate.min.js' type='text/javascript'/>
    <script type='text/javascript'>
        //<![CDATA[

!function(a,b,c,d){function e(b,c){this.settings=null,this.options=a.extend({},e.Defaults,c),this.$element=a(b),this.drag=a.extend({},m),this.state=a.extend({},n),this.e=a.extend({},o),this._plugins={},this._supress={},this._current=null,this._speed=null,this._coordinates=[],this._breakpoint=null,this._width=null,this._items=[],this._clones=[],this._mergers=[],this._invalidated={},this._pipe=[],a.each(e.Plugins,a.proxy(function(a,b){this._plugins[a[0].toLowerCase()+a.slice(1)]=new b(this)},this)),a.each(e.Pipe,a.proxy(function(b,c){this._pipe.push({filter:c.filter,run:a.proxy(c.run,this)})},this)),this.setup(),this.initialize()}function f(a){if(a.touches!==d)return{x:a.touches[0].pageX,y:a.touches[0].pageY};if(a.touches===d){if(a.pageX!==d)return{x:a.pageX,y:a.pageY};if(a.pageX===d)return{x:a.clientX,y:a.clientY}}}function g(a){var b,d,e=c.createElement("div"),f=a;for(b in f)if(d=f[b],"undefined"!=typeof e.style[d])return e=null,[d,b];return[!1]}function h(){return g(["transition","WebkitTransition","MozTransition","OTransition"])[1]}function i(){return g(["transform","WebkitTransform","MozTransform","OTransform","msTransform"])[0]}function j(){return g(["perspective","webkitPerspective","MozPerspective","OPerspective","MsPerspective"])[0]}function k(){return"ontouchstart"in b||!!navigator.msMaxTouchPoints}function l(){return b.navigator.msPointerEnabled}var m,n,o;m={start:0,startX:0,startY:0,current:0,currentX:0,currentY:0,offsetX:0,offsetY:0,distance:null,startTime:0,endTime:0,updatedX:0,targetEl:null},n={isTouch:!1,isScrolling:!1,isSwiping:!1,direction:!1,inMotion:!1},o={_onDragStart:null,_onDragMove:null,_onDragEnd:null,_transitionEnd:null,_resizer:null,_responsiveCall:null,_goToLoop:null,_checkVisibile:null},e.Defaults={items:3,loop:!1,center:!1,mouseDrag:!0,touchDrag:!0,pullDrag:!0,freeDrag:!1,margin:0,stagePadding:0,merge:!1,mergeFit:!0,autoWidth:!1,startPosition:0,rtl:!1,smartSpeed:250,fluidSpeed:!1,dragEndSpeed:!1,responsive:{},responsiveRefreshRate:200,responsiveBaseElement:b,responsiveClass:!1,fallbackEasing:"swing",info:!1,nestedItemSelector:!1,itemElement:"div",stageElement:"div",themeClass:"owl-theme",baseClass:"owl-carousel",itemClass:"owl-item",centerClass:"center",activeClass:"active"},e.Width={Default:"default",Inner:"inner",Outer:"outer"},e.Plugins={},e.Pipe=[{filter:["width","items","settings"],run:function(a){a.current=this._items&&this._items[this.relative(this._current)]}},{filter:["items","settings"],run:function(){var a=this._clones,b=this.$stage.children(".cloned");(b.length!==a.length||!this.settings.loop&&a.length>0)&&(this.$stage.children(".cloned").remove(),this._clones=[])}},{filter:["items","settings"],run:function(){var a,b,c=this._clones,d=this._items,e=this.settings.loop?c.length-Math.max(2*this.settings.items,4):0;for(a=0,b=Math.abs(e/2);b>a;a++)e>0?(this.$stage.children().eq(d.length+c.length-1).remove(),c.pop(),this.$stage.children().eq(0).remove(),c.pop()):(c.push(c.length/2),this.$stage.append(d[c[c.length-1]].clone().addClass("cloned")),c.push(d.length-1-(c.length-1)/2),this.$stage.prepend(d[c[c.length-1]].clone().addClass("cloned")))}},{filter:["width","items","settings"],run:function(){var a,b,c,d=this.settings.rtl?1:-1,e=(this.width()/this.settings.items).toFixed(3),f=0;for(this._coordinates=[],b=0,c=this._clones.length+this._items.length;c>b;b++)a=this._mergers[this.relative(b)],a=this.settings.mergeFit&&Math.min(a,this.settings.items)||a,f+=(this.settings.autoWidth?this._items[this.relative(b)].width()+this.settings.margin:e*a)*d,this._coordinates.push(f)}},{filter:["width","items","settings"],run:function(){var b,c,d=(this.width()/this.settings.items).toFixed(3),e={width:Math.abs(this._coordinates[this._coordinates.length-1])+2*this.settings.stagePadding,"padding-left":this.settings.stagePadding||"","padding-right":this.settings.stagePadding||""};if(this.$stage.css(e),e={width:this.settings.autoWidth?"auto":d-this.settings.margin},e[this.settings.rtl?"margin-left":"margin-right"]=this.settings.margin,!this.settings.autoWidth&&a.grep(this._mergers,function(a){return a>1}).length>0)for(b=0,c=this._coordinates.length;c>b;b++)e.width=Math.abs(this._coordinates[b])-Math.abs(this._coordinates[b-1]||0)-this.settings.margin,this.$stage.children().eq(b).css(e);else this.$stage.children().css(e)}},{filter:["width","items","settings"],run:function(a){a.current&&this.reset(this.$stage.children().index(a.current))}},{filter:["position"],run:function(){this.animate(this.coordinates(this._current))}},{filter:["width","position","items","settings"],run:function(){var a,b,c,d,e=this.settings.rtl?1:-1,f=2*this.settings.stagePadding,g=this.coordinates(this.current())+f,h=g+this.width()*e,i=[];for(c=0,d=this._coordinates.length;d>c;c++)a=this._coordinates[c-1]||0,b=Math.abs(this._coordinates[c])+f*e,(this.op(a,"<=",g)&&this.op(a,">",h)||this.op(b,"<",g)&&this.op(b,">",h))&&i.push(c);this.$stage.children("."+this.settings.activeClass).removeClass(this.settings.activeClass),this.$stage.children(":eq("+i.join("), :eq(")+")").addClass(this.settings.activeClass),this.settings.center&&(this.$stage.children("."+this.settings.centerClass).removeClass(this.settings.centerClass),this.$stage.children().eq(this.current()).addClass(this.settings.centerClass))}}],e.prototype.initialize=function(){if(this.trigger("initialize"),this.$element.addClass(this.settings.baseClass).addClass(this.settings.themeClass).toggleClass("owl-rtl",this.settings.rtl),this.browserSupport(),this.settings.autoWidth&&this.state.imagesLoaded!==!0){var b,c,e;if(b=this.$element.find("img"),c=this.settings.nestedItemSelector?"."+this.settings.nestedItemSelector:d,e=this.$element.children(c).width(),b.length&&0>=e)return this.preloadAutoWidthImages(b),!1}this.$element.addClass("owl-loading"),this.$stage=a("<"+this.settings.stageElement+' class="owl-stage"/>').wrap('<div class="owl-stage-outer">'),this.$element.append(this.$stage.parent()),this.replace(this.$element.children().not(this.$stage.parent())),this._width=this.$element.width(),this.refresh(),this.$element.removeClass("owl-loading").addClass("owl-loaded"),this.eventsCall(),this.internalEvents(),this.addTriggerableEvents(),this.trigger("initialized")},e.prototype.setup=function(){var b=this.viewport(),c=this.options.responsive,d=-1,e=null;c?(a.each(c,function(a){b>=a&&a>d&&(d=Number(a))}),e=a.extend({},this.options,c[d]),delete e.responsive,e.responsiveClass&&this.$element.attr("class",function(a,b){return b.replace(/\b owl-responsive-\S+/g,"")}).addClass("owl-responsive-"+d)):e=a.extend({},this.options),(null===this.settings||this._breakpoint!==d)&&(this.trigger("change",{property:{name:"settings",value:e}}),this._breakpoint=d,this.settings=e,this.invalidate("settings"),this.trigger("changed",{property:{name:"settings",value:this.settings}}))},e.prototype.optionsLogic=function(){this.$element.toggleClass("owl-center",this.settings.center),this.settings.loop&&this._items.length<this.settings.items&&(this.settings.loop=!1),this.settings.autoWidth&&(this.settings.stagePadding=!1,this.settings.merge=!1)},e.prototype.prepare=function(b){var c=this.trigger("prepare",{content:b});return c.data||(c.data=a("<"+this.settings.itemElement+"/>").addClass(this.settings.itemClass).append(b)),this.trigger("prepared",{content:c.data}),c.data},e.prototype.update=function(){for(var b=0,c=this._pipe.length,d=a.proxy(function(a){return this[a]},this._invalidated),e={};c>b;)(this._invalidated.all||a.grep(this._pipe[b].filter,d).length>0)&&this._pipe[b].run(e),b++;this._invalidated={}},e.prototype.width=function(a){switch(a=a||e.Width.Default){case e.Width.Inner:case e.Width.Outer:return this._width;default:return this._width-2*this.settings.stagePadding+this.settings.margin}},e.prototype.refresh=function(){if(0===this._items.length)return!1;(new Date).getTime();this.trigger("refresh"),this.setup(),this.optionsLogic(),this.$stage.addClass("owl-refresh"),this.update(),this.$stage.removeClass("owl-refresh"),this.state.orientation=b.orientation,this.watchVisibility(),this.trigger("refreshed")},e.prototype.eventsCall=function(){this.e._onDragStart=a.proxy(function(a){this.onDragStart(a)},this),this.e._onDragMove=a.proxy(function(a){this.onDragMove(a)},this),this.e._onDragEnd=a.proxy(function(a){this.onDragEnd(a)},this),this.e._onResize=a.proxy(function(a){this.onResize(a)},this),this.e._transitionEnd=a.proxy(function(a){this.transitionEnd(a)},this),this.e._preventClick=a.proxy(function(a){this.preventClick(a)},this)},e.prototype.onThrottledResize=function(){b.clearTimeout(this.resizeTimer),this.resizeTimer=b.setTimeout(this.e._onResize,this.settings.responsiveRefreshRate)},e.prototype.onResize=function(){return this._items.length?this._width===this.$element.width()?!1:this.trigger("resize").isDefaultPrevented()?!1:(this._width=this.$element.width(),this.invalidate("width"),this.refresh(),void this.trigger("resized")):!1},e.prototype.eventsRouter=function(a){var b=a.type;"mousedown"===b||"touchstart"===b?this.onDragStart(a):"mousemove"===b||"touchmove"===b?this.onDragMove(a):"mouseup"===b||"touchend"===b?this.onDragEnd(a):"touchcancel"===b&&this.onDragEnd(a)},e.prototype.internalEvents=function(){var c=(k(),l());this.settings.mouseDrag?(this.$stage.on("mousedown",a.proxy(function(a){this.eventsRouter(a)},this)),this.$stage.on("dragstart",function(){return!1}),this.$stage.get(0).onselectstart=function(){return!1}):this.$element.addClass("owl-text-select-on"),this.settings.touchDrag&&!c&&this.$stage.on("touchstart touchcancel",a.proxy(function(a){this.eventsRouter(a)},this)),this.transitionEndVendor&&this.on(this.$stage.get(0),this.transitionEndVendor,this.e._transitionEnd,!1),this.settings.responsive!==!1&&this.on(b,"resize",a.proxy(this.onThrottledResize,this))},e.prototype.onDragStart=function(d){var e,g,h,i;if(e=d.originalEvent||d||b.event,3===e.which||this.state.isTouch)return!1;if("mousedown"===e.type&&this.$stage.addClass("owl-grab"),this.trigger("drag"),this.drag.startTime=(new Date).getTime(),this.speed(0),this.state.isTouch=!0,this.state.isScrolling=!1,this.state.isSwiping=!1,this.drag.distance=0,g=f(e).x,h=f(e).y,this.drag.offsetX=this.$stage.position().left,this.drag.offsetY=this.$stage.position().top,this.settings.rtl&&(this.drag.offsetX=this.$stage.position().left+this.$stage.width()-this.width()+this.settings.margin),this.state.inMotion&&this.support3d)i=this.getTransformProperty(),this.drag.offsetX=i,this.animate(i),this.state.inMotion=!0;else if(this.state.inMotion&&!this.support3d)return this.state.inMotion=!1,!1;this.drag.startX=g-this.drag.offsetX,this.drag.startY=h-this.drag.offsetY,this.drag.start=g-this.drag.startX,this.drag.targetEl=e.target||e.srcElement,this.drag.updatedX=this.drag.start,("IMG"===this.drag.targetEl.tagName||"A"===this.drag.targetEl.tagName)&&(this.drag.targetEl.draggable=!1),a(c).on("mousemove.owl.dragEvents mouseup.owl.dragEvents touchmove.owl.dragEvents touchend.owl.dragEvents",a.proxy(function(a){this.eventsRouter(a)},this))},e.prototype.onDragMove=function(a){var c,e,g,h,i,j;this.state.isTouch&&(this.state.isScrolling||(c=a.originalEvent||a||b.event,e=f(c).x,g=f(c).y,this.drag.currentX=e-this.drag.startX,this.drag.currentY=g-this.drag.startY,this.drag.distance=this.drag.currentX-this.drag.offsetX,this.drag.distance<0?this.state.direction=this.settings.rtl?"right":"left":this.drag.distance>0&&(this.state.direction=this.settings.rtl?"left":"right"),this.settings.loop?this.op(this.drag.currentX,">",this.coordinates(this.minimum()))&&"right"===this.state.direction?this.drag.currentX-=(this.settings.center&&this.coordinates(0))-this.coordinates(this._items.length):this.op(this.drag.currentX,"<",this.coordinates(this.maximum()))&&"left"===this.state.direction&&(this.drag.currentX+=(this.settings.center&&this.coordinates(0))-this.coordinates(this._items.length)):(h=this.coordinates(this.settings.rtl?this.maximum():this.minimum()),i=this.coordinates(this.settings.rtl?this.minimum():this.maximum()),j=this.settings.pullDrag?this.drag.distance/5:0,this.drag.currentX=Math.max(Math.min(this.drag.currentX,h+j),i+j)),(this.drag.distance>8||this.drag.distance<-8)&&(c.preventDefault!==d?c.preventDefault():c.returnValue=!1,this.state.isSwiping=!0),this.drag.updatedX=this.drag.currentX,(this.drag.currentY>16||this.drag.currentY<-16)&&this.state.isSwiping===!1&&(this.state.isScrolling=!0,this.drag.updatedX=this.drag.start),this.animate(this.drag.updatedX)))},e.prototype.onDragEnd=function(b){var d,e,f;if(this.state.isTouch){if("mouseup"===b.type&&this.$stage.removeClass("owl-grab"),this.trigger("dragged"),this.drag.targetEl.removeAttribute("draggable"),this.state.isTouch=!1,this.state.isScrolling=!1,this.state.isSwiping=!1,0===this.drag.distance&&this.state.inMotion!==!0)return this.state.inMotion=!1,!1;this.drag.endTime=(new Date).getTime(),d=this.drag.endTime-this.drag.startTime,e=Math.abs(this.drag.distance),(e>3||d>300)&&this.removeClick(this.drag.targetEl),f=this.closest(this.drag.updatedX),this.speed(this.settings.dragEndSpeed||this.settings.smartSpeed),this.current(f),this.invalidate("position"),this.update(),this.settings.pullDrag||this.drag.updatedX!==this.coordinates(f)||this.transitionEnd(),this.drag.distance=0,a(c).off(".owl.dragEvents")}},e.prototype.removeClick=function(c){this.drag.targetEl=c,a(c).on("click.preventClick",this.e._preventClick),b.setTimeout(function(){a(c).off("click.preventClick")},300)},e.prototype.preventClick=function(b){b.preventDefault?b.preventDefault():b.returnValue=!1,b.stopPropagation&&b.stopPropagation(),a(b.target).off("click.preventClick")},e.prototype.getTransformProperty=function(){var a,c;return a=b.getComputedStyle(this.$stage.get(0),null).getPropertyValue(this.vendorName+"transform"),a=a.replace(/matrix(3d)?\(|\)/g,"").split(","),c=16===a.length,c!==!0?a[4]:a[12]},e.prototype.closest=function(b){var c=-1,d=30,e=this.width(),f=this.coordinates();return this.settings.freeDrag||a.each(f,a.proxy(function(a,g){return b>g-d&&g+d>b?c=a:this.op(b,"<",g)&&this.op(b,">",f[a+1]||g-e)&&(c="left"===this.state.direction?a+1:a),-1===c},this)),this.settings.loop||(this.op(b,">",f[this.minimum()])?c=b=this.minimum():this.op(b,"<",f[this.maximum()])&&(c=b=this.maximum())),c},e.prototype.animate=function(b){this.trigger("translate"),this.state.inMotion=this.speed()>0,this.support3d?this.$stage.css({transform:"translate3d("+b+"px,0px, 0px)",transition:this.speed()/1e3+"s"}):this.state.isTouch?this.$stage.css({left:b+"px"}):this.$stage.animate({left:b},this.speed()/1e3,this.settings.fallbackEasing,a.proxy(function(){this.state.inMotion&&this.transitionEnd()},this))},e.prototype.current=function(a){if(a===d)return this._current;if(0===this._items.length)return d;if(a=this.normalize(a),this._current!==a){var b=this.trigger("change",{property:{name:"position",value:a}});b.data!==d&&(a=this.normalize(b.data)),this._current=a,this.invalidate("position"),this.trigger("changed",{property:{name:"position",value:this._current}})}return this._current},e.prototype.invalidate=function(a){this._invalidated[a]=!0},e.prototype.reset=function(a){a=this.normalize(a),a!==d&&(this._speed=0,this._current=a,this.suppress(["translate","translated"]),this.animate(this.coordinates(a)),this.release(["translate","translated"]))},e.prototype.normalize=function(b,c){var e=c?this._items.length:this._items.length+this._clones.length;return!a.isNumeric(b)||1>e?d:b=this._clones.length?(b%e+e)%e:Math.max(this.minimum(c),Math.min(this.maximum(c),b))},e.prototype.relative=function(a){return a=this.normalize(a),a-=this._clones.length/2,this.normalize(a,!0)},e.prototype.maximum=function(a){var b,c,d,e=0,f=this.settings;if(a)return this._items.length-1;if(!f.loop&&f.center)b=this._items.length-1;else if(f.loop||f.center)if(f.loop||f.center)b=this._items.length+f.items;else{if(!f.autoWidth&&!f.merge)throw"Can not detect maximum absolute position.";for(revert=f.rtl?1:-1,c=this.$stage.width()-this.$element.width();(d=this.coordinates(e))&&!(d*revert>=c);)b=++e}else b=this._items.length-f.items;return b},e.prototype.minimum=function(a){return a?0:this._clones.length/2},e.prototype.items=function(a){return a===d?this._items.slice():(a=this.normalize(a,!0),this._items[a])},e.prototype.mergers=function(a){return a===d?this._mergers.slice():(a=this.normalize(a,!0),this._mergers[a])},e.prototype.clones=function(b){var c=this._clones.length/2,e=c+this._items.length,f=function(a){return a%2===0?e+a/2:c-(a+1)/2};return b===d?a.map(this._clones,function(a,b){return f(b)}):a.map(this._clones,function(a,c){return a===b?f(c):null})},e.prototype.speed=function(a){return a!==d&&(this._speed=a),this._speed},e.prototype.coordinates=function(b){var c=null;return b===d?a.map(this._coordinates,a.proxy(function(a,b){return this.coordinates(b)},this)):(this.settings.center?(c=this._coordinates[b],c+=(this.width()-c+(this._coordinates[b-1]||0))/2*(this.settings.rtl?-1:1)):c=this._coordinates[b-1]||0,c)},e.prototype.duration=function(a,b,c){return Math.min(Math.max(Math.abs(b-a),1),6)*Math.abs(c||this.settings.smartSpeed)},e.prototype.to=function(c,d){if(this.settings.loop){var e=c-this.relative(this.current()),f=this.current(),g=this.current(),h=this.current()+e,i=0>g-h?!0:!1,j=this._clones.length+this._items.length;h<this.settings.items&&i===!1?(f=g+this._items.length,this.reset(f)):h>=j-this.settings.items&&i===!0&&(f=g-this._items.length,this.reset(f)),b.clearTimeout(this.e._goToLoop),this.e._goToLoop=b.setTimeout(a.proxy(function(){this.speed(this.duration(this.current(),f+e,d)),this.current(f+e),this.update()},this),30)}else this.speed(this.duration(this.current(),c,d)),this.current(c),this.update()},e.prototype.next=function(a){a=a||!1,this.to(this.relative(this.current())+1,a)},e.prototype.prev=function(a){a=a||!1,this.to(this.relative(this.current())-1,a)},e.prototype.transitionEnd=function(a){return a!==d&&(a.stopPropagation(),(a.target||a.srcElement||a.originalTarget)!==this.$stage.get(0))?!1:(this.state.inMotion=!1,void this.trigger("translated"))},e.prototype.viewport=function(){var d;if(this.options.responsiveBaseElement!==b)d=a(this.options.responsiveBaseElement).width();else if(b.innerWidth)d=b.innerWidth;else{if(!c.documentElement||!c.documentElement.clientWidth)throw"Can not detect viewport width.";d=c.documentElement.clientWidth}return d},e.prototype.replace=function(b){this.$stage.empty(),this._items=[],b&&(b=b instanceof jQuery?b:a(b)),this.settings.nestedItemSelector&&(b=b.find("."+this.settings.nestedItemSelector)),b.filter(function(){return 1===this.nodeType}).each(a.proxy(function(a,b){b=this.prepare(b),this.$stage.append(b),this._items.push(b),this._mergers.push(1*b.find("[data-merge]").andSelf("[data-merge]").attr("data-merge")||1)},this)),this.reset(a.isNumeric(this.settings.startPosition)?this.settings.startPosition:0),this.invalidate("items")},e.prototype.add=function(a,b){b=b===d?this._items.length:this.normalize(b,!0),this.trigger("add",{content:a,position:b}),0===this._items.length||b===this._items.length?(this.$stage.append(a),this._items.push(a),this._mergers.push(1*a.find("[data-merge]").andSelf("[data-merge]").attr("data-merge")||1)):(this._items[b].before(a),this._items.splice(b,0,a),this._mergers.splice(b,0,1*a.find("[data-merge]").andSelf("[data-merge]").attr("data-merge")||1)),this.invalidate("items"),this.trigger("added",{content:a,position:b})},e.prototype.remove=function(a){a=this.normalize(a,!0),a!==d&&(this.trigger("remove",{content:this._items[a],position:a}),this._items[a].remove(),this._items.splice(a,1),this._mergers.splice(a,1),this.invalidate("items"),this.trigger("removed",{content:null,position:a}))},e.prototype.addTriggerableEvents=function(){var b=a.proxy(function(b,c){return a.proxy(function(a){a.relatedTarget!==this&&(this.suppress([c]),b.apply(this,[].slice.call(arguments,1)),this.release([c]))},this)},this);a.each({next:this.next,prev:this.prev,to:this.to,destroy:this.destroy,refresh:this.refresh,replace:this.replace,add:this.add,remove:this.remove},a.proxy(function(a,c){this.$element.on(a+".owl.carousel",b(c,a+".owl.carousel"))},this))},e.prototype.watchVisibility=function(){function c(a){return a.offsetWidth>0&&a.offsetHeight>0}function d(){c(this.$element.get(0))&&(this.$element.removeClass("owl-hidden"),this.refresh(),b.clearInterval(this.e._checkVisibile))}c(this.$element.get(0))||(this.$element.addClass("owl-hidden"),b.clearInterval(this.e._checkVisibile),this.e._checkVisibile=b.setInterval(a.proxy(d,this),500))},e.prototype.preloadAutoWidthImages=function(b){var c,d,e,f;c=0,d=this,b.each(function(g,h){e=a(h),f=new Image,f.onload=function(){c++,e.attr("src",f.src),e.css("opacity",1),c>=b.length&&(d.state.imagesLoaded=!0,d.initialize())},f.src=e.attr("src")||e.attr("data-src")||e.attr("data-src-retina")})},e.prototype.destroy=function(){this.$element.hasClass(this.settings.themeClass)&&this.$element.removeClass(this.settings.themeClass),this.settings.responsive!==!1&&a(b).off("resize.owl.carousel"),this.transitionEndVendor&&this.off(this.$stage.get(0),this.transitionEndVendor,this.e._transitionEnd);for(var d in this._plugins)this._plugins[d].destroy();(this.settings.mouseDrag||this.settings.touchDrag)&&(this.$stage.off("mousedown touchstart touchcancel"),a(c).off(".owl.dragEvents"),this.$stage.get(0).onselectstart=function(){},this.$stage.off("dragstart",function(){return!1})),this.$element.off(".owl"),this.$stage.children(".cloned").remove(),this.e=null,this.$element.removeData("owlCarousel"),this.$stage.children().contents().unwrap(),this.$stage.children().unwrap(),this.$stage.unwrap()},e.prototype.op=function(a,b,c){var d=this.settings.rtl;switch(b){case"<":return d?a>c:c>a;case">":return d?c>a:a>c;case">=":return d?c>=a:a>=c;case"<=":return d?a>=c:c>=a}},e.prototype.on=function(a,b,c,d){a.addEventListener?a.addEventListener(b,c,d):a.attachEvent&&a.attachEvent("on"+b,c)},e.prototype.off=function(a,b,c,d){a.removeEventListener?a.removeEventListener(b,c,d):a.detachEvent&&a.detachEvent("on"+b,c)},e.prototype.trigger=function(b,c,d){var e={item:{count:this._items.length,index:this.current()}},f=a.camelCase(a.grep(["on",b,d],function(a){return a}).join("-").toLowerCase()),g=a.Event([b,"owl",d||"carousel"].join(".").toLowerCase(),a.extend({relatedTarget:this},e,c));return this._supress[b]||(a.each(this._plugins,function(a,b){b.onTrigger&&b.onTrigger(g)}),this.$element.trigger(g),this.settings&&"function"==typeof this.settings[f]&&this.settings[f].apply(this,g)),g},e.prototype.suppress=function(b){a.each(b,a.proxy(function(a,b){this._supress[b]=!0},this))},e.prototype.release=function(b){a.each(b,a.proxy(function(a,b){delete this._supress[b]},this))},e.prototype.browserSupport=function(){if(this.support3d=j(),this.support3d){this.transformVendor=i();var a=["transitionend","webkitTransitionEnd","transitionend","oTransitionEnd"];this.transitionEndVendor=a[h()],this.vendorName=this.transformVendor.replace(/Transform/i,""),this.vendorName=""!==this.vendorName?"-"+this.vendorName.toLowerCase()+"-":""}this.state.orientation=b.orientation},a.fn.owlCarousel=function(b){return this.each(function(){a(this).data("owlCarousel")||a(this).data("owlCarousel",new e(this,b))})},a.fn.owlCarousel.Constructor=e}(window.Zepto||window.jQuery,window,document),function(a,b){var c=function(b){this._core=b,this._loaded=[],this._handlers={"initialized.owl.carousel change.owl.carousel":a.proxy(function(b){if(b.namespace&&this._core.settings&&this._core.settings.lazyLoad&&(b.property&&"position"==b.property.name||"initialized"==b.type))for(var c=this._core.settings,d=c.center&&Math.ceil(c.items/2)||c.items,e=c.center&&-1*d||0,f=(b.property&&b.property.value||this._core.current())+e,g=this._core.clones().length,h=a.proxy(function(a,b){this.load(b)},this);e++<d;)this.load(g/2+this._core.relative(f)),g&&a.each(this._core.clones(this._core.relative(f++)),h)},this)},this._core.options=a.extend({},c.Defaults,this._core.options),this._core.$element.on(this._handlers)};c.Defaults={lazyLoad:!1},c.prototype.load=function(c){var d=this._core.$stage.children().eq(c),e=d&&d.find(".owl-lazy");!e||a.inArray(d.get(0),this._loaded)>-1||(e.each(a.proxy(function(c,d){var e,f=a(d),g=b.devicePixelRatio>1&&f.attr("data-src-retina")||f.attr("data-src");this._core.trigger("load",{element:f,url:g},"lazy"),f.is("img")?f.one("load.owl.lazy",a.proxy(function(){f.css("opacity",1),this._core.trigger("loaded",{element:f,url:g},"lazy")},this)).attr("src",g):(e=new Image,e.onload=a.proxy(function(){f.css({"background-image":"url("+g+")",opacity:"1"}),this._core.trigger("loaded",{element:f,url:g},"lazy")},this),e.src=g)},this)),this._loaded.push(d.get(0)))},c.prototype.destroy=function(){var a,b;for(a in this.handlers)this._core.$element.off(a,this.handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.Lazy=c}(window.Zepto||window.jQuery,window,document),function(a){var b=function(c){this._core=c,this._handlers={"initialized.owl.carousel":a.proxy(function(){this._core.settings.autoHeight&&this.update()},this),"changed.owl.carousel":a.proxy(function(a){this._core.settings.autoHeight&&"position"==a.property.name&&this.update()},this),"loaded.owl.lazy":a.proxy(function(a){this._core.settings.autoHeight&&a.element.closest("."+this._core.settings.itemClass)===this._core.$stage.children().eq(this._core.current())&&this.update()},this)},this._core.options=a.extend({},b.Defaults,this._core.options),this._core.$element.on(this._handlers)};b.Defaults={autoHeight:!1,autoHeightClass:"owl-height"},b.prototype.update=function(){this._core.$stage.parent().height(this._core.$stage.children().eq(this._core.current()).height()).addClass(this._core.settings.autoHeightClass)},b.prototype.destroy=function(){var a,b;for(a in this._handlers)this._core.$element.off(a,this._handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.AutoHeight=b}(window.Zepto||window.jQuery,window,document),function(a,b,c){var d=function(b){this._core=b,this._videos={},this._playing=null,this._fullscreen=!1,this._handlers={"resize.owl.carousel":a.proxy(function(a){this._core.settings.video&&!this.isInFullScreen()&&a.preventDefault()},this),"refresh.owl.carousel changed.owl.carousel":a.proxy(function(){this._playing&&this.stop()},this),"prepared.owl.carousel":a.proxy(function(b){var c=a(b.content).find(".owl-video");c.length&&(c.css("display","none"),this.fetch(c,a(b.content)))},this)},this._core.options=a.extend({},d.Defaults,this._core.options),this._core.$element.on(this._handlers),this._core.$element.on("click.owl.video",".owl-video-play-icon",a.proxy(function(a){this.play(a)},this))};d.Defaults={video:!1,videoHeight:!1,videoWidth:!1},d.prototype.fetch=function(a,b){var c=a.attr("data-vimeo-id")?"vimeo":"youtube",d=a.attr("data-vimeo-id")||a.attr("data-youtube-id"),e=a.attr("data-width")||this._core.settings.videoWidth,f=a.attr("data-height")||this._core.settings.videoHeight,g=a.attr("href");if(!g)throw new Error("Missing video URL.");if(d=g.match(/(http:|https:|)\/\/(player.|www.)?(vimeo\.com|youtu(be\.com|\.be|be\.googleapis\.com))\/(video\/|embed\/|watch\?v=|v\/)?([A-Za-z0-9._%-]*)(\&\S+)?/),d[3].indexOf("youtu")>-1)c="youtube";else{if(!(d[3].indexOf("vimeo")>-1))throw new Error("Video URL not supported.");c="vimeo"}d=d[6],this._videos[g]={type:c,id:d,width:e,height:f},b.attr("data-video",g),this.thumbnail(a,this._videos[g])},d.prototype.thumbnail=function(b,c){var d,e,f,g=c.width&&c.height?'style="width:'+c.width+"px;height:"+c.height+'px;"':"",h=b.find("img"),i="src",j="",k=this._core.settings,l=function(a){e='<div class="owl-video-play-icon"></div>',d=k.lazyLoad?'<div class="owl-video-tn '+j+'" '+i+'="'+a+'"></div>':'<div class="owl-video-tn" style="opacity:1;background-image:url('+a+')"></div>',b.after(d),b.after(e)};return b.wrap('<div class="owl-video-wrapper"'+g+"></div>"),this._core.settings.lazyLoad&&(i="data-src",j="owl-lazy"),h.length?(l(h.attr(i)),h.remove(),!1):void("youtube"===c.type?(f="http://img.youtube.com/vi/"+c.id+"/hqdefault.jpg",l(f)):"vimeo"===c.type&&a.ajax({type:"GET",url:"http://vimeo.com/api/v2/video/"+c.id+".json",jsonp:"callback",dataType:"jsonp",success:function(a){f=a[0].thumbnail_large,l(f)}}))},d.prototype.stop=function(){this._core.trigger("stop",null,"video"),this._playing.find(".owl-video-frame").remove(),this._playing.removeClass("owl-video-playing"),this._playing=null},d.prototype.play=function(b){this._core.trigger("play",null,"video"),this._playing&&this.stop();var c,d,e=a(b.target||b.srcElement),f=e.closest("."+this._core.settings.itemClass),g=this._videos[f.attr("data-video")],h=g.width||"100%",i=g.height||this._core.$stage.height();"youtube"===g.type?c='<iframe width="'+h+'" height="'+i+'" src="http://www.youtube.com/embed/'+g.id+"?autoplay=1&v="+g.id+'" frameborder="0" allowfullscreen></iframe>':"vimeo"===g.type&&(c='<iframe src="http://player.vimeo.com/video/'+g.id+'?autoplay=1" width="'+h+'" height="'+i+'" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>'),f.addClass("owl-video-playing"),this._playing=f,d=a('<div style="height:'+i+"px; width:"+h+'px" class="owl-video-frame">'+c+"</div>"),e.after(d)},d.prototype.isInFullScreen=function(){var d=c.fullscreenElement||c.mozFullScreenElement||c.webkitFullscreenElement;return d&&a(d).parent().hasClass("owl-video-frame")&&(this._core.speed(0),this._fullscreen=!0),d&&this._fullscreen&&this._playing?!1:this._fullscreen?(this._fullscreen=!1,!1):this._playing&&this._core.state.orientation!==b.orientation?(this._core.state.orientation=b.orientation,!1):!0},d.prototype.destroy=function(){var a,b;this._core.$element.off("click.owl.video");for(a in this._handlers)this._core.$element.off(a,this._handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.Video=d}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this.core=b,this.core.options=a.extend({},e.Defaults,this.core.options),this.swapping=!0,this.previous=d,this.next=d,this.handlers={"change.owl.carousel":a.proxy(function(a){"position"==a.property.name&&(this.previous=this.core.current(),this.next=a.property.value)},this),"drag.owl.carousel dragged.owl.carousel translated.owl.carousel":a.proxy(function(a){this.swapping="translated"==a.type},this),"translate.owl.carousel":a.proxy(function(){this.swapping&&(this.core.options.animateOut||this.core.options.animateIn)&&this.swap()},this)},this.core.$element.on(this.handlers)};e.Defaults={animateOut:!1,animateIn:!1},e.prototype.swap=function(){if(1===this.core.settings.items&&this.core.support3d){this.core.speed(0);var b,c=a.proxy(this.clear,this),d=this.core.$stage.children().eq(this.previous),e=this.core.$stage.children().eq(this.next),f=this.core.settings.animateIn,g=this.core.settings.animateOut;this.core.current()!==this.previous&&(g&&(b=this.core.coordinates(this.previous)-this.core.coordinates(this.next),d.css({left:b+"px"}).addClass("animated owl-animated-out").addClass(g).one("webkitAnimationEnd mozAnimationEnd MSAnimationEnd oanimationend animationend",c)),f&&e.addClass("animated owl-animated-in").addClass(f).one("webkitAnimationEnd mozAnimationEnd MSAnimationEnd oanimationend animationend",c))}},e.prototype.clear=function(b){a(b.target).css({left:""}).removeClass("animated owl-animated-out owl-animated-in").removeClass(this.core.settings.animateIn).removeClass(this.core.settings.animateOut),this.core.transitionEnd()},e.prototype.destroy=function(){var a,b;for(a in this.handlers)this.core.$element.off(a,this.handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.Animate=e}(window.Zepto||window.jQuery,window,document),function(a,b,c){var d=function(b){this.core=b,this.core.options=a.extend({},d.Defaults,this.core.options),this.handlers={"translated.owl.carousel refreshed.owl.carousel":a.proxy(function(){this.autoplay()
},this),"play.owl.autoplay":a.proxy(function(a,b,c){this.play(b,c)},this),"stop.owl.autoplay":a.proxy(function(){this.stop()},this),"mouseover.owl.autoplay":a.proxy(function(){this.core.settings.autoplayHoverPause&&this.pause()},this),"mouseleave.owl.autoplay":a.proxy(function(){this.core.settings.autoplayHoverPause&&this.autoplay()},this)},this.core.$element.on(this.handlers)};d.Defaults={autoplay:!1,autoplayTimeout:5e3,autoplayHoverPause:!1,autoplaySpeed:!1},d.prototype.autoplay=function(){this.core.settings.autoplay&&!this.core.state.videoPlay?(b.clearInterval(this.interval),this.interval=b.setInterval(a.proxy(function(){this.play()},this),this.core.settings.autoplayTimeout)):b.clearInterval(this.interval)},d.prototype.play=function(){return c.hidden===!0||this.core.state.isTouch||this.core.state.isScrolling||this.core.state.isSwiping||this.core.state.inMotion?void 0:this.core.settings.autoplay===!1?void b.clearInterval(this.interval):void this.core.next(this.core.settings.autoplaySpeed)},d.prototype.stop=function(){b.clearInterval(this.interval)},d.prototype.pause=function(){b.clearInterval(this.interval)},d.prototype.destroy=function(){var a,c;b.clearInterval(this.interval);for(a in this.handlers)this.core.$element.off(a,this.handlers[a]);for(c in Object.getOwnPropertyNames(this))"function"!=typeof this[c]&&(this[c]=null)},a.fn.owlCarousel.Constructor.Plugins.autoplay=d}(window.Zepto||window.jQuery,window,document),function(a){"use strict";var b=function(c){this._core=c,this._initialized=!1,this._pages=[],this._controls={},this._templates=[],this.$element=this._core.$element,this._overrides={next:this._core.next,prev:this._core.prev,to:this._core.to},this._handlers={"prepared.owl.carousel":a.proxy(function(b){this._core.settings.dotsData&&this._templates.push(a(b.content).find("[data-dot]").andSelf("[data-dot]").attr("data-dot"))},this),"add.owl.carousel":a.proxy(function(b){this._core.settings.dotsData&&this._templates.splice(b.position,0,a(b.content).find("[data-dot]").andSelf("[data-dot]").attr("data-dot"))},this),"remove.owl.carousel prepared.owl.carousel":a.proxy(function(a){this._core.settings.dotsData&&this._templates.splice(a.position,1)},this),"change.owl.carousel":a.proxy(function(a){if("position"==a.property.name&&!this._core.state.revert&&!this._core.settings.loop&&this._core.settings.navRewind){var b=this._core.current(),c=this._core.maximum(),d=this._core.minimum();a.data=a.property.value>c?b>=c?d:c:a.property.value<d?c:a.property.value}},this),"changed.owl.carousel":a.proxy(function(a){"position"==a.property.name&&this.draw()},this),"refreshed.owl.carousel":a.proxy(function(){this._initialized||(this.initialize(),this._initialized=!0),this._core.trigger("refresh",null,"navigation"),this.update(),this.draw(),this._core.trigger("refreshed",null,"navigation")},this)},this._core.options=a.extend({},b.Defaults,this._core.options),this.$element.on(this._handlers)};b.Defaults={nav:!1,navRewind:!0,navText:["prev","next"],navSpeed:!1,navElement:"div",navContainer:!1,navContainerClass:"owl-nav",navClass:["owl-prev","owl-next"],slideBy:1,dotClass:"owl-dot",dotsClass:"owl-dots",dots:!0,dotsEach:!1,dotData:!1,dotsSpeed:!1,dotsContainer:!1,controlsClass:"owl-controls"},b.prototype.initialize=function(){var b,c,d=this._core.settings;d.dotsData||(this._templates=[a("<div>").addClass(d.dotClass).append(a("<span>")).prop("outerHTML")]),d.navContainer&&d.dotsContainer||(this._controls.$container=a("<div>").addClass(d.controlsClass).appendTo(this.$element)),this._controls.$indicators=d.dotsContainer?a(d.dotsContainer):a("<div>").hide().addClass(d.dotsClass).appendTo(this._controls.$container),this._controls.$indicators.on("click","div",a.proxy(function(b){var c=a(b.target).parent().is(this._controls.$indicators)?a(b.target).index():a(b.target).parent().index();b.preventDefault(),this.to(c,d.dotsSpeed)},this)),b=d.navContainer?a(d.navContainer):a("<div>").addClass(d.navContainerClass).prependTo(this._controls.$container),this._controls.$next=a("<"+d.navElement+">"),this._controls.$previous=this._controls.$next.clone(),this._controls.$previous.addClass(d.navClass[0]).html(d.navText[0]).hide().prependTo(b).on("click",a.proxy(function(){this.prev(d.navSpeed)},this)),this._controls.$next.addClass(d.navClass[1]).html(d.navText[1]).hide().appendTo(b).on("click",a.proxy(function(){this.next(d.navSpeed)},this));for(c in this._overrides)this._core[c]=a.proxy(this[c],this)},b.prototype.destroy=function(){var a,b,c,d;for(a in this._handlers)this.$element.off(a,this._handlers[a]);for(b in this._controls)this._controls[b].remove();for(d in this.overides)this._core[d]=this._overrides[d];for(c in Object.getOwnPropertyNames(this))"function"!=typeof this[c]&&(this[c]=null)},b.prototype.update=function(){var a,b,c,d=this._core.settings,e=this._core.clones().length/2,f=e+this._core.items().length,g=d.center||d.autoWidth||d.dotData?1:d.dotsEach||d.items;if("page"!==d.slideBy&&(d.slideBy=Math.min(d.slideBy,d.items)),d.dots||"page"==d.slideBy)for(this._pages=[],a=e,b=0,c=0;f>a;a++)(b>=g||0===b)&&(this._pages.push({start:a-e,end:a-e+g-1}),b=0,++c),b+=this._core.mergers(this._core.relative(a))},b.prototype.draw=function(){var b,c,d="",e=this._core.settings,f=(this._core.$stage.children(),this._core.relative(this._core.current()));if(!e.nav||e.loop||e.navRewind||(this._controls.$previous.toggleClass("disabled",0>=f),this._controls.$next.toggleClass("disabled",f>=this._core.maximum())),this._controls.$previous.toggle(e.nav),this._controls.$next.toggle(e.nav),e.dots){if(b=this._pages.length-this._controls.$indicators.children().length,e.dotData&&0!==b){for(c=0;c<this._controls.$indicators.children().length;c++)d+=this._templates[this._core.relative(c)];this._controls.$indicators.html(d)}else b>0?(d=new Array(b+1).join(this._templates[0]),this._controls.$indicators.append(d)):0>b&&this._controls.$indicators.children().slice(b).remove();this._controls.$indicators.find(".active").removeClass("active"),this._controls.$indicators.children().eq(a.inArray(this.current(),this._pages)).addClass("active")}this._controls.$indicators.toggle(e.dots)},b.prototype.onTrigger=function(b){var c=this._core.settings;b.page={index:a.inArray(this.current(),this._pages),count:this._pages.length,size:c&&(c.center||c.autoWidth||c.dotData?1:c.dotsEach||c.items)}},b.prototype.current=function(){var b=this._core.relative(this._core.current());return a.grep(this._pages,function(a){return a.start<=b&&a.end>=b}).pop()},b.prototype.getPosition=function(b){var c,d,e=this._core.settings;return"page"==e.slideBy?(c=a.inArray(this.current(),this._pages),d=this._pages.length,b?++c:--c,c=this._pages[(c%d+d)%d].start):(c=this._core.relative(this._core.current()),d=this._core.items().length,b?c+=e.slideBy:c-=e.slideBy),c},b.prototype.next=function(b){a.proxy(this._overrides.to,this._core)(this.getPosition(!0),b)},b.prototype.prev=function(b){a.proxy(this._overrides.to,this._core)(this.getPosition(!1),b)},b.prototype.to=function(b,c,d){var e;d?a.proxy(this._overrides.to,this._core)(b,c):(e=this._pages.length,a.proxy(this._overrides.to,this._core)(this._pages[(b%e+e)%e].start,c))},a.fn.owlCarousel.Constructor.Plugins.Navigation=b}(window.Zepto||window.jQuery,window,document),function(a,b){"use strict";var c=function(d){this._core=d,this._hashes={},this.$element=this._core.$element,this._handlers={"initialized.owl.carousel":a.proxy(function(){"URLHash"==this._core.settings.startPosition&&a(b).trigger("hashchange.owl.navigation")},this),"prepared.owl.carousel":a.proxy(function(b){var c=a(b.content).find("[data-hash]").andSelf("[data-hash]").attr("data-hash");this._hashes[c]=b.content},this)},this._core.options=a.extend({},c.Defaults,this._core.options),this.$element.on(this._handlers),a(b).on("hashchange.owl.navigation",a.proxy(function(){var a=b.location.hash.substring(1),c=this._core.$stage.children(),d=this._hashes[a]&&c.index(this._hashes[a])||0;return a?void this._core.to(d,!1,!0):!1},this))};c.Defaults={URLhashListener:!1},c.prototype.destroy=function(){var c,d;a(b).off("hashchange.owl.navigation");for(c in this._handlers)this._core.$element.off(c,this._handlers[c]);for(d in Object.getOwnPropertyNames(this))"function"!=typeof this[d]&&(this[d]=null)},a.fn.owlCarousel.Constructor.Plugins.Hash=c}(window.Zepto||window.jQuery,window,document);
$(".main_slider .slider").owlCarousel({
      items: 1,
      autoplay: false,
      loop: true,
      autoplayTimeout: 3000,
      nav: false
    });
//]]>
      </script>

    </b:if>


    <script type='text/javascript'>
        //<![CDATA[
 var previousScroll = 0;
    $(window).scroll(function(){
       var currentScroll = $(this).scrollTop();
       if (currentScroll > previousScroll){
           $("header .mid").addClass('scroll_funcs');
       } else {
          $("header .mid").removeClass('scroll_funcs');
       }
       previousScroll = currentScroll;
    });$("img[src='//resources.blogblog.com/img/blank.gif']").attr('src','https://4.bp.blogspot.com/-oSjP8F09qxo/Wy1J9dp7b0I/AAAAAAAACF0/ggcRfLCFQ9s2SSaeL9BFSE2wyTYzQaTyQCK4BGAYYCw/s35-r/avatar.jpg');
        $("a.menu_toggle").click(function () {
			$("header .m_menu").toggleClass('menu_showw');
			return false;
		});
		$("li.search a").click(function(){
			$(this).closest('li.search').find("input").fadeToggle(200);
			return false;
		});
		$("a.m_search").click(function(){
			$("div.mob_search").toggleClass('ar-flex');
			$("a.m_search i").toggleClass('fa-times');
			return false;
		});
$(".comments-area").each(function() {
	var a = $(this);
	var c = a.find(".secondary-text .comment-reply"),
		d = a.find("#top-continue");
	c.on("click", function() {
		d.show();
	});
	d.on("click", function() {
		d.hide();
	});
});
$(window).scroll(function () {
			scrtop = $(document).scrollTop();
			if (scrtop > 320) {
				$("a.scroll_top").fadeIn(200);
			} else {
				$("a.scroll_top").fadeOut(10);
			}
		});
		$("a.scroll_top").click(function () {
			$("html").animate({
				"scrollTop": 0
			}, 400);
			$("body").animate({
				"scrollTop": 0
			}, 400);
			return false;
		});
        //]]>
      </script>
        <b:if cond='data:view.isMultipleItems'>
<script type='text/javascript'>
  /*<![CDATA[*/
    var urlactivepage=location.href;
    var home_page="/";

if(typeof firstText=="undefined")firstText="First";if(typeof lastText=="undefined")lastText="Last";var noPage;var currentPage;var currentPageNo;var postLabel;pagecurrentg();function looppagecurrentg(pageInfo){var html='';pageNumber=parseInt(numPages / 2);if(pageNumber==numPages-pageNumber){numPages=pageNumber*2+1}
pageStart=currentPageNo-pageNumber;if(pageStart<1)pageStart=1;lastPageNo=parseInt(pageInfo / perPage)+1;if(lastPageNo-1==pageInfo / perPage)lastPageNo=lastPageNo-1;pageEnd=pageStart+numPages-1;if(pageEnd>lastPageNo)pageEnd=lastPageNo;var prevNumber=parseInt(currentPageNo)-1;
if(pageStart>1){if(currentPage=="page"){html+='<span class="displaypageNum"><a href="'+home_page+'">1</a></span>'}else{html+='<span class="displaypageNum"><a href="/search/label/'+postLabel+'?&max-results='+perPage+'">1</a></span>'}}
if(pageStart>2){html+='<span class="dots">...</span>'}
for(var jj=pageStart;jj<=pageEnd;jj++){if(currentPageNo==jj){html+='<span class="pagecurrent">'+jj+'</span>'}else if(jj==1){if(currentPage=="page"){html+='<span class="displaypageNum"><a href="'+home_page+'">1</a></span>'}else{html+='<span class="displaypageNum"><a href="/search/label/'+postLabel+'?&max-results='+perPage+'">1</a></span>'}}else{if(currentPage=="page"){html+='<span class="displaypageNum"><a href="#" onclick="redirectpage('+jj+');return false">'+jj+'</a></span>'}else{html+='<span class="displaypageNum"><a href="#" onclick="redirectlabel('+jj+');return false">'+jj+'</a></span>'}}}
if(pageEnd<lastPageNo-1){html+='<span class="dots">...</span>'}
if(pageEnd<lastPageNo){if(currentPage=="page"){html+='<span class="displaypageNum"><a href="#" onclick="redirectpage('+lastPageNo+');return false">'+lastPageNo+'</a></span>'}else{html+='<span class="displaypageNum"><a href="#" onclick="redirectlabel('+lastPageNo+');return false">'+lastPageNo+'</a></span>'}}
var nextnumber=parseInt(currentPageNo)+1;
var pageArea=document.getElementsByName("pageArea");var blogPager=document.getElementById("blog-pager");for(var p=0;p<pageArea.length;p++){pageArea[p].innerHTML=html}
if(pageArea&&pageArea.length>0){html=''}
if(blogPager){blogPager.innerHTML=html}}
function totalcountdata(root){var feed=root.feed;var totaldata=parseInt(feed.openSearch$totalResults.$t,10);looppagecurrentg(totaldata)}
function pagecurrentg(){var thisUrl=urlactivepage;if(thisUrl.indexOf("/search/label/")!=-1){if(thisUrl.indexOf("?updated-max")!=-1){postLabel=thisUrl.substring(thisUrl.indexOf("/search/label/")+14,thisUrl.indexOf("?updated-max"))}else{postLabel=thisUrl.substring(thisUrl.indexOf("/search/label/")+14,thisUrl.indexOf("?&max"))}}
if(thisUrl.indexOf("?q=")==-1&&thisUrl.indexOf(".html")==-1){if(thisUrl.indexOf("/search/label/")==-1){currentPage="page";if(urlactivepage.indexOf("#PageNo=")!=-1){currentPageNo=urlactivepage.substring(urlactivepage.indexOf("#PageNo=")+8,urlactivepage.length)}else{currentPageNo=1}
document.write("<script src=\""+home_page+"feeds/posts/summary?max-results=1&alt=json-in-script&callback=totalcountdata\"><\/script>")}else{currentPage="label";if(thisUrl.indexOf("&max-results=")==-1){perPage=20}
if(urlactivepage.indexOf("#PageNo=")!=-1){currentPageNo=urlactivepage.substring(urlactivepage.indexOf("#PageNo=")+8,urlactivepage.length)}else{currentPageNo=1}
document.write('<script src="'+home_page+'feeds/posts/summary/-/'+postLabel+'?alt=json-in-script&callback=totalcountdata&max-results=1" ><\/script>')}}}
function redirectpage(numberpage){jsonstart=(numberpage-1)*perPage;noPage=numberpage;var nameBody=document.getElementsByTagName('head')[0];var newInclude=document.createElement('script');newInclude.type='text/javascript';newInclude.setAttribute("src",home_page+"feeds/posts/summary?start-index="+jsonstart+"&max-results=1&alt=json-in-script&callback=finddatepost");nameBody.appendChild(newInclude)}
function redirectlabel(numberpage){jsonstart=(numberpage-1)*perPage;noPage=numberpage;var nameBody=document.getElementsByTagName('head')[0];var newInclude=document.createElement('script');newInclude.type='text/javascript';newInclude.setAttribute("src",home_page+"feeds/posts/summary/-/"+postLabel+"?start-index="+jsonstart+"&max-results=1&alt=json-in-script&callback=finddatepost");nameBody.appendChild(newInclude)}
function finddatepost(root){post=root.feed.entry[0];var timestamp1=post.published.$t.substring(0,19)+post.published.$t.substring(23,29);var timestamp=encodeURIComponent(timestamp1);if(currentPage=="page"){var pAddress="/search?updated-max="+timestamp+"&max-results="+perPage+"#PageNo="+noPage}else{var pAddress="/search/label/"+postLabel+"?updated-max="+timestamp+"&max-results="+perPage+"#PageNo="+noPage}
location.href=pAddress}

  /*]]>*/
</script>
</b:if>
        <script src='/feeds/comments/default?alt=json-in-script&amp;max-results=3&amp;callback=showrecentcomments'/>
  </body>
</html>
