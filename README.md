# barbearia<!doctype html>
<html class="ets-dark">
	<head>
		<!-- Latest IE, Enable Chrome frame, and require ActiveX(flash) in Windows UI mode IE10 -->
		<meta http-equiv="X-UA-Compatible" content="IE=edge, requiresActiveX=true, chrome=1"/>
		<meta name="viewport" content="width=device-width,initial-scale=1.0,minimum-scale=1.0,maximum-scale=1.0,user-scalable=no">
		<meta name="format-detection" content="telephone=no" />
		<meta name="referrer" content="unsafe-url" />
		<meta name="referrer" content="always" />
		<meta charset="utf-8"/>
		<title>EF</title>

		<!-- gudstrap -->
		<link rel="stylesheet" type="text/css" href="https://learn.corporate.ef.com/_shared/gudstrap/1.1.1-ef.1/css/gudstrap.css"/>

		
		<link rel="stylesheet" type="text/css" href="https://learn.corporate.ef.com/new-studyplan/static//school-ui-shared/fonts/EFCircular.css" media="all" />
		<link rel="stylesheet" type="text/css" href="https://learn.corporate.ef.com/new-studyplan/static//school-ui-shared/css/ets-global.min.css" media="all"/>
		<link rel="stylesheet" type="text/css" href="https://learn.corporate.ef.com/new-studyplan/static//school-ui-activity/css/ets-act-main.min.css" media="all"/>
		<link rel="stylesheet" type="text/css" href="https://learn.corporate.ef.com/new-studyplan/static//school-ui-activity-container/css/ets-acc-main.min.css" media="all" />
		<link rel="stylesheet" type="text/css" href="https://learn.corporate.ef.com/new-studyplan/static//school-ui-studyplan-b2b/css/ets-sp-main.min.css" media="all" />
		

		<link rel="stylesheet" type="text/css" href="https://learn.corporate.ef.com/new-studyplan/static//techcheck-ui/css/tck-main.min.css" media="all" />
		<!-- tooltips-ui -->

		<!-- mediaelement css, some rules may be overridden by school-ui-shared -->
		<link rel="stylesheet" type="text/css" href="https://learn.corporate.ef.com/_shared/mediaelement/2.22/mediaelementplayer.min.css" media="all"/>
		<!--shared libs css-->
		<link rel="stylesheet" type="text/css" href="https://learn.corporate.ef.com/_shared/fancybox/1.3.4-ef.1/jquery.fancybox.css" media="all"/>
		<link rel="stylesheet" type="text/css" href="https://learn.corporate.ef.com/_shared/fancybox/2.1.5/jquery.fancybox.css" media="all"/>
		<link rel="stylesheet" type="text/css" href="https://learn.corporate.ef.com/_shared/jquery-scrollbar/3.1.13/jquery.mCustomScrollbar.css"/>

		
		<link rel="stylesheet" type="text/css" href="https://learn.corporate.ef.com/iframed-study/1.0.7/campus-studyplan-ui/css/main.min.css" />
		

		

		

<script type="application/json" id="endpoints--env-config">{
  "accountService": "/api/account/v1/accounts",
  "asrEvalzipPathPrefix": "/api/legacy-school/asr/handlers",
  "asrLog": "/api/legacy-school/services/school/courseware/LogAsrTracking.ashx",
  "exportPdfUrl": "/api/school-proxy/v1/commands/export/pdf",
  "queryproxy": "/api/school-proxy/v1/troop",
  "certUrl": "/iframed-study/certificate?key=",
  "headerfooter": {
    "headersettings": "/api/header-settings/v1/services/shared/headersetting",
    "headerprofile": "/api/header-settings/v1/community/widgets/headerprofile",
    "schoolMenuTop": "/api/header-settings/v1/school/menu/top",
    "schoolMenuAll": "/api/header-settings/v1/school/menu/all",
    "communityMenuLoad": "/api/header-settings/v1/community/menu/load",
    "changeLanguage": "/api/header-settings/v1/services/shared/context/changelanguage"
  },
  "placementTest": {
    "initTest": "/api/school-proxy/v1/placement-test/init",
    "testData": "/api/school-proxy/v1/placement-test"
  },
  "levelTest": {
    "startTest": "/api/school-proxy/v1/commands/leveltest/start",
    "submitSectionScore": "/api/school-proxy/v1/commands/leveltest/submitscore"
  },
  "account": "/api/account/v1/accounts",
  "enrollment": "/api/enrollment/v1/enrollments",
  "commerceBase": "/api/commerce-gateway",
  "commerce": {
    "member": "/api/commerce-gateway/member",
    "studentType": "/api/commerce-gateway/member/student-type",
    "subscription": "/api/commerce-gateway/member/subscription",
    "order": {
      "search": "/api/commerce-gateway/order/search"
    },
    "account": "/api/commerce-gateway/account"
  },
  "student": {
    "settings": "/api/student-settings/v1/student/settings"
  }
}
</script>
<script type="application/json" id="paths--env-config">{
  "placementTest": "/study/test/placementtest/",
  "bookNewPL40Class": "/classes/pl",
  "bookNewPL20Class": "/classes/pl?type=PL20",
  "bookNewCP20Class": "/study/studyplan#study/",
  "changeCourse": "/change-course",
  "evcDownloadApp": "/classes/ef-classroom-app-download",
  "evcMybookings": "/classes/mybookings",
  "evcRoom": "/iframed-classes/room",
  "evcMobileBooking": "/evc-mobile/booking",
  "evcMobileListing": "/evc-mobile/booking",
  "groupClass": "/classes/gl",
  "myBookings": "/classes/mybookings?icid=PL_enter",
  "progressGoals": "/progress-goals",
  "studyPlan": "/study/studyplan",
  "levelTest": "/study/leveltest",
  "enrollment": "/onboarding",
  "uiRedirect": "/",
  "efset30": "/efset30",
  "helpCenterUrl": "https://support.corporate.ef.com/s/login?startURL=/s/&region=other"
}
</script>
<script type="application/json" id="platformAuth--env-config">{
  "queryproxy": {
    "endpoint": "/api/school-proxy/v1/troop"
  }
}
</script>

	</head>
	
	<body class="iframed-self-study">
	
		<div class="gud ets-sp-migtation" data-weave="school-ui-studyplan/widget/migration/main"></div>
		<div class="gud ets-sp-init" data-iframe-height data-delay-stop="200" data-weave="school-ui-studyplan/widget/initialization/main school-ui-studyplan/widget/initialization/hash troopjs-ef/spinner/widget"></div>
		<div class="ets-ui-acc-wrap ets-none" data-weave="school-ui-activity-container/widget/activity/activity-container/main"></div>
		<div data-weave="school-ui-activity/shared/asr/asr-init" class="ets-asr-show" data-action="enable"></div>
		<div class="ets-ui-tts" data-z-index="1100" data-weave="troopjs-ef/ccl/placeholder('school-ui-shared/tts/main')" data-ccl="school.courseware.e12.enableTTS"></div>
		<div data-weave="school-ui-shared/plugins/techcheck/main"></div>
		<script type="text/javascript">
			var require = (function() {

				return {
					
					"baseUrl": "https://learn.corporate.ef.com/",
					"paths": {
						"get-env-config": "_shared/@ef/get-env-config/0.0.1/index"
					},
					"deps": ["get-env-config"],
					
					"callback" : function (getEnvConfig) {

						var partnerCCL;

						
						partnerCCL = '';
						

						var config = {
							"app-version":{
								"school-ui-activity": "{CCL:school.ui.activity.version}",
								"school-ui-activity-container": "{CCL:school.ui.activity.container.version}",
								"school-ui-shared": "{CCL:school.ui.shared.version}",
								"school-ui-studyplan": "{CCL:school.ui.studyplan.version}",
								"campus-studyplan-ui": "{CCL:campus-studyplan-ui.version}"
							},
							
							"cacheServer": "https://learn.corporate.ef.com"
						};

						

						
						var endpoints = getEnvConfig("endpoints")
						var paths = getEnvConfig("paths")

						config["app-version"]["school-ui-activity"] = "";
						config["app-version"]["school-ui-activity-container"] = "";
						config["app-version"]["school-ui-shared"] = "";
						config["app-version"]["school-ui-studyplan"] = "";
						config["app-version"]["campus-studyplan-ui"] = "";
						config["exportPdfUrl"] = endpoints.exportPdfUrl || "/api/school-proxy/v1/commands/export/pdf";
						


						// the version of requirejs we use here doesn't deep merge
						// calls for require.config({config: {}})
						// so we have to do it manually and only call once require.config({config:{}})
						var troop2ModulesConfig = {
							
							"school-ui": config,
							"school-ui-activity": config,
							"school-ui-activity-container": config,
							"school-ui-activity-container/widget/activity/activity-manager/main": config,
							"school-ui-shared/module": config,
							"troopjs-data/query/service": {
								"url" : "/services/shared/queryproxy",
								"type" : "post"
							},
							
							"school-ui-studyplan/module": {
								"cacheServer": config["cacheServer"],
								"certUrl": endpoints.certUrl || "/study/certificate?key=",
								"blurbIds": {
									"cpNextUnit": "719648",
									"cpCourseChange": "701906"
								},
								"changeCourseUrl": paths.changeCourse,
								"progressReportUrl": paths.progressReport,
								"progressGoals": paths.progressGoals,
								"levelTestPath": paths.levelTest,
								"useLegacyUnitId": false
							},
							"techcheck-ui/widget/shared/live-chat/main": paths,
							"school-ui-shared/widget/unit-overview/container/main": {
								"showDownloadButton": false
							},
							
						};
						var troop1ModulesConfig = {
							"school-ui": config,
							"school-ui-shared/module": config,
							"client-state/adapters/context" : {
								data : {
									
									"page.name"				: "Study Plan",
									"page.siteSection"		: "Course",
									"page.siteSubSection"	: "Online Study"
								}
							}
						};


						var deps1x = [
						];
						var deps2x = [
							"livechat-ui"
						];
						if (!config.debug) {
							deps1x.push("school-ui-shared");
							deps1x.push("tooltips-ui");
							deps1x.push("when");

							deps2x.push("techcheck-ui");
							deps2x.push("school-ui-activity");
							deps2x.push("school-ui-activity-container");
							deps2x.push("school-ui-shared");
							deps2x.push("school-ui-studyplan");
							deps2x.push("campus-studyplan-ui");

							if(partnerCCL && partnerCCL.name){
								deps2x.push(partnerCCL.name);
							}
						}

						var callbacks = [];

						require.config({
							"context" : "troopjs-1.0",

							"waitSeconds": 0,

							"baseUrl": "https://learn.corporate.ef.com/",

							"packages": [
								
								{
									"name": "school-ui-shared",
									"location": "new-studyplan/static//school-ui-shared/js/1.x",
									"main": "app-built.min"
								},
								
								{
									"name": "legacy/translator",
									"location": "school/_scripts",
									"main": "translator.min"
								},
								{
									"name": "tooltips-ui",
									"location": "_shared/tooltips-ui/0.5.6/js",
									"main": "app-built.min"
								},
								{
									"name": "troopjs-bundle",
									"location": "_shared/troopjs-bundle/1.0.9-16",
									"main": "troopjs-bundle.min"
								},
								{
									"name": "troopjs-ef",
									"location": "_shared/troopjs-ef/1.0.0-78",
									"main": "nodeps"
								},
								{
									"name": "jquery",
									"location": "_shared/jquery/1.7.2",
									"main": "jquery.min"
								},
								{
									"name": "jquery-jsonp",
									"location": "_shared/jquery-jsonp/2.1.4",
									"main": "jquery-jsonp.min"
								},
								{
									"name": "jquery.easing",
									"location": "_shared/jquery-easing/1.3",
									"main": "jquery.easing.min"
								},
								{
									"name": "jquery.mousewheel",
									"location": "_shared/jquery-mousewheel/3.0.6",
									"main": "jquery.mousewheel.min"
								},
								{
									"name": "jquery.ui",
									"location": "_shared/jquery-ui/1.8.22",
									"main": "jquery-ui.min"
								},
								{
									"name": "jquery.transit",
									"location": "_shared/jquery-transit/0.1.3",
									"main": "jquery.transit.min"
								},
								{
									"name": "jquery.jscrollpane",
									"location": "_shared/jquery-jscrollpane/2.0.0b12",
									"main": "jquery.scrollpane.min"
								},
								{
									"name": "jquery.scrollto",
									"location": "_shared/jquery-scrollto/1.4.2",
									"main": "jquery.scrollto.min"
								},
								{
									"name": "jquery.viewport",
									"location": "_shared/jquery-viewport/1.0",
									"main": "jquery.viewport.min"
								},
								{
									"name": "jquery.flip",
									"location": "_shared/jquery-flip/0.9.10-shim",
									"main": "jquery.flip.min"
								},
								{
									"name": "jquery.form",
									"location": "_shared/jquery-form/3.20",
									"main": "jquery.form.min"
								},
								{
									"name": "swfobject",
									"location": "_shared/swfobject/2.2",
									"main": "swfobject.min"
								},
								{
									"name": "base64",
									"location": "_shared/ScriptSharp/0.5.6",
									"main": "base64-amd.min"
								},
								{
									"name": "underscore",
									"location": "_shared/underscore.js/1.3.3",
									"main": "underscore.min"
								},
								{
									"name": "gollum",
									"location": "_shared/gollum/1.0.0-3",
									"main": "gollum.min"
								},
								{
									"name": "string.split",
									"location": "_shared/string-split/0",
									"main": "string-split.min"
								},
								{
									"name": "tooltip",
									"location": "_shared/tooltip/0",
									"main": "tooltip.min"
								},
								{
									"name": "jquery.counter",
									"location": "_shared/jquery-counter/2.2",
									"main": "jquery.counter.min"
								},
								{
									"name": "mediaelement-and-player",
									"location": "_shared/mediaelement/2.22",
									"main": "mediaelement-and-player.min"
								},
								{
									"name": "mediaelement-plugin-ef",
									"location": "_shared/mediaelement-plugin-ef/1.0.2",
									"main": "app-built.min"
								},
								{
									"name": "markdownjs",
									"location": "_shared/markdown-js/0.4.0",
									"main": "markdown.min"
								},
								{
									"name": "jquery-tipsy",
									"location": "_shared/jquery-tipsy/1.0.0a-refined/javascripts",
									"main": "jquery.tipsy.min"
								},
								{
									"name": "json2",
									"location": "_shared/json2/20111019",
									"main": "json2.min"
								},
								{
									"name": "Cookies",
									"location": "_shared/Cookies/0.3.1",
									"main": "cookies.min"
								},
								{
									"name": "poly",
									"location": "_shared/poly/0.5.1-43-ef.1",
									"main": "poly-bundle.min"
								},
								{
									"name": "client-tracking",
									"location": "_shared/client-tracking/1.0.18",
									"main": "bundle-troopjs.min"
								},
								{
									"name": "when",
									"location": "_shared/when/3.7.7-ef.1",
									"main": "when-bundle.min"
								},
								{
									"name": "jquery.fancybox",
									"location": "_shared/fancybox/1.3.4-ef.1",
									"main": "jquery.fancybox.min"
								},
								{
									"name": "moment",
									"location": "_shared/moment/2.10.3",
									"main": "moment-with-locales.min"
								},
								{
									"name": "jquery.countdown",
									"location": "_shared/jquery.countdown/2.1.0",
									"main": "jquery.countdown.min"
								},
								{
									"name": "jquery.scrollbar",
									"location": "_shared/jquery-scrollbar/3.1.13",
									"main": "jquery.mCustomScrollbar.min"
								},
								{
									"name": "asr-core",
									"location": "_shared/asr-core/1.2.0",
									"main": "main.min"
								}
							],

							"shim" : {
								"json2" : {
									exports : function () {
										return window.JSON;
									}
								},
								"jquery.fancybox" : {
									deps :[ "jquery", "jquery.easing", "jquery.mousewheel" ],
									exports : function ($, easing, mousewheel) {
										return $;
									}
								},
								"jquery.easing" : {
									deps :[ "jquery" ],
									exports : function ($) {
										return $;
									}
								},
								"jquery.mousewheel" :  {
									deps :[ "jquery" ],
									exports : function ($) {
										return $;
									}
								},
								"jquery.scrollto": {
									deps: ["jquery"],
									exports: function($) {
										return $;
									}
								},
								"jquery.viewport": {
									deps: ["jquery"],
									exports: function($) {
										return $;
									}
								},
								"mediaelement-and-player": {
									deps: ["jquery"],
									exports: function () {
										return window.mejs;
									}
								},
								"jquery.ui": {
									deps: ["jquery"],
									exports: function($){
										return $;
									}
								},
								"jquery.transit" : ["jquery"],
								"jquery.flip":{
									deps: ["jquery"],
									exports: function($){
										return $;
									}
								},
								"underscore": {
									exports: function(){
										return _;
									}
								},
								'jquery.counter': {
									deps :[ "jquery" ],
									exports : function ($) {
										return $;
									}
								},
								"jquery.form": {
									deps: ['jquery'],
									exports: function ($) {
										return $;
									}
								},
								"swfobject": {
									exports: function () {
										return window.swfobject;
									}
								},
								"markdownjs": {
									exports: function () {
										return window.markdown;
									}
								},
								"jquery-tipsy": {
									deps: ['jquery'],
									exports: function($) {
										return $;
									}
								},
								"client-tracking": {
									deps: ["troopjs-ef"]
								}
							},

							"map" : {
								"*" : {
									"template" : "troopjs-requirejs/template",
									"logger" : "troopjs-core/logger/pubsub",
									"config" : "troopjs-ef/config"
								}
							},

							"deps": ["require", "jquery", "poly", "troopjs-bundle", "troopjs-ef"],

							"config": troop1ModulesConfig,

							"callback" : function (localRequire, jQuery) {

								define("jquery.mediaelement.player",
										["jquery", "mediaelement-and-player"],
										function ($) {
											
											return $;
										});

								define("jquery.mediaelement",
										["jquery", "mediaelement-and-player"],
										function ($) {
											
											return $;
										});


								localRequire([ "config" ].concat(deps1x), function (_config) {

									jQuery.extend(_config, config);

									localRequire([
										"troopjs-ef/widget/application",
										"troopjs-ef/data/cache",
										"troopjs-ef/service/query",
										"troopjs-core/remote/ajax",
										"troopjs-jquery/weave",
										"troopjs-jquery/destroy",
										"troopjs-jquery/action",
										"troopjs-jquery/resize",
										"troopjs-jquery/dimensions",
										"troopjs-jquery/hashchange",
										"client-tracking"
									], function (Application, Cache, Query, Ajax) {
											Ajax().start();
											Query(Cache());
//										callbacks.push(function () {
//											Application(jQuery("html"), "bootstrap").start();
//										});
									});
								});
							}
						});

						require.config({
							"context" : "troopjs-2.0",

							"waitSeconds": 0,

							"baseUrl": "https://learn.corporate.ef.com/",

							"packages": [
								
								{
									"name": "school-ui-shared",
									"location": "new-studyplan/static//school-ui-shared/js/2.x",
									"main": "app-built.min"
								},
								{
									"name": "school-ui-studyplan",
									"location": "new-studyplan/static//school-ui-studyplan-b2b/js",
									"main": "app-built.min"
								},
								{
									"name": "school-ui-activity",
									"location": "new-studyplan/static//school-ui-activity/js",
									"main": "app-built.min"
								},
								{
									"name": "school-ui-activity-container",
									"location": "new-studyplan/static//school-ui-activity-container/js",
									"main": "app-built.min"
								},
								{
									"name": "campus-studyplan-ui",
									"location": "iframed-study/1.0.7/campus-studyplan-ui/js",
									"main": "app-built.min"
								},
								
								{
									"name": "techcheck-ui",
									"location": "new-studyplan/static//techcheck-ui/js",
									"main": "app-built.min"
								},
								{
									"name": partnerCCL && partnerCCL.name ? partnerCCL.name : "",
									"location": partnerCCL && partnerCCL.name ? (partnerCCL.location + "/" + (partnerCCL.version ? partnerCCL.version : "snapshot") + "/" + "js") : "",
									"main": "app-built.min"
								},
								{
									"name": "troopjs-bundle",
									"location": "_shared/troopjs-bundle/2.0.2-8-ef.4",
									"main": "maxi.min"
								},
								{
									"name": "troopjs-ef",
									"location": "_shared/troopjs-ef/2.0.2-ef.5",
									"main": "nodeps"
								},
								{
									"name": "jquery",
									"location": "_shared/jquery/1.9.1",
									"main": "jquery-1.9.1.min"
								},
								{
									"name": "jquery.gudstrap",
									"location": "_shared/gudstrap/1.1.1-ef.1/js",
									"main": "gudstrap.min"
								},
								{
									"name": "jquery-jsonp",
									"location": "_shared/jquery-jsonp/2.1.4",
									"main": "jquery-jsonp.min"
								},
								{
									"name": "poly",
									"location": "_shared/poly/0.5.1-43-ef.1",
									"main": "poly-bundle.min"
								},
								{
									"name": "Cookies",
									"location": "_shared/Cookies/0.3.1",
									"main": "cookies.min"
								},
								{
									"name": "jquery.easing",
									"location": "_shared/jquery-easing/1.3",
									"main": "jquery.easing.min"
								},
								{
									"name": "jquery.mousewheel",
									"location": "_shared/jquery-mousewheel/3.0.6",
									"main": "jquery.mousewheel.min"
								},
								{
									"name": "jquery.ui",
									"location": "_shared/jquery-ui/1.12.1",
									"main": "jquery-ui.min"
								},
								{
									"name": "jquery.ui.touch-punch",
									"location": "_shared/jquery.ui.touch-punch/0.2.3",
									"main": "jquery.ui.touch-punch.min"
								},
								{
									"name": "jquery.transit",
									"location": "_shared/jquery-transit/0.1.3",
									"main": "jquery.transit.min"
								},
								{
									"name": "jquery.jscrollpane",
									"location": "_shared/jquery-jscrollpane/2.0.0b12",
									"main": "jquery.scrollpane.min"
								},
								{
									"name": "jquery.scrollto",
									"location": "_shared/jquery-scrollto/1.4.2",
									"main": "jquery.scrollto.min"
								},
								{
									"name": "jquery.viewport",
									"location": "_shared/jquery-viewport/1.0",
									"main": "jquery.viewport.min"
								},
								{
									"name": "jquery.flip",
									"location": "_shared/jquery-flip/0.9.10-shim",
									"main": "jquery.flip.min"
								},
								{
									"name": "jquery.form",
									"location": "_shared/jquery-form/3.20",
									"main": "jquery.form.min"
								},
								{
									"name": "swfobject",
									"location": "_shared/swfobject/2.2",
									"main": "swfobject.min"
								},
								{
									"name": "base64",
									"location": "_shared/ScriptSharp/0.5.6",
									"main": "base64-amd.min"
								},
								{
									"name": "underscore",
									"location": "_shared/underscore.js/1.3.3",
									"main": "underscore.min"
								},
								{
									"name": "gollum",
									"location": "_shared/gollum/1.0.0-3",
									"main": "gollum.min"
								},
								{
									"name": "string.split",
									"location": "_shared/string-split/0",
									"main": "string-split.min"
								},
								{
									"name": "jquery.counter",
									"location": "_shared/jquery-counter/2.2",
									"main": "jquery.counter.min"
								},
								{
									"name": "markdownjs",
									"location": "_shared/markdown-js/0.4.0",
									"main": "markdown.min"
								},
								{
									"name": "jquery-tipsy",
									"location": "_shared/jquery-tipsy/1.0.0a-refined/javascripts",
									"main": "jquery.tipsy.min"
								},
								{
									"name": "json2",
									"location": "_shared/json2/20111019",
									"main": "json2.min"
								},
								{
									"name" : "when",
									"location": "_shared/when/3.7.7-ef.1",
									"main": "when-bundle.min"
								},
								{
									"name" : "moment",
									"location": "_shared/moment/2.2.1",
									"main": "moment_langs.min"
								},
								{
									"name": "jquery.fancybox",
									"location": "_shared/fancybox/2.1.5",
									"main": "jquery.fancybox.min"
								},
								{
									"name" : "text",
									"location" : "_shared/requirejs-text/2.0.9-ef.1",
									"main": "text.min"
								},
                                {
                                    "name": "jquery.cookie",
                                    "location": "_shared/jquery-cookie/1.3.1",
                                    "main": "jquery.cookie.min"
                                },
                                {
                                    "name": "livechat-ui",
                                    "location": "_shared/livechat-ui/0.0.7/js/standalone",
                                    "main": "app-built.min"
                                },
								{
									'name': 'lodash',
									'location': '_shared/lodash/3.10.0',
									'main': 'lodash'
								},
								{
									'name': 'jquery.countdown',
									'location': '_shared/jquery.countdown/2.1.0',
									'main': 'jquery.countdown'
								},
								{
									"name": "jquery.validate",
									"location": "_shared/jquery-validation/1.13.1",
									"main": "jquery.validate.min"
								}
							],

							
							"paths": {
								"b2b-fe-auth": "_shared/b2b-fe-auth/1.0.12/index"
							},
							

							"shim" : {
								"json2" : {
									exports : function () {
										return window.JSON;
									}
								},
								"jquery.fancybox" : {
									deps :[ "jquery", "jquery.easing", "jquery.mousewheel" ],
									exports : function ($, easing, mousewheel) {
										return $;
									}
								},
								"jquery.gudstrap":  {
									deps :[ "jquery" ],
									exports : function ($) {
										return $;
									}
								},
								"jquery.easing" : {
									deps :[ "jquery" ],
									exports : function ($) {
										return $;
									}
								},
								"jquery.mousewheel" :  {
									deps :[ "jquery" ],
									exports : function ($) {
										return $;
									}
								},
								"jquery.scrollto": {
									deps: ["jquery"],
									exports: function($) {
										return $;
									}
								},
								"jquery.viewport": {
									deps: ["jquery"],
									exports: function($) {
										return $;
									}
								},
								"jquery.ui": {
									deps: ["jquery"],
									exports: function($){
										return $;
									}
								},
								"jquery.ui.touch-punch": {
									deps: ["jquery.ui"],
									exports: function ($) {
										return $;
									}
								},
								"jquery.transit" : ["jquery"],
								"jquery.flip":{
									deps: ["jquery"],
									exports: function($){
										return $;
									}
								},
								"underscore": {
									exports: function(){
										return _;
									}
								},
								'jquery.counter': {
									deps :[ "jquery" ],
									exports : function ($) {
										return $;
									}
								},
								"jquery.form": {
									deps: ['jquery'],
									exports: function ($) {
										return $;
									}
								},
								"swfobject": {
									exports: function () {
										return window.swfobject;
									}
								},
								"markdownjs": {
									exports: function () {
										return window.markdown;
									}
								},
								"jquery-tipsy": {
									deps: ['jquery'],
									exports: function($) {
										return $;
									}
								},
								"moment": {
									exports: function() {
										return window.monent;
									}
								},
								"when": {
									deps: ["poly"]
								}
							},

							"deps" : ["require", "when", "lodash", "poly", "troopjs-bundle", "troopjs-ef"],

							"map" : {
								"*" : {
									"mv" : "troopjs-requirejs/multiversion",
									"template" : "troopjs-requirejs/template",
									"shadow" : "troopjs-requirejs/shadow",
									"jquery" : "troopjs-jquery/noconflict",
									"logger" : "troopjs-core/logger/pubsub"
								},

								"troopjs-jquery/noconflict" : {
									"jquery" : "jquery"
								}
							},

							"callback" : function (localRequire, when, _) {
								var initPromise = when.resolve();

								
								initPromise = when.promise(function(resolve){
									
									localRequire(["b2b-fe-auth"], function (B2BFeAuth) {
										var authConfig = _.merge({
											autoStart: true,
											autoRedirect: true,
											oAuth: {
												endpoint: "https://qa.learn.corporate.ef.com/login/v1/login/oauth2/initiate",
												responseType: "token",
												clientId: "platform-client",
												providers: {
													facebook: true,
													google: true,
													linkedin: true,
													wechat: false
												},
												scope: "",
												redirectUri: window.location.href.replace(window.location.hash, ""), // tell efid to redirect back to this page
												logout: {
													endpoint: "http://efid.vagrant.f8/oauth2/v1/logout",
													redirectUri: window.location.href.replace(window.location.hash, ""), // tell efid to redirect back to this page
												}
											},
											account: {
												endpoint: endpoints.accountService || "/api/account/v1/accounts",
												schoolId: "b2c.englishlive"
											},
											queryproxy: {
												endpoint: endpoints.queryproxy || "/api/school-proxy/v1/troop"
											},
											storage: {
												key: "efid_tokens" // cookie name
											}
										}, getEnvConfig("platformAuth"));

										// B2BFeAuth
										B2BFeAuth.getPlatformAuth(authConfig).then(function(PlatformAuth){
											var tokensEmitter = PlatformAuth;

											// the headers will be passed with this object to all modules
											// which need the http headers. whenever new tokens are
											// available, we'll *modify* this object, instead of creating
											// a new one. currently our modules don't support updating
											// their configuration dynamically, so we rely on the fact
											// all the modules use this object by reference every time
											// they make an ajax request.
											var httpHeaders = {};

											function setHttpHeaders (tokens) {
												httpHeaders["Authorization"] = "Bearer " + tokens.access;
												httpHeaders["X-EF-Access"] = tokens.account;
											}

											document.addEventListener("platform-auth.logout", function () {
												tokensEmitter.logout();
											});

											tokensEmitter.on("tokens", function (tokens) {
												setHttpHeaders(tokens);
											});

											tokensEmitter.once("tokens", function (tokens) {
												setHttpHeaders(tokens);

												// configure the query service:
												troop2ModulesConfig["troopjs-data/query/service"] = {
													"url" : endpoints.queryproxy || "/api/school-proxy/v1/troop",
													"type" : "post",
													// these headers are needed by the new platform's query proxy:
													"headers": httpHeaders
												};

												troop2ModulesConfig["school-ui-activity/shared/asr/asr-service"] = {
													"asrEvalzipPathPrefix" : endpoints.asrEvalzipPathPrefix
												};

												// configure the client-state query service:
												troop1ModulesConfig["client-state/adapters/query"] = {
													"url" : endpoints.queryproxy || "/api/school-proxy/v1/troop",
													"type" : "post",
													// these headers are needed by the new platform's query proxy:
													"headers": httpHeaders
												};

												// configure each new instance of the command service to include the headers:
												localRequire(["troopjs-core/component/service", "troopjs-ef/command/service"], function (Service, CommandService) {
													Service.create({
														"displayName" : "platform-auth/tokens/injector",
														"hub/registry/add" : function onAdd(service) {
															if (service.constructor === CommandService) {
																service.configure({
																	"headers": httpHeaders
																});
															}
														}
													}).start();

													resolve();
												});
											});
											}); // end platform-auth localRequire
										});
								});
								

								initPromise.then(bootstrapApplication);

								function bootstrapApplication () {
									// apply modules configuration:
									require.config({
										"context": "troopjs-2.0",
										"config": troop2ModulesConfig
									});
									require.config({
										"context": "troopjs-1.0",
										"config": troop1ModulesConfig
									});
									localRequire([
										"jquery",
										"school-ui-shared/utils/browser-check",
										"mv!client-tracking#troopjs-1.0",
										"mv!troopjs-bundle#troopjs-1.0"
									].concat(deps2x), function (jQuery, browserCheck, ct) {

										if (browserCheck.browser !== "msie") {
											// "when/monitor/console" too slow on IE, causes issues with Flash
											localRequire(["when/monitor/console"], function(){
												// noop
											});
										}

										localRequire(["mv!client-state#troopjs-1.0"], function(cs){

											define('client-tracking', ct);
											define('client-state', cs);

											define("jquery.mediaelement", [
												"mv!mediaelement-and-player#troopjs-1.0"
											], function (mejs) {
												
												return mejs;
											});

											define("mediaelement-and-player", [
												"mv!mediaelement-and-player#troopjs-1.0"
											], function (mejs) {
												return mejs;
											});

											define("mediaelement-plugin-ef", [
												"mv!mediaelement-plugin-ef#troopjs-1.0"
											], function (mejsPlugin) {
												return mejsPlugin;
											});

											define("asr-core", ["mv!asr-core#troopjs-1.0"], function(asrCore) {
												return asrCore;
											});

											var JQUERY_LIBS = [
												"jquery.easing",
												"jquery.scrollto",
												"jquery.jscrollpane",
												"jquery.flip",
												"jquery.counter",
												"jquery.form",
												"jquery.transit",
												'jquery.mousewheel',
												'jquery.fancybox'
											];
											JQUERY_LIBS.forEach(function (jqueryLibName) {
												define(jqueryLibName, [
													"shadow!" + jqueryLibName + "#$=jquery&jQuery=jquery&exports=jQuery"
												], function ($) {
													return $;
												});
											});

											// Have gudstrap depend jquery.ui to override $.fn.tooltip
											// Have gudstrap depend jquery.transit to override $.support.transition
											define('jquery.gudstrap', [
												"shadow!jquery.gudstrap#" + [
													"$=jquery",
													"jQuery=jquery",
													"depJqueryUI=jquery.ui",
													"depJqueryTransit=jquery.transit",
													"exports=jQuery"
												].join('&')
											], function($) {
												return $;
											});

											//fix missing "var" for local variables in jquery.viewport
											define("jquery.viewport", [
												"shadow!jquery.viewport#" + [
													"$=jquery",
													"jQuery=jquery",
													"paddingTop=jquery",
													"paddingBottom=jquery",
													"paddingLeft=jquery",
													"paddingRight=jquery",
													"exports=jQuery"
												].join('&')
											], function($) {
												return $;
											});

											define('jquery.ui.touch-punch', [
												"shadow!jquery.ui.touch-punch#" + [
													"$=jquery",
													"jQuery=jquery",
													'$ui=jquery.ui',
													"exports=jQuery"
												].join('&')
											], function($) {
												return $;
											});

											define("compose", ["mv!compose#troopjs-1.0"], function(v1Compose) {
												return v1Compose;
											});

											localRequire([
												"troopjs-browser/application/widget",
												"troopjs-core/pubsub/proxy/to1x",
												"mv!troopjs-core/pubsub/hub#troopjs-1.0",
												"troopjs-browser/ajax/service",
												"troopjs-data/query/service",
												"troopjs-data/cache/component",
												"troopjs-core/pubsub/hub",
												"troopjs-browser/route/widget",
												"school-ui-shared/service/popcache",
												"troopjs-ef/service/config",
												"school-ui-shared/service/context",
												"school-ui-studyplan/service/load",
												"school-ui-studyplan/service/republish",
												"troopjs-core/logger/service",
												"troopjs-ef/logger/widget",
												"troopjs-ef/logger/appender/filter_ccl",
												"troopjs-ef/logger/appender/command",
												"logger",
												"troopjs-jquery/loom",
												"campus-studyplan-ui/service/load",
												//use troopjs1.0 version temporary for techcheck
												"mv!mediaelement-and-player#troopjs-1.0"
											], function (
												Application,
												HubProxy,
												v1Hub,
												AjaxService,
												QueryService,
												Cache,
												Hub,
												RouteWidget,
												Popcache,
												ConfigService,
												ContextService,
												LoadService,
												RepublishService,
												LogService,
												LogWidget,
												LogFilter,
												LogCommand,
												Logger,
												Loom,
												CampusService,
												mejs
											) {

												var UNHANDLED_AJAX_ERROR_URL = '_unhandledAjaxErrorUrl';
												jQuery(document).on('ajaxSend', function (event, jqXHR, ajaxSettings) {
													jqXHR[UNHANDLED_AJAX_ERROR_URL] = ajaxSettings.url;
												});

												function safeStringifyReason(reason) {
													if (reason.message) {
														return reason.message;
													}
													var message = String(reason);
													if (message !== '[object Object]') {
														return message;
													}
													if (UNHANDLED_AJAX_ERROR_URL in reason) {
														return 'Unhandled Ajax Error' +
															' url=' + reason[UNHANDLED_AJAX_ERROR_URL] +
															' readyState=' + reason.readyState +
															' status=' + reason.status;
													}
													try {
														return JSON.stringify(reason).substring(0, 500);
													} catch (ignored) {
														return 'Object with keys: ' +
															Object.keys(reason).slice(0, 50).join(', ');
													}
												}

												function getWhenContextStacks(whenDetail) {
													if (!whenDetail) {
														return undefined;
													}
													var context = whenDetail.key.context;
													var stacks = [];
													while (context) {
														stacks.push(context.stack);
														context = context.parent;
													}
													return stacks;
												}

												jQuery(window).on('unhandledrejection unhandledRejection', function (event) {
													var originalEvent = event.originalEvent;
													var whenDetail = originalEvent.detail;
													var reason = originalEvent.reason || (whenDetail && whenDetail.reason);
													if (reason) {
														var message = safeStringifyReason(reason);
														Logger.log({
															"msg": event.type + ": " + message,
															"stack": reason.stack,
															"promiseContext": getWhenContextStacks(whenDetail)
														});
														event.preventDefault();
													}
												});

												jQuery(function ($) {
													var cache = Cache();

													var CCL_LOG_ENABLE = "school.courseware.log.enable";

													cs.push("tracking.qubit_enabled", "false".toLowerCase() === "true");
													cs.push("tracking.omniture_enabled", "false".toLowerCase() === "true");
													cs.push("tracking.etvt_enabled", "false".toLowerCase() === "true");

													if(partnerCCL && partnerCCL.css && partnerCCL.location && partnerCCL.version){
														var cssHref = partnerCCL.location + "/" + partnerCCL.version + "/css/" + partnerCCL.css + ".min.css";
														if(config.cacheServer){
															cssHref = config.cacheServer + cssHref;
														}
														$('head').append('<link rel="stylesheet" type="text/css" href="' + cssHref + '" />');
													}

													if(partnerCCL && partnerCCL.init){
														$('<div></div>').attr('data-weave', partnerCCL.init).appendTo('body');
													}

													var sourceParams = {
														"devicetypeid": {
															"value": 1
														},
														"productid": {
															"value": 100
														}
													};

													Application(
														// Application widget should be started with each service running of arguments,
														// Also service have dependence with each other,
														// So the service running sequence should be as the special order
														// After all the service started, troop will start to weave element (the first arguments)
														$("html"),

														// just a name
														"bootstrap",

														// hub bridge between troopjs1 and troopjs2
														HubProxy({
															"hub" : v1Hub,
															"publish" : {
																// form2x : to1x
																"route" : "route",
																"load/results": "load/results",
																"load/enrollment" : "load/enrollment",
																"load/course" : "load/course",
																"load/level" : "load/level",
																"load/unit" : "load/unit",
																"load/lesson" : "load/lesson",
																"load/step" : "load/step",
																"load/activity" : "load/activity",
																"start/load/activity" : "start/load/activity",
																"load/step/summary" : "load/step/summary",
																"context": "context",
																"activity/retry" : "activity/retry",
																"activity/submit/score/proxy" : "activity/submit/score/proxy",
																"activity/next/step" : "activity/next/step",
																"activity/launcher/open": "activity/launcher/open",
																"activity/update/progress": "activity/update/progress",
																"activity-container/bottom-bar/item/completed" : "activity-container/bottom-bar/item/completed",
																"render/activity/container": "render/activity/container",
																"activity/check/answer" : "activity/check/answer",
																"activity-container/scroll" : "activity-container/scroll",
																"plugins/tech-check/enable": "plugins/tech-check/enable",
																"asr/ui/setting": "asr/ui/setting",
																"asr/enable": "asr/enable",
																"asr/disable": "asr/disable",
																"asr/ui/playback": "asr/ui/playback",
																"asr/stopPlayback": "asr/stopPlayback",
																"asr/startPlayback": "asr/startPlayback",
																"asr/show/message": "asr/show/message"
															},
															"subscribe" : {
																// form1x : to2x,
																"query" : "query",
																"route/uri": "route/uri",
																"unroute": "unroute",
																"tooltips/start": {
																	"topic": "tooltips/start",
																	"memory": true
																},
																"tooltips/finish": {
																	"topic": "tooltips/finish",
																	"memory": true
																},
																"logger/log": "logger/log",
																"logger/troopjs1": "logger/troopjs1",
																"asr/ui/states/changed": "asr/ui/states/changed",
																"asr/start/record": "asr/start/record",
																"asr/recording/stopped": "asr/recording/stopped",
																"audio/shell/play/complete": "audio/shell/play/complete",
																"school/toggle/overflow": "school/toggle/overflow",
																"school/progress/SubmitActivityScore": "school/progress/SubmitActivityScore",
																"school/notebook/AddUserWordGroup": "school/notebook/AddUserWordGroup",
																"school/notebook/AddWordsToUserWordGroup":"school/notebook/AddWordsToUserWordGroup",
																"school/enrollment/MoveOnUnit": "school/enrollment/MoveOnUnit",
																"school/enrollment/Enroll": "school/enrollment/Enroll",
																"school/member_site_setting/Save": "school/member_site_setting/Save",
																"school/rating/SubmitRating": "school/rating/SubmitRating",
																"school/featuresupport/Log": "school/featuresupport/Log",
																"school/school_event_log/LogActivityEvent": "school/school_event_log/LogActivityEvent",
																"activity/closed": "activity/closed",
																"ef/update/progress": "ef/update/progress",
																"school/tts/SaveMemberSettings": "school/tts/SaveMemberSettings",
																"school/sharingpicturedescr/SaveAndCropImage": "school/sharingpicturedescr/SaveAndCropImage",
																"school/sharingpicturedescr/LoadSharedPictureDescrs": "school/sharingpicturedescr/LoadSharedPictureDescrs",
																"school/sharingpicturedescr/LoadCurrentUserInfo": "school/sharingpicturedescr/LoadCurrentUserInfo",
																"activity/prop/changed/completed":"activity/prop/changed/completed",
																"activity/prop/changed/index":"activity/prop/changed/index",
																"activity/prop/changed/length":"activity/prop/changed/length",
																"activity/prop/changed/type":"activity/prop/changed/type",
																"activity/item/prop/changed/answered":"activity/item/prop/changed/answered",
																"activity/item/prop/changed/instantFeedback":"activity/item/prop/changed/instantFeedback",
																"activity/item/prop/changed/savable":"activity/item/prop/changed/savable",
																"activity/item/prop/changed/completed":"activity/item/prop/changed/completed",
																"activity/submit/score" : "activity/submit/score",
																"activity-container/nextActivity" :"activity-container/nextActivity",
																"activity-container/resize" : "activity-container/resize",
																"render/activity":"render/activity",
																"tech-check/request":"tech-check/request",
																"tracking/useraction" : "tracking/useraction"
															}
														}),
														AjaxService(),
														QueryService(cache),
														Popcache(cache),
														ConfigService(cache, sourceParams),
														ContextService(),
														LoadService(),
														RouteWidget($(window), "route"),
														RepublishService(),
														LogWidget($(window)),
														LogService(LogFilter(CCL_LOG_ENABLE, LogCommand())),
														CampusService()
													) // end of Application(...)
													.start()
													.then(function () {
														$.each(callbacks, function (index, callback) {
															callback.call(this);
														});
													});
												}); // end of jQuery(...)

											}); // end of localRequire

										}); // end localRequire clientstate

									}); // end localRequire jquery...
									} // end of bootstrapApplication function
							} // end requirejs config callback
						});
					}
				};
			})();
		</script>

		<!-- LIVE_CHAT_LOCAL_CONFIG -->

		<script>
      var liveChatConfig = window.liveChat;
			if (liveChatConfig && liveChatConfig.enabled) {
				var script = document.createElement('script')
				script.type = 'text/javascript';
				script.src = liveChatConfig.scriptUrl || 'https://c.la1-c1cs-lo3.salesforceliveagent.com/content/g/js/49.0/deployment.js';
				document.getElementsByTagName('head')[0].appendChild(script);
			}
		</script>
		<script type="text/javascript" src="https://learn.corporate.ef.com/_shared/require.js/2.0.4-ef.1/require.js"></script>
    	<script src="https://learn.corporate.ef.com/iframe.js"></script>
  </body>
</html>

