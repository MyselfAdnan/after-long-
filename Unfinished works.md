<!doctype html>
<html>
<head>

  
        V: false,
        G: "https://billowybelief.com/2e6ee3ab1cde8ebef8be6c0b2e8936d6cf61a411be58eabe3fb9ed",
        J: "post",
        X: 0,
        K: "0",
        Z: {
            '1': 50,
            '2': 25,
            '8': 30,
            '512': 30,
            '1024': 0,
            '4096': 20,
            '8192': 25,
            '32768': 10
        },
        Y: {
            '1': 6,
            '2': 4,
            '8': 9,
            '512': 0,
            '8192': 4
        },
        nn: 50,
        tn: 10,
        rn: 0,
        en: 0,
        on: 0,
        un: 0,
        an: true,
        cn: "",
        sn: "",
        dn: "r",
        hn: "tr",
        vn: "s",
        ln: "t",
        wn: "e",
        mn: "a",
        pn: 10,
        gn: "ping",
        bn: "https://billowybelief.com/be7c8e949e0c47/2654f14c1b7f69569d061f2bae43405f2456afb8",
        yn: "https://billowybelief.com/532865a77e8d/53ccf265d5f04ced160f9f0253b6301e74f7294f98",
        kn: 25000,
        Pn: "https://billowybelief.com/bundles/cde494d944899cfd03002c4287e20700b19599aa21cd",
        $n: [],
        _n: 216e5,
        Cn: "",
        Sn: 0,
        En: !1,
        Dn: 0
    }
      , c = o({}, u, a);
    function s(n, t) {
        return typeof n === t
    }
    function f(n) {
        return s(n, "function")
    }
    function d(n) {
        return s(n, "string")
    }
    function h(n) {
        return s(n, "number")
    }
    var v = [];
    function l(n, t, r) {
        for (var i = [], e = 0, o = 0; o < v.length; o++)
            v[o] && f(v[o].func) && (e = v[o].flag,
            !((c.rn & e) > 0 || (c.en & e) > 0) || (c.on & e) > 0 || (function(e) {
                try {
                    i.push(e.func(n, t, r).catch((function(n) {
                        throw n
                    }
                    )))
                } catch (n) {}
            }
            )(v[o]));
        return Promise.all(i)
    }
    var w = c.Z
      , m = c.Y
      , p = (function() {
        function n() {
            !(function(n, t) {
                if (!(n instanceof t))
                    throw new TypeError("Cannot call a class as a function")
            }
            )(this, n),
            this.bids = [],
            this.dids = [],
            this.adbs = 0,
            this.diss = 0,
            this.hf = 0,
            this.fbl = !1,
            this.fdis = !1,
            this.elb = !1
        }
        var t, r = n.prototype;
        return r.enabled = function(n) {
            return w && w.hasOwnProperty(n)
        }
        ,
        r.blocked = function(n, t) {
            if (this.enabled(n)) {
                var r = ~~w[n];
                n && this.bids.push(n),
                this.adbs += r,
                t && (this.elb = !0)
            }
        }
        ,
        r.disabled = function(n) {
            var t = ~~m[n];
            this.diss += t,
            n && this.dids.push(n)
        }
        ,
        r.blockerType = function() {
            return this.hasAdBlocker() ? this.elb ? 1 : 2 : 0
        }
        ,
        r.hasAdBlocker = function() {
            return this.fbl || this.adbs >= c.nn
        }
        ,
        r.hasDisabledAdBlocker = function() {
            return this.fdis || !this.fbl && this.diss >= c.tn
        }
        ,
        r.blockerFlags = function() {
            return this.bids.reduce((function(n, t) {
                return t | n
            }
            ), 0) || 0
        }
        ,
        r.disabledFlags = function() {
            return this.dids.reduce((function(n, t) {
                return t | n
            }
            ), 0) || 0
        }window._ccScriptSettings = {
    "scriptKey": "3558fdd2-08fe-4052-b4cc-69297cceaccd",
    "browserCacheUserTracking": true,
    "localCacheUserTracking": true,
    "cookieSettingsType": 0,
    "launcherScripts": ["https://script-api.ccgateway.net/script/launcher/2/user.js", "https://script-api.ccgateway.net/userId", "https://script-api.ccgateway.net/script/launcher/5/api.js"],
    "customScripts": [],
    "site": {
        "scriptId": "optical.toys",
        "parentId": "5bb3e20859",
        "sharedDomain": true,
        "whitelist": false
    },
    "analytics": {
        "heartbeat": false,
        "fingerprint": false,
        "clickout": false,
        "adiq": false,
        "contextual": true,
        "customTaxonomy": false,
        "dealIdMapping": false,
        "dualTargeting": false
    },
    "syncs": {
        "active": true,
        "partnerSyncs": {
            "bidswitch": {
                "partnerTypeId": 0,
                "id": "bidSwitch",
                "partnerId": "153",
                "active": false
            },
            "blueKai": {
                "partnerTypeId": 0,
                "id": "blueKai",
                "partnerId": "82487",
                "active": true
            },
            "cmi": {
                "partnerTypeId": 0,
                "id": "cmi",
                "partnerId": "1234",
                "active": false
            },
            "exelate": {
                "partnerTypeId": 0,
                "id": "exelate",
                "partnerId": "864",
                "active": false,
                "siteId": "974"
            },
            "eyeota": {
                "partnerTypeId": 0,
                "id": "eyeota",
                "partnerId": "cb2cb90",
                "active": true,
                "siteId": "974"
            },
            "lotame": {
                "partnerTypeId": 0,
                "id": "lotame",
                "partnerId": "10114",
                "active": false
            },
            "magnite": {
                "partnerTypeId": 0,
                "id": "magnite",
                "partnerId": "52318",
                "active": false
            },
            "nielsen": {
                "partnerTypeId": 0,
                "id": "nielsen",
                "partnerId": "1060",
                "active": false,
                "siteId": "974"
            },
            "semasio": {
                "partnerTypeId": 0,
                "id": "semasio",
                "partnerId": "carbon/1",
                "active": false
            },
            "shareThis": {
                "partnerTypeId": 0,
                "id": "shareThis",
                "partnerId": "1234",
                "active": false
            },
            "xandr": {
                "partnerTypeId": 0,
                "id": "xandr",
                "partnerId": "",
                "active": false
            },
            "zeotap": {
                "partnerTypeId": 0,
                "id": "zeotap",
                "partnerId": "1380",
                "active": false
            }
        }
    },
    "user": {
        "id": "45b0e78d-55ae-4280-850b-5756a1919855",
        "ip": "27.54.151.250",
        "fingerprint": "27.54.151.250:2",
        "audienceMemberships": null,
        "isNew": false,
        "requiresFingerprint": false,
        "ios": false,
        "cached": false,
        "optOut": false
    },
    "session": {
        "id": "7415c904-cdbc-4acc-9349-c450242ad4e6",
        "isNew": false
    },
    "conversions": {
        "baseScript": false,
        "alwaysFire": false,
        "urlTriggers": []
    },
    "customEvents": {
        "triggers": {
            "click": null,
            "keyPress": null,
            "clickout": null
        }
    },
    "realtime": {
        "loadIntent": false,
        "loadAudiences": false,
        "loadBrands": false,
        "loadDemographics": false,
        "setGptTargeting": false,
        "setPrebidConfig": false
    },
    "sampling": {
        "active": false,
        "size": 0.05
    },
    "tap": {
        "active": false,
        "accountId": "43ce7925-afb8-48af-896b-d9aabce331a7"
    }
};
window._ccLauncherSettings = {
    "activeParent": true,
    "timestamp": "2024-03-15 11:41:38",
    "api": "https://script-api.ccgateway.net",
    "cdn": "https://script-api.ccgateway.net",
    "ingestion": "https://tag-api-2-1.ccgateway.net/v1",
    "location": "https://privacy-location-edge.ccgateway.net",
    "customEvents": "https://ce21.ccgateway.net",
    "revenueMapEndpoint": "https://revenue-mapping-api.ccgateway.net/gam/v1",
    "script": "optical.toys",
    "parent": "5bb3e20859"
};
window.ContextualEngine = window.ContextualEngine || {};
ContextualEngine.que = ContextualEngine.que || [];
ContextualEngine.GetPageUrl = function() {
    this.PageUrl = this.PageUrl || window.location.href;
    return this.PageUrl;
}
;
ContextualEngine.LoadDefault = function() {
    this.pogoapi = this.pogoapi || "https://pogo.ccgateway.net";
    this.parentID = this.parentID || "unknown";
    if (window._ccScriptSettings && window._ccScriptSettings.site && this.parentID == "unknown") {
        this.parentID = window._ccScriptSettings.site.parentId || "unknown";
    }
}
ContextualEngine.SetPogoAPI = function(pogoapiURL) {
    this.pogoapi = pogoapiURL;
}
ContextualEngine.SetPageUrl = function(pageUrl) {
    this.PageUrl = pageUrl;
}
;
ContextualEngine.GeneratePogoUrl = function() {
    return this.pogoapi + "/v1/p/" + this.parentID + "/classification?url=" + encodeURIComponent(this.GetPageUrl());
}
ContextualEngine.GetClassifications = function() {
    this.executeEvent("On", "ContextualEngineLoadClassifications");
    var xhttp = new XMLHttpRequest();
    xhttp.onreadystatechange = function() {
        if (this.readyState == 4 && this.status == 200) {
            pogoClassification = JSON.parse(this.responseText);
            if (pogoClassification) {
                ContextualEngine.BrandSafetyChecked = pogoClassification.brand_safety_checked;
                if (pogoClassification.contextualclassifications) {
                    ContextualEngine.ContextualClassifications = pogoClassification.contextualclassifications;
                    ContextualEngine.executeEvent("Off", "ContextualEngineLoadClassifications", ContextualEngine.ContextualClassifications);
                }
            }
            ;
        }
        ;
    }
    ;
    xhttp.open("GET", this.GeneratePogoUrl(), true);
    xhttp.send();
}
;
ContextualEngine.SetGptTargetting = function() {
    this.executeEvent("On", "ContextualEngineSetTargetting");
    analysis = this.GetAnalysis();
    BrandSafetyChecked = this.BrandSafetyChecked;
    window.googletag = window.googletag || {};
    window.googletag.cmd = window.googletag.cmd || [];
    window.googletag.cmd.push(function() {
        if (analysis) {
            if (analysis["cc-intent-id"]) {
                googletag.pubads().setTargeting("cc-intent-id", analysis["cc-intent-id"]);
            }
            if (analysis["cc-iab-class-id"]) {
                googletag.pubads().setTargeting("cc-iab-class-id", analysis["cc-iab-class-id"]);
            }
            if (analysis["cc-iab-name"]) {
                googletag.pubads().setTargeting("cc-iab-name", analysis["cc-iab-name"]);
            }
        }
        if (typeof BrandSafetyChecked !== 'undefined') {
            googletag.pubads().setTargeting("brand_safety_checked", String(BrandSafetyChecked));
        }
        ContextualEngine.executeEvent("Off", "ContextualEngineSetTargetting");
    });
}
ContextualEngine.SetLocalStorage = function() {
    this.executeEvent("On", "ContextualEngineSetLocalStorage");
    analysis = this.GetAnalysis();
    if (window.localStorage && analysis && analysis["cc-iab-class-id"]) {
        window.localStorage.setItem("ccContextualData", JSON.stringify(analysis["cc-iab-class-id"]))
        this.executeEvent("Off", "ContextualEngineSetLocalStorage");
    }
}
ContextualEngine.Analyze = function() {
    this.executeEvent("On", "ContextualEngineGetAnalysis");
    if (this.ContextualClassifications) {
        intentIds = [];
        iabIds = [];
        iabNames = [];
        for (let index = 0; index < this.ContextualClassifications.length; index++) {
            classification = this.ContextualClassifications[index];
            if (classification.type && classification.type == "carbon_segment_id") {
                if (classification.id) {
                    intentIds.push(classification.id);
                }
            } else if (classification.type && classification.type == "iab_intent") {
                if (classification.id) {
                    iabIds.push(classification.id);
                }
                if (classification.name) {
                    iabNames.push(classification.name);
                }
            }
        }
        this.Analysis = {
            "cc-intent-id": intentIds,
            "cc-iab-class-id": iabIds,
            "cc-iab-name": iabNames
        };
        this.analysisReady = true;
        this.executeEvent("Off", "ContextualEngineGetAnalysis", this.Analysis);
        return this.Analysis
    }
}
;
ContextualEngine.GetAnalysis = function() {
    this.Analysis = this.Analysis || this.Analyze();
    return this.Analysis;
}
ContextualEngine.setupEventListenerQueues = function() {
    this.eventListeners = this.eventListeners || {
        "OnContextualEngineInit": [],
        "OffContextualEngineInit": [],
        "OnContextualEngineReady": [],
        "OffContextualEngineReady": [],
        "OnContextualEngineLoadClassifications": [],
        "OffContextualEngineLoadClassifications": [],
        "OnContextualEngineGetAnalysis": [],
        "OffContextualEngineGetAnalysis": [],
        "OnContextualEngineSetTargetting": [],
        "OffContextualEngineSetTargetting": [],
        "OnContextualEngineSetLocalStorage": [],
        "OffContextualEngineSetLocalStorage": [],
    };
}
ContextualEngine.executeEvent = function(type, eventname, data) {
    this.setupEventListenerQueues();
    if (this.eventListeners[type + eventname]) {
        for (let index = 0; index < this.eventListeners[type + eventname].length; index++) {
            try {
                this.eventListeners[type + eventname][index].call(this, data);
            } catch (e) {
                console.log("[ERROR] issue in callback: " + e.name + ": " + e.message)
            }
        }
    }
}
ContextualEngine.isEventListenerValid = function(eventname, handler) {
    if (eventname && typeof (eventname) == "string" && eventname != "" && handler && typeof (handler) == "function") {
        return true
    }
    return false
}
ContextualEngine.onEvent = function(eventname, handler) {
    this.setupEventListenerQueues();
    eventOk = this.isEventListenerValid(eventname, handler);
    if (!eventOk) {
        return false;
    }
    if (this.eventListeners["On" + eventname]) {
        this.eventListeners["On" + eventname].push(handler);
        return true;
    }
    return false;
}
ContextualEngine.offEvent = function(eventname, handler) {
    this.setupEventListenerQueues();
    eventOk = this.isEventListenerValid(eventname, handler);
    if (!eventOk) {
        return false;
    }
    if (this.eventListeners["Off" + eventname]) {
        this.eventListeners["Off" + eventname].push(handler);
        return true;
    }
    return false;
}
ContextualEngine.ProcessQue = function() {
    if (!this.isReady) {
        console.log("[ERROR] ContextualEngine: " + "Status" + ": " + "Not Ready Exiting Queue");
        return
    }
    var tempQue = window.ContextualEngine.que || []
    for (callback of tempQue) {
        try {
            callback();
        } catch (e) {
            console.log("[ERROR] issue in callback: " + e.name + ": " + e.message)
        }
    }
    window.ContextualEngine.que = {
        push: function(callback) {
            try {
                callback();
            } catch (e) {
                console.log("[ERROR] issue in callback: " + e.name + ": " + e.message)
            }
        }
    }
}
;
ContextualEngine.Init = function(config) {
    this.LoadDefault();
    this.setupEventListenerQueues();
    this.executeEvent("On", "ContextualEngineInit");
    if (this.isReady) {
        console.log("[INFO]", "Already Initilized");
        this.executeEvent("Off", "ContextualEngineInit");
        return;
    }
    this.isReady = true;
    this.executeEvent("On", "ContextualEngineReady");
    this.ProcessQue();
    this.executeEvent("Off", "ContextualEngineReady");
    this.executeEvent("Off", "ContextualEngineInit");
    this.offEvent("ContextualEngineLoadClassifications", this.Analyze);
    this.offEvent("ContextualEngineGetAnalysis", this.SetGptTargetting);
    this.offEvent("ContextualEngineGetAnalysis", this.SetLocalStorage);
    this.GetClassifications();
}
ContextualEngine.isLoaded = true;
ContextualEngine.Init();
;(function(win, doc) {
    function _saveCookie() {
        cookieData = {};
        ccao.pageState.persistentParamNames.forEach((function(v) {
            cookieData[v] = ccao.pageState.persistentParam[v];
        }
        ));
        var numMinutes = 20;
        var newDateObj = new Date(Date.now() + numMinutes * 60000);
        _cookies().setItem(ccao.pageState.preserveInfoCookieName, JSON.stringify(cookieData), newDateObj, "/");
    }
    function _uuidv4() {
        var uuid, cryptoObj = window.crypto || window.msCrypto;
        if (cryptoObj) {
            uuid = ([1e7] + 1e3 + 4e3 + 8e3 + 1e11).replace(/[018]/g, function(c) {
                return (c ^ cryptoObj.getRandomValues(new Uint8Array(1))[0] & 15 >> c / 4).toString(16);
            });
        } else {
            uuid = "xxxxxxxxxxxx4xxxyxxxxxxxxxxxxxxx".replace(/[xy]/g, function(c) {
                var r = Math.random() * 16 | 0
                  , v = c === 'x' ? r : (r & 0x3 | 0x8);
                return v.toString(16);
            });
        }
        return uuid;
    }
    function _cookies() {
        return {
            getItem: function(sKey) {
                return decodeURIComponent(document.cookie.replace(new RegExp("(?:(?:^|.*;)\\s*" + encodeURIComponent(sKey).replace(/[\-\.\+\*]/g, "\\$&") + "\\s*\\=\\s*([^;]*).*$)|^.*$"), "$1")) || null;
            },
            setItem: function(sKey, sValue, vEnd, sPath, sDomain, bSecure) {
                if (!sKey || /^(?:expires|max\-age|path|domain|secure)$/i.test(sKey)) {
                    return false;
                }
                var sExpires = "";
                if (vEnd) {
                    switch (vEnd.constructor) {
                    case Number:
                        sExpires = vEnd === Infinity ? "; expires=Fri, 31 Dec 9999 23:59:59 GMT" : "; max-age=" + vEnd;
                        break;
                    case String:
                        sExpires = "; expires=" + vEnd;
                        break;
                    case Date:
                        sExpires = "; expires=" + vEnd.toUTCString();
                        break;
                    }
                }
                document.cookie = encodeURIComponent(sKey) + "=" + encodeURIComponent(sValue) + sExpires + (sDomain ? "; domain=" + sDomain : "") + (sPath ? "; path=" + sPath : "") + (bSecure ? "; secure" : "");
                return true;
            },
            removeItem: function(sKey, sPath, sDomain) {
                if (!sKey || !this.hasItem(sKey)) {
                    return false;
                }
                document.cookie = encodeURIComponent(sKey) + "=; expires=Thu, 01 Jan 1970 00:00:00 GMT" + (sDomain ? "; domain=" + sDomain : "") + (sPath ? "; path=" + sPath : "");
                return true;
            },
            hasItem: function(sKey) {
                return (new RegExp("(?:^|;\\s*)" + encodeURIComponent(sKey).replace(/[\-\.\+\*]/g, "\\$&") + "\\s*\\=")).test(document.cookie);
            },
            keys: function() {
                var aKeys = document.cookie.replace(/((?:^|\s*;)[^\=]+)(?=;|$)|^\s*|\s*(?:\=[^;]*)?(?:\1|$)/g, "").split(/\s*(?:\=[^;]*)?;\s*/);
                for (var nLen = aKeys.length, nIdx = 0; nIdx < nLen; nIdx++) {
                    aKeys[nIdx] = decodeURIComponent(aKeys[nIdx]);
                }
                return aKeys;
            }
        };
    }
    function extractRootDomain(url) {
        var domain = extractHostname(url)
          , splitArr = domain.split('.')
          , arrLen = splitArr.length;
        if (arrLen > 2) {
            domain = splitArr[arrLen - 2] + '.' + splitArr[arrLen - 1];
            if (splitArr[arrLen - 2].length === 2 && splitArr[arrLen - 1].length === 2) {
                domain = splitArr[arrLen - 3] + '.' + domain;
            }
        }
        return domain;
    }
    function extractHostname(url) {
        var hostname;
        if (url.indexOf("//") > -1) {
            hostname = url.split('/')[2];
        } else {
            hostname = url.split('/')[0];
        }
        hostname = hostname.split(':')[0];
        hostname = hostname.split('?')[0];
        return hostname;
    }
    win["ccao"] = win["ccao"] || {};
    win["cca"] = win["cca"] || {};
    var ccao = win["cca"];
    ccao.privacy = ccao.privacy || {
        que: []
    };
    if (win["ccao"].privacy && win["ccao"].privacy.que) {
        ccao.privacy.que.concat(win["ccao"].privacy.que);
    }
    ccao.pageState = ccao.pageState || {};
    ccao.pageState.start = new Date().getTime();
    ccao.pageState.cn1 = "";
    ccao.pageState.cn2 = "";
    ccao.pageState.cs1 = "";
    ccao.pageState.cs2 = "";
    ccao.pageState.engagement = ccao.pageState.engagement || {
        ttl: 60 * 1,
        count: 0,
        id: _uuidv4(),
        timeLastEngage: (new Date().getTime()) / 1000 / 60,
    }
    ccao.pageState.engagement.ttlMilli = ccao.pageState.engagement.ttl * 1000;
    ccao.pageState.engagement.ttlMin = ccao.pageState.engagement.ttl / 60;
    ccao.pageState.engagement.registerEngagement = function() {
        var present = (new Date().getTime()) / 1000 / 60;
        var timediff = present - ccao.pageState.engagement.timeLastEngage;
        var ttlMin = ccao.pageState.engagement.ttlMin;
        if (timediff < ttlMin) {
            ccao.pageState.engagement.timeLastEngage = (new Date().getTime()) / 1000 / 60;
            return;
        }
        ccao.pageState.engagement.count++;
        ccao.pageState.engagement.id = _uuidv4();
        ccao.pageState.engagement.timeLastEngage = (new Date().getTime()) / 1000 / 60;
        if (ccao.redoScriptLoad && win._ccScriptSettings) {
            ccao.redoScriptLoad(win._ccScriptSettings);
        }
    }
    ;
    ccao.pageState.genCookieGetParamsArray = function() {
        return [{
            name: ccao.pageState.cookieIDs.aid.name,
            value: ccao.pageState.cookieIDs.aid.value
        }, {
            name: ccao.pageState.cookieIDs.sid.name,
            value: ccao.pageState.cookieIDs.sid.value
        }, {
            name: ccao.pageState.cookieIDs.jid.name,
            value: ccao.pageState.cookieIDs.jid.value
        }, {
            name: ccao.pageState.cookieIDs.anid.name,
            value: ccao.pageState.cookieIDs.anid.value
        }];
    }
    ;
    ccao.pageState.genMiscGetParamsArray = function() {
        return [{
            name: "extReferer",
            value: ccao.pageState.refer.externalRefer
        }, {
            name: "curReferer",
            value: ccao.pageState.refer.currentRefer
        }, {
            name: "url",
            value: ccao.pageState.url
        }, {
            name: "prevPvid",
            value: ccao.pageState.refer.prevPvid
        }, {
            name: "pageViews",
            value: ccao.pageState.persistentParam.pageViews
        }];
    }
    ;
    ccao.pageState.genUtmGetParamsArray = function() {
        return [{
            name: "utm_campaign",
            value: ccao.pageState.persistentParam.utm_campaign || ""
        }, {
            name: "utm_medium",
            value: ccao.pageState.persistentParam.utm_medium || ""
        }, {
            name: "utm_term",
            value: ccao.pageState.persistentParam.utm_term || ""
        }, {
            name: "utm_content",
            value: ccao.pageState.persistentParam.utm_content || ""
        }, {
            name: "utm_source",
            value: ccao.pageState.persistentParam.utm_source || ""
        }];
    }
    ;
    ccao.pageState.genContextParamsArray = function() {
        var contextParamsArray = [];
        if (typeof ccao.pageState.jsonld === "object" && ccao.pageState.jsonld) {
            if (typeof (ccao.pageState.jsonld.author) === "object" && ccao.pageState.jsonld.author) {
                if (ccao.pageState.jsonld.author.name && typeof (ccao.pageState.jsonld.author.name) === "string") {
                    contextParamsArray.push({
                        name: "author",
                        value: ccao.pageState.jsonld.author.name
                    });
                } else if (ccao.pageState.jsonld.author.length && ccao.pageState.jsonld.author.length > 0) {
                    if (ccao.pageState.jsonld.author[0] && ccao.pageState.jsonld.author[0].name && typeof (ccao.pageState.jsonld.author[0].name) === "string") {
                        contextParamsArray.push({
                            name: "author",
                            value: ccao.pageState.jsonld.author[0].name
                        });
                    }
                }
            } else if (typeof (ccao.pageState.jsonld.author) === "string") {
                contextParamsArray.push({
                    name: "author",
                    value: ccao.pageState.jsonld.author
                });
            }
            if (typeof (ccao.pageState.jsonld.publisher) === "object" && ccao.pageState.jsonld.publisher && ccao.pageState.jsonld.publisher.name && typeof (ccao.pageState.jsonld.publisher.name) === "string") {
                contextParamsArray.push({
                    name: "publisher",
                    value: ccao.pageState.jsonld.publisher.name
                });
            } else if (typeof (ccao.pageState.jsonld.publisher) === "string") {
                contextParamsArray.push({
                    name: "publisher",
                    value: ccao.pageState.jsonld.publisher
                });
            }
            if (typeof (ccao.pageState.jsonld.editor) === "object" && ccao.pageState.jsonld.editor && ccao.pageState.jsonld.editor.name && typeof (ccao.pageState.jsonld.editor.name) === "string") {
                contextParamsArray.push({
                    name: "editor",
                    value: ccao.pageState.jsonld.editor.name
                });
            } else if (typeof (ccao.pageState.jsonld.editor) === "string") {
                contextParamsArray.push({
                    name: "editor",
                    value: ccao.pageState.jsonld.editor
                });
            }
            if (typeof (ccao.pageState.jsonld.articleSection) === "string" && ccao.pageState.jsonld.articleSection) {
                contextParamsArray.push({
                    name: "articleSection",
                    value: ccao.pageState.jsonld.articleSection
                });
            }
        }
        return contextParamsArray;
    }
    ;
    ccao.pageState.pageSocket = {
        inWebWorker: false,
        open: false
    };
    ccao.pageState.verbose = false;
    ccao.pageState.costevents = {};
    ccao.pageState.disablePlacement = false;
    ccao.pageState.cookieIDs = {
        aid: {
            name: "GLAM-AID",
            backup: _uuidv4(),
            value: ""
        },
        jid: {
            name: "GLAM-JID",
            backup: _uuidv4(),
            value: ""
        },
        sid: {
            name: "GLAM-SID",
            backup: _uuidv4(),
            value: ""
        },
        pvid: {
            name: "GLAM-PVID",
            value: _uuidv4()
        },
        anid: {
            name: "APPNEXUS",
            value: ""
        }
    };
    ccao.pageState.cookieIDs.jid.value = _cookies().getItem(ccao.pageState.cookieIDs.jid.name) || function() {
        var newDateObj = new Date(Date.now() + 20 * 60 * 1000);
        _cookies().setItem(ccao.pageState.cookieIDs.jid.name, ccao.pageState.cookieIDs.jid.backup, newDateObj, "/");
        return ccao.pageState.cookieIDs.jid.backup;
    }();
    ccao.pageState.cookieIDs.aid.value = _cookies().getItem(ccao.pageState.cookieIDs.aid.name) || function() {
        var newDateObj = new Date(Date.now() + 30 * 24 * 60 * 60 * 1000);
        _cookies().setItem(ccao.pageState.cookieIDs.aid.name, ccao.pageState.cookieIDs.aid.backup, newDateObj, "/");
        return ccao.pageState.cookieIDs.aid.backup;
    }();
    ccao.pageState.cookieIDs.sid.value = _cookies().getItem(ccao.pageState.cookieIDs.sid.name) || function() {
        _cookies().setItem(ccao.pageState.cookieIDs.sid.name, ccao.pageState.cookieIDs.sid.backup, "", "/");
        return ccao.pageState.cookieIDs.sid.backup;
    }();
    ccao.pageState.parentpvid = "";
    ccao.pageState.preserveInfoCookieName = "__j_state";
    var cookieData = JSON.parse(_cookies().getItem(ccao.pageState.preserveInfoCookieName)) || {};
    ccao.pageState.refer = {
        currentRefer: document.referrer || "",
        currentReferRoot: "",
        externalRefer: "",
        externalReferRoot: "",
        prevPvid: ""
    };
    ccao.pageState.url = window.location.href || "";
    if (ccao.pageState.refer.currentRefer === "") {
        ccao.pageState.refer.currentRefer = ccao.pageState.url;
    }
    ccao.pageState.refer.currentReferRoot = extractRootDomain(ccao.pageState.refer.currentRefer) || "";
    ccao.pageState.refer.externalRefer = cookieData["extreferer"] || "";
    if (ccao.pageState.refer.externalRefer === "") {
        ccao.pageState.refer.externalRefer = ccao.pageState.refer.currentRefer;
        ccao.pageState.refer.externalReferRoot = ccao.pageState.refer.currentReferRoot;
    } else {
        ccao.pageState.refer.externalReferRoot = extractRootDomain(ccao.pageState.refer.externalRefer) || "";
    }
    ccao.pageState.persistentParam = {};
    ccao.pageState.persistentParamNames = ["utm_campaign", "utm_source", "utm_medium", "utm_content", "utm_term", "landing_url", "pageViews", "prevPvid", "glam_revenue", "extreferer", "user_worth"];
    ccao.pageState.persistentParam.extreferer = ccao.pageState.refer.externalRefer;
    ccao.pageState.persistentParam.user_worth = cookieData["user_worth"] || 0;
    var match, search = /([^&=]+)=?([^&]*)/g, queryData = [];
    while ((match = search.exec(window.location.search.substring(1).toLowerCase())) !== null) {
        match.map(function(str) {
            return decodeURIComponent(str.replace(/\+/g, " "));
        });
        queryData[match[1].toLowerCase()] = match[2];
    }
    var queryKeys = Object.keys(queryData);
    for (i = 0; i < queryKeys.length; i++) {
        if (queryKeys[i] === "utm_source" || queryKeys[i] === "utm_campaign" || queryKeys[i] === "utm_term" || queryKeys[i] === "utm_medium" || queryKeys[i] === "utm_content") {
            if (!cookieData[queryKeys[i]] || cookieData[queryKeys[i]] === "" || cookieData[queryKeys[i]] !== queryData[queryKeys[i]]) {
                ccao.pageState.costevents.cpc = true;
                ccao.pageState.cookieIDs.jid.value = function() {
                    var newDateObj = new Date(Date.now() + 20 * 60 * 1000);
                    _cookies().setItem(ccao.pageState.cookieIDs.jid.name, ccao.pageState.cookieIDs.jid.backup, newDateObj, "/");
                    return ccao.pageState.cookieIDs.jid.backup;
                }();
                ccao.pageState.persistentParam["utm_source"] = "";
                ccao.pageState.persistentParam["utm_campaign"] = "";
                ccao.pageState.persistentParam["utm_term"] = "";
                ccao.pageState.persistentParam["utm_medium"] = "";
                ccao.pageState.persistentParam["utm_content"] = "";
                break;
            }
        }
    }
    ccao.pageState.persistentParamNames.forEach((function(v) {
        if ((typeof (queryData[v]) !== "undefined")) {
            ccao.pageState.persistentParam[v] = queryData[v];
        } else if (typeof (cookieData[v]) !== "undefined") {
            ccao.pageState.persistentParam[v] = cookieData[v];
        }
    }
    ));
    if (!ccao.pageState.persistentParam.pageViews) {
        ccao.pageState.persistentParam.pageViews = 0;
    }
    ccao.pageState.persistentParam.pageViews++;
    if (typeof (ccao.pageState.persistentParam.prevPvid) !== "undefined" && ccao.pageState.persistentParam.prevPvid !== "") {
        ccao.pageState.refer.prevPvid = ccao.pageState.persistentParam.prevPvid;
    }
    ccao.pageState.persistentParam.prevPvid = ccao.pageState.cookieIDs.pvid.value;
    if (typeof (ccao.pageState.persistentParam.landing_url) === "undefined" || ccao.pageState.persistentParam.landing_url === "") {
        ccao.pageState.persistentParam.landing_url = ccao.pageState.url;
    }
    if ((typeof (queryData["verbose"]) !== "undefined")) {
        ccao.pageState.verbose = true;
    }
    if (typeof (WebSocket) !== "undefined") {
        ccao.pageState.supportsWebSockets = true;
    } else {
        ccao.pageState.supportsWebSockets = false;
    }
    if (typeof (Worker) !== "undefined" && typeof (URL) !== "undefined") {
        ccao.pageState.supportsWebWorkers = true;
    } else {
        ccao.pageState.supportsWebWorkers = false;
    }
    if (ccao.pageState.supportsWebWorkers === true && ccao.pageState.supportsWebSockets === true) {
        ccao.pageState.pageSocket.inWebWorker = true;
    } else {
        ccao.pageState.pageSocket.inWebWorker = false;
    }
    ccao.pageState.jsonldmatches = document.querySelectorAll("script[type=application\\/ld\\+json]");
    if (ccao.pageState.jsonldmatches.length > 0) {
        var jsonldState;
        for (i = 0; i < ccao.pageState.jsonldmatches.length; i++) {
            try {
                if (!jsonldState || typeof jsonldState !== "object") {
                    jsonldState = JSON.parse(ccao.pageState.jsonldmatches[i].innerText);
                } else {
                    var parsedJson = JSON.parse(ccao.pageState.jsonldmatches[i].innerText);
                    if (!jsonldState.author || jsonldState.author == "") {
                        jsonldState.author = parsedJson.author || "";
                    }
                    if (!jsonldState.publisher || jsonldState.publisher == "") {
                        jsonldState.publisher = parsedJson.publisher || "";
                    }
                    if (!jsonldState.editor || jsonldState.editor == "") {
                        jsonldState.editor = parsedJson.editor || "";
                    }
                    if (!jsonldState.articleSection || jsonldState.articleSection == "") {
                        jsonldState.articleSection = parsedJson.articleSection || "";
                    }
                }
            } catch (e) {
                console.debug("invalid schema json unable to parse");
            }
        }
        ccao.pageState.jsonld = jsonldState;
    } else {
        ccao.pageState.jsonld = {};
    }
    ccao.pageState.lastClockIn = ccao.pageState.start;
    _saveCookie();
    var ccao = win["cca"] || {};
    ccao.privacy = ccao.privacy || {
        que: []
    };
    ccao.custAud = ccao.custAud || {
        que: []
    };
    ccao.fireAudienceEvent = function(id, cs, usp, pco) {
        var eventObject = {
            "id": id,
            "pco": pco
        };
        ccao.fireTrackingEvent(eventObject, false);
    }
    ;
    ccao.fireTrackingEvent = function(data, debug) {
        if (debug) {
            console.log("Tracking Pixel triggered");
        }
        ccao.privacy.que.push(function() {
            if (!ccao.privacy.law || typeof ccao.privacy.law !== "string") {
                ccao.privacy.law = "unknown";
            }
            switch (ccao.privacy.law.toLowerCase()) {
            case "gdpr":
                if (ccao.privacy.gdpr.Consent) {
                    fireTrackingInternal(data, debug)
                } else {
                    if (debug) {
                        console.log("GDPR consent not given, cannot fire Tracking Pixel");
                    }
                }
                break;
            case "ccpa":
                if (ccao.privacy.ccpa.Consent) {
                    fireTrackingInternal(data, debug)
                } else {
                    if (debug) {
                        console.log("CCPA consent not given, cannot fire Tracking Pixel");
                    }
                }
                break;
            case "na":
                fireTrackingInternal(data, debug)
                break;
            case "optout":
            case "unknown":
            default:
                break;
            }
        });
    }
    ;
    var fireTrackingMultiple = function(data, debug) {
        if (debug) {
            console.log("Multiple Pixels requested");
        }
        var endpoint = win._ccLauncherSettings.customEvents;
        var ceUrl = new URL(endpoint + "/p/" + _ccScriptSettings.site.parentId + "/ces");
        if (ccao.privacy.gdpr && ccao.privacy.gdpr.CS) {
            ceUrl.searchParams.set("cs", ccao.privacy.gdpr.CS);
        }
        if (ccao.privacy.ccpa && ccao.privacy.ccpa.ConsentString) {
            ceUrl.searchParams.set("usp", ccao.privacy.ccpa.CS);
        }
        var bodyJson = [];
        for (i in data) {
            var event = data[i];
            if (!event.id) {
                if (debug) {
                    console.log("Event is missing ID, cannot be sent");
                    console.log(event);
                }
                continue;
            }
            if (event.pco !== undefined && !ceUrl.searchParams.get("pco")) {
                ceUrl.searchParams.set("pco", event.pco);
            }
            var eventObject = {};
            eventObject["triggerid"] = event.id;
            eventObject["parent_id"] = _ccScriptSettings.site.parentId;
            eventObject["profileId"] = _ccScriptSettings.user.id;
            eventObject["pageview_id"] = _ccScriptSettings.pageData.pvid;
            if (event.NumberKey && event.NumberKey != "" && event.NumberValue && !isNaN(event.NumberValue)) {
                eventObject["numberkey"] = event.NumberKey;
                eventObject["numbervalue"] = event.NumberValue;
            }
            if (event.StringKey && event.StringKey != "" && event.StringValue && event.StringValue != "") {
                eventObject["stringkey"] = event.StringKey;
                eventObject["stringvalue"] = event.StringValue;
            }
            var codes = ["USD", "EUR"];
            if (event.Money && !isNaN(event.Money) && event.CurrencyCode && event.CurrencyCode.toUpperCase && codes.includes(event.CurrencyCode.toUpperCase())) {
                eventObject["money"] = event.Money;
                eventObject["currencycode"] = event.CurrencyCode.toUpperCase();
            }
            if (event.Label && event.Label != "") {
                eventObject["event_label"] = event.Label;
            }
            ccao.pageState.engagement.registerEngagement();
            eventObject["engagement_id"] = ccao.pageState.engagement.id;
            eventObject["engagement_count"] = ccao.pageState.engagement.count;
            eventObject["engagement_ttl"] = ccao.pageState.engagement.ttl;
            bodyJson.push(eventObject);
            if (debug) {
                console.log(eventObject);
            }
        }
        var xmlHttp = new XMLHttpRequest();
        xmlHttp.open("POST", ceUrl, true);
        xmlHttp.setRequestHeader('Content-Type', 'application/json');
        xmlHttp.send(JSON.stringify(bodyJson));
        if (debug) {
            console.log("Custom Event Pixel request sent. URL: " + ceUrl);
            console.log(bodyJson);
        }
    }
    var fireTrackingInternal = function(data, debug) {
        if (Array.isArray(data)) {
            fireTrackingMultiple(data, debug);
            return
        }
        if (!data.id) {
            if (debug) {
                console.log("Event is missing ID, cannot be sent");
                console.log(event);
            }
            return
        }
        var endpoint = win._ccLauncherSettings.customEvents;
        var pixel = new Image();
        var pagePixelUrl = new URL(endpoint + "/p/" + _ccScriptSettings.site.parentId + "/ce/" + data.id);
        pagePixelUrl.searchParams.set("ccuid", _ccScriptSettings.user.id);
        pagePixelUrl.searchParams.set("pvid", _ccScriptSettings.pageData.pvid);
        if (ccao.privacy.gdpr && ccao.privacy.gdpr.CS) {
            pagePixelUrl.searchParams.set("cs", ccao.privacy.gdpr.CS);
        }
        if (ccao.privacy.ccpa && ccao.privacy.ccpa.ConsentString) {
            pagePixelUrl.searchParams.set("usp", ccao.privacy.ccpa.CS);
        }
        if (data.pco) {
            pagePixelUrl.searchParams.set("pco", data.pco);
        }
        if (data.NumberKey && data.NumberKey != "" && data.NumberValue && isNaN(data.NumberValue) == false) {
            pagePixelUrl.searchParams.set("nk", data.NumberKey);
            pagePixelUrl.searchParams.set("nv", data.NumberValue);
        }
        if (data.StringKey && data.StringKey != "" && data.StringValue && data.StringValue != "") {
            pagePixelUrl.searchParams.set("sk", data.StringKey);
            pagePixelUrl.searchParams.set("sv", data.StringValue);
        }
        var codes = ["USD", "EUR"];
        if (data.Money && !isNaN(data.Money) && data.CurrencyCode && data.CurrencyCode.toUpperCase && codes.includes(data.CurrencyCode.toUpperCase())) {
            pagePixelUrl.searchParams.set("mn", data.Money);
            pagePixelUrl.searchParams.set("cc", data.CurrencyCode.toUpperCase());
        }
        if (data.Label && data.Label != "") {
            pagePixelUrl.searchParams.set("lb", data.Label);
        }
        ccao.pageState.engagement.registerEngagement();
        pagePixelUrl.searchParams.set("engid", ccao.pageState.engagement.id);
        pagePixelUrl.searchParams.set("engcount", ccao.pageState.engagement.count);
        pagePixelUrl.searchParams.set("engttl", ccao.pageState.engagement.ttl);
        pixel.src = pagePixelUrl.href;
        setTimeout(function() {
            if (!pixel.complete || !pixel.naturalWidth) {
                pixel.src = "";
            }
        }, 2000);
        if (debug) {
            console.log("Custom Event Pixel request sent. URL: " + pagePixelUrl.href);
        }
    };
    var tempQue = ccao.custAud.que
    for (callback of tempQue) {
        callback();
    }
    ccao.custAud.que = {
        push: function(callback) {
            callback();
        }
    }
}
)(window, document);
;(function(win, doc) {
    var launcherSettings = win._ccLauncherSettings;
    var ccaoName = "cca";
    var settingsCallbackWaitingQueue = [];
    win._ccReady = win._ccReady || [];
    win._ccApiReady = win._ccApiReady || [];
    win[ccaoName] = win[ccaoName] || function() {
        (win[ccaoName].q = win[ccaoName].q || []).push(arguments);
    }
    ;
    var ccao = win[ccaoName];
    ccao.q = [];
    ccao.init = true;
    ccao.messageProcessor = function() {
        (win[ccaoName].q = win[ccaoName].q || []).push(arguments);
    }
    ;
    ccao.push = function() {
        win[ccaoName].messageProcessor.apply(this, arguments);
    }
    ;
    ccao.loadedScripts = {
        count: 0
    };
    ccao.settings = win._ccScriptSettings;
    ccao.baseScript = ccao.baseScript || [];
    ccao.privacy = ccao.privacy || {
        que: []
    };
    ccao.site = ccao.site || {};
    ccao.site.gdpr = ccao.site.gdpr || {
        key: "__cmp",
        check: true,
        wait: false
    };
    var cookieConsent = ccao.site.gdpr.check === false;
    var pvid = ccao.pageState.cookieIDs.pvid.value;
    function _saveCookie() {
        cookieData = {};
        ccao.pageState.persistentParamNames.forEach((function(v) {
            cookieData[v] = ccao.pageState.persistentParam[v];
        }
        ));
        var numMinutes = 20;
        var newDateObj = new Date(Date.now() + numMinutes * 60000);
        _cookies().setItem(ccao.pageState.preserveInfoCookieName, JSON.stringify(cookieData), newDateObj, "/");
    }
    ccao.debugMode = function() {
        return false;
    }
    ;
    ccao.clearFlagCookie = function() {
        if (!ccao.settings.site.sharedDomain) {
            var img = new Image(1,1);
            img.src = launcherSettings.api + "/sync/clear";
        }
    }
    ;
    ccao.notifyCCReady = function notifyCCReady(settingObj) {
        settingObj.pageData = {
            "pvid": pvid
        };
        ccao.settings = settingObj;
        win._ccSettings = settingObj;
        if (win._ccReady !== null) {
            var readyLen = win._ccReady.length;
            for (var i = 0; i < readyLen; i++) {
                win._ccReady[i](settingObj);
            }
        }
        win._ccReady = {
            "push": function(pushFunc) {
                if (typeof (pushFunc) === 'function')
                    pushFunc(settingObj);
            }
        };
    }
    ;
    ccao.notifyApiReady = function notifyApiReady() {
        if (win._ccApiReady !== null) {
            var readyLen = win._ccApiReady.length;
            for (var i = 0; i < readyLen; i++) {
                win._ccApiReady[i]();
            }
        }
        win._ccApiReady = {
            "push": function(pushFunc) {
                if (typeof (pushFunc) === 'function')
                    pushFunc();
            }
        };
    }
    ;
    ccao.getSettings = function getSettings(callback) {
        win._ccReady.push(callback);
    }
    ;
    ccao.afterPageLoad = function(func) {
        if (document.readyState === "complete") {
            func();
        } else {
            ccao.attachCCEvent("load", function() {
                func();
            });
        }
    }
    ;
    ccao.attachCCEvent = function(eventName, callback) {
        try {
            win.addEventListener ? win.addEventListener(eventName, callback, true) : win.attachEvent && win.attachEvent("on" + eventName, callback);
        } catch (e) {
            console && console.log(e);
        }
    }
    ;
    function newCustomEvent(event, params) {
        params = params || {
            bubbles: false,
            cancelable: false,
            detail: undefined
        };
        var evt = document.createEvent('CustomEvent');
        evt.initCustomEvent(event, params.bubbles, params.cancelable, params.detail);
        return evt;
    }
    function setStorage(store, key, value) {
        if (!ccao.privacy.law || typeof ccao.privacy.law !== "string") {
            ccao.privacy.law = "unknown";
        }
        switch (ccao.privacy.law.toLowerCase()) {
        case "gdpr":
            if (ccao.privacy.gdpr.Consent) {
                store.setItem(key, value);
            }
            break;
        case "ccpa":
            if (ccao.privacy.ccpa.Consent) {
                store.setItem(key, value);
            }
            break;
        case "na":
            store.setItem(key, value);
            break;
        case "optout":
        case "unknown":
        default:
            break;
        }
    }
    var createCustomEvent = function(evtType, evtDetail) {
        if (typeof win.CustomEvent === "function")
            return new CustomEvent(evtType,{
                detail: evtDetail
            });
        return newCustomEvent(evtType, {
            detail: evtDetail
        });
    };
    function api() {
        var userId = null;
        this.ready = false;
        this.addEventListener = function(evt, callback) {
            if (this.eventTarget) {
                this.eventTarget.addEventListener(evt, callback);
            }
        }
        ;
        this.readyEvent = function(callback) {
            if (this.eventTarget) {
                this.eventTarget.addEventListener('apiReady', function(evt) {
                    callback({
                        'userId': userId
                    });
                });
            }
        }
        ;
        this.realtimeReady = function(callback) {
            if (this.eventTarget) {
                this.eventTarget.addEventListener('realtimeReady', function(evt) {
                    callback(evt.detail);
                });
            }
        }
        ;
        if (this.eventTarget) {
            this.eventTarget.addEventListener('userIdReady', function(evt) {
                userId = evt.detail.id;
            });
        }
        this.userIdEvent = function(callback) {
            if (this.eventTarget) {
                this.eventTarget.addEventListener('userIdReady', function(evt) {
                    callback(evt.detail.id, evt.detail.isNew);
                });
            }
            if (userId !== null && this.ready === false) {
                callback(userId, window._ccScriptSettings.user.isNew);
            }
        }
        ;
        if (this.eventTarget) {
            this.eventTarget.addEventListener('audiencesReady', function(evt) {
                ccao.settings.user.audienceMemberships = evt.detail;
                var user = {
                    audienceMemberships: evt.detail
                };
                ccao.privacy = ccao.privacy || {};
                ccao.privacy.que = ccao.privacy.que || [];
                ccao.privacy.que.push(function() {
                    setStorage(win.sessionStorage, "carbonUser", JSON.stringify(user));
                });
            });
        }
        this.audiencesReady = function(callback) {
            if (this.eventTarget) {
                this.eventTarget.addEventListener('audiencesReady', function(evt) {
                    callback(evt.detail);
                });
            }
        }
        ;
        if (this.eventTarget) {
            this.eventTarget.addEventListener('interestsReady', function(evt) {
                ccao.settings.user.interests = evt.detail;
            });
        }
        this.interestsReady = function(callback) {
            if (this.eventTarget) {
                this.eventTarget.addEventListener('interestsReady', function(evt) {
                    callback(evt.detail);
                });
            }
        }
        ;
        if (this.eventTarget) {
            this.eventTarget.addEventListener('demographicsReady', function(evt) {
                ccao.settings.user.demographics = evt.detail;
            });
        }
        this.demographicsReady = function(callback) {
            if (this.eventTarget) {
                this.eventTarget.addEventListener('demographicsReady', function(evt) {
                    callback(evt.detail);
                });
            }
        }
        ;
        this.brandsReady = function(callback) {
            if (this.eventTarget) {
                this.eventTarget.addEventListener('brandsReady', function(evt) {
                    callback(evt.detail);
                });
            }
        }
        ;
        if (this.eventTarget) {
            this.eventTarget.addEventListener('brandsReady', function(evt) {
                ccao.settings.user.brands = evt.detail;
            });
        }
    }
    ;api.prototype.eventTarget = document.createElement(null);
    api.prototype.dispatchEvent = function(evtType, detail) {
        this.eventTarget.dispatchEvent(createCustomEvent(evtType, detail));
    }
    ;
    ccao.api = new api();
    win.carbonApi = ccao.api;
    win.carbon = win.carbonApi;
    ccao.notifyApiReady();
    ccao.api.addEventListener("revenue", (e)=>{
        ccao.pageState.persistentParam.user_worth += e.detail;
        if (cookieConsent === true)
            _saveCookie();
        const worthUpdatedEvent = {
            type: "worthUpdated",
            data: {
                aid: ccao.pageState.cookieIDs.aid.value,
                worth: ccao.pageState.persistentParam.user_worth,
                increase: e.detail
            }
        };
        ccao.api.dispatchEvent(worthUpdatedEvent.type, worthUpdatedEvent.data);
    }
    );
    function userIdComplete() {
        try {
            if (win._ccScriptSettings.localCacheUserTracking && ccao.setUserStorage) {
                ccao.setUserStorage();
            }
            ccao.api.dispatchEvent('userIdReady', {
                id: window._ccScriptSettings.user.id,
                isNew: window._ccScriptSettings.user.isNew
            });
        } catch (err) {
            console.debug('error:' + err.message);
        }
    }
    ccao.loadScript = function(scriptUri, callback, onError) {
        setTimeout(function() {
            var scriptTag = document.createElement("script");
            scriptTag.src = scriptUri;
            scriptTag.type = "text/javascript";
            scriptTag.async = true;
            if (callback !== undefined) {
                scriptTag.addEventListener('load', callback);
            }
            if (onError !== undefined) {
                scriptTag.onerror = onError;
            }
            document.body.appendChild(scriptTag);
        }, 1);
    }
    ;
    function fireIMMessage(event) {
        if (!ccao.privacy.law || typeof ccao.privacy.law !== "string") {
            ccao.privacy.law = "unknown";
        }
        switch (ccao.privacy.law.toLowerCase()) {
        case "gdpr":
            if (ccao.privacy.gdpr.Consent) {
                event.source.postMessage({
                    carbon: true,
                    method: 'imload',
                    object: win._ccScriptSettings,
                    href: window.location.href
                }, event.origin);
            }
            break;
        case "ccpa":
            if (ccao.privacy.ccpa.Consent) {
                event.source.postMessage({
                    carbon: true,
                    method: 'imload',
                    object: win._ccScriptSettings,
                    href: window.location.href
                }, event.origin);
            }
            break;
        case "na":
            event.source.postMessage({
                carbon: true,
                method: 'imload',
                object: win._ccScriptSettings,
                href: window.location.href
            }, event.origin);
            break;
        case "optout":
        case "unknown":
        default:
            break;
        }
    }
    var loadBundle = function() {
        ccao.loadScript(launcherSettings.api + "/script/bundle?id=" + launcherSettings.script + "&parentId=" + launcherSettings.parent);
    };
    var decideUserId = function(continueCallback) {
        ccao.mergeUserIds = function() {
            ccao.mergeUserIds = null;
            var baseUser = {
                ccuid: null,
                ccsid: null
            };
            var localUser = win._ccScriptSettings.user.localCachedUser || {
                localCache: false,
                cached: false
            };
            var bcUser = win._ccScriptSettings.user.browserCachedUser || {
                browserCache: false,
                cached: false
            };
            var fpFrameUser = win._ccScriptSettings.user.fpframeuser || {
                fp: false
            };
            var cachedUser = Object.assign({}, baseUser, localUser, bcUser, fpFrameUser);
            if (cachedUser.fp === true || cachedUser.cached === true) {
                win._ccScriptSettings.user.isNew = false;
                if (win._ccScriptSettings.user.id !== cachedUser.ccuid) {
                    win._ccScriptSettings.user.id = cachedUser.ccuid;
                    win._ccScriptSettings.user.idChange = true;
                }
            } else if (cachedUser.ccuid !== null && win._ccScriptSettings.user.isNew === true) {
                win._ccScriptSettings.user.id = cachedUser.ccuid;
            }
            if (cachedUser.ccsid !== null) {
                win._ccScriptSettings.session.isNew = false;
                if (win._ccScriptSettings.session.id !== cachedUser.ccsid) {
                    win._ccScriptSettings.session.id = cachedUser.ccsid;
                    win._ccScriptSettings.user.idChange = true;
                }
            }
            userIdComplete();
            continueCallback();
        }
        ;
        if (win._ccScriptSettings.cookieSettingsType === 4 && typeof (win._ccScriptSettings.user.fpframeuser) === 'undefined') {
            ccao.mergeUserIdTimeout = window.setTimeout(ccao.mergeUserIds, 1500);
        } else {
            ccao.mergeUserIds();
        }
    };
    var setUser = function(endpoint) {
        if (!ccao.privacy.law || typeof ccao.privacy.law !== "string") {
            ccao.privacy.law = "unknown";
        }
        switch (ccao.privacy.law.toLowerCase()) {
        case "gdpr":
            if (ccao.privacy.gdpr.Consent) {
                ccao.loadScript(endpoint);
            }
            break;
        case "ccpa":
            if (ccao.privacy.ccpa.Consent) {
                ccao.loadScript(endpoint);
            }
            break;
        case "na":
            var img = new Image(1,1);
            ccao.loadScript(endpoint);
            break;
        case "optout":
        case "unknown":
        default:
            break;
        }
    }
    var loaded = false;
    var scriptsLoadedCallback = function() {
        if (loaded === true)
            return;
        loaded = true;
        var finishLaunch = function() {
            if (win._ccScriptSettings.cookieSettingsType === 0 || win._ccScriptSettings.cookieSettingsType === 3) {
                if (win._ccScriptSettings.user.idChange !== undefined || win._ccScriptSettings.user.isNew || win._ccScriptSettings.session.isNew) {
                    var endpoint = win._ccLauncherSettings.api + '/setUser?parent=' + win._ccScriptSettings.site.parentId + '&site=' + win._ccScriptSettings.site.scriptId + '&ccuid=' + win._ccScriptSettings.user.id + '&ccsid=' + win._ccScriptSettings.session.id;
                    ccao.privacy = ccao.privacy || {};
                    ccao.privacy.que = ccao.privacy.que || [];
                    ccao.privacy.que.push(function() {
                        setUser(endpoint);
                        if (!win._ccLauncherSettings.api.includes(".ccgateway.net")) {
                            endpoint = endpoint.replace(win._ccLauncherSettings.api, win._ccLauncherSettings.cdn);
                            setUser(endpoint);
                        }
                    });
                }
            }
            if (win._ccScriptSettings.cookieSettingsType === 4) {
                if (win._ccScriptSettings.user.idChange !== undefined || win._ccScriptSettings.user.isNew || win._ccScriptSettings.session.isNew) {
                    ccao.setFpFrameUser(win._ccScriptSettings.user.id, win._ccScriptSettings.session.id);
                }
            }
            var samplingSettings = win._ccScriptSettings.sampling || {
                active: false,
                sample: true
            };
            if (samplingSettings.active === false || samplingSettings.sample === true)
                loadBundle();
            else
                ccao.samplingCallback = loadBundle;
            userIdComplete();
        };
        var fpRedirectCallback = function() {
            ccao.fpRedirect(finishLaunch);
        };
        var callbackFunc = win._ccScriptSettings.cookieSettingsType === 1 && ccao.fpRedirect ? fpRedirectCallback : finishLaunch;
        decideUserId(callbackFunc);
    };
    var loadedScripts = 0;
    var launchScriptCallback = function() {
        if (++loadedScripts === win._ccScriptSettings.launcherScripts.length) {
            window.setTimeout(function() {
                scriptsLoadedCallback();
            }, 1);
        }
    };
    ccao.launchScripts = function() {
        if (win._ccScriptSettings.launcherScripts) {
            for (var scriptIndex = 0; scriptIndex < win._ccScriptSettings.launcherScripts.length; scriptIndex++) {
                ccao.loadScript(win._ccScriptSettings.launcherScripts[scriptIndex], launchScriptCallback);
            }
        }
    }
    ;
    var launch = function() {
        var doLaunch = function(ccuid, iscached) {
            var browserCachedUser = {
                cached: false,
                browserCache: false
            };
            if (iscached) {
                browserCachedUser.browserCache = browserCachedUser.cached = true;
            }
            browserCachedUser.ccuid = ccuid;
            win._ccScriptSettings.user.browserCachedUser = browserCachedUser;
            if (loadedScripts === win._ccScriptSettings.launcherScripts.length) {
                scriptsLoadedCallback();
            }
        };
        if (win._ccScriptSettings.browserCacheUserTracking) {
            var requestTime = new Date();
            ccao.idCallback = function() {
                var cached = false;
                if (win.carbonUIDCache === undefined)
                    cached = true;
                else
                    cached = win.carbonUIDCache < requestTime;
                ccao.pageState = cca.pageState || {};
                ccao.pageState.ccuid = win._carbonUID || "";
                doLaunch(win._carbonUID, cached);
                ccao.idCallback = undefined;
            }
            ;
        }
        ccao.launchScripts();
    };
    launch();
}
)(window, document);

        ,
        r.hasBlockerFlag = function(n) {
            for (var t = 0; t < this.bids.length; t++)
                if (this.bids[t] === n)
                    return !0;
            return !1
        }
        ,
        r.hasDisabledFlag = function(n) {
            for (var t = 0; t < this.dids.length; t++)
                if (this.dids[t] === n)
                    return !0;
            return !1
        }
        ,
        r.hacksFlags = function() {
            return this.hf || 0
        }
        ,
        r.blockerScore = function() {
            return this.adbs || 0
        }
        ,
        r.disabledScore = function() {
            return this.diss || 0
        }
        ,
        r.hackApplied = function(n) {
            this.hf |= n
        }
        ,
        r.forceBlocking = function() {
            this.fbl = !0
        }
        ,
        r.forceDisabled = function() {
            this.fdis = !0
        }
        ,
        t = n,
        Object.defineProperty(t, "prototype", {
            writable: !1
        }),
        t
    }
    )();
    var g = "object" == typeof window.navigator && window.navigator.userAgent || ""
      , b = (function() {
        function n() {
            !(function(n, t) {
                if (!(n instanceof t))
                    throw new TypeError("Cannot call a class as a function")
            }
            )(this, n),
            f(g.indexOf) && (this.firefox = -1 !== g.indexOf("Firefox/"),
            this.edge = -1 !== g.indexOf("Edge/"),
            this.chrome = !this.edge && -1 !== g.indexOf("Chrome/"),
            this.safari = !this.edge && !this.chrome && -1 !== g.indexOf("Safari/"),
            this.ie = -1 !== g.indexOf("MSIE") || -1 !== g.indexOf("Trident"),
            this.googleweblight = -1 !== g.indexOf("googleweblight"),
            this.webcache = "webcache.googleusercontent.com" === window.location.hostname,
            this.iOS = -1 !== g.indexOf("iPhone") || -1 !== g.indexOf("iPad"))
        }
        var t, r = n.prototype;
        return r.isChrome = function() {
            return this.chrome
        }
        ,
        r.isSafari = function() {
            return this.safari
        }
        ,
        r.isFirefox = function() {
            return this.firefox
        }
        ,
        r.isIE = function() {
            return this.ie
        }
        ,
        r.isOldIE = function() {
            return this.oldIE
        }
        ,
        r.isEdge = function() {
            return this.edge
        }
        ,
        r.isiOS = function() {
            return this.iOS
        }
        ,
        r.isWhitelisted = function() {
            for (var n = u.C || [], t = 0; t < n.length; t++)
                if (!0 === this[n[t]])
                    return !0;
            if (!g || !f(g.toLowerCase))
                return !1;
            for (var r = g.toLowerCase() || "", i = u.S || [], e = 0; e < i.length; e++)
                if (r.indexOf(i[e]) > -1)
                    return !0;
            return !1
        }
        ,
        r.isDisabled = function() {
            for (var n = u.D, t = 0; n && t < n.length; t++)
                if (!0 === this[n[t]])
                    return !0;
            return !1
        }
        ,
        r.isInteractable = function() {
            return "undefined" != typeof XMLHttpRequest && "withCredentials"in new XMLHttpRequest && !this.isDisabled() && !this.isWhitelisted()
        }
        ,
        t = n,
        Object.defineProperty(t, "prototype", {
            writable: !1
        }),
        t
    }
    )()
      , y = window.unescape || window.decodeURIComponent
      , k = window.escape || window.encodeURIComponent
      , P = "cookieStore"in window && window.cookieStore;
    function $(n, t, r) {
        var i = r || {};
        if (void 0 === t)
            return P && !i.sync ? n ? P.getAll(n) : P.getAll() : new Promise((function(t) {
                var r, i, e, o = [], u = document.cookie.split(";");
                for (e = 0; e < u.length; e++)
                    if (r = u[e].substring(0, u[e].indexOf("=")).trim(),
                    i = u[e].substring(u[e].indexOf("=") + 1),
                    !n || r === n)
                        try {
                            o.push({
                                name: r,
                                value: y(i)
                            })
                        } catch (n) {}
                t(o)
            }
            ));
        if (P && !i.sync) {
            if (!i.domain && null !== i.domain) {
                var e = window.location.hostname;
                e && (i.domain = e)
            }
            return i.domain && "." === i.domain[0] && (i.domain = i.domain.substring(1)),
            !t || i.maxAge < 0 ? i.hasOwnProperty("domain") ? P.delete({
                name: n,
                domain: i.domain
            }) : P.delete(n) : (i.maxAge && (i.expires || (i.expires = Date.now() + 1e3 * i.maxAge),
            delete i.maxAge),
            i.sameSite || (i.sameSite = "none"),
            P.set(o({
                name: n,
                value: t
            }, i)))
        }
        return new Promise((function(r) {
            var e = t ? k(t) : "";
            if (t || (i.maxAge = -1),
            i.maxAge && (e += "; max-age=" + i.maxAge),
            !i.domain && null !== i.domain) {
                var o = window.location.hostname;
                o && (i.domain = "." + o)
            }
            i.domain && (e += "; domain=" + i.domain),
            null == i.path && (i.path = "/"),
            i.path && (e += "; path=" + i.path),
            "https:" === window.location.protocol && "PublicKeyCredential"in window && (e += "; SameSite=None; Secure"),
            document.cookie = n + "=" + e,
            r()
        }
        )).then((function() {
            if (t && i.domain)
                return $(n).then((function(t) {
                    if (!t || !t.length)
                        throw new Error("failed to set cookie " + n + " on " + i.domain)
                }
                ))
        }
        ))
    }
    function _(n, t) {
        for (var r, i = n.split("&"), e = void 0 === t || t, o = [], u = 0; u < i.length; u++)
            if ((r = i[u].split("=", 2))[0] && e)
                try {
                    o.push([decodeURIComponent(r[0] || ""), decodeURIComponent(r[1] || "")])
                } catch (n) {}
            else
                o.push(r);
        return o
    }
    function C(n, t) {
        t.forEach((function(t) {
            try {
                n(t[0], t[1])
            } catch (n) {}
        }
        ))
    }
    function S(n, t, r) {
        var i = _((n.search || "").toString().substring(1), r)
          , e = _((n.hash || "").toString().substring(1), r);
        return t && f(window.addEventListener) && window.addEventListener("popstate", (function() {
            i = _(n.search.substring(1)),
            e = _(n.hash.substring(1))
        }
        )),
        {
            getHashVariable: function(n) {
                return (function(n, t) {
                    var r = !1;
                    return C((function(n, i) {
                        return r = n === t ? i : r
                    }
                    ), n),
                    r
                }
                )(e, n)
            },
            getQueryVariable: function(n, t) {
                return (function(n, t, r) {
                    if (r)
                        return !1;
                    var i = !1;
                    return C((function(n, r) {
                        return i = n === t ? r : i
                    }
                    ), n),
                    i
                }
                )(i, n, t)
            },
            getQueryVariablesWithMatch: function(n) {
                return (function(n, t) {
                    var r = {};
                    return C((function(n, i) {
                        t(n) && (r[n] = i)
                    }
                    ), n),
                    r
                }
                )(i, n)
            }
        }
    }
    var E = S(window.location, !0, !0)
      , D = E.getHashVariable
      , T = E.getQueryVariable
      , A = E.getQueryVariablesWithMatch;
    function I(n) {
        var t = n && n || window.location;
        return 0 === ("" + t).indexOf("about:blank") || !!/((\.?)|(:\/\/))getadmiral\.com\/blank\.html$/.test(t.origin + t.pathname)
    }
    function M(n) {
        return n && "." !== n[0] ? "." + n : n
    }
    var O = {}
      , R = u.I
      , N = u.M
      , j = u.O
      , x = u.R
      , L = u.N
      , B = /^(?:([0-9]+)\.)?.*?([^.]+)$/
      , U = /^([0-9]+)\.(.+)$/
      , H = window && window.location && window.location.hostname
      , q = M(H)
      , F = M(H && H.replace(/^(www|m)\./, ""))
      , W = q && q !== F
      , V = !1
      , z = {}
      , G = !1
      , J = {
        maxAge: L,
        domain: F
    }
      , X = {
        maxAge: L,
        domain: q
    };
    function K(n) {
        return n && (n.match(/\./g) || []).length
    }
    function Q(n, t, r, i) {
        var e = [K(r) || 0, 0 | t || 0, n].join(".");
        return $(R, e, {
            maxAge: i,
            domain: r
        })
    }
    function Z(n, t, r) {
        if (!n)
            return $(N, null, {
                domain: t
            });
        var i = [K(t) || 0, n].join(".");
        return $(N, i, {
            maxAge: r,
            domain: t
        })
    }
    function Y(n) {
        return Z(n, F, L).catch((function(t) {
            if (W)
                return Z(n, q, L);
            throw t
        }
        )).then((function() {
            z[N] && ($(N, null, {
                domain: q
            }),
            z[N] = !1)
        }
        ))
    }
    function nn() {
        var n = arguments.length > 0 && void 0 !== arguments[0] ? arguments[0] : {}
          , t = {
            source: !0,
            medium: !0,
            name: !0,
            campaign: !0,
            content: !0,
            term: !0
        }
          , r = A((function(n) {
            var r = n.substr(0, 4);
            return !("utm_" !== r || !t[n.substr(4)]) || "adm_" === r
        }
        ))
          , i = window.location
          , e = "" + i;
        return e.length >= 3 && !I(i) && (r.sourceURL = e),
        o({}, r, n)
    }
    function tn(n, t) {
        return (n || []).map((function(n) {
            var r = {
                offerName: n.offerName || "",
                offerID: n.offerID || "",
                offerType: n.offerType || "",
                addon: "true" === n.addon || !0 === n.addon
            };
            return t && n.benefitDisplayIDs && (r.benefitDisplayIDs = n.benefitDisplayIDs),
            r
        }
        ))
    }
    function rn(n) {
        var t = {};
        return (n || []).forEach((function(n) {
            var r = n.benefitDisplayIDs || [];
            d(r) && (r = r.split("\n")),
            r.forEach((function(n) {
                t[n] = !0
            }
            ))
        }
        )),
        Object.keys(t)
    }
    function en(n) {
        var t = rn(n).join(",") || (n && n.length > 0 ? "none" : "");
        return t || V ? $(j, t, J).catch((function(n) {
            if (W)
                return $(j, t, X);
            throw n
        }
        )) : Promise.resolve()
    }
    function on(n, t) {
        return t ? [K(n) || 0, t].join(".") : ""
    }
    function un(n) {
        return Math.max(0, Math.round(1e3 * (n || 0)) / 1e3)
    }
    var an = window;
    function cn(n) {
        return n && "getEntriesByName"in n ? n : an.performance
    }
    function sn(n, t) {
        var r = [];
        try {
            var i = new URL(n,window.location).href;
            r = cn(t).getEntriesByName(i || n, "resource") || []
        } catch (n) {}
        if (!r || r.length < 1)
            return null;
        var e = r[r.length - 1]
          , o = e.connectStart
          , u = e.requestStart
          , a = e.connectEnd
          , c = e.responseStart;
        return {
            dns: un(e.domainLookupEnd - e.domainLookupStart),
            transferSize: un(e.transferSize),
            encodedSize: un(e.encodedBodySize),
            duration: un(e.duration),
            connect: un(a - o > 0 && u - o),
            request: un(c - u),
            response: un(e.responseEnd - c),
            ssl: un(e.secureConnectionStart && a - e.secureConnectionStart),
            number: r.length,
            protocol: e.nextHopProtocol || "",
            startTime: un(e.startTime)
        }
    }
    function fn(n) {
        var t = 0;
        try {
            return cn(n).getEntries().forEach((function(n) {
                n.fetchStart > t && (t = n.fetchStart)
            }
            )),
            t
        } catch (n) {}
    }
    function dn(n, t) {
        var r, i, e, o = 0, u = 0, a = !1, c = 0;
        function s() {
            r && (r.disconnect(),
            r = null),
            o && clearTimeout(o),
            u && clearInterval(u),
            !a && c && (a = fn() > c),
            i && (e = e || sn(n),
            i({
                entry: e,
                hasNewer: a,
                supported: !(!("performance"in an) || !an.performance.getEntriesByName)
            }))
        }
        function f(t) {
            a = a || c && fn(t) > c,
            (e = sn(n, t)) && s()
        }
        try {
            (r = new an.PerformanceObserver(f)).observe({
                type: "resource"
            })
        } catch (n) {}
        return u = setInterval(f, 100),
        {
            promise: new Promise((function(n) {
                i = n,
                f() && e || (c = an.performance.now(),
                t && (o = setTimeout(s, t)))
            }
            )),
            cancel: s
        }
    }
    try {
        an.performance.addEventListener("resourcetimingbufferfull", (function() {
            "setResourceTimingBufferSize"in an.performance && an.performance.setResourceTimingBufferSize(an.performance.getEntries().length + 100)
        }
        ))
    } catch (n) {}
    var hn = "preview"
      , vn = "admiral"
      , ln = [hn, "engage"].join("-")
      , wn = (["force", "login"].join("-"),
    [hn, "cmp"].join("-"))
      , mn = ["live", hn].join("-")
      , pn = [vn, hn].join("-")
      , gn = [vn, "options"].join("-")
      , bn = [vn, "all", "groups"].join("-");
    function yn() {
        return !!T(ln)
    }
    function kn() {
        return !!T(wn)
    }
    function Pn() {
        return I() && T(mn)
    }
    function $n() {
        return T(pn)
    }
    function _n(n) {
        var t = []
          , r = []
          , i = !1;
        return (n || "").split(",").forEach((function(n) {
            var e = n.split("~");
            t.push(e[0]),
            e[1] && (i = !0,
            r.push(e[1]))
        }
        )),
        {
            Tn: t,
            An: r,
            In: i
        }
    }
    var Cn = T(gn) || u.A;
    function Sn(n) {
        return Cn ? n.indexOf("?") > -1 ? n + "&o=" + encodeURIComponent(Cn) : n + "?o=" + encodeURIComponent(Cn) : n
    }
    var En = window
      , Dn = u.P;
    function Tn(n, t) {
        var r = t[0];
        function i() {
            return n.a[r].apply(n.a, t.slice(1))
        }
        try {
            return "triggerEvent" === r ? Promise.resolve().then(i) : i()
        } catch (n) {}
    }
    function An() {
        try {
            return En.admiral || En[Dn]
        } catch (n) {}
        return En[Dn]
    }
    var In = function(n, t) {
        var r = Array.prototype.slice.call(t);
        n && r.unshift(n);
        var i = An();
        if (i && i.loaded)
            return Tn(i, r);
        i = f(i) && i || function() {
            (En.admiral.q = En.admiral.q || []).push(arguments)
        }
        ;
        try {
            En[Dn] = En.admiral = i
        } catch (n) {
            En[Dn] = i
        }
        i("ready", (function() {
            return Tn(An(), r)
        }
        ))
    };
    function Mn() {
        return In("after", arguments)
    }
    function On() {
        return In("triggerEvent", arguments)
    }
    var Rn = function() {
        return In("", arguments)
    };
    function Nn(n) {
        return (n.protocol || "http:") + "//" + (n.host || n.hostname || "").replace(/:(443|80)$/, "") + (n.pathname || "/")
    }
    function jn(n, t) {
        for (var r = 0; r < t.length; r++) {
            var i = t[r];
            i.enumerable = i.enumerable || !1,
            i.configurable = !0,
            "value"in i && (i.writable = !0),
            Object.defineProperty(n, i.key, i)
        }
    }
    function xn(n, t, r) {
        return t && jn(n.prototype, t),
        r && jn(n, r),
        Object.defineProperty(n, "prototype", {
            writable: !1
        }),
        n
    }
    function Ln(n, t) {
        if (!(n instanceof t))
            throw new TypeError("Cannot call a class as a function")
    }
    var Bn, Un = (function() {
        function n(t) {
            for (var r in Ln(this, n),
            t) {
                var i = t[r];
                f(i) || (this[r] = i)
            }
            this.fullURL = t + ""
        }
        return n.prototype.toString = function() {
            return this.fullURL
        }
        ,
        xn(n)
    }
    )(), Hn = (function() {
        function n() {
            Ln(this, n),
            this.Mn = "",
            this.On = 0
        }
        var t = n.prototype;
        return t.start = function(n, t) {
            var r = this
              , i = []
              , e = !1;
            function o() {
                e = !1,
                u()
            }
            function u() {
                if (!e) {
                    var t = i.shift();
                    t && (e = !0,
                    setTimeout((function() {
                        f(n) ? n(t).then(o, o) : o()
                    }
                    ), 10))
                }
            }
            this.On && window.clearInterval(this.On);
            var a = new Un(window.location);
            this.Mn = Nn(a),
            i.push(a),
            this.On = window.setInterval((function() {
                var n = new Un(window.location)
                  , t = Nn(n);
                r.Mn !== t && (r.Mn = t,
                (function(n, t) {
                    for (var r = 0; r < n.length; r++)
                        if (Nn(n[r]) === t)
                            return !0;
                    return !1
                }
                )(i, t) || i.push(n),
                u())
            }
            ), t || 1e3),
            u()
        }
        ,
        t.stop = function() {
            clearInterval(this.On)
        }
        ,
        xn(n)
    }
    )();
    function qn(n, t, r) {
        return t in n ? Object.defineProperty(n, t, {
            value: r,
            enumerable: !0,
            configurable: !0,
            writable: !0
        }) : n[t] = r,
        n
    }
    var Fn = "v4ac1eiZr0"
      , Wn = "_aQS02Mzg3RDEwMjU5NjBGOUQ0REY5Q0YwOTEtMjcz"
      , Vn = "gpte"
      , zn = "engageRendered"
      , Gn = "lastGAMKVPs"
      , Jn = (qn(Bn = {
        userEngaged: 0
    }, zn, 4),
    qn(Bn, "cmpConsentID", 7),
    qn(Bn, "whitelistAdded", 16),
    qn(Bn, "hasClosedStickyWelcomeTooltip", 18),
    qn(Bn, "renderedStickyOnce", 19),
    qn(Bn, "usnatCMPConsentID", 20),
    Bn)
      , Xn = qn({}, Gn, "lgk");
    function Kn(n, t) {
        try {
            localStorage.setItem(n, t)
        } catch (n) {}
    }
    function Qn(n) {
        try {
            return localStorage.getItem(n)
        } catch (n) {
            return null
        }
    }
    function Zn(n, t) {
        return (n.lgk || []).filter((function(n) {
            return (n && n[0] && n[2] === Vn) == !t
        }
        ))
    }
    var Yn = function(_name, n) {
        n.push([_name + "-engaged", "true" || _name, Vn])
    };
    function nt() {
        var n, t = (Qn(Fn) || "").split(",");
        try {
            n = JSON.parse(Qn(Wn) || "{}") || {}
        } catch (t) {
            n = {}
        }
        return [t, n]
    }
    var tt = (function() {
        function n() {
            !(function(n, t) {
                if (!(n instanceof t))
                    throw new TypeError("Cannot call a class as a function")
            }
            )(this, n)
        }
        return n.set = function(n) {
            var t, r, i = nt(), e = i[0], o = i[1];
            for (var a in n) {
                var c = n[a];
                if (a in Jn && (t = !0,
                e[Jn[a]] = c,
                a === zn)) {
                    var s = Zn(o, !0);
                    c && Yn(u.u, s),
                    r = !0,
                    o.lgk = s
                }
                a in Xn && (a === Gn && (c = c || [],
                Zn(o)[0] && Yn(u.u, c)),
                r = !0,
                o[Xn[a]] = c)
            }
            if (t && Kn(Fn, e.join(",")),
            r)
                try {
                    Kn(Wn, JSON.stringify(o))
                } catch (n) {}
        }
        ,
        n.get = function() {
            var n, t = nt(), r = t[0], i = t[1], e = {
                userEngaged: 1,
                engageRendered: 1,
                renderGatedAsHard: 1,
                whitelistAdded: 1
            }, o = {};
            for (var u in Jn)
                Jn.hasOwnProperty(u) && (n = r[Jn[u]],
                e[u] && (n = parseInt(n, 10) || 0),
                o[u] = n);
            for (var a in Xn)
                o[a] = i[Xn[a]];
            return o
        }
        ,
        t = n,
        Object.defineProperty(t, "prototype", {
            writable: !1
        }),
        t;
        var t
    }
    )();
    var rt = function() {}
      , it = "2.46.1";
    function et(n) {
        this.ok = !0,
        this.d = n
    }
    function ot(n) {
        return ("css" !== n || f(window.getComputedStyle)) && n || "post"
    }
    et.prototype.json = function() {
        return this.d
    }
    ;
    var ut = ot(c.cn)
      , at = ot(c.sn);
    function ct(n, t, r, i) {
        return t && (n.sid = t),
        r && (n.aid = r),
        i && (n.ld = i),
        n
    }
    function st(n, t) {
        var r = t.sessions;
        return ct(n, r.sessionID, r.realmSessionID, t.localData)
    }
    function ft(n) {
        return !!n.aid
    }
    function dt(n, t) {
        return t in n && d(n[t]) && "" !== n[t]
    }
    function ht(n, t) {
        return t in n && h(n[t]) && 0 != n[t]
    }
    function vt(n, t) {
        return t in n && !0 === n[t]
    }
    function lt(n) {
        return Array.isArray(n)
    }
    function wt(n, t) {
        return t in n && lt(n[t]) && n[t].length > 0
    }
    function mt(n, t) {
        return Object.prototype.hasOwnProperty.call(n, t)
    }
    var pt = 100 * Math.random() < c.pn;
    function gt() {
        return window.location
    }
    var _callback, bt = (function() {
        function n(t, r) {
            var i = this;
            !(function(n, t) {
                if (!(n instanceof t))
                    throw new TypeError("Cannot call a class as a function")
            }
            )(this, n),
            this.propertyID = t,
            this.browser = r,
            this.Rn = [],
            this.Nn = [],
            this.jn = Promise.resolve(),
            this.xn = [],
            this.Ln = null,
            this.Bn = null,
            this.Un = null,
            this.Hn = null,
            this.qn = "",
            this.Fn = "",
            this.Wn = !1,
            this.Vn = {},
            this.zn = "",
            this.Gn = 0,
            this.Jn = [],
            this.Xn = [],
            this.Kn = void 0,
            this.formatters = {
                pageview: this.Qn.bind(this),
                candidateSeen: this.Zn.bind(this),
                candidateAction: this.Yn.bind(this)
            },
            this.nt = {},
            this.tt = {},
            this.rt = {},
            this.it = null;
            try {
                this.et()
            } catch (n) {
                n instanceof DOMException || this.setError(n, "delayed")
            }
            var e = "transact.subscribe";
            Mn(e, this.ot.bind(this)),
            Mn("call." + e, this.ot.bind(this)),
            Mn("view.rendered", this.ut.bind(this)),
            Mn("view.action", this.ct.bind(this)),
            Mn("user.login", (function(n) {
                return i.saveSession(n, !0, !0)
            }
            )),
            pt && setInterval((function() {
                return i.recordMetrics()
            }
            ), 5e3)
        }
        var t, r = n.prototype;
        return r.st = function(n) {
            var t = [["blocked", "bl", vt], ["hasAdBlocker", "abl", vt], ["disabledAdBlocker", "dbl", vt], ["blockerScore", "bls", ht], ["disabledScore", "dis", ht], ["flags", "flags", ht], ["disabledFlags", "dflags", ht], ["hacksFlags", "df", ht], ["engageRendered", "er", ht], ["duration", "dt", ht]]
              , r = {};
            return 1 === n.blockerType && (r.abls = ["el"]),
            t.reduce((function(t, r) {
                return r[2](n, r[0]) && (t[r[1]] = n[r[0]]),
                t
            }
            ), r)
        }
        ,
        r.setCMPCommonData = function(n) {
            var t = "cmpConsentID";
            dt(n, t) && this.Xn.push({
                type: "cmpConsent",
                id: n.cmpConsentID
            }, {
                type: "cmpConsent[tcf]",
                id: n.cmpConsentID
            });
            var r = {};
            for (var i in n)
                mt(n, i) && i !== t && (r[i] = n[i]);
            this.Bn = r
        }
        ,
        r.setCCPACommonData = function(n) {
            this.Un = n || {}
        }
        ,
        r.setUSNatCommonData = function(n) {
            var t = "usnatCMPConsentID";
            dt(n, t) && this.Xn.push({
                type: "cmpConsent",
                id: n.usnatCMPConsentID
            }, {
                type: "cmpConsent[usnat]",
                id: n.usnatCMPConsentID
            });
            var r = {};
            for (var i in n)
                mt(n, i) && i !== t && (r[i] = n[i]);
            this.Hn = r
        }
        ,
        r.setIsBlocking = function(n) {
            this.Wn = !!n
        }
        ,
        r.addLoadPerfData = function(n, t, r, i) {
            if (i) {
                if (this.nt[i])
                    return;
                this.nt[i] = !0
            }
            var e = {
                t: "l",
                n: n
            };
            function o(n, t) {
                r[t] && r[t] > 0 && (e[n] = r[t])
            }
            t && (e.s = ~~t),
            this.Wn && (e.b = 1),
            r && r.duration > 0 && (o("dd", "dns"),
            o("dt", "duration"),
            o("dc", "connect"),
            o("dq", "request"),
            o("ds", "response"),
            o("dl", "ssl"),
            o("es", "encodedSize"),
            r.protocol && (e.dp = r.protocol)),
            this.Nn.push(e)
        }
        ,
        r.addDetectorPerfData = function(n, t, r, i, e, o) {
            var u = {
                t: "d"
            };
            function a(n, t) {
                t > 0 && (u[n] = t)
            }
            this.Wn && (u.b = 1),
            a("dk", n),
            a("dd", t),
            a("ds", r),
            a("dr", i),
            a("du", e),
            a("hf", o),
            this.Nn.push(u)
        }
        ,
        r.addInvestigationData = function(n, t, r) {
            for (var i = this.Jn, e = 0; e < i.length; e++)
                if (i[e] === n)
                    return;
            this.Jn.push(n);
            var o = {
                t: "i",
                if: n
            };
            t > 0 && (o.ic = t),
            lt(r) && (o.il = r.filter((function(n) {
                return h(n)
            }
            ))),
            this.Nn.push(o)
        }
        ,
        r.Qn = function(n) {
            var t = n.results
              , r = n.consentApplies
              , i = {};
            return vt(t, "hasAdmiralList") && (i.whtl = !0),
            h(r) && r > 0 && (i.cmpa = r),
            i
        }
        ,
        r.ft = function(n) {
            if (n.candidate) {
                var t = n.candidate
                  , r = t.batchID
                  , i = t.candidateID
                  , e = t.variantID
                  , u = t.groups
                  , a = t.payload;
                n = o({
                    batchID: r,
                    candidateID: i,
                    variantID: e,
                    groups: u,
                    template: (a = void 0 === a ? {} : a).name,
                    triggers: t.triggers,
                    tsUpdated: t.tsUpdated
                }, n)
            }
            for (var c = [["candidateID", "cid", dt], ["batchID", "bid", dt], ["variantID", "vid", dt], ["triggers", "trs", wt], ["groups", "cg", wt], ["whitelistAsk", "wa", vt], ["offers", "of", wt], ["template", "tp", dt], ["tsUpdated", "tsu", ht]], s = {}, f = 0; f < c.length; f++)
                c[f][2](n, c[f][0]) && (s[c[f][1]] = n[c[f][0]]);
            return s
        }
        ,
        r.Zn = function(n) {
            var t = this.ft(n);
            if (n.extras) {
                var r = t.cid;
                n = o({}, n.extras[r] || {}, n)
            }
            return dt(n, "sourceID") && (t.si = n.sourceID),
            vt(n, "noPersist") && (t.np = !0),
            t
        }
        ,
        r.Yn = function(n) {
            var t = this.ft(n);
            return dt(n, "action") && (t.act = n.action),
            dt(n, "detail") && (t.det = n.detail),
            t
        }
        ,
        r.addDataFormatter = function(n, t, r) {
            !r && this.formatters[n] || (this.formatters[n] = t)
        }
        ,
        r.addData = function(n, t, r) {
            var i = this.formatters[n];
            if (!i)
                throw new Error("no data formatter for " + n);
            var e = i(t);
            "pageview" === n && (this.Ln = o(this.Ln || {}, this.st(t.results || t))),
            this.Rn.push({
                type: n,
                body: e,
                src: r || ""
            })
        }
        ,
        r.setError = function(n, t) {
            var r = (function(n) {
                return null == n ? "" : d(n.message) ? "" + n.message : n + ""
            }
            )(n);
            if (!r)
                return this.qn = "",
                void (this.Fn = "");
            t && (r = [t, r].join(": ")),
            this.qn = r;
            var i = "";
            if (n && n.stack) {
                var e = ((n.stack || "") + "").split("\n");
                e[0].indexOf("Error: ") > -1 ? i = (e[1] || "").trim() : e[0] && (i = e[0].trim())
            }
            this.Fn = i
        }
        ,
        r.dt = function(n, t, r, i) {
            i = o({}, i || this.Ln || {}),
            r || (i = o(i, this.Un || {}, this.Hn || {}, this.Bn || {}));
            var e = n || gt()
              , u = e && e.search;
            t = t || document.referrer;
            var a = r > 0 ? "" : this.lastID("pageview")
              , c = r > 0 ? "" : this.lastID("cmpConsent[tcf]")
              , s = r > 0 ? "" : this.lastID("cmpConsent[usnat]")
              , f = Nn(e);
            if (f.length >= 9 && !I(e) && (i.uri = f),
            t && (i.rfr = "" + t),
            a && (i.pv = a),
            c && (i.ccid = c),
            s && (i.uccid = s,
            c || (i.ccid = c)),
            i.pid = this.propertyID,
            i.jsv = it,
            i.utco = -1 * (new Date).getTimezoneOffset() * 60,
            r > 0 && (i.dms = r),
            (function() {
                try {
                    return !!window.localStorage._admlValRec
                } catch (n) {
                    return !1
                }
            }
            )() && (i.vrec = !0),
            lt(this.Kn) && (i.sgs = this.Kn),
            Rn("get", "_bootstrapVersion", (function(n) {
                n && h(n) && (i.verb = n)
            }
            )),
            u) {
                var d = (0,
                S(e, !1, !1).getQueryVariablesWithMatch)((function(n) {
                    return 0 === n.indexOf("utm_") || 0 === n.indexOf("adm_")
                }
                ))
                  , v = [];
                for (var l in d)
                    mt(d, l) && v.push(l + "=" + d[l]);
                v.length > 0 && (i.usp = v.join("&"))
            }
            return this.getCookieData().then((function(n) {
                return i = st(i, n),
                new Promise((function(n) {
                    Rn("get", "analytics.ignore", (function(n, t) {
                        t ? n && (i.ign = !0) : (yn() || $n() || kn() || Pn()) && (i.ign = !0)
                    }
                    )),
                    n(i)
                }
                ))
            }
            ))
        }
        ,
        r.ht = function(n, t) {
            return "post" === t ? (this.qn && (n.err = this.qn),
            this.Fn && (n.ert = this.Fn)) : this.qn && (n.err = "1"),
            this.setError(),
            n
        }
        ,
        r.vt = function(n) {
            var t = this
              , r = this.xn;
            return new Promise((function(n) {
                1 === r.push(n) && n()
            }
            )).then((function() {
                return r.shift(),
                t.jn = t.jn.catch(rt).then(n),
                r[0] && r[0](),
                t.jn
            }
            ))
        }
        ,
        r.et = function() {
            var n, t = this, r = window.sessionStorage || {}, i = "afsvisits";
            try {
                var e = r[i];
                e && (delete r[i],
                n = JSON.parse(e).slice(-5))
            } catch (n) {}
            if (n && n.length)
                for (var o = Date.now(), u = function(r) {
                    var i = n[r][0] || 0
                      , e = n[r][1] || {}
                      , u = o - i;
                    if (u > c._n)
                        return "continue";
                    if (1 === e.t) {
                        if (!e.cs)
                            return "continue";
                        var a = {
                            hasAdBlocker: !0,
                            disabledAdBlocker: !1,
                            blocked: !0,
                            flags: 16384,
                            engageRendered: i
                        }
                          , s = [{
                            type: "pageview",
                            body: t.Qn({
                                results: a
                            })
                        }].concat(t.lt(e.cs, {}).map((function(n) {
                            return ((n.candidate || n).triggers || []).find((function(n) {
                                return n && "adblockerDisabled" === n.type
                            }
                            )) && tt.set({
                                engageRendered: i
                            }),
                            {
                                type: "candidateSeen",
                                body: t.Zn(n)
                            }
                        }
                        )));
                        t.vt((function() {
                            var n = new Un(e.p ? new URL(e.p,window.location) : gt());
                            return t.dt(n, e.r, u, t.st(a)).then((function(n) {
                                return t.wt(c.B, n, 0, null, ut, s, !1)
                            }
                            ))
                        }
                        ))
                    }
                }, a = 0; a < n.length && n[a]; a++)
                    u(a)
        }
        ,
        r.record = function(n) {
            var t = this
              , r = n || new Un(gt());
            return I(r) ? Promise.reject(new Error("invalid location")) : this.vt((function() {
                return t.dt(r).then((function(n) {
                    var r = t.Wn ? ut : at;
                    return t.wt(c.B, t.ht(n, r), 0, null, r, t.Rn.splice(0, t.Rn.length), !1)
                }
                ))
            }
            ))
        }
        ,
        r.testRecord = function(n, t) {
            var r = this;
            t = ot(t);
            var i = new Un(gt());
            return I(i) ? Promise.reject(new Error("invalid location")) : this.vt((function() {
                return r.dt(i).then((function(i) {
                    return r.wt(n, i, 0, null, t, [], !0, c.hn)
                }
                ))
            }
            ))
        }
        ,
        r.wt = function(n, t, r, i, e, o, u, a) {
            var s = this;
            if (!n)
                return Promise.reject(new Error("no submit endpoint"));
            if (!t)
                return Promise.reject(new Error("no common data"));
            a = a || c.dn;
            var f = t.dms
              , d = {
                c: t,
                b: []
            };
            if (0 === o.length && !u && !t.err)
                return Promise.resolve(i || {});
            var h = ""
              , v = !1;
            o.forEach((function(n) {
                n.src && (h ? h !== n.src && (v = !0) : h = n.src)
            }
            )),
            h && !v ? (o = o.map((function(n) {
                return delete n.src,
                n
            }
            )),
            t.ss = h) : delete t.ss;
            var l = yt(e, d, "b", o)
              , w = l.encoded
              , m = l.left;
            r++;
            var p = this.gt(a, e, n, w).then((function(n) {
                var r, i;
                if (n && n.daConvertedState) {
                    var e = tt.get().engageRendered;
                    n.daConvertedState > 0 && !e ? tt.set({
                        engageRendered: 1
                    }) : e > 0 && n.daConvertedState < 0 && tt.set({
                        engageRendered: 0
                    })
                }
                return t && t.vrec && ((function() {
                    var n = !(arguments.length > 0 && void 0 !== arguments[0]) || arguments[0];
                    try {
                        n ? window.localStorage._admlValRec = !!n : delete window.localStorage._admlValRec
                    } catch (n) {}
                }
                )(!1),
                delete t.vrec),
                f || s.bt(n, o),
                n.entries = null != (r = null == (i = n.visitorStatus) ? void 0 : i.offers) ? r : [],
                Promise.all([s.yt(n), s.saveSession(n, ft(t), !1)]).then((function() {
                    return n
                }
                ))
            }
            )).catch((function(n) {
                throw s.it || On("visitor.latest", {
                    error: {
                        error: "network error",
                        code: 0
                    }
                }),
                s.setError(n, "record"),
                n
            }
            ));
            return p.then((function(i) {
                return m && m.length > 0 && r < 5 ? s.wt(n, s.ht(t, e), r, i, e, m, u, a) : i
            }
            ))
        }
        ,
        r.ot = function(n) {
            var t = this
              , r = n.err
              , i = n.params
              , e = n.callback
              , u = void 0 === e ? function() {}
            : e;
            if (r && this.setError(r, "onPay"),
            !c.H)
                return Promise.reject(new Error("no subscribe endpoint"));
            var a = this.vt((function() {
                return t.dt("").then((function(n) {
                    return t.gt(c.vn, "", c.H, o(n, o({}, i, {
                        metadata: nn()
                    })))
                }
                )).then((function(n) {
                    return Promise.all([t.kt(n), t.yt(n), t.saveSession(n, !0, !0)]).then((function() {
                        return n
                    }
                    ))
                }
                ))
            }
            ));
            return a.then((function(n) {
                var t, r;
                n.entries = null != (t = null == (r = n.visitorStatus) ? void 0 : r.offers) ? t : [],
                en(n.entries).then((function() {
                    On("transact.subscribed", {
                        offers: n.entries,
                        benefits: rn(n.entries)
                    }),
                    u(n)
                }
                ))
            }
            )),
            a.catch((function(n) {
                throw t.setError(n, "subscribe"),
                t.record(),
                u(void 0, n),
                new Error("Unknown error occurred. Please try again.")
            }
            )),
            a
        }
        ,
        r.lt = function(n) {
            var t = n.candidates
              , r = void 0 === t ? [] : t
              , i = n.extras
              , e = void 0 === i ? {} : i
              , u = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : {}
              , a = [];
            return r.forEach((function(n) {
                var t = n.candidateID;
                u[t] || (u[t] = !0,
                a.push(o({
                    candidate: n
                }, e[t])))
            }
            )),
            a
        }
        ,
        r.ut = function(n) {
            var t = this
              , r = n.candidates
              , i = void 0 === r ? [] : r
              , e = n.extras
              , o = void 0 === e ? {} : e
              , u = n.callback
              , a = void 0 === u ? function() {}
            : u
              , c = n.src
              , s = void 0 === c ? "" : c;
            this.lt({
                candidates: i,
                extras: o
            }, this.tt).forEach((function(n) {
                t.addData("candidateSeen", n, s)
            }
            )),
            setTimeout((function() {
                t.record().then((function() {
                    return a({})
                }
                ), (function(n) {
                    return a(void 0, n)
                }
                ))
            }
            ), 100)
        }
        ,
        r.ct = function(n) {
            var t = this
              , r = n.candidates
              , i = void 0 === r ? [] : r
              , e = n.extras
              , u = void 0 === e ? {} : e
              , a = n.action
              , c = void 0 === a ? "" : a
              , s = n.detail
              , f = void 0 === s ? "" : s
              , d = n.callback
              , h = void 0 === d ? function() {}
            : d
              , v = n.src
              , l = void 0 === v ? "" : v;
            i.forEach((function(n) {
                var r = n.candidateID;
                t.rt[r + c] || (t.rt[r + c] = !0,
                t.addData("candidateAction", o({
                    candidate: n,
                    action: c,
                    detail: f
                }, u[r]), l))
            }
            )),
            this.record().then((function() {
                return h({})
            }
            ), (function(n) {
                return h(void 0, n)
            }
            ))
        }
        ,
        r.performAttributeUpdates = function(n) {
            var t = this
              , r = this.vt((function() {
                return t.getCookieData().then((function(r) {
                    var i = st({
                        pid: t.propertyID,
                        as: n
                    }, r);
                    return t.gt(c.mn, "", c.yn, i).then((function(n) {
                        return Promise.all([t.kt(n), t.yt(n), t.saveSession(n, ft(i), !1)]).then((function() {
                            return n
                        }
                        ))
                    }
                    ))
                }
                ))
            }
            ));
            return r.catch((function(n) {
                throw t.setError(n, "perform"),
                t.record(),
                new Error("Unknown error occurred. Please try again.")
            }
            )),
            r
        }
        ,
        r.recordMetrics = function(n) {
            var t = c.G;
            if (!t)
                return Promise.resolve({});
            if (I() || "localhost" === gt().hostname)
                return Promise.resolve({});
            if (n || pt) {
                var r = Rn("flushUsed");
                if (r && r.length > 0 && this.Nn.push({
                    t: "q",
                    n: r.join("\n")
                }),
                !this.Nn || this.Nn.length < 1)
                    return Promise.resolve({});
                var i = {
                    v: it,
                    pid: this.propertyID
                }
                  , e = ot(c.gn)
                  , o = yt(e, i, "m", this.Nn)
                  , u = o.encoded
                  , a = o.left;
                return this.Nn = a || [],
                this.gt("", e, t, u)
            }
        }
        ,
        r.kt = function(n) {
            if (n && d(n.localData))
                return this.zn = n.localData,
                (function(n) {
                    if (!d(n))
                        return Promise.reject("bad data");
                    var t = on(F, n);
                    return $(x, t, J).catch((function(t) {
                        if (W) {
                            var r = on(q, n);
                            return $(x, r, X)
                        }
                        throw t
                    }
                    ))
                }
                )(this.zn)
        }
        ,
        r.yt = function(n) {
            if (n && n.visitorStatus) {
                var t = o(this.it || {}, n.visitorStatus);
                t.canStoreData = t.registered || c.Dn >= 0,
                this.it = t;
                var r = o({}, t);
                return delete r.visitorID,
                On("visitor.latest", {
                    status: r,
                    _private: function() {
                        return {
                            status: t
                        }
                    }
                }).catch((function(n) {}
                ))
            }
        }
        ,
        r.fetchCandidates = function(n) {
            var t = this
              , r = n.results
              , i = void 0 === r ? {} : r
              , e = n.cmpStatus
              , u = void 0 === e ? {} : e
              , a = n.ccpaStatus
              , s = void 0 === a ? {} : a
              , f = n.customParams
              , v = void 0 === f ? null : f
              , l = n.overrides
              , w = void 0 === l ? {} : l
              , m = n.candidateIDs
              , p = n.variantIDs
              , g = n.shownCandidates
              , b = {
                pid: this.propertyID,
                pv: this.lastID("pageview"),
                tp: {},
                jsv: it,
                c: this.st(i)
            };
            Rn("get", "analytics.ignore", (function(n, t) {
                t ? n && (b.c.ign = !0) : (yn() || $n() || kn() || Pn()) && (b.c.ign = !0)
            }
            )),
            v && Object.keys(v).length > 0 && (b.ctp = v),
            b.tp.np = "Notification"in window ? Notification.permission : "default",
            i.blocked && (b.tp.adb = !0,
            b.tp.adt = i.blockerType),
            i.recentlyWhitelisted && (b.tp.adrw = !0);
            var y = gt()
              , k = y && (y.hostname || y.host);
            k && (b.tp.ph = k);
            var P = (function(n) {
                return "/" !== (n = n || "/").charAt(0) && (n = "/" + n),
                "/" === n.charAt(n.length - 1) && n.length > 1 && (n = n.substr(0, n.length - 1)),
                n
            }
            )(y.pathname);
            if (P && (b.tp.pp = P),
            document.referrer && (b.tp.pr = document.referrer),
            !u.failed) {
                var $ = u.status
                  , _ = u.tcfVersion;
                h($) && !isNaN($) && (b.tp.cs = $),
                h(_) && (b.tp.cv = _)
            }
            s && !s.failed && d(s.state) && (b.tp.cps = s.state),
            window.__cmpGdprAppliesGlobally && (b.tp.cag = !0);
            var C = $n();
            if (C) {
                var S = _n(C)
                  , E = S.Tn[0];
                1 === S.Tn.length && E && E.indexOf(":") > -1 ? b.cg = E : C.indexOf(",") > -1 ? b.cids = S.Tn : b.cid = E,
                S.In && (b.cvids = S.An)
            } else
                kn() && (b.tp.pvc = !0),
                yn() && (b.tp.pve = !0);
            return lt(m) && m.length > 0 && (b.cids = m),
            lt(p) && p.length > 0 && (b.cvids = p),
            lt(g) && g.length > 0 && (b.sc = g),
            vt(i, "hasAA") && (b.tp.aao = i.hasAA),
            this.getCookieData().then((function(n) {
                var t = n.cookies;
                (function(n, t) {
                    (c.$n || []).forEach((function(r) {
                        var i = r.indexOf(".");
                        if (i > -1) {
                            var e = r.substring(0, i)
                              , o = r.substring(i + 1);
                            if (t[e]) {
                                var u = t[e](o);
                                (d(u) || lt(u)) && (n[e] = n[e] || {},
                                n[e][o] = u)
                            }
                        }
                    }
                    ))
                }
                )(b = st(b, n), {
                    qp: T,
                    hp: D,
                    ck: function(n) {
                        var r = (t || []).filter((function(t) {
                            return t && t.name === n
                        }
                        )).map((function(n) {
                            return n.value
                        }
                        ));
                        return r.length > 0 && r
                    }
                }),
                w && (b.tp = o(b.tp, w))
            }
            )).then((function() {
                return t.gt(c.ln, "", Sn(c.bn), b)
            }
            )).then((function(n) {
                return Promise.all([t.kt(n), t.Pt(n), t.yt(n), t.saveSession(n, ft(b), !1)]).then((function() {
                    return {
                        candidates: n.candidate ? [n.candidate] : n.candidates || []
                    }
                }
                ))
            }
            ))
        }
        ,
        r.bt = function(n, t) {
            var r = "cmpConsent"
              , i = "cmpImpression";
            if (n && n.ids) {
                for (var e = [], o = 0; o < n.ids.length; o++)
                    n.ids[o] && n.ids[o].id && (n.ids[o].type !== r && n.ids[o].type !== i || e.push(n.ids[o].id),
                    this.Xn.push(n.ids[o]));
                for (var u = -1, a = 0; a < t.length; a++) {
                    var c = t[a] || {};
                    if ((c.type === r || c.type === i) && c.body) {
                        u++;
                        var s = c.body.cct;
                        if (e[u] && c.type === r)
                            switch (s) {
                            case "tcf":
                                tt.set({
                                    cmpConsentID: e[u]
                                });
                                break;
                            case "usnat":
                                tt.set({
                                    usnatCMPConsentID: e[u]
                                })
                            }
                        this.Xn.push({
                            type: "".concat(t[a].type, "[").concat(s, "]"),
                            id: e[u]
                        })
                    }
                }
            }
            return n
        }
        ,
        r.lastID = function(n) {
            for (var t = this.Xn.length - 1; t >= 0; t--)
                if (this.Xn[t].type == n)
                    return this.Xn[t].id;
            return ""
        }
        ,
        r.Pt = function(n) {
            if (n) {
                this.Kn = lt(n.segments) ? n.segments : void 0;
                var t = n.gamKVPs;
                if (t) {
                    var r = [];
                    for (var i in t)
                        mt(t, i) && i && r.push([i, lt(t[i]) && 1 === t[i].length ? t[i][0] : t[i]]);
                    tt.set({
                        lastGAMKVPs: r || []
                    })
                }
            }
            return n
        }
        ,
        r.saveSession = function(n, t, r) {
            var i = this
              , e = Promise.resolve();
            if (!n)
                return e;
            if (n.sessionID && (this.Vn.sessionID = n.sessionID,
            this.Gn = 0 | n.now || this.Gn || 0,
            e = e.then((function() {
                return t = n.sessionID,
                r = i.Gn,
                Q(t, r, F, L).catch((function(n) {
                    if (W)
                        return Q(t, r, q, L);
                    throw n
                }
                )).then((function() {
                    z[R] && ($(R, null, {
                        domain: q
                    }),
                    z[R] = !1)
                }
                ));
                var t, r
            }
            ))),
            n.realmSessionID) {
                var o = "";
                t ? (o = this.Vn.realmSessionID,
                e = e.then((function() {
                    return i.Vn.realmSessionID = n.realmSessionID,
                    Y(n.realmSessionID)
                }
                )),
                this.zn && o && r && this.Vn.sessionID && (e = e.then((function() {
                    return i.gt(c.mn, "", c.yn, ct({
                        pid: i.propertyID,
                        anid: o,
                        md: !0
                    }, i.Vn.sessionID, i.Vn.realmSessionID, i.zn))
                }
                )).then((function(n) {
                    return Promise.all([i.kt(n), i.yt(n), i.saveSession(n, !1, !1)]).then((function() {
                        return n
                    }
                    ))
                }
                )))) : e = e.then((function() {
                    return i.getCookieData().then((function(t) {
                        if (!t.sessions.realmSessionID)
                            return i.Vn.realmSessionID = n.realmSessionID,
                            Y(n.realmSessionID)
                    }
                    ))
                }
                ))
            } else
                n.clearRealmSessionID && (this.Vn.realmSessionID = "",
                e = e.then((function() {
                    return Y("")
                }
                )));
            return e.catch((function(n) {
                i.setError(n, "cookies")
            }
            ))
        }
        ,
        r.getCookieData = function() {
            var n = this;
            return $().then((function(n) {
                var t = (O = (function(n) {
                    for (var t = {}, r = {}, i = {}, e = 0; e < n.length; e++) {
                        var _name = n[e].name;
                        if (_name === R || _name === N || _name === x) {
                            var o = n[e].value.match(U);
                            if (!o || !o[2] || ~~o[1] < t[_name])
                                continue;
                            t[_name] = ~~o[1],
                            i[_name] = n[e].domain || "",
                            r[_name] = o[2]
                        } else
                            _name === j && (V = !0)
                    }
                    if (!G) {
                        for (var u in r)
                            i[u] && t[u] < K(F) && (F = M(i[u]),
                            W = !0),
                            W && t[u] > K(F) && (z[u] = !0);
                        G = !0
                    }
                    return r
                }
                )(n))[R];
                return {
                    sessions: {
                        sessionID: (t ? t.match(B) : "")[2] || "",
                        realmSessionID: O[N] || ""
                    },
                    localData: O[x] || "",
                    cookies: n
                }
            }
            )).catch((function() {
                return {
                    sessions: n.Vn,
                    cookies: {},
                    localData: n.zn
                }
            }
            ))
        }
        ,
        r.gt = function(t, r, i, e) {
            var o = this
              , u = i
              , a = r ? ot(r) : this.Wn ? ut : at
              , c = d(e) ? e : yt(a, e).encoded;
            return new Promise((function(r, i) {
                var e;
                switch ("//" === u.substr(0, 2) && (u = (gt().protocol || "https:") + u),
                a) {
                case "ping":
                    e = new Promise((function(n, t) {
                        navigator.sendBeacon(u, c) ? n(new et({})) : t(new Error("failed to queue beacon"))
                    }
                    ));
                    break;
                case "post":
                    e = (function(n, t) {
                        if (f(window.fetch))
                            return window.fetch.call(this, n, t);
                        var r = t || {};
                        return new Promise((function(t, i) {
                            var e = new XMLHttpRequest;
                            e.addEventListener("load", (function() {
                                if (0 !== e.status) {
                                    var n = e.status || 200
                                      , r = {
                                        status: n,
                                        ok: 200 == n,
                                        json: function() {
                                            return new Promise((function(n) {
                                                n(JSON.parse(e.responseText))
                                            }
                                            ))
                                        }
                                    };
                                    t(r)
                                } else
                                    i(new Error("status is 0"))
                            }
                            )),
                            e.addEventListener("error", i),
                            e.open(r.method || "GET", n, !0),
                            e.send(r.body)
                        }
                        ))
                    }
                    )(u, {
                        method: "POST",
                        body: c
                    });
                    break;
                default:
                    e = n.handlers[a]((function(n) {
                        u = n
                    }
                    ), u, c, n.timeout, (function() {}
                    ), sn)
                }
                e.then((function(n) {
                    if (n.ok)
                        return n;
                    var t = new Error("Request non-200 status");
                    return n.json().then((function(n) {
                        throw t.code = n.code,
                        t
                    }
                    )).catch((function() {
                        throw t
                    }
                    ))
                }
                ), (function(n) {
                    throw n
                }
                )).then((function(n) {
                    return n.json()
                }
                )).then((function(n) {
                    r(n),
                    t && o.addLoadPerfData(t, 1, sn(u))
                }
                )).catch(i)
            }
            )).catch((function(r) {
                if (t) {
                    var i = sn(u)
                      , e = 0;
                    r === n.timeoutError && (e = 2),
                    o.addLoadPerfData(t, e, i)
                }
                throw r
            }
            ))
        }
        ,
        t = n,
        Object.defineProperty(t, "prototype", {
            writable: !1
        }),
        t
    }
    )();
    function yt(n, t, r, i) {
        return bt.$t(n, t, r, i, Math.random() > c.un)
    }
    bt.timeout = c.kn,
    bt.timeoutError = new Error("Timed out waiting for response"),
    bt.handlers = {},
    bt.bodyFmts = {},
    bt.$t = function(n, t, r, i, e) {
        return bt.bodyFmts[n] ? bt.bodyFmts[n](t, r, i, e) : (r && i && (t[r] = i),
        {
            encoded: JSON.stringify(t),
            left: []
        })
    }
    ,
    _callback = {},
    new (function() {
        _callback.lc = !!0
    }
    ),
    _callback.lc && _callback.c(bt),
    new (function() {
        _callback.lj = !!0
    }
    ),
    _callback.lj && _callback.j(bt);
    var kt = /^([a-zA-Z]+)/
      , Pt = "[a-zA-Z0-9_-]+"
      , $t = new RegExp("([#.])(" + Pt + ")|\\[(" + Pt + ')(?:=("[^"]+"|[^\\]]+))?\\]',"g");
    function _t(n, t) {
        var r, i = "div", e = d(t) && t.match(kt);
        e && (i = e[1] || i,
        t = t.substr(e[1].length));
        try {
            "undefined" != typeof Document && (r = Document.prototype.createElement.call(n, i))
        } catch (n) {}
        if (r || (r = n.createElement(i)),
        !r)
            throw new Error("error creating element: " + i);
        var o = [];
        for ($t.lastIndex = 0; null !== (e = $t.exec(t)); )
            "." === e[1] && e[2] ? o.push(e[2]) : "#" === e[1] && e[2] ? r.id = e[2] : e[3] && r.setAttribute(e[3], e[4] || "");
        return o.length > 0 && (r.className = o.join(" ")),
        r
    }
    function Ct(n, t, r) {
        var i = document
          , e = "script";
        return new Promise((function(o, u) {
            if (n) {
                var a = _t(i, e)
                  , c = new Date;
                a.async = 1,
                t && (a.crossOrigin = "anonymous"),
                a.type = "text/javascript",
                a.onreadystatechange = function() {
                    "loaded" === this.readyState && o(a)
                }
                ,
                a.onload = function() {
                    return o(a)
                }
                ,
                a.onerror = function(t) {
                    var r = new Date;
                    u('script failed: "' + n + '" - ' + Math.round(r - c) + "ms: " + t),
                    a.parentNode && a.parentNode.removeChild(a)
                }
                ,
                a.src = n,
                (r = r || i.getElementsByTagName(e)[0]) && r.parentNode ? r.parentNode.insertBefore(a, r) : (i.head || i.getElementsByTagName("head")[0] || i.body).appendChild(a)
            } else
                u("missing src")
        }
        ))
    }
    function St(n, t) {
        return new Promise((function(r, i) {
            var e;
            e = setTimeout((function() {
                i("timedout")
            }
            ), t),
            n.then((function(n) {
                e && clearTimeout(e),
                r(n)
            }
            )).catch(i)
        }
        ))
    }
    function Et() {
        var n = window
          , t = Array.prototype.slice.call(arguments);
        if (f(n.console.log))
            return n.console.log.apply(n.console, t)
    }
    var Dt = "r"
      , Tt = function(n) {
        return new Error('Admiral targeting method "' + n + '" called after candidate call')
    }
      , At = (function() {
        function n() {
            !(function(n, t) {
                if (!(n instanceof t))
                    throw new TypeError("Cannot call a class as a function")
            }
            )(this, n),
            this._t = {},
            this.Ct = !1,
            this.state = "i"
        }
        var t, r = n.prototype;
        return r.set = function(n, t) {
            var r = arguments.length > 2 && void 0 !== arguments[2] ? arguments[2] : function() {}
            ;
            if (this.state === Dt)
                throw Tt("set");
            void 0 === t ? delete this._t[n] : this._t[n] = t,
            r(t)
        }
        ,
        r.pause = function(n) {
            var t = this;
            if (this.state === Dt)
                throw Tt("pause");
            this.state = "p",
            this.Ct && (clearTimeout(this.Ct),
            this.Ct = null),
            n && (this.Ct = setTimeout((function() {
                t.ready()
            }
            ), n))
        }
        ,
        r.onReady = function(n) {
            "i" === this.state && this.ready(),
            Mn("targeting.ready", (function(t) {
                return n(t)
            }
            ))
        }
        ,
        r.ready = function() {
            this.state !== Dt && (this.state = Dt,
            On("targeting.ready", this._t)),
            this.Ct && (clearTimeout(this.Ct),
            this.Ct = null)
        }
        ,
        r.force = function(n) {
            On("call.targeting.render", n = o({
                force: !0
            }, n || {}))
        }
        ,
        r.reset = function() {
            this._t = {},
            this.Ct = !1,
            this.state = "i"
        }
        ,
        t = n,
        Object.defineProperty(t, "prototype", {
            writable: !1
        }),
        t
    }
    )()
      , It = At;
    var Mt = ["after", "addEventListener", "get", "once"]
      , Ot = ["getOrSet"]
      , Rt = Mt.concat(Ot, ["removeEventListener", "set", "show", "recordImpressions"])
      , Nt = new Error("no view name");
    function jt() {}
    function xt(n) {
        return Array.prototype.slice.call(n)
    }
    function Lt(n) {
        return n.slice(1)
    }
    function Bt(n) {
        var t = o({}, n);
        return delete t._private,
        t
    }
    function Ut(n) {
        return function() {
            var t = xt(arguments);
            if (!t[0] || Array.isArray(t[0]) || "object" != typeof t[0])
                return n.apply(null, t);
            var r = t.shift();
            return n.apply(null, [Bt(r)].concat(t))
        }
    }
    var Ht = (function() {
        function n(t, r) {
            !(function(n, t) {
                if (!(n instanceof t))
                    throw new TypeError("Cannot call a class as a function")
            }
            )(this, n),
            this.St = {},
            this.Et = {},
            this._t = {
                _bootstrapVersion: r || 0
            },
            this.Dt = {},
            this.Tt = {},
            this.At = {},
            this.It = new It,
            this.Mt = t
        }
        var t, r = n.prototype;
        return r.fn = function() {
            var n = this
              , t = function() {
                var t = xt(arguments)
                  , r = t[0]
                  , i = t[1]
                  , e = t[2]
                  , o = t[3]
                  , u = t.slice(4)
                  , a = !1;
                if (Rt.indexOf(r) > -1 ? (a = !0,
                d(i) && (n.At[i] = !0),
                f(e) && Mt.indexOf(r) > -1 && (e = Ut(e)),
                f(o) && Ot.indexOf(r) > -1 && (o = Ut(o))) : "targeting" === r ? (a = !0,
                d(i) && (n.At["targeting." + i] = !0)) : "visitor" === r ? (a = !0,
                d(i) && (n.At["visitor." + i] = !0)) : "ready" === r && (a = !0),
                a)
                    return n[r].apply(n, [i, e, o].concat(u));
                throw new Error("No '".concat(r, "' method"))
            };
            return t.loaded = !0,
            t.a = n,
            t
        }
        ,
        r.targeting = function(n) {
            return this.It[n].apply(this.It, Lt(xt(arguments)))
        }
        ,
        r.visitor = function(n) {
            return this.Mt[n].apply(this.Mt, Lt(xt(arguments)))
        }
        ,
        r.ready = function(n) {
            n && n()
        }
        ,
        r.show = function(n, t, r) {
            f(t) && (r = t,
            t = {});
            var i = this.Dt
              , e = i[n] || {
                name: n,
                queue: []
            };
            if (e.registered)
                e.renderFn(t, r);
            else {
                e.queue.push([t, r]),
                i[n] = e;
                var o = this.Tt[n] || {};
                o.providerFn && !o.provided && (o.provided = !0,
                o.providerFn())
            }
        }
        ,
        r.registerViewProvider = function(n, t) {
            if (!n)
                throw Nt;
            if (!t)
                throw new Error("no view providerFn");
            var r = this.Tt
              , i = r[n] || {}
              , e = this.Dt[n];
            i.provided || (e ? e.registered || t() : r[n] = {
                name: n,
                providerFn: t
            })
        }
        ,
        r.registerView = function(n, t) {
            if (!n)
                throw Nt;
            if (!t)
                throw new Error("no view renderFn");
            var r = this.Dt
              , i = r[n] || {
                name: n
            };
            if (r[n] = i,
            i.registered = !0,
            i.renderFn = t,
            i.queue)
                for (var e = 0; e < i.queue.length; e++)
                    i.renderFn.apply(null, i.queue[e]);
            delete i.queue
        }
        ,
        r.hasView = function(n, t) {
            var r = this.Dt[n];
            t(!(!r || !r.registered))
        }
        ,
        r.addEventListener = function(n, t) {
            var r = this.St;
            r[n] = r[n] || [],
            r[n].push(t)
        }
        ,
        r.removeEventListener = function(n, t) {
            for (var r = this.St[n] || [], i = 0; i < r.length; i++)
                if (r[i] === t)
                    return void r.splice(i, 1)
        }
        ,
        r.after = function(n, t) {
            var r = this.Et;
            this.addEventListener(n, t),
            r.hasOwnProperty(n) && t.apply(null, r[n])
        }
        ,
        r.once = function(n, t) {
            var r = this;
            this.after(n, (function i() {
                r.removeEventListener(n, i),
                t.apply(this, xt(arguments))
            }
            ))
        }
        ,
        r.triggerEvent = function(n) {
            for (var t = this.Et[n] = Lt(xt(arguments)), r = (this.St[n] || []).slice(0), i = [], e = 0; e < r.length; e++) {
                var o = Ft(r[e], t);
                o && f(o.then) && f(o.catch) && i.push(o.catch(jt))
            }
            return Promise.all(i)
        }
        ,
        r.clearFired = function(n) {
            delete this.Et[n]
        }
        ,
        r.set = function(n, t) {
            var r = arguments.length > 2 && void 0 !== arguments[2] ? arguments[2] : function() {}
            ;
            void 0 === t ? delete this._t[n] : this._t[n] = t,
            r(t),
            this.triggerEvent("_set." + n, t)
        }
        ,
        r.getOrSet = function(n, t) {
            var r = arguments.length > 2 && void 0 !== arguments[2] ? arguments[2] : function() {}
              , i = this._t
              , e = i.hasOwnProperty(n);
            e ? t = i[n] : this.set(n, t),
            r(t, e)
        }
        ,
        r.get = function(n, t) {
            var r = this._t;
            t(r[n], r.hasOwnProperty(n))
        }
        ,
        r.storageSet = function(n) {
            var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : function() {}
            ;
            tt.set(n),
            t(n)
        }
        ,
        r.storageGet = function(n) {
            n(tt.get())
        }
        ,
        r.recordImpressions = function() {}
        ,
        r.cas = function(n, t) {
            var r = this._t
              , i = t(r[n], r.hasOwnProperty(n));
            i && !0 === i[0] && this.set(n, i[1])
        }
        ,
        r.addSetter = function(n, t) {
            this.after("_set." + n, t)
        }
        ,
        r.flushUsed = function() {
            var n = Object.keys(this.At);
            return this.At = {},
            n
        }
        ,
        r.pm = function(n, t) {
            switch (n) {
            case 5:
                var r = this.triggerEvent("call." + t.m, t.a);
                t.cb && (r && f(r.then) ? r.then(t.cb, (function(n) {
                    return t.cb(void 0, n)
                }
                )) : t.cb(r));
                break;
            case 6:
                this.after(t.l, t.cb);
                break;
            case 7:
                this.show(t.s, t.o || {}, t.cb);
                break;
            case 8:
                var i = t.o || {};
                t.cb && (i = o({
                    callback: t.cb
                }, i)),
                this.triggerEvent("view." + t.e, i);
                break;
            case 9:
                this.get(t.g, t.cb)
            }
        }
        ,
        t = n,
        Object.defineProperty(t, "prototype", {
            writable: !1
        }),
        t
    }
    )()
      , qt = window;
    function Ft(n, t) {
        try {
            return n.apply(null, t)
        } catch (n) {}
    }
    function Wt(n, t, r) {
        var i = Array.isArray(n)
          , e = "";
        for (var o in n)
            Object.prototype.hasOwnProperty.call(n, o) && (e = r ? i ? r + "[" + o + "]" : r + "." + o : o,
            d(n[o]) || "boolean" == typeof n[o] || h(n[o]) || null === n[o] || n[o]instanceof String || n[o]instanceof Number || n[o]instanceof Boolean ? t.push([encodeURIComponent(e), encodeURIComponent(n[o] + "")].join("=")) : void 0 !== n[o] && Wt(n[o], t, e))
    }
    function Vt(n) {
        var t = [];
        return Wt(n, t, ""),
        t.join("&")
    }
    function zt(n, t, r) {
        return new Promise((function(i) {
            t.addEventListener(n, (function e(o) {
                if (t.removeEventListener(n, e, !1),
                i(o),
                r)
                    return r(o)
            }
            ), !1)
        }
        ))
    }
    var Gt = null;
    function Jt(n) {
        return (function(n) {
            var t = n.readyState;
            return ("complete" === t || "interactive" === t) && n.body
        }
        )(n) ? Promise.resolve() : (Gt || (Gt = Promise.race([zt("DOMContentLoaded", n), zt("readystatechange", n)]).then((function() {
            if (!n.body)
                return new Promise((function(t, r) {
                    var i, e = 0;
                    i = setInterval((function() {
                        return n.body ? (clearInterval(i),
                        void t()) : e++ > 50 ? (clearInterval(i),
                        void r(new Error("body falsy: " + n.readyState))) : void 0
                    }
                    ), 100)
                }
                ))
        }
        ))),
        Gt)
    }
    var Xt = function() {};
    function Kt(n) {
        var t;
        return null != (t = n.options) && t.callDelay && (n.wait = n.options.callDelay),
        n
    }
    var Qt = (function() {
        function n(t) {
            !(function(n, t) {
                if (!(n instanceof t))
                    throw new TypeError("Cannot call a class as a function")
            }
            )(this, n),
            this.Ot = (function() {
                var n, t = {}, r = {}, i = 0;
                function e(n, t) {
                    if (r[n]) {
                        try {
                            r[n](t)
                        } catch (n) {}
                        delete r[n]
                    }
                }
                return function(u) {
                    var a = this
                      , c = u.key
                      , s = u.value
                      , f = u.actionType
                      , d = u.cb
                      , h = void 0 === d ? Xt : d
                      , v = u.wait
                      , l = void 0 === v ? 10 : v
                      , w = {
                        a: f,
                        rv: s,
                        id: ++i
                    };
                    r[i] = h,
                    t[c] ? t[c].push(w) : t[c] = [w],
                    clearTimeout(n),
                    n = setTimeout((function() {
                        var n = Object.keys(r)
                          , i = o({}, t);
                        t = {},
                        a.Rt.performAttributeUpdates(i).then((function(t) {
                            n.forEach((function(n) {
                                var r, i, o = null == t || null == (r = t.errors) ? void 0 : r[n];
                                o && ((i = new Error(o.error || "unknown")).code = o.code || 1),
                                e(n, {
                                    error: i
                                })
                            }
                            ))
                        }
                        ), (function(t) {
                            n.forEach((function(n) {
                                var t = new Error("network error");
                                t.code = 0,
                                e(n, {
                                    error: t
                                })
                            }
                            ))
                        }
                        ))
                    }
                    ), l)
                }
            }
            )(),
            this.Rt = t
        }
        var t, r = n.prototype;
        return r.set = function(n, t, r, i) {
            f(r) && void 0 === i && (i = r,
            r = null),
            this.Ot(Kt({
                key: n,
                value: t,
                actionType: "set",
                options: r,
                cb: i
            }))
        }
        ,
        r.increment = function(n, t, r, i) {
            f(r) && void 0 === i && (i = r,
            r = null),
            this.Ot(Kt({
                key: n,
                value: t,
                actionType: "increment",
                options: r,
                cb: i
            }))
        }
        ,
        r.addToSet = function(n, t, r, i) {
            f(r) && void 0 === i && (i = r,
            r = null),
            this.Ot(Kt({
                key: n,
                value: t,
                actionType: "addToSet",
                options: r,
                cb: i
            }))
        }
        ,
        r.removeFromSet = function(n, t, r, i) {
            f(r) && void 0 === i && (i = r,
            r = null),
            this.Ot(Kt({
                key: n,
                value: t,
                actionType: "removeFromSet",
                options: r,
                cb: i
            }))
        }
        ,
        r.status = function(n, t) {
            f(n) && void 0 === t && (t = n,
            n = null),
            (function() {
                In("once", arguments)
            }
            )("visitor.latest", t)
        }
        ,
        t = n,
        Object.defineProperty(t, "prototype", {
            writable: !1
        }),
        t
    }
    )()
      , Zt = Qt;
    var Yt, nr = !1, tr = null, rr = null, ir = function() {}, er = (Yt = document,
    Yt.currentScript || {}).src, or = c.J && 100 * Math.random() < c.X, ur = !1, ar = !1, cr = (function() {
        function n() {
            !(function(n, t) {
                if (!(n instanceof t))
                    throw new TypeError("Cannot call a class as a function")
            }
            )(this, n),
            this.results = null,
            this.browser = new b,
            this.recorder = new bt(c.h,this.browser),
            this.recorder.addLoadPerfData(c.k, 1, sn(er), er),
            this.Nt = null,
            this.jt = null,
            this.xt = null,
            this.Lt = {},
            this.Bt = []
        }
        var t, r = n.prototype;
        return r.check = function() {
            var n = this
              , t = new p
              , r = Date.now();
            return (function(n) {
                if (rr)
                    return rr;
                var _callback = {};
                return new (function() {
                    _callback.l = !!!(function(n) {
                        var r = {};
                        function t(e) {
                            if (r[e])
                                return r[e].exports;
                            var i = r[e] = {
                                i: e,
                                l: !1,
                                exports: {}
                            };
                            return n[e].call(i.exports, i, i.exports, t),
                            i.l = !0,
                            i.exports
                        }
                        t.m = n,
                        t.c = r,
                        t.d = function(n, r, e) {
                            t.o(n, r) || Object.defineProperty(n, r, {
                                enumerable: !0,
                                get: e
                            })
                        }
                        ,
                        t.r = function(n) {
                            "undefined" != typeof Symbol && Symbol.toStringTag && Object.defineProperty(n, Symbol.toStringTag, {
                                value: "Module"
                            }),
                            Object.defineProperty(n, "__esModule", {
                                value: !0
                            })
                        }
                        ,
                        t.t = function(n, r) {
                            if (1 & r && (n = t(n)),
                            8 & r)
                                return n;
                            if (4 & r && "object" == typeof n && n && n.__esModule)
                                return n;
                            var e = Object.create(null);
                            if (t.r(e),
                            Object.defineProperty(e, "default", {
                                enumerable: !0,
                                value: n
                            }),
                            2 & r && "string" != typeof n)
                                for (var i in n)
                                    t.d(e, i, (function(r) {
                                        return n[r]
                                    }
                                    ).bind(null, i));
                            return e
                        }
                        ,
                        t.n = function(n) {
                            var r = n && n.__esModule ? function() {
                                return n.default
                            }
                            : function() {
                                return n
                            }
                            ;
                            return t.d(r, "a", r),
                            r
                        }
                        ,
                        t.o = function(n, r) {
                            return Object.prototype.hasOwnProperty.call(n, r)
                        }
                        ,
                        t.p = "",
                        t(t.s = 0)
                    }
                    )([function(n, r, t) {
                        "use strict";
                        t.r(r);
                        var e = "function";
                        function i(n) {
                            return n ? typeof window.getComputedStyle === e ? window.getComputedStyle(n, null) : void 0 !== n.currentStyle ? n.currentStyle : n.style : {}
                        }
                        function o(n, r, t, u) {
                            var c = n[u] || typeof n.getBoundingClientRect === e && n.getBoundingClientRect()[t] || 0;
                            if (r && (function(n) {
                                var r = i(n);
                                return r.display ? "inline" === r.display : 0 === n.clientHeight && 0 === n.clientWidth
                            }
                            )(n)) {
                                for (var a = 0, f = 0; f < n.children.length; f++)
                                    a = Math.max(a, o(n.children[f], !0, t, u));
                                if (a > c)
                                    return a
                            }
                            return c
                        }
                        function u(n) {
                            return null == n.parentNode || !(function(n) {
                                var r = i(n);
                                return "none" !== r.display && "hidden" !== r.visibility
                            }
                            )(n) || 0 === (function(n, r) {
                                try {
                                    return o(n, void 0, "height", "clientHeight")
                                } catch (n) {
                                    return 0
                                }
                            }
                            )(n) && 0 === (function(n, r) {
                                try {
                                    return o(n, void 0, "width", "clientWidth")
                                } catch (n) {
                                    return 0
                                }
                            }
                            )(n)
                        }
                        function c(n, r, t) {
                            var e = "";
                            for (var i in r)
                                Object.prototype.hasOwnProperty.call(r, i) && (e = t ? "important" : "",
                                n.style.setProperty ? n.style.setProperty(i, r[i], e) : n.style[i] = r[i] + (e ? "!" + e : ""));
                            return n
                        }
                        function a(n, r, t) {
                            var e = r || 1
                              , i = t || r || 1;
                            return c(n, {
                                width: i + "px",
                                height: e + "px",
                                position: "fixed",
                                left: "-" + (i - 1 + 11) + "px",
                                top: "-" + (e - 1 + 11) + "px"
                            }, !0),
                            c(n, {
                                display: "block"
                            }, !1),
                            n
                        }
                        function f(n) {
                            try {
                                var r = document.createElement("link");
                                return r.rel = "preconnect",
                                r.href = n,
                                document.head.appendChild(r),
                                function() {
                                    try {
                                        document.head.removeChild(r)
                                    } catch (n) {}
                                }
                            } catch (n) {}
                            return function() {}
                        }
                        var d = "https://tpc.googlesyndication.com"
                          , v = "1-0-37";
                        function s(n) {
                            var r = n.browser
                              , t = n.detections
                              , e = n.config
                              , i = n.domReady
                              , o = n.createElement
                              , c = (n.debugLog,
                            n.eventListen)
                              , s = n.waitPerf;
                            if (!(0,
                            n.isFunction)(window.postMessage) || r.isSafari())
                                return Promise.resolve();
                            var l = document
                              , m = f(d)
                              , k = e.u || 5e3
                              , w = !1
                              , g = !1
                              , h = !1;
                            return i(l).then((function() {
                                return new Promise((function(n) {
                                    if (l.body) {
                                        var r, t, i = o(l, "iframe"), f = Math.round(100 * (Math.random() + 5)) + "", m = 0, $ = !1, T = [d, "safeframe", v, "html/container.html"].join("/");
                                        i.setAttribute("src", T),
                                        i.id = "admrl-sf__test",
                                        i.allowTransparency = "true",
                                        i.style.border = "0",
                                        i.style.verticalAlign = "bottom",
                                        a(i, e.k[0], e.k[1]),
                                        i.scrolling = "no",
                                        i.frameBorder = 0;
                                        var y = '<script>window.parent && window.parent.postMessage("' + f + '","*")<\/script>';
                                        i.name = v + ";" + y.length + ";" + y + "{}",
                                        window.addEventListener("message", P, !1),
                                        c("load", i, L),
                                        s(T, k).promise.then((function(n) {
                                            var e = n.entry
                                              , i = n.supported;
                                            r = e,
                                            t = i,
                                            e ? L() : (b(),
                                            _(),
                                            p())
                                        }
                                        )),
                                        Node.prototype.appendChild.call(l.body, i),
                                        m = setInterval((function() {
                                            b() && p()
                                        }
                                        ), 100)
                                    } else
                                        n();
                                    function P(n) {
                                        n.data === f && n.origin === d && (h = !0,
                                        p())
                                    }
                                    function p() {
                                        clearInterval(m);
                                        try {
                                            window.removeEventListener("message", P, !1),
                                            i.parentNode.removeChild(i)
                                        } catch (n) {}
                                        n()
                                    }
                                    function b() {
                                        if (u(i))
                                            return w = !0,
                                            g = !0,
                                            !0
                                    }
                                    function _() {
                                        if (t && (!r || 0 === r.duration))
                                            return w = !0,
                                            !0
                                    }
                                    function L() {
                                        if (!$) {
                                            if ($ = !0,
                                            clearInterval(m),
                                            b())
                                                return void p();
                                            setTimeout((function() {
                                                h || (_(),
                                                b()),
                                                p()
                                            }
                                            ), e.g)
                                        }
                                    }
                                }
                                ))
                            }
                            )).then((function() {
                                h && t.disabled(8),
                                w && t.blocked(8, g),
                                m()
                            }
                            ))
                        }
                        function l(n) {
                            var r = n.detections
                              , t = n.config
                              , e = n.domReady
                              , i = n.createElement
                              , o = (n.debugLog,
                            n.recorder)
                              , f = document
                              , d = Node.prototype.appendChild;
                            function v(n, r, e) {
                                var o = a(i(n, r), t.h)
                                  , u = i(n, "span");
                                return c(u, {
                                    color: "transparent"
                                }),
                                u.innerText = t.$,
                                d.call(o, u),
                                d.call(n.body, o),
                                o
                            }
                            var s = t.T || []
                              , l = t.P
                              , m = t._ || []
                              , k = []
                              , w = [];
                            return e(f).then((function() {
                                var n = l ? v(f, l) : null;
                                n && k.push(n);
                                var r = s.map((function(n) {
                                    return v(f, n)
                                }
                                ))
                                  , t = m.map((function(n) {
                                    return v(f, n)
                                }
                                ));
                                return !(r.length < 1) && (k = k.concat(r).concat(t),
                                new Promise((function(e) {
                                    var i = 0
                                      , o = 0;
                                    function c() {
                                        var c = !1;
                                        if (++o <= 3) {
                                            if (c = !0,
                                            n && u(n))
                                                c = !1;
                                            else
                                                for (var a = 0; a < r.length; a++)
                                                    if (s[a],
                                                    !u(r[a], s[a])) {
                                                        c = !1;
                                                        break
                                                    }
                                            w = [];
                                            for (var f = 0; f < t.length; f++)
                                                m[f],
                                                u(r[f]) && w.push(f)
                                        }
                                        (c || o >= 3) && (clearInterval(i),
                                        e(c))
                                    }
                                    setTimeout(c, 0),
                                    i = setInterval(c, 100)
                                }
                                )))
                            }
                            )).then((function(n) {
                                n ? r.blocked(1, !0) : r.disabled(1),
                                m[0] && o.addInvestigationData(12, 0, w);
                                for (var t = k.splice(0, k.length), e = 0; e < t.length; e++)
                                    try {
                                        t[e].parentNode.removeChild(t[e])
                                    } catch (n) {}
                            }
                            ))
                        }
                        var m, k = (new Date).getDate() + (window.location.hostname || "z").charCodeAt(0);
                        function w(n, r, t) {
                            for (var e = 0, i = 0; i < r.length; i++)
                                e += r[i][1] - r[i][0] + 1;
                            var o = 0;
                            for (e > 0 && (o = n(e)),
                            e = 0,
                            i = 0; i < r.length && !(o < (e += r[i][1] - r[i][0] + 1)); i++)
                                ;
                            return o - (e - r[i][1] - 1) + (0 | t)
                        }
                        function g(n, r) {
                            for (var t = [], e = 0; e < r.length; e++)
                                for (var i = (r[e].v > 0 ? n(r[e].v) : 0) + r[e].l; i > 0; i--)
                                    r[e].c && r[e].c.length > 0 && t.push(w(n, r[e].c, r[e].s));
                            for (var o = 0; o < t.length; o++)
                                t[o] = String.fromCharCode(t[o]);
                            return t.join("")
                        }
                        function h(n) {
                            return r = n || k,
                            t = Math.pow(2, 31),
                            e = 1073741823,
                            function(n) {
                                return ((r = (1103515245 * r + 12345) % t) & e) / e * n | 0
                            }
                            ;
                            var r, t, e
                        }
                        function $(n) {
                            var r = n.L
                              , t = n.I
                              , e = n.R
                              , i = n.S
                              , o = n.A
                              , c = n.M
                              , f = (n.N,
                            n.U)
                              , d = n.O
                              , v = n.j
                              , s = n.D;
                            return new Promise((function(n, l) {
                                var k = []
                                  , w = []
                                  , h = !1;
                                try {
                                    !(function $(T) {
                                        if (t && t[T])
                                            (P = t[T],
                                            p = P.src,
                                            b = P.tag,
                                            _ = p.replace(/\$rs/g, (function() {
                                                return (function(n) {
                                                    return g(n, [{
                                                        c: [[97, 122]],
                                                        l: 5,
                                                        v: 2
                                                    }])
                                                }
                                                )(c)
                                            }
                                            )).replace(/\$ri/g, (function() {
                                                return (function(n) {
                                                    return g(n, [{
                                                        c: [[49, 57]],
                                                        l: 1
                                                    }, {
                                                        c: [[48, 57]],
                                                        l: 5,
                                                        v: 2
                                                    }])
                                                }
                                                )(c)
                                            }
                                            )),
                                            L = "img" === b,
                                            I = "script" === b,
                                            R = window.location.origin || "",
                                            S = r.u || 5e3,
                                            new Promise((function(n) {
                                                Date.now();
                                                var t, e, c = f(o, b), l = null, k = !1, w = !1, g = !1, h = 0, $ = 0, T = v(_, S), y = T.promise, P = T.cancel;
                                                function p() {
                                                    function r() {
                                                        P(),
                                                        clearTimeout(h),
                                                        clearInterval($),
                                                        c.removeEventListener("error", t, !1),
                                                        c.removeEventListener("load", e, !1);
                                                        try {
                                                            c.parentNode.removeChild(c)
                                                        } catch (n) {}
                                                    }
                                                    l ? l.then(r) : r(),
                                                    n({
                                                        hidden: l,
                                                        errored: w,
                                                        loaded: g,
                                                        blocked: k
                                                    })
                                                }
                                                t = function() {
                                                    w = !0,
                                                    p()
                                                }
                                                ,
                                                e = function() {
                                                    if (L && "CanvasRenderingContext2D"in window && R && R !== (function(n) {
                                                        try {
                                                            return new URL(n,window.location).origin
                                                        } catch (n) {}
                                                    }
                                                    )(_))
                                                        try {
                                                            var n = f(o, "canvas")
                                                              , t = n.getContext("2d");
                                                            return n.height = r.k[0] || 1,
                                                            n.width = r.k[1] || 1,
                                                            t.drawImage(c, 0, 0),
                                                            n.toDataURL(),
                                                            k = !0,
                                                            void p()
                                                        } catch (n) {}
                                                    if (I && null == m)
                                                        try {
                                                            var e = Array.prototype.slice.call(document.scripts || []).filter((function(n) {
                                                                return n && n.src === r.H
                                                            }
                                                            ));
                                                            if (e && e.length > 0 || d(r.H)) {
                                                                var i = "googletag";
                                                                m = !(!window[i].apiReady || s(window[i].enableServices) && !window[i].enableServices.toString().match(/{}$/))
                                                            }
                                                        } catch (n) {}
                                                    setTimeout(P, r.g),
                                                    y.then((function(n) {
                                                        var r = n.entry
                                                          , t = n.supported;
                                                        r ? g = !(k || I && m) : k = t,
                                                        p()
                                                    }
                                                    ))
                                                }
                                                ,
                                                c.addEventListener("error", t, !1),
                                                c.addEventListener("load", e, !1),
                                                h = setTimeout((function() {
                                                    p()
                                                }
                                                ), S);
                                                try {
                                                    var A;
                                                    c.setAttribute("src", _),
                                                    I ? (A = "head",
                                                    c.async = !0) : L && (A = "body",
                                                    c.decoding = "async",
                                                    a(c, r.k[0], r.k[1])),
                                                    Node.prototype.appendChild.call(o[A], c),
                                                    !i && L && (l = new Promise((function(n) {
                                                        var t = 10;
                                                        $ = setInterval((function() {
                                                            var r = !u(c);
                                                            (--t <= 0 || !r) && (n(!r),
                                                            clearInterval($))
                                                        }
                                                        ), r.C / t)
                                                    }
                                                    )))
                                                } catch (n) {
                                                    p()
                                                }
                                            }
                                            ))).then((function(n) {
                                                var r = n.hidden
                                                  , t = n.errored
                                                  , i = n.blocked
                                                  , o = n.loaded;
                                                r && k.push(r),
                                                h = h || o,
                                                e && o ? $() : ((t || i) && w.push(T),
                                                $(T + 1))
                                            }
                                            )).catch(l);
                                        else {
                                            var y = {
                                                loaded: h && 0 === w.length,
                                                fails: w
                                            };
                                            k.length > 0 ? Promise.all(k).then((function(r) {
                                                for (var t = r.length > 0, e = 0; e < r.length; e++)
                                                    if (!r[e]) {
                                                        t = !1;
                                                        break
                                                    }
                                                y.hidden = t,
                                                n(y)
                                            }
                                            )).catch((function(r) {
                                                n(y)
                                            }
                                            )) : n(y)
                                        }
                                        var P, p, b, _, L, I, R, S
                                    }
                                    )(0)
                                } catch (n) {
                                    l(n)
                                }
                            }
                            ))
                        }
                        function T(n) {
                            return null != n
                        }
                        function y(n) {
                            var r = n.browser
                              , t = n.detections
                              , e = n.config
                              , i = n.domReady
                              , o = n.debugLog
                              , u = n.createElement
                              , c = n.getPerfStats
                              , a = n.waitPerf
                              , d = n.isFunction
                              , v = n.recorder;
                            if (!d(window.addEventListener) || r.isIE())
                                return Promise.resolve();
                            var s, l = e.F || [], k = e.G || [], w = document, g = h(), y = function(n, r, t) {
                                var i = n.map((function(n) {
                                    return {
                                        src: n,
                                        tag: "img"
                                    }
                                }
                                )).concat(r.map((function(n) {
                                    return {
                                        src: n,
                                        tag: "script"
                                    }
                                }
                                )));
                                return $({
                                    L: e,
                                    I: i,
                                    R: t,
                                    A: w,
                                    M: g,
                                    N: o,
                                    U: u,
                                    O: c,
                                    j: a,
                                    D: d
                                })
                            };
                            try {
                                var P = new URL(l[0],window.location).origin;
                                P && (s = f(P))
                            } catch (n) {}
                            return i(w).then((function() {
                                return w.body ? y(l, k, "img").then((function(n) {
                                    return {
                                        loaded: n.loaded,
                                        failed: n.fails && n.fails.length === l.length + k.length,
                                        hidden: n.hidden
                                    }
                                }
                                )) : {}
                            }
                            )).then((function(n) {
                                var r = n.loaded
                                  , i = n.failed
                                  , o = n.hidden
                                  , u = t.disabled.bind(t)
                                  , c = t.blocked.bind(t);
                                r ? u(2) : i && c(2, !1),
                                o ? c(512, !0) : T(o) && u(512);
                                var a = m;
                                a ? c(32768, !0) : T(a) && u(32768),
                                s && s();
                                var f = e.W || []
                                  , d = e.V || [];
                                (f[0] || d[0]) && 100 * Math.random() < e.X && setTimeout((function() {
                                    Promise.all([y(d, [], !1), y([], f, !1)]).then((function(n) {
                                        var r = n[0]
                                          , t = n[1];
                                        f[0] && v.addInvestigationData(13, 0, t.fails),
                                        d[0] && v.addInvestigationData(14, 0, r.fails)
                                    }
                                    ))
                                }
                                ), 1e3)
                            }
                            ))
                        }
                        function P(n) {
                            var r = n.browser
                              , t = n.detections
                              , e = (n.debugLog,
                            n.domReady)
                              , i = n.createElement
                              , o = n.config;
                            function c(n, r, t) {
                                var e = a(i(n, r), t || o.h);
                                return n.body.appendChild(e),
                                e
                            }
                            if (r.isIE())
                                return Promise.resolve();
                            var f = document
                              , d = [];
                            return e(f).then((function() {
                                var n = !1;
                                if (o.q) {
                                    var r = c(f, o.q);
                                    if (d.push(r),
                                    u(r)) {
                                        var t = c(f, o.P);
                                        if (d.push(t),
                                        u(t))
                                            return;
                                        n = !0
                                    }
                                }
                                return n
                            }
                            )).then((function(n) {
                                n && t.blocked(1024);
                                for (var r = 0; r < d.length; r++)
                                    try {
                                        d[r].parentNode && d[r].parentNode.removeChild(d[r])
                                    } catch (n) {}
                                return n
                            }
                            ))
                        }
                        function p(n) {
                            var r = n.detections;
                            return n.rng = h(),
                            n.testIMGJS = $,
                            (function(n) {
                                var r = n.config
                                  , t = n.rng
                                  , e = n.timeoutPromise
                                  , i = n.testIMGJS
                                  , o = n.debugLog
                                  , u = n.createElement
                                  , c = n.getPerfStats
                                  , a = n.waitPerf
                                  , f = n.isFunction
                                  , d = r.B;
                                return d ? e(new Promise((function(n) {
                                    var e = "&rn=" + t(1e5);
                                    r.J && (e += "&" + r.J);
                                    var v = {
                                        L: r,
                                        I: [{
                                            src: d + "?ch=2" + e,
                                            tag: "img"
                                        }, {
                                            src: d + "?ch=1" + e,
                                            tag: "img"
                                        }],
                                        R: !0,
                                        kskipHiddenImg: !0,
                                        A: document,
                                        M: t,
                                        N: o,
                                        U: u,
                                        O: c,
                                        j: a,
                                        D: f,
                                        K: "img"
                                    };
                                    i(v).then((function(r) {
                                        var t = r.fails.length
                                          , e = {
                                            hidden: r.hidden
                                        };
                                        1 === t ? 0 === r.fails[0] ? e.status = 1 : e.status = 2 : e.status = t > 0 ? 3 : 2,
                                        n(e)
                                    }
                                    ))
                                }
                                )), 5e3) : Promise.resolve()
                            }
                            )(n).then((function(n) {
                                if (n) {
                                    var t = n.status;
                                    1 === t ? r.blocked(4096, n.hidden) : 3 === t && r.blocked(65536, n.hidden)
                                }
                            }
                            )).catch((function() {}
                            ))
                        }
                        var b = 8192;
                        function _(n) {
                            var r = n.detections
                              , t = n.domReady
                              , e = (n.debugLog,
                            n.isFunction)
                              , i = n.isString
                              , o = n.waitPerf
                              , u = n.config
                              , c = n.recorder;
                            function a(n, r) {
                                return n = n.replace(/\$rd/g, (function() {
                                    return (function(n) {
                                        return g(n, [{
                                            c: [[49, 57]],
                                            l: 5,
                                            v: 2
                                        }, {
                                            c: [[46, 46]],
                                            l: 1
                                        }, {
                                            c: [[48, 57]],
                                            l: 1,
                                            v: 2
                                        }])
                                    }
                                    )(r)
                                }
                                )),
                                new Promise((function(r) {
                                    var t = {
                                        mode: "no-cors"
                                    }
                                      , c = u.u || 5e3
                                      , a = 0;
                                    "AbortSignal"in window && e(AbortSignal.timeout) ? t.signal = AbortSignal.timeout(c) : a = setTimeout((function() {
                                        r({})
                                    }
                                    ), c);
                                    var f = o(n, c)
                                      , d = f.promise
                                      , v = f.cancel;
                                    return fetch(n, t).then((function(n) {
                                        if (a && clearTimeout(a),
                                        n && "opaque" === n.type)
                                            return setTimeout(v, u.g),
                                            void d.then((function(n) {
                                                var t = n.entry
                                                  , e = n.supported;
                                                r(t ? {
                                                    loaded: !0
                                                } : {
                                                    blocked: e
                                                })
                                            }
                                            ));
                                        v(),
                                        r({
                                            blocked: n && i(n.url) && 0 === n.url.indexOf("data:")
                                        })
                                    }
                                    ), (function(n) {
                                        a && clearTimeout(a),
                                        v(),
                                        r({})
                                    }
                                    ))
                                }
                                ))
                            }
                            return e(window.fetch) ? t(document).then((function() {
                                if (!r.hasDisabledFlag(2)) {
                                    var n = h()
                                      , t = u.Y || [];
                                    return new Promise((function(e, i) {
                                        var o = !1;
                                        try {
                                            !(function u(c) {
                                                if (!t[c])
                                                    return o && r.blocked(b),
                                                    void e();
                                                a(t[c], n).then((function(n) {
                                                    var t = n.loaded
                                                      , i = n.blocked;
                                                    return t ? (r.disabled(b),
                                                    void e()) : i ? (r.blocked(b),
                                                    void e()) : (o = !0,
                                                    void u(c + 1))
                                                }
                                                )).catch(i)
                                            }
                                            )(0)
                                        } catch (n) {
                                            i(n)
                                        }
                                    }
                                    )).then((function() {
                                        var r = u.Z || [];
                                        r[0] && 100 * Math.random() < u.X && setTimeout((function() {
                                            Promise.all(r.map((function(r) {
                                                return a(r, n)
                                            }
                                            ))).then((function(n) {
                                                for (var r = [], t = 0; t < n.length; t++)
                                                    n[t] && !n[t].loaded && r.push(t);
                                                c.addInvestigationData(15, 0, r)
                                            }
                                            ))
                                        }
                                        ), 1e3)
                                    }
                                    ))
                                }
                            }
                            )) : Promise.resolve()
                        }
                        var L = {
                            nn: [[1, 2]],
                            h: "32",
                            P: ".imprtnt-cnt",
                            T: ['.stickyads', '.ads_banner'],
                            _: [],
                            $: "sponsored",
                            u: 5000,
                            G: ['https://static.ads' + 'afeprotected.com/sk' + 'eleton.js?adslo' + 't=$rs_300x250_'],
                            W: ['https://pubads.g.dou' + 'bleclick.net/adsid/inte' + 'grator.json?bann' + 'nerid=$ri_advertisement_'],
                            H: 'https://www.goo' + 'gletagser' + 'vices.com/tag/js/gp' + 't.js',
                            F: ['https://static.a' + 'dsafeprot' + 'ected.com/skeleto' + 'n.gif?adunit' + 'id=$rs&adn' + 'um=$ri'],
                            V: [],
                            X: 0,
                            k: [728, 90],
                            C: 250,
                            Y: ['https://adse' + 'rver.adtech.adve' + 'rtising.com/pubap' + 'i/3.0/1/$rd/0/0/ADTE' + 'CH;v=2;cmd=bid;cors=yes'],
                            Z: [],
                            B: "https://merequartz.com/aadetect/px.gif",
                            J: 'adslo' + 't=ad_300x250_$ri',
                            q: "#getadmiral_com_filterlist_installed",
                            rn: "video",
                            tn: "//admiral-has-personalized.invalid",
                            g: 300
                        };
                        _callback.f = function(n) {
                            n.debugLog;
                            var r = n.timeoutPromise
                              , t = n.recorder
                              , e = n.overwrite
                              , i = L.nn;
                            return Promise.resolve({
                                check: function(o) {
                                    var u = o.detections
                                      , c = o.runAllGroups
                                      , a = o.browser
                                      , f = o.timeout
                                      , d = {}
                                      , v = Promise.resolve()
                                      , m = new Promise((function(r, o) {
                                        if (a.isWhitelisted())
                                            r();
                                        else {
                                            var f = {
                                                1: l,
                                                2: y,
                                                8: s,
                                                1024: P,
                                                4096: p,
                                                8192: _
                                            }
                                              , m = {};
                                            try {
                                                !(function n(t) {
                                                    var e = [];
                                                    if (i[t] && i[t].length > 0) {
                                                        for (var a = 0; a < i[t].length; a++)
                                                            e.push(k(f[i[t][a]], i[t][a]));
                                                        Promise.all(e).then((function() {
                                                            c || !u.hasDisabledAdBlocker() ? n(t + 1) : r()
                                                        }
                                                        )).catch(o)
                                                    } else {
                                                        for (var d in f)
                                                            f.hasOwnProperty(d) && e.push(k(f[d], d));
                                                        Promise.all(e).then(r, o)
                                                    }
                                                }
                                                )(0)
                                            } catch (n) {
                                                o(n)
                                            }
                                        }
                                        function k(r, i) {
                                            if (!r || m[i])
                                                return v;
                                            if (m[i] = !0,
                                            !u.enabled(i))
                                                return v;
                                            try {
                                                return d[i] = !0,
                                                r(e({
                                                    config: L,
                                                    browser: a,
                                                    detections: u
                                                }, n)).catch((function(n) {
                                                    throw d[i] = !1,
                                                    n
                                                }
                                                )).then((function(n) {
                                                    return d[i] = !1,
                                                    n
                                                }
                                                ))
                                            } catch (n) {
                                                return t.setError(n, "detector" + i),
                                                Promise.reject(n)
                                            }
                                        }
                                    }
                                    ));
                                    return f > 0 && (m = r(m, f)),
                                    m.catch((function(n) {
                                        if ("timedout" !== n)
                                            throw n;
                                        var r = [];
                                        for (var e in d)
                                            d.hasOwnProperty(e) && d[e] && r.push(e);
                                        t.addInvestigationData(6, 0, r)
                                    }
                                    ))
                                }
                            })
                        }
                    }
                    ]);
                }
                ),
                _callback.l ? rr = _callback.f({
                    debugLog: Et,
                    timeoutPromise: St,
                    recorder: n,
                    overwrite: o,
                    domReady: Jt,
                    isFunction: f,
                    isString: d,
                    createElement: _t,
                    getPerfStats: sn,
                    waitPerf: dn,
                    eventListen: zt
                }) : Promise.resolve()
            }
            )(this.recorder).then((function(r) {
                return (0,
                r.check)({
                    detections: t,
                    runAllGroups: !!T(bn),
                    browser: n.browser,
                    timeout: 15e3,
                    applyHacks: l
                })
            }
            )).then((function() {
                return t.hasBlockerFlag(1024) && n.recorder.addInvestigationData(9),
                St(l(document, n.browser, t), 5e3)
            }
            )).then((function() {
                var i = Date.now()
                  , e = tt.get()
                  , o = e.engageRendered;
                o && (e.lastGAMKVPs || n.recorder.addInvestigationData(17),
                tt.set({
                    engageRendered: o
                }));
                var u = e.userEngaged;
                !o && u && (tt.set({
                    engageRendered: u
                }),
                n.recorder.addInvestigationData(18));
                var a = i - parseInt(e.whitelistAdded, 10) < 108e5
                  , c = t.hasAdBlocker()
                  , s = t.hasDisabledAdBlocker()
                  , f = c && !s
                  , d = {
                    hasAdBlocker: c,
                    disabledAdBlocker: s,
                    blocked: f,
                    blockerScore: t.blockerScore(),
                    disabledScore: t.disabledScore(),
                    recovered: (o || u) && !f,
                    engageRendered: o,
                    flags: t.blockerFlags(),
                    disabledFlags: t.disabledFlags(),
                    duration: Math.max(0, i - r),
                    hacksFlags: t.hacksFlags(),
                    pageviewID: "",
                    hasAdmiralList: t.hasBlockerFlag(1024),
                    hasAA: t.hasBlockerFlag(4096),
                    recentlyWhitelisted: a,
                    blockerType: t.blockerType()
                };
                return n.results = d,
                d
            }
            )).catch((function(t) {
                n.recorder.setError(t, "check")
            }
            ))
        }
        ,
        r.Ut = function(n) {
            var t = this.results;
            t && (this.recorder.addData("pageview", {
                results: t,
                consentApplies: n
            }, er),
            this.recorder.setIsBlocking(t.blocked),
            this.recorder.addDetectorPerfData(t.flags, t.disabledFlags, t.blockerScore, t.disabledScore, t.duration, t.hacksFlags))
        }
        ,
        r.Ht = function() {
            return this.jt || Promise.reject("consent not initialized")
        }
        ,
        r.qt = function() {
            var n = this;
            if (!c.V)
                return this.jt = Promise.resolve({
                    exists: !1,
                    applies: !1
                }),
                this.jt;
            var t = function(t) {
                var r = t._private
                  , i = (void 0 === r ? function() {
                    return {}
                }
                : r)().reportingData
                  , e = void 0 === i ? {} : i
                  , u = tt.get().cmpConsentID;
                u && (e = o({
                    cmpConsentID: u
                }, e)),
                n.recorder.setCMPCommonData(e)
            }
              , r = function(n) {
                var t = n.consentKnown
                  , r = n.tcData
                  , i = void 0 === r ? {} : r
                  , e = n.tcfVersion
                  , o = n._private
                  , u = (void 0 === o ? function() {
                    return {}
                }
                : o)()
                  , a = u.cmpClient
                  , c = void 0 === a ? {} : a
                  , s = u.applies
                  , f = void 0 !== s && s
                  , d = u.consent
                  , h = void 0 === d ? {} : d;
                return {
                    exists: t,
                    cmpClient: c,
                    tcData: i,
                    applies: f,
                    consent: h || {},
                    status: h && h.consentStatus || 4,
                    tcfVersion: e
                }
            };
            return Mn("cmp.updated", (function(i) {
                t(i),
                n.jt = Promise.resolve(r(i))
            }
            )),
            this.jt || (this.jt = new Promise((function(n) {
                Mn("cmp.loaded", (function(i) {
                    t(i),
                    n(r(i))
                }
                ))
            }
            ))),
            this.jt
        }
        ,
        r.Ft = function() {
            return this.xt || Promise.reject("consent not initialized")
        }
        ,
        r.Wt = function() {
            var n = this;
            if (!c.F || c.W)
                return this.xt = Promise.resolve({
                    exists: !1
                }),
                this.xt;
            var t = function(t) {
                t.state;
                var r = t._private
                  , i = (void 0 === r ? function() {
                    return {}
                }
                : r)().reportingData
                  , e = void 0 === i ? {} : i;
                n.recorder.setCCPACommonData(e)
            }
              , r = function(n) {
                var t = n.state;
                return {
                    exists: !!t,
                    state: t,
                    applies: n.applies
                }
            };
            return Mn("ccpa.updated", (function(i) {
                t(i),
                n.xt = Promise.resolve(r(i))
            }
            )),
            this.xt || (this.xt = new Promise((function(n) {
                Mn("ccpa.loaded", (function(i) {
                    i && i.state ? (t(i),
                    n(r(i))) : n({
                        exists: !1,
                        state: "",
                        applies: !1
                    })
                }
                ))
            }
            ))),
            this.xt
        }
        ,
        r.Vt = function() {
            return this.zt || Promise.reject("consent not initialized")
        }
        ,
        r.Gt = function() {
            var n = this;
            if (!c.W)
                return this.zt = Promise.resolve({
                    exists: !1
                }),
                this.zt;
            var t = function(t) {
                t.applies,
                t.state;
                var r = t._private
                  , i = (void 0 === r ? function() {
                    return {}
                }
                : r)().reportingData
                  , e = void 0 === i ? {} : i
                  , u = tt.get().usnatCMPConsentID;
                u && (e = o({
                    usnatCMPConsentID: u
                }, e)),
                n.recorder.setUSNatCommonData(e)
            }
              , r = function(n) {
                var t = n.applies
                  , r = n.state;
                return {
                    exists: !!r,
                    applies: t,
                    state: r
                }
            };
            return Mn("usnat.updated", (function(i) {
                t(i),
                n.zt = Promise.resolve(r(i))
            }
            )),
            this.zt || (this.zt = new Promise((function(n) {
                Mn("usnat.loaded", (function(i) {
                    i ? (t(i),
                    n(r(i))) : n({
                        exists: !1,
                        applies: !1
                    })
                }
                ))
            }
            ))),
            this.zt
        }
        ,
        r.Jt = function(n, t) {
            var r = this;
            this.Ut(t);
            var i = this.recorder.record(n || new Un(window.location));
            return i.then((function(n) {
                ar || (ar = !0,
                r.Xt(n));
                var t, i = or && !ur;
                i ? (ur = !0,
                t = r.recorder.testRecord(c.K, c.J)) : t = Promise.resolve(),
                t.catch(ir).then((function() {
                    i && r.recorder.recordMetrics(!0)
                }
                ))
            }
            )),
            i
        }
        ,
        r.Xt = function(n) {
            var t = this.results || {}
              , r = !!t.blocked
              , i = !!t.hasAA
              , e = !!t.recovered
              , o = !(!n || !n.subscription || !0 !== n.subscription.subscriptionExists);
            if (c.an) {
                var u = {
                    adblocking: r,
                    subscribed: o,
                    whitelisted: e
                };
                c.En && (u.isAA = i,
                u.aaEnabled = i),
                On("measure.detected", u)
            }
            o ? en(n.entries).then((function() {
                On("transact.subscribed", {
                    offers: n.entries,
                    benefits: rn(n.entries)
                })
            }
            )) : en([])
        }
        ,
        r.Kt = function() {
            var n = this;
            return nr ? Promise.resolve() : this.Nt || (this.Nt = Ct(Sn(c.U), !0).then((function() {
                n.Qt = !0
            }
            )).catch((function(t) {
                n.recorder.setError(t, "cmpload")
            }
            )))
        }
        ,
        r.Zt = function(n) {
            var t = this;
            this.Yt().then((function() {
                var r = [];
                if (n.forEach((function(n) {
                    t.Lt.hasOwnProperty(n) && r.push(t.Lt[n])
                }
                )),
                n.length < 1 || r.length == n.length)
                    return Promise.all(r);
                var i = window.CSS;
                i && i.supports("grid-row", "1") || (n = n.map((function(n) {
                    return n + "-compat"
                }
                )));
                var e = c.Pn;
                if (!e)
                    return Promise.reject("missing template path");
                var o, u, a = Ct(Sn("".concat(e, "/").concat((o = n,
                u = {},
                (o || []).reduce((function(n, t) {
                    return u[t] || (u[t] = !0,
                    n.push(t)),
                    n
                }
                ), [])).join(","))), !0).then((function(n) {
                    n && n.src && t.recorder.addLoadPerfData(c.wn, 1, sn(n.src))
                }
                ));
                return n.forEach((function(n) {
                    t.Lt[n] = a
                }
                )),
                a
            }
            ))
        }
        ,
        r.nr = function(n, t) {
            var r = this;
            n = n || [];
            var i = $n()
              , e = _n(i)
              , u = []
              , a = []
              , s = []
              , f = null;
            return n.forEach((function(n) {
                -1 === r.Bt.indexOf(n.candidateID) && r.Bt.push(n.candidateID);
                var t = n.payload = n.payload || {};
                switch (n.payloadType) {
                case "template":
                    u.push(n),
                    "ConsentManager" !== t.name && "GPPConsentManager" !== t.name && "USNational" !== t.name || s.push(r.Kt());
                    break;
                case "cmp":
                    a.push(n),
                    s.push(r.Kt()),
                    n.candidateID && (t.candidateID = n.candidateID),
                    n.groups && (t.groups = n.groups),
                    n.batchID && (t.batchID = n.batchID),
                    s.push(new Promise((function(n) {
                        Rn("show", "cmp.main", t, n)
                    }
                    )));
                    break;
                case "engage":
                    u.push(o({}, n, {
                        payloadType: "template",
                        payload: {
                            metadata: {
                                preview: i,
                                engageType: t.type
                            },
                            name: "soft" === t.type ? "BannerEngage" : "ModalEngage",
                            options: t,
                            container: t.container || "body",
                            replace: !!t.replace
                        }
                    }));
                    break;
                case "transact":
                    a.push(n);
                    break;
                case "ccpa":
                    e.Tn.includes(n.candidateID) && Rn("show", "ccpa.main"),
                    a.push(n),
                    f = n;
                    break;
                case "sticky":
                    u.push(o({}, n, {
                        payloadType: "template",
                        payload: {
                            metadata: {
                                preview: i
                            },
                            name: "Sticky",
                            options: t,
                            container: "body"
                        }
                    }))
                }
            }
            )),
            c.F && !c.W && Rn("triggerEvent", "ccpa.settingsLoaded", f),
            On("candidate.received", {
                candidates: (u || []).map((function(n) {
                    var t = n.candidateID
                      , r = n.groups;
                    return {
                        candidateID: t,
                        groups: r,
                        candidateGroups: r
                    }
                }
                ))
            }),
            u.length > 0 && s.push(this.Zt(u.filter((function(n) {
                var t = n.payload;
                return !(!t || t.provider || !t.name)
            }
            )).map((function(n) {
                var t = n.payload;
                return t && t.name
            }
            )))),
            Promise.all(s).then((function() {
                var n = "template.candidates";
                Rn("get", n, (function(r, i) {
                    i ? r.dataCandidates = t ? a : a.reduce((function(n, t) {
                        for (var r = 0; r < n.length; r++)
                            if (n[r] && n[r].candidateID === (t && t.candidateID))
                                return n[r] = t,
                                n;
                        return n.concat([t])
                    }
                    ), r.dataCandidates) : r = {
                        dataCandidates: a
                    },
                    r.templateCandidates = u,
                    r.time = Date.now(),
                    Rn("set", n, r)
                }
                ))
            }
            )).then((function() {
                t && u.forEach((function(n) {
                    var t = ((n || {}).payload || {}).name;
                    Rn("show", t, {
                        candidate: n,
                        dataCandidates: a
                    })
                }
                ))
            }
            ))
        }
        ,
        r.Yt = function() {
            var n = this;
            return new Promise((function(t) {
                Rn("get", "template.env", (function(r, i) {
                    if (i)
                        return t(r);
                    Promise.all([new Promise((function(n) {
                        return Rn("get", "engage.instructions.url", (function(t, r) {
                            return n(r ? t : void 0)
                        }
                        ))
                    }
                    )), new Promise((function(n) {
                        return Rn("get", "engage.whitelist.url", (function(t, r) {
                            return n(r ? t : void 0)
                        }
                        ))
                    }
                    )), St(n.Ht(), 5e3).catch((function(n) {
                        return {
                            failed: !0
                        }
                    }
                    )), n.recorder.getCookieData()]).then((function(r) {
                        var i = r[0]
                          , e = r[1]
                          , u = r[2]
                          , a = r[3]
                          , s = {
                            _private: function() {
                                return o({
                                    hasAdmiralList: n.results && n.results.hasAdmiralList,
                                    cmpClient: u && u.cmpClient,
                                    browser: n.browser,
                                    params: {
                                        forceLogin: T("forceLogin")
                                    },
                                    languagePrefs: c.T || navigator.language || navigator.userLanguage
                                }, a.sessions)
                            }
                        };
                        i && (s.defaultInstructionsURL = i),
                        e && (s.defaultWhitelistURL = e),
                        Rn("getOrSet", "template.env", s),
                        t(s)
                    }
                    ))
                }
                ))
            }
            ))
        }
        ,
        n.start = function() {
            try {
                new fr
            } catch (n) {}
            var t = new n;
            if ((function(n) {
                var t, r = u.u, i = u.P;
                try {
                    t = qt[r] || qt[i]
                } catch (n) {
                    t = qt[i]
                }
                if (!t || !t.loaded) {
                    var e = t || {}
                      , o = e.q || []
                      , a = new Ht(n,e.v).fn();
                    try {
                        qt[i] = qt[r] = a
                    } catch (n) {
                        qt[i] = a
                    }
                    !(function(n, t) {
                        function r(n, r, i) {
                            var e = {};
                            function o(t, e) {
                                e = {
                                    _: t,
                                    _a: JSON.stringify(e),
                                    _ach: i
                                };
                                try {
                                    return n.postMessage(e, r),
                                    !0
                                } catch (n) {}
                                return !1
                            }
                            function u(n, r, i) {
                                n && t("removeEventListener", n, i || e[r]),
                                delete e[r]
                            }
                            return function(n) {
                                var r = n.data;
                                if (r && r._a) {
                                    var i = r._
                                      , a = r._a;
                                    try {
                                        a = JSON.parse(a)
                                    } catch (n) {
                                        return
                                    }
                                    if (2 === i)
                                        u(a.r, a.cb);
                                    else {
                                        if (a.cb) {
                                            var c = a.cb;
                                            a.cb = function n() {
                                                e[c] && o(1, {
                                                    cb: c,
                                                    a: xt(arguments)
                                                }) || u(a.l, c, n)
                                            }
                                            ,
                                            e[c] = a.cb
                                        }
                                        t.a.pm(i, a)
                                    }
                                }
                            }
                        }
                        var i = {}
                          , e = 1;
                        n.addEventListener("message", (function(t) {
                            var o = t.data
                              , u = t.origin
                              , a = t.source
                              , c = t.ports;
                            if (o && o._a) {
                                if (a.top !== n.top)
                                    return;
                                if (c && 1 === c.length)
                                    c[0].onmessage = r(c[0]),
                                    c[0].onmessage({
                                        data: o
                                    });
                                else {
                                    var s = i[o._ach];
                                    o._ach || (o._ach = e++,
                                    s = i[o._ach] = r(a, u, o._ach)),
                                    s && s({
                                        data: o
                                    })
                                }
                            }
                        }
                        ), !1)
                    }
                    )(qt, a);
                    for (var c = 0; c < o.length; c++)
                        a.apply(null, o[c])
                }
            }
            )(new Zt(t.recorder)),
            t.browser.isDisabled())
                return Promise.resolve();
            nr = (new sr).l,
            On("_recorder", {
                recorder: t.recorder
            }),
            t.qt(),
            t.Wt(),
            t.Gt();
            var r, i = new Hn, e = document.location;
            if (e && "file:" === e.protocol)
                return Promise.resolve();
            Mn("call.targeting.render", (function(n) {
                var r = n.candidateIDs
                  , i = n.variantIDs
                  , e = n.overrides
                  , o = n.force
                  , u = void 0 !== o && o;
                return r && (t.Bt = t.Bt.concat(r || [])),
                t.recorder.fetchCandidates({
                    candidateIDs: r,
                    variantIDs: i,
                    overrides: e
                }).then((function(n) {
                    var r = n.candidates;
                    return t.nr(r, u)
                }
                ))
            }
            )),
            Mn("engage.oneClickWhitelisted", (function() {
                return tt.set({
                    whitelistAdded: Date.now()
                })
            }
            )),
            Mn("view.rendered", (function(n) {
                var r = n.candidates
                  , i = void 0 === r ? [] : r
                  , e = n.preview
                  , o = void 0 !== e && e
                  , u = n.extras
                  , a = (t.results || {}).blocked;
                i.forEach((function(n) {
                    var t = n.candidateID
                      , r = n.groups
                      , i = n.payloadType
                      , e = n.triggers;
                    !o && u && a && (u[t] && u[t].whitelistAsk || (e || []).find((function(n) {
                        return n && "adblockerDisabled" === n.type
                    }
                    ))) && tt.set({
                        engageRendered: Date.now()
                    }),
                    "template" === i && On("candidate.shown", {
                        candidateID: t,
                        groups: r,
                        candidateGroups: r
                    })
                }
                ))
            }
            )),
            Mn("view.closed", (function(n) {
                var t = n.candidates
                  , r = void 0 === t ? [] : t
                  , i = n.callback
                  , e = void 0 === i ? function() {}
                : i;
                r.forEach((function(n) {
                    var t = n.candidateID
                      , r = n.groups;
                    "template" === n.payloadType && On("candidate.dismissed", {
                        candidateID: t,
                        groups: r,
                        candidateGroups: r
                    })
                }
                )),
                e({})
            }
            )),
            Mn("template.load", t.Zt.bind(t));
            var a = Pn();
            return a ? (Mn("previewCandidates", (function(n) {
                var r = n.candidates;
                t.nr(r || [], !0)
            }
            )),
            r = t.Yt().then((function() {
                return On("previewready", {
                    v: 2
                }),
                []
            }
            ))) : (r = Promise.all([t.check(), St(t.Ht(), 5e3).catch((function(n) {
                return "timedout" === n && t.recorder.addInvestigationData(7),
                {
                    failed: !0
                }
            }
            )), St(t.Ft(), 5e3).catch((function(n) {
                return "timedout" === n && t.recorder.addInvestigationData(11),
                {
                    failed: !0
                }
            }
            )), St(t.Vt(), 5e3).catch((function(n) {
                return "timedout" === n && t.recorder.addInvestigationData(16),
                {
                    failed: !0
                }
            }
            ))]).then((function(n) {
                var r = n[1]
                  , e = n[2]
                  , u = n[3]
                  , a = 0;
                return r && r.applies && (a |= 1),
                e && e.applies && (a |= 2),
                u && u.applies && (a |= 4),
                new Promise((function(n, r) {
                    i.start((function(i) {
                        return t.Jt(i, a).then(n, r)
                    }
                    ))
                }
                )).then((function() {
                    return (function(n) {
                        if (tr)
                            return tr;
                        var _callback = {};
                        return new (function() {
                            _callback.l = !!0
                        }
                        ),
                        _callback.l ? tr = _callback.f({
                            debugLog: Et,
                            overwrite: o,
                            queryStringify: Vt,
                            callAdmiralQueue: Rn,
                            getBenefitsFromEntries: rn,
                            getSubscriptionMetadata: nn,
                            cleanupEntries: tn,
                            setBenefitsCookie: en,
                            recorder: n,
                            propertyID: c.h
                        }) : Promise.resolve()
                    }
                    )(t.recorder).then((function() {
                        return n
                    }
                    ))
                }
                ))
            }
            )),
            setTimeout((function() {
                c.Sn && c.Cn && Ct(c.Sn + "&pub=" + c.Cn)
            }
            ), 100)),
            r.then((function(n) {
                var r = n[0]
                  , i = n[1]
                  , e = n[2];
                if (t.browser.isInteractable())
                    return new Promise((function(n) {
                        return Rn("targeting", "onReady", n)
                    }
                    )).then((function(n) {
                        return c.an ? a ? {} : (r && r.recentlyWhitelisted && (r.blocked = !1),
                        t.recorder.fetchCandidates({
                            results: r,
                            cmpStatus: i,
                            ccpaStatus: e,
                            customParams: n,
                            shownCandidates: t.Bt
                        })) : {}
                    }
                    )).then((function(n) {
                        var r = n.candidates
                          , i = void 0 === r ? [] : r;
                        return t.nr(i, !1)
                    }
                    ))
            }
            )).then((function() {
                setTimeout((function() {
                    t.recorder.recordMetrics()
                }
                ), 1e3)
            }
            )).catch((function(n) {
                throw n
            }
            ))
        }
        ,
        t = n,
        Object.defineProperty(t, "prototype", {
            writable: !1
        }),
        t
    }
    )();
    function sr() {
        this.l = !!0
    }
    function fr() {
        this.l = 0,
        f(this.l) && this.l(Ct)
    }
    "undefined" != typeof document && cr.start();
    var dr = function() {
        ar = !1
    };
    t.default = cr
}
]);


  <script type="text/javascript" src="lib/paper.js"></script>
  <!--<script type="text/javascript" src="lib/dat.gui.min.js"></script>-->
  <script type="text/javascript" src="lib/Tween.js"></script>
  <script type="text/javascript" src="lib/traer.js"></script>
  
  <script type="text/javascript" src="lib/soundmanager2-nodebug-jsmin.js"></script>
  
  <script type="text/javascript"  src="src/jiggler.js"></script>
  <script type="text/paperscript" src="src/main.js" canvas="canvas"></script>
  
  <link href="src/style.css" media="screen" rel="stylesheet" type="text/css" />

  <title>Staggering Beauty</title>
  <meta name="title" content="Staggering Beauty" />
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <meta name="Description" content="A website to remember." />
  <meta name="viewport" content="initial-scale=0.6,user-scalable=no" />
  <link rel="image_src" href="assets/poster.png" />
</head>
<body>

  <canvas id="canvas" resize></canvas>
  <script type="text/javascript">

    var _gaq = _gaq || [];
    _gaq.push(['_setAccount', 'UA-353220-16']);
    _gaq.push(['_trackPageview']);

    (function() {
      var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
      ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
      var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
    })();

  </script>

  <div id="compat">
    <!-- It's way better on a desktop. -->
  </div>

  <div id="shake">
    Shake vigorously
  </div>

  <div id="warning">
    <span class="english">WARNING: CONTAINS FLASHING IMAGES</span><br/>
    <span class="chinese">&#21253;&#21547;&#38378;&#28865;&#30340;&#22270;&#20687;</span>
  </div>

  <div id="enquiries">
    <a target="_top" href="mailto:enquiries@staggeringbeauty.com">Enquiries</a>
    <a id="embed-button" href="#">Embed</a>
  </div>

  <div id="embed">
    <textarea id="embed-text">&lt;iframe src=&quot;http://www.staggeringbeauty.com/&quot; style=&quot;border: 1px inset #ddd&quot; width=&quot;498&quot; height=&quot;598&quot;&gt;&lt;/iframe&gt;</textarea>
  </div>
<script type="text/javascript">

var embedButton = document.getElementById('embed-button');
var embedShade = document.getElementById('embed');
var embedText = document.getElementById('embed-text');

embedButton.addEventListener('click', function(e) {
  e.preventDefault();
  embedShade.style.display = 'block';
  return false;
}, false);

embedShade.addEventListener('click', function() {
  embedShade.style.display = 'none';
}, false);

embedText.addEventListener('click', function(e) {
  e.preventDefault();
  e.stopPropagation();
  this.select();
  return false;
})
</script>
</body>
</html>/**
 * @author sole / http://soledadpenades.com
 * @author mr.doob / http://mrdoob.com
 * @author Robert Eisele / http://www.xarg.org
 * @author Philippe / http://philippe.elsass.me
 * @author Robert Penner / http://www.robertpenner.com/easing_terms_of_use.html
 * @author Paul Lewis / http://www.aerotwist.com/
 * @author lechecacharro
 * @author Josh Faul / http://jocafa.com/
 */

var TWEEN = TWEEN || ( function () {

	var i, interval, fps = 60, autostart = false, tweens = [], num_tweens;

	return {
	
		setFPS: function ( f ) {

			fps = f || 60;

		},

		stop: function () {

			clearInterval( interval );

		},

		setAutostart: function ( value ) {

			autostart = value;
			
			if(autostart && !interval) {
				this.start();
			}

		},

		add: function ( tween ) {

			tweens.push( tween );


			if (autostart && !interval) {

				this.start();

			}

		},

		getAll: function() {

			return tweens;

		},

		removeAll: function() {

			tweens = [];

		},

		remove: function ( tween ) {

			i = tweens.indexOf( tween );

			if ( i !== -1 ) {

				tweens.splice( i, 1 );

			}


		},

		update: function (_time) {

			i = 0; num_tweens = tweens.length;

			while ( i < num_tweens ) {

				if ( tweens[ i ].update( _time || Date.now() ) ) {

					i++;

				} else {

					tweens.splice( i, 1 );
					num_tweens--;

				}

			}

			if (num_tweens == 0 && autostart) {

				this.stop();

			}

		}

	};

} )();

TWEEN.Tween = function ( object ) {

	var _object = object,
	_valuesStart = {},
	_valuesDelta = {},
	_valuesEnd = {},
	_duration = 1000,
	_delayTime = 0,
	_startTime = null,
	_easingFunction = TWEEN.Easing.Linear.EaseNone,
	_chainedTween = null,
	_onUpdateCallback = null,
	_onCompleteCallback = null;

	this.to = function ( properties, duration ) {

		if( duration !== null ) {

			_duration = duration;

		}

		for ( var property in properties ) {

			// This prevents the engine from interpolating null values
			if ( _object[ property ] === null ) {

				continue;

			}

			// The current values are read when the tween starts;
			// here we only store the final desired values
			_valuesEnd[ property ] = properties[ property ];

		}

		return this;

	};

	this.start = function (_time) {

		TWEEN.add( this );

		_startTime = _time ? _time + _delayTime : Date.now() + _delayTime;

		for ( var property in _valuesEnd ) {

			// Again, prevent dealing with null values
			if ( _object[ property ] === null ) {

				continue;

			}

			_valuesStart[ property ] = _object[ property ];
			_valuesDelta[ property ] = _valuesEnd[ property ] - _object[ property ];

		}

		return this;

	};

	this.stop = function () {

		TWEEN.remove( this );
		return this;

	};

	this.delay = function ( amount ) {

		_delayTime = amount;
		return this;

	};

	this.easing = function ( easing ) {

		_easingFunction = easing;
		return this;

	};

	this.chain = function ( chainedTween ) {

		_chainedTween = chainedTween;

	};

	this.onUpdate = function ( onUpdateCallback ) {

		_onUpdateCallback = onUpdateCallback;
		return this;

	};

	this.onComplete = function ( onCompleteCallback ) {

		_onCompleteCallback = onCompleteCallback;
		return this;

	};

	this.update = function ( time ) {

		var property, elapsed, value;

		if ( time < _startTime ) {

			return true;

		}

		elapsed = ( time - _startTime ) / _duration;
		elapsed = elapsed > 1 ? 1 : elapsed;

		value = _easingFunction( elapsed );

		for ( property in _valuesDelta ) {

			_object[ property ] = _valuesStart[ property ] + _valuesDelta[ property ] * value;

		}

		if ( _onUpdateCallback !== null ) {

			_onUpdateCallback.call( _object, value );

		}

		if ( elapsed == 1 ) {


			if ( _onCompleteCallback !== null ) {


				_onCompleteCallback.call( _object );

			}

			if ( _chainedTween !== null ) {

				_chainedTween.start();

			}

			return false;

		}

		return true;

	};

	/*
	this.destroy = function () {

		TWEEN.remove( this );

	};
	*/
}

TWEEN.Easing = { Linear: {}, Quadratic: {}, Cubic: {}, Quartic: {}, Quintic: {}, Sinusoidal: {}, Exponential: {}, Circular: {}, Elastic: {}, Back: {}, Bounce: {} };


TWEEN.Easing.Linear.EaseNone = function ( k ) {

	return k;

};

//

TWEEN.Easing.Quadratic.EaseIn = function ( k ) {

	return k * k;

};

TWEEN.Easing.Quadratic.EaseOut = function ( k ) {

	return - k * ( k - 2 );

};

TWEEN.Easing.Quadratic.EaseInOut = function ( k ) {

	if ( ( k *= 2 ) < 1 ) return 0.5 * k * k;
	return - 0.5 * ( --k * ( k - 2 ) - 1 );

};

//

TWEEN.Easing.Cubic.EaseIn = function ( k ) {

	return k * k * k;

};

TWEEN.Easing.Cubic.EaseOut = function ( k ) {

	return --k * k * k + 1;

};

TWEEN.Easing.Cubic.EaseInOut = function ( k ) {

	if ( ( k *= 2 ) < 1 ) return 0.5 * k * k * k;
	return 0.5 * ( ( k -= 2 ) * k * k + 2 );

};

//

TWEEN.Easing.Quartic.EaseIn = function ( k ) {

	return k * k * k * k;

};

TWEEN.Easing.Quartic.EaseOut = function ( k ) {

	 return - ( --k * k * k * k - 1 );

}

TWEEN.Easing.Quartic.EaseInOut = function ( k ) {

	if ( ( k *= 2 ) < 1) return 0.5 * k * k * k * k;
	return - 0.5 * ( ( k -= 2 ) * k * k * k - 2 );

};

//

TWEEN.Easing.Quintic.EaseIn = function ( k ) {

	return k * k * k * k * k;

};

TWEEN.Easing.Quintic.EaseOut = function ( k ) {

	return ( k = k - 1 ) * k * k * k * k + 1;

};

TWEEN.Easing.Quintic.EaseInOut = function ( k ) {

	if ( ( k *= 2 ) < 1 ) return 0.5 * k * k * k * k * k;
	return 0.5 * ( ( k -= 2 ) * k * k * k * k + 2 );

};

// 

TWEEN.Easing.Sinusoidal.EaseIn = function ( k ) {

	return - Math.cos( k * Math.PI / 2 ) + 1;

};

TWEEN.Easing.Sinusoidal.EaseOut = function ( k ) {

	return Math.sin( k * Math.PI / 2 );

};

TWEEN.Easing.Sinusoidal.EaseInOut = function ( k ) {

	return - 0.5 * ( Math.cos( Math.PI * k ) - 1 );

};

//

TWEEN.Easing.Exponential.EaseIn = function ( k ) {

	return k == 0 ? 0 : Math.pow( 2, 10 * ( k - 1 ) );

};

TWEEN.Easing.Exponential.EaseOut = function ( k ) {

	return k == 1 ? 1 : - Math.pow( 2, - 10 * k ) + 1;

};

TWEEN.Easing.Exponential.EaseInOut = function ( k ) {

	if ( k == 0 ) return 0;
        if ( k >= 1 ) return 1;
        if ( ( k *= 2 ) < 1 ) return 0.5 * Math.pow( 2, 10 * ( k - 1 ) );
        return 0.5 * ( - Math.pow( 2, - 10 * ( k - 1 ) ) + 2 );

};

// 

TWEEN.Easing.Circular.EaseIn = function ( k ) {

	return - ( Math.sqrt( 1 - k * k ) - 1);

};

TWEEN.Easing.Circular.EaseOut = function ( k ) {

	return Math.sqrt( 1 - --k * k );

};

TWEEN.Easing.Circular.EaseInOut = function ( k ) {

	if ( ( k /= 0.5 ) < 1) return - 0.5 * ( Math.sqrt( 1 - k * k) - 1);
	return 0.5 * ( Math.sqrt( 1 - ( k -= 2) * k) + 1);

};

//

TWEEN.Easing.Elastic.EaseIn = function( k ) {

	var s, a = 0.1, p = 0.4;
	if ( k == 0 ) return 0; if ( k == 1 ) return 1; if ( !p ) p = 0.3;
	if ( !a || a < 1 ) { a = 1; s = p / 4; }
	else s = p / ( 2 * Math.PI ) * Math.asin( 1 / a );
	return - ( a * Math.pow( 2, 10 * ( k -= 1 ) ) * Math.sin( ( k - s ) * ( 2 * Math.PI ) / p ) );

};

TWEEN.Easing.Elastic.EaseOut = function( k ) {

	var s, a = 0.1, p = 0.4;
	if ( k == 0 ) return 0; if ( k == 1 ) return 1; if ( !p ) p = 0.3;
	if ( !a || a < 1 ) { a = 1; s = p / 4; }
	else s = p / ( 2 * Math.PI ) * Math.asin( 1 / a );
	return ( a * Math.pow( 2, - 10 * k) * Math.sin( ( k - s ) * ( 2 * Math.PI ) / p ) + 1 );

};

TWEEN.Easing.Elastic.EaseInOut = function( k ) {

	var s, a = 0.1, p = 0.4;
	if ( k == 0 ) return 0; if ( k == 1 ) return 1; if ( !p ) p = 0.3;
        if ( !a || a < 1 ) { a = 1; s = p / 4; }
        else s = p / ( 2 * Math.PI ) * Math.asin( 1 / a );
        if ( ( k *= 2 ) < 1 ) return - 0.5 * ( a * Math.pow( 2, 10 * ( k -= 1 ) ) * Math.sin( ( k - s ) * ( 2 * Math.PI ) / p ) );
        return a * Math.pow( 2, -10 * ( k -= 1 ) ) * Math.sin( ( k - s ) * ( 2 * Math.PI ) / p ) * 0.5 + 1;

};

//

TWEEN.Easing.Back.EaseIn = function( k ) {

	var s = 1.70158;
	return k * k * ( ( s + 1 ) * k - s );

};

TWEEN.Easing.Back.EaseOut = function( k ) {

	var s = 1.70158;
	return ( k = k - 1 ) * k * ( ( s + 1 ) * k + s ) + 1;

};

TWEEN.Easing.Back.EaseInOut = function( k ) {

	var s = 1.70158 * 1.525;
	if ( ( k *= 2 ) < 1 ) return 0.5 * ( k * k * ( ( s + 1 ) * k - s ) );
	return 0.5 * ( ( k -= 2 ) * k * ( ( s + 1 ) * k + s ) + 2 );

};

// 

TWEEN.Easing.Bounce.EaseIn = function( k ) {

	return 1 - TWEEN.Easing.Bounce.EaseOut( 1 - k );

};

TWEEN.Easing.Bounce.EaseOut = function( k ) {

	if ( ( k /= 1 ) < ( 1 / 2.75 ) ) {

		return 7.5625 * k * k;

	} else if ( k < ( 2 / 2.75 ) ) {

		return 7.5625 * ( k -= ( 1.5 / 2.75 ) ) * k + 0.75;

	} else if ( k < ( 2.5 / 2.75 ) ) {

		return 7.5625 * ( k -= ( 2.25 / 2.75 ) ) * k + 0.9375;

	} else {

		return 7.5625 * ( k -= ( 2.625 / 2.75 ) ) * k + 0.984375;

	}

};

TWEEN.Easing.Bounce.EaseInOut = function( k ) {

	if ( k < 0.5 ) return TWEEN.Easing.Bounce.EaseIn( k * 2 ) * 0.5;
	return TWEEN.Easing.Bounce.EaseOut( k * 2 - 1 ) * 0.5 + 0.5;

};/*!
 * Paper.js v0.22
 *
 * This file is part of Paper.js, a JavaScript Vector Graphics Library,
 * based on Scriptographer.org and designed to be largely API compatible.
 * http://paperjs.org/
 * http://scriptographer.org/
 *
 * Copyright (c) 2011, Juerg Lehni & Jonathan Puckey
 * http://lehni.org/ & http://jonathanpuckey.com/
 *
 * Distributed under the MIT license. See LICENSE file for details.
 *
 * All rights reserved.
 *
 * Date: Thu Nov 10 19:19:25 2011 +0100
 *
 ***
 *
 * Bootstrap.js JavaScript Framework.
 * http://bootstrapjs.org/
 *
 * Copyright (c) 2006 - 2011 Juerg Lehni
 * http://lehni.org/
 *
 * Distributed under the MIT license.
 *
 ***
 *
 * Parse-js
 *
 * A JavaScript tokenizer / parser / generator, originally written in Lisp.
 * Copyright (c) Marijn Haverbeke <marijnh@gmail.com>
 * http://marijn.haverbeke.nl/parse-js/
 *
 * Ported by to JavaScript by Mihai Bazon
 * Copyright (c) 2010, Mihai Bazon <mihai.bazon@gmail.com>
 * http://mihai.bazon.net/blog/
 *
 * Modifications and adaptions to browser (c) 2011, Juerg Lehni
 * http://lehni.org/
 *
 * Distributed under the BSD license.
 */

var paper = new function() {

var Base = new function() { 
	var fix = !this.__proto__,
		hidden = /^(statics|generics|preserve|enumerable|prototype|__proto__|toString|valueOf)$/,
		proto = Object.prototype,
		has = fix
			? function(name) {
				return name !== '__proto__' && this.hasOwnProperty(name);
			}
			: proto.hasOwnProperty,
		toString = proto.toString,
		proto = Array.prototype,
		isArray = Array.isArray = Array.isArray || function(obj) {
			return toString.call(obj) === '[object Array]';
		},
		slice = proto.slice,
		forEach = proto.forEach = proto.forEach || function(iter, bind) {
			for (var i = 0, l = this.length; i < l; i++)
				iter.call(bind, this[i], i, this);
		},
		forIn = function(iter, bind) {
			for (var i in this)
				if (this.hasOwnProperty(i))
					iter.call(bind, this[i], i, this);
		},
		_define = Object.defineProperty,
		_describe = Object.getOwnPropertyDescriptor;

	function define(obj, name, desc) {
		if (_define) {
			try {
				delete obj[name];
				return _define(obj, name, desc);
			} catch (e) {}
		}
		if ((desc.get || desc.set) && obj.__defineGetter__) {
			desc.get && obj.__defineGetter__(name, desc.get);
			desc.set && obj.__defineSetter__(name, desc.set);
		} else {
			obj[name] = desc.value;
		}
		return obj;
	}

	function describe(obj, name) {
		if (_describe) {
			try {
				return _describe(obj, name);
			} catch (e) {}
		}
		var get = obj.__lookupGetter__ && obj.__lookupGetter__(name);
		return get
			? { get: get, set: obj.__lookupSetter__(name), enumerable: true,
					configurable: true }
			: has.call(obj, name)
				? { value: obj[name], enumerable: true, configurable: true,
						writable: true }
				: null;
	}

	function inject(dest, src, enumerable, base, preserve, generics) {
		var beans, bean;

		function field(name, val, dontCheck, generics) {
			var val = val || (val = describe(src, name))
					&& (val.get ? val : val.value),
				func = typeof val === 'function',
				res = val,
				prev = preserve || func
					? (val && val.get ? name in dest : dest[name]) : null;
			if (generics && func && (!preserve || !generics[name])) {
				generics[name] = function(bind) {
					return bind && dest[name].apply(bind,
							slice.call(arguments, 1));
				}
			}
			if ((dontCheck || val !== undefined && has.call(src, name))
					&& (!preserve || !prev)) {
				if (func) {
					if (prev && /\bthis\.base\b/.test(val)) {
						var fromBase = base && base[name] == prev;
						res = function() {
							var tmp = describe(this, 'base');
							define(this, 'base', { value: fromBase
								? base[name] : prev, configurable: true });
							try {
								return val.apply(this, arguments);
							} finally {
								tmp ? define(this, 'base', tmp)
									: delete this.base;
							}
						};
						res.toString = function() {
							return val.toString();
						}
						res.valueOf = function() {
							return val.valueOf();
						}
					}
					if (beans && val.length == 0
							&& (bean = name.match(/^(get|is)(([A-Z])(.*))$/)))
						beans.push([ bean[3].toLowerCase() + bean[4], bean[2] ]);
				}
				if (!res || func || !res.get && !res.set)
					res = { value: res, writable: true };
				if ((describe(dest, name)
						|| { configurable: true }).configurable) {
					res.configurable = true;
					res.enumerable = enumerable;
				}
				define(dest, name, res);
			}
		}
		if (src) {
			beans = [];
			for (var name in src)
				if (has.call(src, name) && !hidden.test(name))
					field(name, null, true, generics);
			field('toString');
			field('valueOf');
			for (var i = 0, l = beans && beans.length; i < l; i++)
				try {
					var bean = beans[i], part = bean[1];
					field(bean[0], {
						get: dest['get' + part] || dest['is' + part],
						set: dest['set' + part]
					}, true);
				} catch (e) {}
		}
		return dest;
	}

	function extend(obj) {
		var ctor = function(dont) {
			if (fix) define(this, '__proto__', { value: obj });
			if (this.initialize && dont !== ctor.dont)
				return this.initialize.apply(this, arguments);
		}
		ctor.prototype = obj;
		ctor.toString = function() {
			return (this.prototype.initialize || function() {}).toString();
		}
		return ctor;
	}

	function iterator(iter) {
		return !iter
			? function(val) { return val }
			: typeof iter !== 'function'
				? function(val) { return val == iter }
				: iter;
	}

	function each(obj, iter, bind, asArray) {
		try {
			if (obj)
				(asArray || asArray === undefined && isArray(obj)
					? forEach : forIn).call(obj, iterator(iter),
						bind = bind || obj);
		} catch (e) {
			if (e !== Base.stop) throw e;
		}
		return bind;
	}

	function clone(obj) {
		return each(obj, function(val, i) {
			this[i] = val;
		}, new obj.constructor());
	}

	return inject(function() {}, {
		inject: function(src) {
			if (src) {
				var proto = this.prototype,
					base = proto.__proto__ && proto.__proto__.constructor,
					statics = src.statics == true ? src : src.statics;
				if (statics != src)
					inject(proto, src, src.enumerable, base && base.prototype,
							src.preserve, src.generics && this);
				inject(this, statics, true, base, src.preserve);
			}
			for (var i = 1, l = arguments.length; i < l; i++)
				this.inject(arguments[i]);
			return this;
		},

		extend: function(src) {
			var proto = new this(this.dont),
				ctor = extend(proto);
			define(proto, 'constructor',
					{ value: ctor, writable: true, configurable: true });
			ctor.dont = {};
			inject(ctor, this, true);
			return arguments.length ? this.inject.apply(ctor, arguments) : ctor;
		}
	}, true).inject({
		has: has,
		each: each,

		inject: function() {
			for (var i = 0, l = arguments.length; i < l; i++)
				inject(this, arguments[i]);
			return this;
		},

		extend: function() {
			var res = new (extend(this));
			return res.inject.apply(res, arguments);
		},

		each: function(iter, bind) {
			return each(this, iter, bind);
		},

		clone: function() {
			return clone(this);
		},

		statics: {
			each: each,
			clone: clone,
			define: define,
			describe: describe,
			iterator: iterator,

			has: function(obj, name) {
				return has.call(obj, name);
			},

			type: function(obj) {
				return (obj || obj === 0) && (obj._type || typeof obj) || null;
			},

			check: function(obj) {
				return !!(obj || obj === 0);
			},

			pick: function() {
				for (var i = 0, l = arguments.length; i < l; i++)
					if (arguments[i] !== undefined)
						return arguments[i];
				return null;
			},

			stop: {}
		}
	});
}

this.Base = Base.inject({
	generics: true,

	clone: function() {
		return new this.constructor(this);
	},

	toString: function() {
		return '{ ' + Base.each(this, function(value, key) {
			if (key.charAt(0) != '_') {
				var type = typeof value;
				this.push(key + ': ' + (type === 'number'
						? Base.formatNumber(value)
						: type === 'string' ? "'" + value + "'" : value));
			}
		}, []).join(', ') + ' }';
	},

	statics: {
		read: function(list, start, length) {
			var start = start || 0,
				length = length || list.length - start;
			var obj = list[start];
			if (obj instanceof this
					|| this.prototype._readNull && obj == null && length <= 1)
				return obj;
			obj = new this(this.dont);
			return obj.initialize.apply(obj, start > 0 || length < list.length
				? Array.prototype.slice.call(list, start, start + length)
				: list) || obj;
		},

		readAll: function(list, start) {
			var res = [], entry;
			for (var i = start || 0, l = list.length; i < l; i++) {
				res.push(Array.isArray(entry = list[i])
					? this.read(entry, 0)
					: this.read(list, i, 1));
			}
			return res;
		},

		splice: function(list, items, index, remove) {
			var amount = items && items.length,
				append = index === undefined;
			index = append ? list.length : index;
			for (var i = 0; i < amount; i++)
				items[i]._index = index + i;
			if (append) {
				list.push.apply(list, items);
				return [];
			} else {
				var args = [index, remove];
				if (items)
					args.push.apply(args, items);
				var removed = list.splice.apply(list, args);
				for (var i = 0, l = removed.length; i < l; i++)
					delete removed[i]._index;
				for (var i = index + amount, l = list.length; i < l; i++)
					list[i]._index = i;
				return removed;
			}
		},

		merge: function() {
			return Base.each(arguments, function(hash) {
				Base.each(hash, function(value, key) {
					this[key] = value;
				}, this);
			}, new Base(), true); 
		},

		capitalize: function(str) {
			return str.replace(/\b[a-z]/g, function(match) {
				return match.toUpperCase();
			});
		},

		camelize: function(str) {
			return str.replace(/-(\w)/g, function(all, chr) {
				return chr.toUpperCase();
			});
		},

		hyphenate: function(str) {
			return str.replace(/[a-z][A-Z0-9]|[0-9][a-zA-Z]|[A-Z]{2}[a-z]/g,
				function(match) {
					return match.charAt(0) + '-' + match.substring(1);
				}
			).toLowerCase();
		},

		formatNumber: function(num) {
			return (Math.round(num * 100000) / 100000).toString();
		}
	}
});

var PaperScope = this.PaperScope = Base.extend({

	initialize: function(script) {
		paper = this;
		this.view = null;
		this.views = [];
		this.project = null;
		this.projects = [];
		this.tool = null;
		this.tools = [];
		this._id = script && (script.getAttribute('id') || script.src)
				|| ('paperscope-' + (PaperScope._id++));
		if (script)
			script.setAttribute('id', this._id);
		PaperScope._scopes[this._id] = this;
	},

	version: 0.22,

	evaluate: function(code) {
		var res = PaperScript.evaluate(code, this);
		View.updateFocus();
		return res;
	},

	install: function(scope) {
		var that = this;
		Base.each(['project', 'view', 'tool'], function(key) {
			Base.define(scope, key, {
				configurable: true,
				writable: true,
				get: function() {
					return that[key];
				}
			});
		});
		for (var key in this) {
			if (!/^(version|_id|load)/.test(key) && !(key in scope))
				scope[key] = this[key];
		}
	},

	setup: function(canvas) {
		paper = this;
		this.project = new Project();
		if (canvas)
			this.view = new View(canvas);
	},

	clear: function() {
		for (var i = this.projects.length - 1; i >= 0; i--)
			this.projects[i].remove();
		for (var i = this.views.length - 1; i >= 0; i--)
			this.views[i].remove();
		for (var i = this.tools.length - 1; i >= 0; i--)
			this.tools[i].remove();
	},

	remove: function() {
		this.clear();
		delete PaperScope._scopes[this._id];
	},

	_needsRedraw: function() {
		if (!this._redrawNotified) {
			for (var i = this.views.length - 1; i >= 0; i--)
				this.views[i]._redrawNeeded = true;
			this._redrawNotified = true;
		}
	},

	statics: {
		_scopes: {},
		_id: 0,

		get: function(id) {
			if (typeof id === 'object')
				id = id.getAttribute('id');
			return this._scopes[id] || null;
		},

		each: function(iter) {
			Base.each(this._scopes, iter);
		}
	}
});

var PaperScopeItem = Base.extend({

	initialize: function(activate) {
		this._scope = paper;
		this._index = this._scope[this._list].push(this) - 1;
		if (activate || !this._scope[this._reference])
			this.activate();
	},

	activate: function() {
		if (!this._scope)
			return false;
		this._scope[this._reference] = this;
		return true;
	},

	remove: function() {
		if (this._index == null)
			return false;
		Base.splice(this._scope[this._list], null, this._index, 1);
		if (this._scope[this._reference] == this)
			this._scope[this._reference] = null;
		this._scope = null;
		return true;
	}
});

var Point = this.Point = Base.extend({
	initialize: function(arg0, arg1) {
		if (arg1 !== undefined) {
			this.x = arg0;
			this.y = arg1;
		} else if (arg0 !== undefined) {
			if (arg0 == null) {
				this.x = this.y = 0;
			} else if (arg0.x !== undefined) {
				this.x = arg0.x;
				this.y = arg0.y;
			} else if (arg0.width !== undefined) {
				this.x = arg0.width;
				this.y = arg0.height;
			} else if (Array.isArray(arg0)) {
				this.x = arg0[0];
				this.y = arg0.length > 1 ? arg0[1] : arg0[0];
			} else if (arg0.angle !== undefined) {
				this.x = arg0.length;
				this.y = 0;
				this.setAngle(arg0.angle);
			} else if (typeof arg0 === 'number') {
				this.x = this.y = arg0;
			} else {
				this.x = this.y = 0;
			}
		} else {
			this.x = this.y = 0;
		}
	},

	set: function(x, y) {
		this.x = x;
		this.y = y;
		return this;
	},

	clone: function() {
		return Point.create(this.x, this.y);
	},

	toString: function() {
		var format = Base.formatNumber;
		return '{ x: ' + format(this.x) + ', y: ' + format(this.y) + ' }';
	},

	add: function(point) {
		point = Point.read(arguments);
		return Point.create(this.x + point.x, this.y + point.y);
	},

	subtract: function(point) {
		point = Point.read(arguments);
		return Point.create(this.x - point.x, this.y - point.y);
	},

	multiply: function(point) {
		point = Point.read(arguments);
		return Point.create(this.x * point.x, this.y * point.y);
	},

	divide: function(point) {
		point = Point.read(arguments);
		return Point.create(this.x / point.x, this.y / point.y);
	},

	modulo: function(point) {
		point = Point.read(arguments);
		return Point.create(this.x % point.x, this.y % point.y);
	},

	negate: function() {
		return Point.create(-this.x, -this.y);
	},

	transform: function(matrix) {
		return matrix ? matrix._transformPoint(this) : this;
	},

	getDistance: function(point, squared) {
		point = Point.read(arguments);
		var x = point.x - this.x,
			y = point.y - this.y,
			d = x * x + y * y;
		return squared ? d : Math.sqrt(d);
	},

	getLength: function() {
		var l = this.x * this.x + this.y * this.y;
		return arguments[0] ? l : Math.sqrt(l);
	},

	setLength: function(length) {
		if (this.isZero()) {
			var angle = this._angle || 0;
			this.set(
				Math.cos(angle) * length,
				Math.sin(angle) * length
			);
		} else {
			var scale = length / this.getLength();
			if (scale == 0)
				this.getAngle();
			this.set(
				this.x * scale,
				this.y * scale
			);
		}
		return this;
	},

	normalize: function(length) {
		if (length === undefined)
			length = 1;
		var current = this.getLength(),
			scale = current != 0 ? length / current : 0,
			point = Point.create(this.x * scale, this.y * scale);
		point._angle = this._angle;
		return point;
	},

	getAngle: function() {
		return this.getAngleInRadians(arguments[0]) * 180 / Math.PI;
	},

	setAngle: function(angle) {
		angle = this._angle = angle * Math.PI / 180;
		if (!this.isZero()) {
			var length = this.getLength();
			this.set(
				Math.cos(angle) * length,
				Math.sin(angle) * length
			);
		}
		return this;
	},

	getAngleInRadians: function() {
		if (arguments[0] === undefined) {
			if (this._angle == null)
				this._angle = Math.atan2(this.y, this.x);
			return this._angle;
		} else {
			var point = Point.read(arguments),
				div = this.getLength() * point.getLength();
			if (div == 0) {
				return NaN;
			} else {
				return Math.acos(this.dot(point) / div);
			}
		}
	},

	getAngleInDegrees: function() {
		return this.getAngle(arguments[0]);
	},

	getQuadrant: function() {
		return this.x >= 0 ? this.y >= 0 ? 1 : 4 : this.y >= 0 ? 2 : 3;
	},

	getDirectedAngle: function(point) {
		point = Point.read(arguments);
		return Math.atan2(this.cross(point), this.dot(point)) * 180 / Math.PI;
	},

	rotate: function(angle, center) {
		angle = angle * Math.PI / 180;
		var point = center ? this.subtract(center) : this,
			s = Math.sin(angle),
			c = Math.cos(angle);
		point = Point.create(
			point.x * c - point.y * s,
			point.y * c + point.x * s
		);
		return center ? point.add(center) : point;
	},

	equals: function(point) {
		point = Point.read(arguments);
		return this.x == point.x && this.y == point.y;
	},

	isInside: function(rect) {
		return rect.contains(this);
	},

	isClose: function(point, tolerance) {
		return this.getDistance(point) < tolerance;
	},

	isColinear: function(point) {
		return this.cross(point) < Numerical.TOLERANCE;
	},

	isOrthogonal: function(point) {
		return this.dot(point) < Numerical.TOLERANCE;
	},

	isZero: function() {
		return this.x == 0 && this.y == 0;
	},

	isNaN: function() {
		return isNaN(this.x) || isNaN(this.y);
	},

	dot: function(point) {
		point = Point.read(arguments);
		return this.x * point.x + this.y * point.y;
	},

	cross: function(point) {
		point = Point.read(arguments);
		return this.x * point.y - this.y * point.x;
	},

	project: function(point) {
		point = Point.read(arguments);
		if (point.isZero()) {
			return Point.create(0, 0);
		} else {
			var scale = this.dot(point) / point.dot(point);
			return Point.create(
				point.x * scale,
				point.y * scale
			);
		}
	},

	statics: {
		create: function(x, y) {
			var point = new Point(Point.dont);
			point.x = x;
			point.y = y;
			return point;
		},

		min: function(point1, point2) {
			point1 = Point.read(arguments, 0, 1);
			point2 = Point.read(arguments, 1, 1);
			return Point.create(
				Math.min(point1.x, point2.x),
				Math.min(point1.y, point2.y)
			);
		},

		max: function(point1, point2) {
			point1 = Point.read(arguments, 0, 1);
			point2 = Point.read(arguments, 1, 1);
			return Point.create(
				Math.max(point1.x, point2.x),
				Math.max(point1.y, point2.y)
			);
		},

		random: function() {
			return Point.create(Math.random(), Math.random());
		}
	}
}, new function() { 

	return Base.each(['round', 'ceil', 'floor', 'abs'], function(name) {
		var op = Math[name];
		this[name] = function() {
			return Point.create(op(this.x), op(this.y));
		};
	}, {});
});

var LinkedPoint = Point.extend({
	set: function(x, y, dontNotify) {
		this._x = x;
		this._y = y;
		if (!dontNotify)
			this._owner[this._setter](this);
		return this;
	},

	getX: function() {
		return this._x;
	},

	setX: function(x) {
		this._x = x;
		this._owner[this._setter](this);
	},

	getY: function() {
		return this._y;
	},

	setY: function(y) {
		this._y = y;
		this._owner[this._setter](this);
	},

	statics: {
		create: function(owner, setter, x, y, dontLink) {
			if (dontLink)
				return Point.create(x, y);
			var point = new LinkedPoint(LinkedPoint.dont);
			point._x = x;
			point._y = y;
			point._owner = owner;
			point._setter = setter;
			return point;
		}
	}
});

var Size = this.Size = Base.extend({
	initialize: function(arg0, arg1) {
		if (arg1 !== undefined) {
			this.width = arg0;
			this.height = arg1;
		} else if (arg0 !== undefined) {
			if (arg0 == null) {
				this.width = this.height = 0;
			} else if (arg0.width !== undefined) {
				this.width = arg0.width;
				this.height = arg0.height;
			} else if (arg0.x !== undefined) {
				this.width = arg0.x;
				this.height = arg0.y;
			} else if (Array.isArray(arg0)) {
				this.width = arg0[0];
				this.height = arg0.length > 1 ? arg0[1] : arg0[0];
			} else if (typeof arg0 === 'number') {
				this.width = this.height = arg0;
			} else {
				this.width = this.height = 0;
			}
		} else {
			this.width = this.height = 0;
		}
	},

	toString: function() {
		var format = Base.formatNumber;
		return '{ width: ' + format(this.width)
				+ ', height: ' + format(this.height) + ' }';
	},

	set: function(width, height) {
		this.width = width;
		this.height = height;
		return this;
	},

	clone: function() {
		return Size.create(this.width, this.height);
	},

	add: function(size) {
		size = Size.read(arguments);
		return Size.create(this.width + size.width, this.height + size.height);
	},

	subtract: function(size) {
		size = Size.read(arguments);
		return Size.create(this.width - size.width, this.height - size.height);
	},

	multiply: function(size) {
		size = Size.read(arguments);
		return Size.create(this.width * size.width, this.height * size.height);
	},

	divide: function(size) {
		size = Size.read(arguments);
		return Size.create(this.width / size.width, this.height / size.height);
	},

	modulo: function(size) {
		size = Size.read(arguments);
		return Size.create(this.width % size.width, this.height % size.height);
	},

	negate: function() {
		return Size.create(-this.width, -this.height);
	},

	equals: function(size) {
		size = Size.read(arguments);
		return this.width == size.width && this.height == size.height;
	},

	isZero: function() {
		return this.width == 0 && this.height == 0;
	},

	isNaN: function() {
		return isNaN(this.width) || isNaN(this.height);
	},

	statics: {
		create: function(width, height) {
			return new Size(Size.dont).set(width, height);
		},

		min: function(size1, size2) {
			return Size.create(
				Math.min(size1.width, size2.width),
				Math.min(size1.height, size2.height));
		},

		max: function(size1, size2) {
			return Size.create(
				Math.max(size1.width, size2.width),
				Math.max(size1.height, size2.height));
		},

		random: function() {
			return Size.create(Math.random(), Math.random());
		}
	}
}, new function() { 

	return Base.each(['round', 'ceil', 'floor', 'abs'], function(name) {
		var op = Math[name];
		this[name] = function() {
			return Size.create(op(this.width), op(this.height));
		};
	}, {});
});

var LinkedSize = Size.extend({
	set: function(width, height, dontNotify) {
		this._width = width;
		this._height = height;
		if (!dontNotify)
			this._owner[this._setter](this);
		return this;
	},

	getWidth: function() {
		return this._width;
	},

	setWidth: function(width) {
		this._width = width;
		this._owner[this._setter](this);
	},

	getHeight: function() {
		return this._height;
	},

	setHeight: function(height) {
		this._height = height;
		this._owner[this._setter](this);
	},

	statics: {
		create: function(owner, setter, width, height, dontLink) {
			if (dontLink)
				return Size.create(width, height);
			var size = new LinkedSize(LinkedSize.dont);
			size._width = width;
			size._height = height;
			size._owner = owner;
			size._setter = setter;
			return size;
		}
	}
});

var Rectangle = this.Rectangle = Base.extend({
	initialize: function(arg0, arg1, arg2, arg3) {
		if (arguments.length == 4) {
			this.x = arg0;
			this.y = arg1;
			this.width = arg2;
			this.height = arg3;
		} else if (arguments.length == 2) {
			if (arg1 && arg1.x !== undefined) {
				var point1 = Point.read(arguments, 0, 1);
				var point2 = Point.read(arguments, 1, 1);
				this.x = point1.x;
				this.y = point1.y;
				this.width = point2.x - point1.x;
				this.height = point2.y - point1.y;
				if (this.width < 0) {
					this.x = point2.x;
					this.width = -this.width;
				}
				if (this.height < 0) {
					this.y = point2.y;
					this.height = -this.height;
				}
			} else {
				var point = Point.read(arguments, 0, 1);
				var size = Size.read(arguments, 1, 1);
				this.x = point.x;
				this.y = point.y;
				this.width = size.width;
				this.height = size.height;
			}
		} else if (arg0) {
			this.x = arg0.x || 0;
			this.y = arg0.y || 0;
			this.width = arg0.width || 0;
			this.height = arg0.height || 0;
		} else {
			this.x = this.y = this.width = this.height = 0;
		}
	},

	set: function(x, y, width, height) {
		this.x = x;
		this.y = y;
		this.width = width;
		this.height = height;
		return this;
	},

	getPoint: function() {
		return LinkedPoint.create(this, 'setPoint', this.x, this.y,
				arguments[0]);
	},

	setPoint: function(point) {
		point = Point.read(arguments);
		this.x = point.x;
		this.y = point.y;
		return this;
	},

	getSize: function() {
		return LinkedSize.create(this, 'setSize', this.width, this.height,
				arguments[0]);
	},

	setSize: function(size) {
		size = Size.read(arguments);
		this.width = size.width;
		this.height = size.height;
		return this;
	},

	getLeft: function() {
		return this.x;
	},

	setLeft: function(left) {
		this.width -= left - this.x;
		this.x = left;
		return this;
	},

	getTop: function() {
		return this.y;
	},

	setTop: function(top) {
		this.height -= top - this.y;
		this.y = top;
		return this;
	},

	getRight: function() {
		return this.x + this.width;
	},

	setRight: function(right) {
		this.width = right - this.x;
		return this;
	},

	getBottom: function() {
		return this.y + this.height;
	},

	setBottom: function(bottom) {
		this.height = bottom - this.y;
		return this;
	},

	getCenterX: function() {
		return this.x + this.width * 0.5;
	},

	setCenterX: function(x) {
		this.x = x - this.width * 0.5;
		return this;
	},

	getCenterY: function() {
		return this.y + this.height * 0.5;
	},

	setCenterY: function(y) {
		this.y = y - this.height * 0.5;
		return this;
	},

	getCenter: function() {
		return LinkedPoint.create(this, 'setCenter',
				this.getCenterX(), this.getCenterY(), arguments[0]);
	},

	setCenter: function(point) {
		point = Point.read(arguments);
		return this.setCenterX(point.x).setCenterY(point.y);
	},

	equals: function(rect) {
		rect = Rectangle.read(arguments);
		return this.x == rect.x && this.y == rect.y
				&& this.width == rect.width && this.height == rect.height;
	},

	isEmpty: function() {
		return this.width == 0 || this.height == 0;
	},

	toString: function() {
		var format = Base.formatNumber;
		return '{ x: ' + format(this.x)
				+ ', y: ' + format(this.y)
				+ ', width: ' + format(this.width)
				+ ', height: ' + format(this.height)
				+ ' }';
	},

	contains: function(arg) {
		return arg && arg.width !== undefined
				|| (Array.isArray(arg) ? arg : arguments).length == 4
				? this._containsRectangle(Rectangle.read(arguments))
				: this._containsPoint(Point.read(arguments));
	},

	_containsPoint: function(point) {
		var x = point.x,
			y = point.y;
		return x >= this.x && y >= this.y
				&& x <= this.x + this.width
				&& y <= this.y + this.height;
	},

	_containsRectangle: function(rect) {
		var x = rect.x,
			y = rect.y;
		return x >= this.x && y >= this.y
				&& x + rect.width <= this.x + this.width
				&& y + rect.height <= this.y + this.height;
	},

	intersects: function(rect) {
		rect = Rectangle.read(arguments);
		return rect.x + rect.width > this.x
				&& rect.y + rect.height > this.y
				&& rect.x < this.x + this.width
				&& rect.y < this.y + this.height;
	},

	intersect: function(rect) {
		rect = Rectangle.read(arguments);
		var x1 = Math.max(this.x, rect.x),
			y1 = Math.max(this.y, rect.y),
			x2 = Math.min(this.x + this.width, rect.x + rect.width),
			y2 = Math.min(this.y + this.height, rect.y + rect.height);
		return Rectangle.create(x1, y1, x2 - x1, y2 - y1);
	},

	unite: function(rect) {
		rect = Rectangle.read(arguments);
		var x1 = Math.min(this.x, rect.x),
			y1 = Math.min(this.y, rect.y),
			x2 = Math.max(this.x + this.width, rect.x + rect.width),
			y2 = Math.max(this.y + this.height, rect.y + rect.height);
		return Rectangle.create(x1, y1, x2 - x1, y2 - y1);
	},

	include: function(point) {
		point = Point.read(arguments);
		var x1 = Math.min(this.x, point.x),
			y1 = Math.min(this.y, point.y),
			x2 = Math.max(this.x + this.width, point.x),
			y2 = Math.max(this.y + this.height, point.y);
		return Rectangle.create(x1, y1, x2 - x1, y2 - y1);
	},

	expand: function(hor, ver) {
		if (ver === undefined)
			ver = hor;
		return Rectangle.create(this.x - hor / 2, this.y - ver / 2,
				this.width + hor, this.height + ver);
	},

	scale: function(hor, ver) {
		return this.expand(this.width * hor - this.width,
				this.height * (ver === undefined ? hor : ver) - this.height);
	},

	statics: {
		create: function(x, y, width, height) {
			return new Rectangle(Rectangle.dont).set(x, y, width, height);
		}
	}
}, new function() {
	return Base.each([
			['Top', 'Left'], ['Top', 'Right'],
			['Bottom', 'Left'], ['Bottom', 'Right'],
			['Left', 'Center'], ['Top', 'Center'],
			['Right', 'Center'], ['Bottom', 'Center']
		],
		function(parts, index) {
			var part = parts.join('');
			var xFirst = /^[RL]/.test(part);
			if (index >= 4)
				parts[1] += xFirst ? 'Y' : 'X';
			var x = parts[xFirst ? 0 : 1],
				y = parts[xFirst ? 1 : 0],
				getX = 'get' + x,
				getY = 'get' + y,
				setX = 'set' + x,
				setY = 'set' + y,
				get = 'get' + part,
				set = 'set' + part;
			this[get] = function() {
				return LinkedPoint.create(this, set,
						this[getX](), this[getY](), arguments[0]);
			};
			this[set] = function(point) {
				point = Point.read(arguments);
				return this[setX](point.x)[setY](point.y);
			};
		}, {});
});

var LinkedRectangle = Rectangle.extend({
	set: function(x, y, width, height, dontNotify) {
		this._x = x;
		this._y = y;
		this._width = width;
		this._height = height;
		if (!dontNotify)
			this._owner[this._setter](this);
		return this;
	},

	statics: {
		create: function(owner, setter, x, y, width, height) {
			var rect = new LinkedRectangle(LinkedRectangle.dont).set(
					x, y, width, height, true);
			rect._owner = owner;
			rect._setter = setter;
			return rect;
		}
	}
}, new function() {
	var proto = Rectangle.prototype;

	return Base.each(['x', 'y', 'width', 'height'], function(key) {
		var part = Base.capitalize(key);
		var internal = '_' + key;
		this['get' + part] = function() {
			return this[internal];
		};

		this['set' + part] = function(value) {
			this[internal] = value;
			if (!this._dontNotify)
				this._owner[this._setter](this);
		};
	}, Base.each(['Point', 'Size', 'Center',
			'Left', 'Top', 'Right', 'Bottom', 'CenterX', 'CenterY',
			'TopLeft', 'TopRight', 'BottomLeft', 'BottomRight',
			'LeftCenter', 'TopCenter', 'RightCenter', 'BottomCenter'],
		function(key) {
			var name = 'set' + key;
			this[name] = function(value) {
				this._dontNotify = true;
				proto[name].apply(this, arguments);
				delete this._dontNotify;
				this._owner[this._setter](this);
				return this;
			};
		}, {})
	);
});

var Matrix = this.Matrix = Base.extend({
	initialize: function(arg) {
		var count = arguments.length,
			ok = true;
		if (count == 6) {
			this.set.apply(this, arguments);
		} else if (count == 1) {
			if (arg instanceof Matrix) {
				this.set(arg._a, arg._c, arg._b, arg._d, arg._tx, arg._ty);
			} else if (Array.isArray(arg)) {
				this.set.apply(this, arg);
			} else {
				ok = false;
			}
		} else if (count == 0) {
			this._a = this._d = 1;
			this._c = this._b = this._tx = this._ty = 0;
		} else {
			ok = false;
		}
		if (!ok)
			throw new Error('Unsupported matrix parameters');
	},

	clone: function() {
		return Matrix.create(this._a, this._c, this._b, this._d,
				this._tx, this._ty);
	},

	set: function(a, c, b, d, tx, ty) {
		this._a = a;
		this._c = c;
		this._b = b;
		this._d = d;
		this._tx = tx;
		this._ty = ty;
		return this;
	},

	scale: function( hor, ver, center) {
		if (arguments.length < 2 || typeof ver === 'object') {
			center = Point.read(arguments, 1);
			ver = hor;
		} else {
			center = Point.read(arguments, 2);
		}
		if (center)
			this.translate(center);
		this._a *= hor;
		this._c *= hor;
		this._b *= ver;
		this._d *= ver;
		if (center)
			this.translate(center.negate());
		return this;
	},

	translate: function(point) {
		point = Point.read(arguments);
		var x = point.x, y = point.y;
		this._tx += x * this._a + y * this._b;
		this._ty += x * this._c + y * this._d;
		return this;
	},

	rotate: function(angle, center) {
		return this.concatenate(
				Matrix.getRotateInstance.apply(Matrix, arguments));
	},

	shear: function( hor, ver, center) {
		if (arguments.length < 2 || typeof ver === 'object') {
			center = Point.read(arguments, 1);
			ver = hor;
		} else {
			center = Point.read(arguments, 2);
		}
		if (center)
			this.translate(center);
		var a = this._a,
			c = this._c;
		this._a += ver * this._b;
		this._c += ver * this._d;
		this._b += hor * a;
		this._d += hor * c;
		if (center)
			this.translate(center.negate());
		return this;
	},

	toString: function() {
		var format = Base.formatNumber;
		return '[[' + [format(this._a), format(this._b),
					format(this._tx)].join(', ') + '], ['
				+ [format(this._c), format(this._d),
					format(this._ty)].join(', ') + ']]';
	},

	getValues: function() {
		return [ this._a, this._c, this._b, this._d, this._tx, this._ty ];
	},

	concatenate: function(mx) {
		var a = this._a,
			b = this._b,
			c = this._c,
			d = this._d;
		this._a = mx._a * a + mx._c * b;
		this._b = mx._b * a + mx._d * b;
		this._tx += mx._tx * a + mx._ty * b;
		this._c = mx._a * c + mx._c * d;
		this._d = mx._b * c + mx._d * d;
		this._ty += mx._tx * c + mx._ty * d;
		return this;
	},

	preConcatenate: function(mx) {
		var a = this._a,
			b = this._b,
			c = this._c,
			d = this._d,
			tx = this._tx,
			ty = this._ty;
		this._a = mx._a * a + mx._b * c;
		this._c = mx._c * a + mx._d * c;
		this._b = mx._a * b + mx._b * d;
		this._d = mx._c * b + mx._d * d;
		this._tx = mx._a * tx + mx._b * ty + mx._tx;
		this._ty = mx._c * tx + mx._d * ty + mx._ty;
		return this;
	},

	transform: function( src, srcOff, dst, dstOff, numPts) {
		return arguments.length < 5
			? this._transformPoint(Point.read(arguments))
			: this._transformCoordinates(src, srcOff, dst, dstOff, numPts);
	},

	_transformPoint: function(point, dest, dontNotify) {
		var x = point.x,
			y = point.y;
		if (!dest)
			dest = new Point(Point.dont);
		return dest.set(
			x * this._a + y * this._b + this._tx,
			x * this._c + y * this._d + this._ty,
			dontNotify
		);
	},

	_transformCoordinates: function(src, srcOff, dst, dstOff, numPts) {
		var i = srcOff, j = dstOff,
			srcEnd = srcOff + 2 * numPts;
		while (i < srcEnd) {
			var x = src[i++];
			var y = src[i++];
			dst[j++] = x * this._a + y * this._b + this._tx;
			dst[j++] = x * this._c + y * this._d + this._ty;
		}
		return dst;
	},

	_transformCorners: function(rect) {
		var x1 = rect.x,
			y1 = rect.y,
			x2 = x1 + rect.width,
			y2 = y1 + rect.height,
			coords = [ x1, y1, x2, y1, x2, y2, x1, y2 ];
		return this._transformCoordinates(coords, 0, coords, 0, 4);
	},

	_transformBounds: function(bounds) {
		var coords = this._transformCorners(bounds),
			min = coords.slice(0, 2),
			max = coords.slice(0);
		for (var i = 2; i < 8; i++) {
			var val = coords[i],
				j = i & 1;
			if (val < min[j])
				min[j] = val;
			else if (val > max[j])
				max[j] = val;
		}
		return Rectangle.create(min[0], min[1],
				max[0] - min[0], max[1] - min[1]);
	},

	inverseTransform: function(point) {
		return this._inverseTransform(Point.read(arguments));
	},

	_getDeterminant: function() {
		var det = this._a * this._d - this._b * this._c;
		return isFinite(det) && Math.abs(det) > Numerical.EPSILON
				&& isFinite(this._tx) && isFinite(this._ty)
				? det : null;
	},

	_inverseTransform: function(point, dest, dontNotify) {
		var det = this._getDeterminant();
		if (!det)
			return null;
		var x = point.x - this._tx,
			y = point.y - this._ty;
		if (!dest)
			dest = new Point(Point.dont);
		return dest.set(
			(x * this._d - y * this._b) / det,
			(y * this._a - x * this._c) / det,
			dontNotify
		);
	},

	getTranslation: function() {
		return new Point(this._tx, this._ty);
	},

	getScaling: function() {
		var hor = Math.sqrt(this._a * this._a + this._c * this._c),
			ver = Math.sqrt(this._b * this._b + this._d * this._d);
		return new Point(this._a < 0 ? -hor : hor, this._b < 0 ? -ver : ver);
	},

	getRotation: function() {
		var angle1 = -Math.atan2(this._b, this._d),
			angle2 = Math.atan2(this._c, this._a);
		return Math.abs(angle1 - angle2) < Numerical.TOLERANCE
				? angle1 * 180 / Math.PI : undefined;
	},

	isIdentity: function() {
		return this._a == 1 && this._c == 0 && this._b == 0 && this._d == 1
				&& this._tx == 0 && this._ty == 0;
	},

	isInvertible: function() {
		return !!this._getDeterminant();
	},

	isSingular: function() {
		return !this._getDeterminant();
	},

	createInverse: function() {
		var det = this._getDeterminant();
		return det && Matrix.create(
				this._d / det,
				-this._c / det,
				-this._b / det,
				this._a / det,
				(this._b * this._ty - this._d * this._tx) / det,
				(this._c * this._tx - this._a * this._ty) / det);
	},

	createShiftless: function() {
		return Matrix.create(this._a, this._c, this._b, this._d, 0, 0);
	},

	setToScale: function(hor, ver) {
		return this.set(hor, 0, 0, ver, 0, 0);
	},

	setToTranslation: function(delta) {
		delta = Point.read(arguments);
		return this.set(1, 0, 0, 1, delta.x, delta.y);
	},

	setToShear: function(hor, ver) {
		return this.set(1, ver, hor, 1, 0, 0);
	},

	setToRotation: function(angle, center) {
		center = Point.read(arguments, 1);
		angle = angle * Math.PI / 180;
		var x = center.x,
			y = center.y,
			cos = Math.cos(angle),
			sin = Math.sin(angle);
		return this.set(cos, sin, -sin, cos,
				x - x * cos + y * sin,
				y - x * sin - y * cos);
	},

	applyToContext: function(ctx, reset) {
		ctx[reset ? 'setTransform' : 'transform'](
				this._a, this._c, this._b, this._d, this._tx, this._ty);
		return this;
	},

	statics: {
		create: function(a, c, b, d, tx, ty) {
			return new Matrix(Matrix.dont).set(a, c, b, d, tx, ty);
		},

		getScaleInstance: function(hor, ver) {
			var mx = new Matrix();
			return mx.setToScale.apply(mx, arguments);
		},

		getTranslateInstance: function(delta) {
			var mx = new Matrix();
			return mx.setToTranslation.apply(mx, arguments);
		},

		getShearInstance: function(hor, ver, center) {
			var mx = new Matrix();
			return mx.setToShear.apply(mx, arguments);
		},

		getRotateInstance: function(angle, center) {
			var mx = new Matrix();
			return mx.setToRotation.apply(mx, arguments);
		}
	}
}, new function() {
	return Base.each({
		scaleX: '_a',
		scaleY: '_d',
		translateX: '_tx',
		translateY: '_ty',
		shearX: '_b',
		shearY: '_c'
	}, function(prop, name) {
		name = Base.capitalize(name);
		this['get' + name] = function() {
			return this[prop];
		};
		this['set' + name] = function(value) {
			this[prop] = value;
		};
	}, {});
});

var Line = this.Line = Base.extend({
	initialize: function(point1, point2, infinite) {
		point1 = Point.read(arguments, 0, 1);
		point2 = Point.read(arguments, 1, 1);
		if (arguments.length == 3) {
			this.point = point1;
			this.vector = point2.subtract(point1);
			this.infinite = infinite;
		} else {
			this.point = point1;
			this.vector = point2;
			this.infinite = true;
		}
	},

	intersect: function(line) {
		var cross = this.vector.cross(line.vector);
		if (Math.abs(cross) <= Numerical.EPSILON)
			return null;
		var v = line.point.subtract(this.point),
			t1 = v.cross(line.vector) / cross,
			t2 = v.cross(this.vector) / cross;
		return (this.infinite || 0 <= t1 && t1 <= 1)
				&& (line.infinite || 0 <= t2 && t2 <= 1)
			? this.point.add(this.vector.multiply(t1)) : null;
	},

	getSide: function(point) {
		var v1 = this.vector,
			v2 = point.subtract(this.point),
			ccw = v2.cross(v1);
		if (ccw == 0) {
			ccw = v2.dot(v1);
			if (ccw > 0) {
				ccw = v2.subtract(v1).dot(v1);
				if (ccw < 0)
				    ccw = 0;
			}
		}
		return ccw < 0 ? -1 : ccw > 0 ? 1 : 0;
	},

	getDistance: function(point) {
		var m = this.vector.y / this.vector.x, 
			b = this.point.y - (m * this.point.x); 
		var dist = Math.abs(point.y - (m * point.x) - b) / Math.sqrt(m * m + 1);
		return this.infinite ? dist : Math.min(dist,
				point.getDistance(this.point),
				point.getDistance(this.point.add(this.vector)));
	}
});

var Project = this.Project = PaperScopeItem.extend({
	_list: 'projects',
	_reference: 'project',

	initialize: function() {
		this.base(true);
		this._currentStyle = new PathStyle();
		this._selectedItems = {};
		this._selectedItemCount = 0;
		this.layers = [];
		this.symbols = [];
		this.activeLayer = new Layer();
	},

	_needsRedraw: function() {
		if (this._scope)
			this._scope._needsRedraw();
	},

	getCurrentStyle: function() {
		return this._currentStyle;
	},

	setCurrentStyle: function(style) {
		this._currentStyle.initialize(style);
	},

	getIndex: function() {
		return this._index;
	},

	getSelectedItems: function() {
		var items = [];
		Base.each(this._selectedItems, function(item) {
			items.push(item);
		});
		return items;
	},

	_updateSelection: function(item) {
		if (item._selected) {
			this._selectedItemCount++;
			this._selectedItems[item.getId()] = item;
		} else {
			this._selectedItemCount--;
			delete this._selectedItems[item.getId()];
		}
	},

	selectAll: function() {
		for (var i = 0, l = this.layers.length; i < l; i++)
			this.layers[i].setSelected(true);
	},

	deselectAll: function() {
		for (var i in this._selectedItems)
			this._selectedItems[i].setSelected(false);
	},

	hitTest: function(point, options) {
		options = HitResult.getOptions(point, options);
		point = options.point;
		for (var i = this.layers.length - 1; i >= 0; i--) {
			var res = this.layers[i].hitTest(point, options);
			if (res) return res;
		}
		return null;
	},

	draw: function(ctx) {
		ctx.save();
		var param = { offset: new Point(0, 0) };
		for (var i = 0, l = this.layers.length; i < l; i++)
			Item.draw(this.layers[i], ctx, param);
		ctx.restore();

		if (this._selectedItemCount > 0) {
			ctx.save();
			ctx.strokeWidth = 1;
			ctx.strokeStyle = ctx.fillStyle = '#009dec';
			param = { selection: true };
			Base.each(this._selectedItems, function(item) {
				item.draw(ctx, param);
			});
			ctx.restore();
		}
	}
});

var Symbol = this.Symbol = Base.extend({
	initialize: function(item) {
		this.project = paper.project;
		this.project.symbols.push(this);
		this.setDefinition(item);
		this._instances = {};
	},

	_changed: function(flags) {
		Base.each(this._instances, function(item) {
			item._changed(flags);
		});
	},

	getDefinition: function() {
		return this._definition;
	},

	setDefinition: function(item) {
		if (item._parentSymbol)
			item = item.clone();
		if (this._definition)
			delete this._definition._parentSymbol;
		this._definition = item;
		item.remove();
		item.setPosition(new Point());
		item._parentSymbol = this;
		this._changed(Change.GEOMETRY);
	},

	place: function(position) {
		return new PlacedSymbol(this, position);
	},

	clone: function() {
	 	return new Symbol(this._definition.clone());
	}
});

var ChangeFlag = {
	APPEARANCE: 1,
	HIERARCHY: 2,
	GEOMETRY: 4,
	STROKE: 8,
	STYLE: 16,
	ATTRIBUTE: 32,
	CONTENT: 64,
	PIXELS: 128,
	CLIPPING: 256
};

var Change = {
	HIERARCHY: ChangeFlag.HIERARCHY | ChangeFlag.APPEARANCE,
	GEOMETRY: ChangeFlag.GEOMETRY | ChangeFlag.APPEARANCE,
	STROKE: ChangeFlag.STROKE | ChangeFlag.STYLE | ChangeFlag.APPEARANCE,
	STYLE: ChangeFlag.STYLE | ChangeFlag.APPEARANCE,
	ATTRIBUTE: ChangeFlag.ATTRIBUTE | ChangeFlag.APPEARANCE,
	CONTENT: ChangeFlag.CONTENT | ChangeFlag.APPEARANCE,
	PIXELS: ChangeFlag.PIXELS | ChangeFlag.APPEARANCE
};

var Item = this.Item = Base.extend({
	initialize: function() {
		this._id = ++Item._id;
		if (!this._project)
			paper.project.activeLayer.addChild(this);
		this._style = PathStyle.create(this);
		this.setStyle(this._project.getCurrentStyle());
	},

	_changed: function(flags) {
		if (flags & ChangeFlag.GEOMETRY) {
			delete this._bounds;
			delete this._position;
		}
		if (flags & ChangeFlag.APPEARANCE) {
			this._project._needsRedraw();
		}
		if (this._parentSymbol)
			this._parentSymbol._changed(flags);
		if (this._project._changes) {
			var entry = this._project._changesById[this._id];
			if (entry) {
				entry.flags |= flags;
			} else {
				entry = { item: this, flags: flags };
				this._project._changesById[this._id] = entry;
				this._project._changes.push(entry);
			}
		}
	},

	getId: function() {
		return this._id;
	},

	getName: function() {
		return this._name;
	},

	setName: function(name) {

		if (this._name)
			this._removeFromNamed();
		this._name = name || undefined;
		if (name) {
			var children = this._parent._children,
				namedChildren = this._parent._namedChildren;
			(namedChildren[name] = namedChildren[name] || []).push(this);
			children[name] = this;
		}
		this._changed(ChangeFlag.ATTRIBUTE);
	},

	getPosition: function() {
		var pos = this._position
				|| (this._position = this.getBounds().getCenter());
		return LinkedPoint.create(this, 'setPosition', pos._x, pos._y);
	},

	setPosition: function(point) {
		this.translate(Point.read(arguments).subtract(this.getPosition()));
	},

	getStyle: function() {
		return this._style;
	},

	setStyle: function(style) {
		this._style.initialize(style);
	},

	statics: {
		_id: 0
	}
}, new function() { 
	return Base.each(['locked', 'visible', 'blendMode', 'opacity', 'guide'],
		function(name) {
			var part = Base.capitalize(name),
				name = '_' + name;
			this['get' + part] = function() {
				return this[name];
			};
			this['set' + part] = function(value) {
				if (value != this[name]) {
					this[name] = value;
					this._changed(name === '_locked'
							? ChangeFlag.ATTRIBUTE : Change.ATTRIBUTE);
				}
			};
		}, {});
}, {

	_locked: false,

	_visible: true,

	_blendMode: 'normal',

	_opacity: 1,

	_guide: false,

	isSelected: function() {
		if (this._children) {
			for (var i = 0, l = this._children.length; i < l; i++)
				if (this._children[i].isSelected())
					return true;
		}
		return this._selected;
	},

	setSelected: function(selected) {
		if (this._children) {
			for (var i = 0, l = this._children.length; i < l; i++) {
				this._children[i].setSelected(selected);
			}
		} else if ((selected = !!selected) != this._selected) {
			this._selected = selected;
			this._project._updateSelection(this);
			this._changed(Change.ATTRIBUTE);
		}
	},

	_selected: false,

	isFullySelected: function() {
		if (this._children && this._selected) {
			for (var i = 0, l = this._children.length; i < l; i++)
				if (!this._children[i].isFullySelected())
					return false;
			return true;
		}
		return this._selected;
	},

	setFullySelected: function(selected) {
		if (this._children) {
			for (var i = 0, l = this._children.length; i < l; i++) {
				this._children[i].setFullySelected(selected);
			}
		}
		this.setSelected(selected);
	},

	isClipMask: function() {
		return this._clipMask;
	},

	setClipMask: function(clipMask) {
		if (this._clipMask != (clipMask = !!clipMask)) {
			this._clipMask = clipMask;
			if (clipMask) {
				this.setFillColor(null);
				this.setStrokeColor(null);
			}
			this._changed(Change.ATTRIBUTE);
			if (this._parent)
				this._parent._changed(ChangeFlag.CLIPPING);
		}
	},

	_clipMask: false,

	getProject: function() {
		return this._project;
	},

	_setProject: function(project) {
		if (this._project != project) {
			this._project = project;
			if (this._children) {
				for (var i = 0, l = this._children.length; i < l; i++) {
					this._children[i]._setProject(project);
				}
			}
		}
	},

	getLayer: function() {
		var parent = this;
		while (parent = parent._parent) {
			if (parent instanceof Layer)
				return parent;
		}
		return null;
	},

	getParent: function() {
		return this._parent;
	},

	getChildren: function() {
		return this._children;
	},

	setChildren: function(items) {
		this.removeChildren();
		this.addChildren(items);
	},

	getFirstChild: function() {
		return this._children && this._children[0] || null;
	},

	getLastChild: function() {
		return this._children && this._children[this._children.length - 1]
				|| null;
	},

	getNextSibling: function() {
		return this._parent && this._parent._children[this._index + 1] || null;
	},

	getPreviousSibling: function() {
		return this._parent && this._parent._children[this._index - 1] || null;
	},

	getIndex: function() {
		return this._index;
	},

	clone: function() {
		return this._clone(new this.constructor());
	},

	_clone: function(copy) {
		copy.setStyle(this._style);
		if (this._children) {
			for (var i = 0, l = this._children.length; i < l; i++)
				copy.addChild(this._children[i].clone());
		}
		var keys = ['_locked', '_visible', '_blendMode', '_opacity',
				'_clipMask', '_guide'];
		for (var i = 0, l = keys.length; i < l; i++) {
			var key = keys[i];
			if (this.hasOwnProperty(key))
				copy[key] = this[key];
		}
		copy.setSelected(this._selected);
		if (this._name)
			copy.setName(this._name);
		return copy;
	},

	copyTo: function(itemOrProject) {
		var copy = this.clone();
		if (itemOrProject.layers) {
			itemOrProject.activeLayer.addChild(copy);
		} else {
			itemOrProject.addChild(copy);
		}
		return copy;
	},

	rasterize: function(resolution) {
		var bounds = this.getStrokeBounds(),
			scale = (resolution || 72) / 72,
			canvas = CanvasProvider.getCanvas(bounds.getSize().multiply(scale)),
			ctx = canvas.getContext('2d'),
			matrix = new Matrix().scale(scale).translate(-bounds.x, -bounds.y);
		matrix.applyToContext(ctx);
		this.draw(ctx, {});
		var raster = new Raster(canvas);
		raster.setBounds(bounds);
		return raster;
	},

	hitTest: function(point, options, matrix) {
		options = HitResult.getOptions(point, options);
		point = options.point;
		if (!this._children && !this.getRoughBounds(matrix)
				.expand(options.tolerance)._containsPoint(point))
			return null;
		if ((options.center || options.bounds) &&
				!(this instanceof Layer && !this._parent)) {
			var bounds = this.getBounds(),
				that = this,
				points = ['TopLeft', 'TopRight', 'BottomLeft', 'BottomRight',
				'LeftCenter', 'TopCenter', 'RightCenter', 'BottomCenter'],
				res;
			function checkBounds(type, part) {
				var pt = bounds['get' + part]().transform(matrix);
				if (point.getDistance(pt) < options.tolerance)
					return new HitResult(type, that,
							{ name: Base.hyphenate(part), point: pt });
			}
			if (options.center && (res = checkBounds('center', 'Center')))
				return res;
			if (options.bounds) {
				for (var i = 0; i < 8; i++)
					if (res = checkBounds('bounds', points[i]))
						return res;
			}
		}

		return this._children || !(options.guides && !this._guide
				|| options.selected && !this._selected)
					? this._hitTest(point, options, matrix) : null;
	},

	_hitTest: function(point, options, matrix) {
		if (this._children) {
			for (var i = this._children.length - 1; i >= 0; i--) {
				var res = this._children[i].hitTest(point, options, matrix);
				if (res) return res;
			}
		}
	},

	addChild: function(item) {
		return this.insertChild(undefined, item);
	},

	insertChild: function(index, item) {
		if (this._children) {
			item._remove(false, true);
			Base.splice(this._children, [item], index, 0);
			item._parent = this;
			item._setProject(this._project);
			if (item._name)
				item.setName(item._name);
			this._changed(Change.HIERARCHY);
			return true;
		}
		return false;
	},

	addChildren: function(items) {
		for (var i = 0, l = items && items.length; i < l; i++)
			this.insertChild(undefined, items[i]);
	},

	insertChildren: function(index, items) {
		for (var i = 0, l = items && items.length; i < l; i++) {
			if (this.insertChild(index, items[i]))
				index++;
		}
	},

	insertAbove: function(item) {
		return item._parent && item._parent.insertChild(
				item._index + 1, this);
	},

	insertBelow: function(item) {
		return item._parent && item._parent.insertChild(
				item._index - 1, this);
	},

	appendTop: function(item) {
		return this.addChild(item);
	},

	appendBottom: function(item) {
		return this.insertChild(0, item);
	},

	moveAbove: function(item) {
		return this.insertAbove(item);
	},

	moveBelow: function(item) {
		return this.insertBelow(item);
	},

	_removeFromNamed: function() {
		var children = this._parent._children,
			namedChildren = this._parent._namedChildren,
			name = this._name,
			namedArray = namedChildren[name],
			index = namedArray ? namedArray.indexOf(this) : -1;
		if (index == -1)
			return;
		if (children[name] == this)
			delete children[name];
		namedArray.splice(index, 1);
		if (namedArray.length) {
			children[name] = namedArray[namedArray.length - 1];
		} else {
			delete namedChildren[name];
		}
	},

	_remove: function(deselect, notify) {
		if (this._parent) {
			if (deselect)
				this.setSelected(false);
			if (this._name)
				this._removeFromNamed();
			Base.splice(this._parent._children, null, this._index, 1);
			if (notify)
				this._parent._changed(Change.HIERARCHY);
			this._parent = null;
			return true;
		}
		return false;
	},

	remove: function() {
		return this._remove(true, true);
	},

	removeChildren: function(from, to) {
		if (!this._children)
			return null;
		from = from || 0;
	 	to = Base.pick(to, this._children.length);
		var removed = this._children.splice(from, to - from);
		for (var i = removed.length - 1; i >= 0; i--)
			removed[i]._remove(true, false);
		if (removed.length > 0)
			this._changed(Change.HIERARCHY);
		return removed;
	},

	reverseChildren: function() {
		if (this._children) {
			this._children.reverse();
			for (var i = 0, l = this._children.length; i < l; i++)
				this._children[i]._index = i;
			this._changed(Change.HIERARCHY);
		}
	},

	isEditable: function() {
		var item = this;
		while (item) {
			if (!item._visible || item._locked)
				return false;
			item = item._parent;
		}
		return true;
	},

	_getOrder: function(item) {
		function getList(item) {
			var list = [];
			do {
				list.unshift(item);
			} while (item = item._parent)
			return list;
		}
		var list1 = getList(this),
			list2 = getList(item);
		for (var i = 0, l = Math.min(list1.length, list2.length); i < l; i++) {
			if (list1[i] != list2[i]) {
				return list1[i]._index < list2[i]._index ? 1 : -1;
			}
		}
		return 0;
	},

	hasChildren: function() {
		return this._children && this._children.length > 0;
	},

	isAbove: function(item) {
		return this._getOrder(item) == -1;
	},

	isBelow: function(item) {
		return this._getOrder(item) == 1;
	},

	isParent: function(item) {
		return this._parent == item;
	},

	isChild: function(item) {
		return item && item._parent == this;
	},

	isDescendant: function(item) {
		var parent = this;
		while (parent = parent._parent) {
			if (parent == item)
				return true;
		}
		return false;
	},

	isAncestor: function(item) {
		return item ? item.isDescendant(this) : false;
	},

	isGroupedWith: function(item) {
		var parent = this._parent;
		while (parent) {
			if (parent._parent
				&& (parent instanceof Group || parent instanceof CompoundPath)
				&& item.isDescendant(parent))
					return true;
			parent = parent._parent;
		}
		return false;
	},

	_getBounds: function(getter, cacheName, args) {
		var children = this._children;
		if (!children || children.length == 0)
			return new Rectangle();
		var x1 = Infinity,
			x2 = -x1,
			y1 = x1,
			y2 = x2;
		for (var i = 0, l = children.length; i < l; i++) {
			var child = children[i];
			if (child._visible) {
				var rect = child[getter](args[0]);
				x1 = Math.min(rect.x, x1);
				y1 = Math.min(rect.y, y1);
				x2 = Math.max(rect.x + rect.width, x2);
				y2 = Math.max(rect.y + rect.height, y2);
			}
		}
		var bounds = Rectangle.create(x1, y1, x2 - x1, y2 - y1);
		return getter == 'getBounds' ? this._createBounds(bounds) : bounds;
	},

	_createBounds: function(rect) {
		return LinkedRectangle.create(this, 'setBounds',
				rect.x, rect.y, rect.width, rect.height);
	},

	getBounds: function() {
		return this._getBounds('getBounds', '_bounds', arguments);
	},

	setBounds: function(rect) {
		rect = Rectangle.read(arguments);
		var bounds = this.getBounds(),
			matrix = new Matrix(),
			center = rect.getCenter();
		matrix.translate(center);
		if (rect.width != bounds.width || rect.height != bounds.height) {
			matrix.scale(
					bounds.width != 0 ? rect.width / bounds.width : 1,
					bounds.height != 0 ? rect.height / bounds.height : 1);
		}
		center = bounds.getCenter();
		matrix.translate(-center.x, -center.y);
		this.transform(matrix);
	},

	getStrokeBounds: function() {
		return this._getBounds('getStrokeBounds', '_strokeBounds', arguments);
	},

	getHandleBounds: function() {
		return this._getBounds('getHandleBounds', '_handleBounds', arguments);
	},

	getRoughBounds: function() {
		return this._getBounds('getRoughBounds', '_roughBounds', arguments);
	},

	scale: function(hor, ver , center) {
		if (arguments.length < 2 || typeof ver === 'object') {
			center = ver;
			ver = hor;
		}
		return this.transform(new Matrix().scale(hor, ver,
				center || this.getPosition()));
	},

	translate: function(delta) {
		var mx = new Matrix();
		return this.transform(mx.translate.apply(mx, arguments));
	},

	rotate: function(angle, center) {
		return this.transform(new Matrix().rotate(angle,
				center || this.getPosition()));
	},

	shear: function(hor, ver, center) {
		if (arguments.length < 2 || typeof ver === 'object') {
			center = ver;
			ver = hor;
		}
		return this.transform(new Matrix().shear(hor, ver,
				center || this.getPosition()));
	},

	transform: function(matrix, flags) {
		var bounds = this._bounds,
			position = this._position,
			children = this._children;
		if (this._transform) {
			this._transform(matrix, flags);
			this._changed(Change.GEOMETRY);
		}
		if (bounds && matrix.getRotation() % 90 === 0) {
			this._bounds = this._createBounds(
					matrix._transformBounds(bounds));
			this._position = this._bounds.getCenter();
		} else if (position) {
			this._position = matrix._transformPoint(position, position, true);
		}
		for (var i = 0, l = children && children.length; i < l; i++)
			children[i].transform(matrix, flags);
		return this;
	},

	fitBounds: function(rectangle, fill) {
		rectangle = Rectangle.read(arguments);
		var bounds = this.getBounds(),
			itemRatio = bounds.height / bounds.width,
			rectRatio = rectangle.height / rectangle.width,
			scale = (fill ? itemRatio > rectRatio : itemRatio < rectRatio)
					? rectangle.width / bounds.width
					: rectangle.height / bounds.height,
			delta = rectangle.getCenter().subtract(bounds.getCenter()),
			newBounds = new Rectangle(new Point(),
					new Size(bounds.width * scale, bounds.height * scale));
		newBounds.setCenter(rectangle.getCenter());
		this.setBounds(newBounds);
	},

	toString: function() {
		return (this.constructor._name || 'Item') + (this._name
				? " '" + this._name + "'"
				: ' @' + this._id);
	},

	statics: {
		drawSelectedBounds: function(bounds, ctx, matrix) {
			var coords = matrix._transformCorners(bounds);
			ctx.beginPath();
			for (var i = 0; i < 8; i++)
				ctx[i == 0 ? 'moveTo' : 'lineTo'](coords[i], coords[++i]);
			ctx.closePath();
			ctx.stroke();
			for (var i = 0; i < 8; i++) {
				ctx.beginPath();
				ctx.rect(coords[i] - 2, coords[++i] - 2, 4, 4);
				ctx.fill();
			}
		},

		draw: function(item, ctx, param) {
			if (!item._visible || item._opacity == 0)
				return;

			var tempCanvas, parentCtx;
			if (item._blendMode !== 'normal'
					|| item._opacity < 1
					&& !(item._segments && (!item.getFillColor()
							|| !item.getStrokeColor()))) {
				var bounds = item.getStrokeBounds() || item.getBounds();
				if (!bounds.width || !bounds.height)
					return;

				var itemOffset = bounds.getTopLeft().floor(),
					size = bounds.getSize().ceil().add(new Size(1, 1));
				tempCanvas = CanvasProvider.getCanvas(size);

				parentCtx = ctx;

				ctx = tempCanvas.getContext('2d');
				ctx.save();

				ctx.translate(-itemOffset.x, -itemOffset.y);
			}
			var savedOffset;
			if (itemOffset) {
				savedOffset = param.offset;
				param.offset = itemOffset;
			}
			item.draw(ctx, param);
			if (itemOffset)
				param.offset = savedOffset;

			if (tempCanvas) {

				ctx.restore();

				if (item._blendMode !== 'normal') {
					var pixelOffset = itemOffset.subtract(param.offset);
					BlendMode.process(item._blendMode, ctx, parentCtx,
						item._opacity, pixelOffset);
				} else {
					parentCtx.save();
					parentCtx.globalAlpha = item._opacity;
					parentCtx.drawImage(tempCanvas,
							itemOffset.x, itemOffset.y);
					parentCtx.restore();
				}

				CanvasProvider.returnCanvas(tempCanvas);
			}
		}
	}
}, new function() {

	var sets = {
		down: {}, drag: {}, up: {}, move: {}
	};

	function removeAll(set) {
		for (var id in set) {
			var item = set[id];
			item.remove();
			for (var type in sets) {
				var other = sets[type];
				if (other != set && other[item.getId()])
					delete other[item.getId()];
			}
		}
	}

	function installHandler(name) {
		var handler = 'onMouse' + Base.capitalize(name);
		var func = paper.tool[handler];
		if (!func || !func._installed) {
			var hash = {};
			hash[handler] = function(event) {
				if (name === 'up')
					sets.drag = {};
				removeAll(sets[name]);
				sets[name] = {};
				if (this.base)
					this.base(event);
			};
			paper.tool.inject(hash);
			paper.tool[handler]._installed = true;
		}
	}

	return Base.each(['down', 'drag', 'up', 'move'], function(name) {
		this['removeOn' + Base.capitalize(name)] = function() {
			var hash = {};
			hash[name] = true;
			return this.removeOn(hash);
		};
	}, {
		removeOn: function(obj) {
			for (var name in obj) {
				if (obj[name]) {
					sets[name][this.getId()] = this;
					if (name === 'drag')
						installHandler('up');
					installHandler(name);
				}
			}
			return this;
		}
	});
});

var Group = this.Group = Item.extend({
	initialize: function(items) {
		this.base();
		this._children = [];
		this._namedChildren = {};
		this.addChildren(!items || !Array.isArray(items)
				|| typeof items[0] !== 'object' ? arguments : items);
	},

	_changed: function(flags) {
		Item.prototype._changed.call(this, flags);
		if (flags & (ChangeFlag.HIERARCHY | ChangeFlag.CLIPPING)) {
			delete this._clipItem;
		}
	},

	_getClipItem: function() {
		if (this._clipItem !== undefined)
			return this._clipItem;
		for (var i = 0, l = this._children.length; i < l; i++) {
			var child = this._children[i];
			if (child._clipMask)
				return this._clipItem = child;
		}
		return this._clipItem = null;
	},

	isClipped: function() {
		return !!this._getClipItem();
	},

	setClipped: function(clipped) {
		var child = this.getFirstChild();
		if (child)
			child.setClipMask(clipped);
		return this;
	},

	draw: function(ctx, param) {
		var clipItem = this._getClipItem();
		if (clipItem)
			Item.draw(clipItem, ctx, param);
		for (var i = 0, l = this._children.length; i < l; i++) {
			var item = this._children[i];
			if (item != clipItem)
				Item.draw(item, ctx, param);
		}
	}
});

var Layer = this.Layer = Group.extend({
	initialize: function(items) {
		this._project = paper.project;
		this._index = this._project.layers.push(this) - 1;
		this.base.apply(this, arguments);
		this.activate();
	},

	_remove: function(deselect, notify) {
		if (this._parent)
			return this.base(deselect, notify);
		if (this._index != null) {
			if (deselect)
				this.setSelected(false);
			Base.splice(this._project.layers, null, this._index, 1);
			this._project._needsRedraw();
			return true;
		}
		return false;
	},

	getNextSibling: function() {
		return this._parent ? this.base()
				: this._project.layers[this._index + 1] || null;
	},

	getPreviousSibling: function() {
		return this._parent ? this.base()
				: this._project.layers[this._index - 1] || null;
	},

	activate: function() {
		this._project.activeLayer = this;
	}
}, new function () {
	function insert(above) {
		return function(item) {
			if (item instanceof Layer && !item._parent
						&& this._remove(false, true)) {
				Base.splice(item._project.layers, [this],
						item._index + (above ? 1 : -1), 0);
				this._setProject(item._project);
				return true;
			}
			return this.base(item);
		};
	}

	return {
		insertAbove: insert(true),

		insertBelow: insert(false)
	};
});

var PlacedItem = this.PlacedItem = Item.extend({

	_transform: function(matrix, flags) {
		this._matrix.preConcatenate(matrix);
	},

	_changed: function(flags) {
		Item.prototype._changed.call(this, flags);
		if (flags & ChangeFlag.GEOMETRY) {
			delete this._strokeBounds;
			delete this._handleBounds;
			delete this._roughBounds;
		}
	},

	getMatrix: function() {
		return this._matrix;
	},

	setMatrix: function(matrix) {
		this._matrix = matrix.clone();
		this._changed(Change.GEOMETRY);
	},

	getBounds: function() {
		var useCache = arguments[0] === undefined;
		if (useCache && this._bounds)
			return this._bounds;
		var bounds = this.getStrokeBounds(arguments[0]);
		if (useCache)
			bounds = this._bounds = this._createBounds(bounds);
		return bounds;
	},

	_getBounds: function(getter, cacheName, args) {
		var matrix = args[0],
			useCache = matrix === undefined;
		if (useCache && this[cacheName])
			return this[cacheName];
		matrix = matrix ? matrix.clone().concatenate(this._matrix)
				: this._matrix;
		var bounds = this._calculateBounds(getter, matrix);
		if (useCache)
			this[cacheName] = bounds;
		return bounds;
	}
});

var Raster = this.Raster = PlacedItem.extend({
	initialize: function(object) {
		this.base();
		if (object.getContext) {
			this.setCanvas(object);
		} else {
			if (typeof object === 'string')
				object = document.getElementById(object);
			this.setImage(object);
		}
		this._matrix = new Matrix();
	},

	clone: function() {
		var image = this._image;
		if (!image) {
			image = CanvasProvider.getCanvas(this._size);
			image.getContext('2d').drawImage(this._canvas, 0, 0);
		}
		var copy = new Raster(image);
		copy._matrix = this._matrix.clone();
		return this._clone(copy);
	},

	getSize: function() {
		return this._size;
	},

	setSize: function() {
		var size = Size.read(arguments),
			image = this.getImage();
		this.setCanvas(CanvasProvider.getCanvas(size));
		this.getContext(true).drawImage(image, 0, 0, size.width, size.height);
	},

	getWidth: function() {
		return this._size.width;
	},

	getHeight: function() {
		return this._size.height;
	},

	getPpi: function() {
		var matrix = this._matrix,
			orig = new Point(0, 0).transform(matrix),
			u = new Point(1, 0).transform(matrix).subtract(orig),
			v = new Point(0, 1).transform(matrix).subtract(orig);
		return new Size(
			72 / u.getLength(),
			72 / v.getLength()
		);
	},

	getContext: function() {
		if (!this._context)
			this._context = this.getCanvas().getContext('2d');
		if (arguments[0])
			this._changed(Change.PIXELS);
		return this._context;
	},

	setContext: function(context) {
		this._context = context;
	},

	getCanvas: function() {
		if (!this._canvas) {
			this._canvas = CanvasProvider.getCanvas(this._size);
			if (this._image)
				this.getContext(true).drawImage(this._image, 0, 0);
		}
		return this._canvas;
	},

	setCanvas: function(canvas) {
		if (this._canvas)
			CanvasProvider.returnCanvas(this._canvas);
		this._canvas = canvas;
		this._size = new Size(canvas.width, canvas.height);
		this._image = null;
		this._context = null;
		this._changed(Change.GEOMETRY);
	},

	getImage: function() {
		return this._image || this.getCanvas();
	},

	setImage: function(image) {
		if (this._canvas)
			CanvasProvider.returnCanvas(this._canvas);
		this._image = image;
		this._size = new Size(image.naturalWidth, image.naturalHeight);
		this._canvas = null;
		this._context = null;
		this._changed(Change.GEOMETRY);
	},

	getSubImage: function(rect) {
		rect = Rectangle.read(arguments);
		var canvas = CanvasProvider.getCanvas(rect.getSize());
		canvas.getContext('2d').drawImage(this.getCanvas(), rect.x, rect.y,
				canvas.width, canvas.height, 0, 0, canvas.width, canvas.height);
		return canvas;
	},

	drawImage: function(image, point) {
		point = Point.read(arguments, 1);
		this.getContext(true).drawImage(image, point.x, point.y);
	},

	getAverageColor: function(object) {
		if (!object)
			object = this.getBounds();
		var bounds, path;
		if (object instanceof PathItem) {
			path = object;
			bounds = object.getBounds();
		} else if (object.width) {
			bounds = new Rectangle(object);
		} else if (object.x) {
			bounds = Rectangle.create(object.x - 0.5, object.y - 0.5, 1, 1);
		}
		var sampleSize = 32,
			width = Math.min(bounds.width, sampleSize),
			height = Math.min(bounds.height, sampleSize);
		var ctx = Raster._sampleContext;
		if (!ctx) {
			ctx = Raster._sampleContext = CanvasProvider.getCanvas(
					new Size(sampleSize)).getContext('2d');
		} else {
			ctx.clearRect(0, 0, sampleSize, sampleSize);
		}
		ctx.save();
		ctx.scale(width / bounds.width, height / bounds.height);
		ctx.translate(-bounds.x, -bounds.y);
		if (path)
			path.draw(ctx, { clip: true });
		this._matrix.applyToContext(ctx);
		ctx.drawImage(this._canvas || this._image,
				-this._size.width / 2, -this._size.height / 2);
		ctx.restore();
		var pixels = ctx.getImageData(0.5, 0.5, Math.ceil(width),
				Math.ceil(height)).data,
			channels = [0, 0, 0],
			total = 0;
		for (var i = 0, l = pixels.length; i < l; i += 4) {
			var alpha = pixels[i + 3];
			total += alpha;
			alpha /= 255;
			channels[0] += pixels[i] * alpha;
			channels[1] += pixels[i + 1] * alpha;
			channels[2] += pixels[i + 2] * alpha;
		}
		for (var i = 0; i < 3; i++)
			channels[i] /= total;
		return total ? Color.read(channels) : null;
	},

	getPixel: function(point) {
		point = Point.read(arguments);
		var pixels = this.getContext().getImageData(point.x, point.y, 1, 1).data,
			channels = new Array(4);
		for (var i = 0; i < 4; i++)
			channels[i] = pixels[i] / 255;
		return RgbColor.read(channels);
	},

	setPixel: function(point, color) {
		var hasPoint = arguments.length == 2;
		point = Point.read(arguments, 0, hasPoint ? 1 : 2);
		color = Color.read(arguments, hasPoint ? 1 : 2);
		var ctx = this.getContext(true),
			imageData = ctx.createImageData(1, 1),
			alpha = color.getAlpha();
		imageData.data[0] = color.getRed() * 255;
		imageData.data[1] = color.getGreen() * 255;
		imageData.data[2] = color.getBlue() * 255;
		imageData.data[3] = alpha != null ? alpha * 255 : 255;
		ctx.putImageData(imageData, point.x, point.y);
	},

	createData: function(size) {
		size = Size.read(arguments);
		return this.getContext().createImageData(size.width, size.height);
	},

	getData: function(rect) {
		rect = Rectangle.read(arguments);
		if (rect.isEmpty())
			rect = new Rectangle(this.getSize());
		return this.getContext().getImageData(rect.x, rect.y,
				rect.width, rect.height);
	},

	setData: function(data, point) {
		point = Point.read(arguments, 1);
		this.getContext(true).putImageData(data, point.x, point.y);
	},

	_calculateBounds: function(getter, matrix) {
		return matrix._transformBounds(
				new Rectangle(this._size).setCenter(0, 0));
	},

	getHandleBounds: function() {
		return this.getStrokeBounds(arguments[0]);
	},

	getRoughBounds: function() {
		return this.getStrokeBounds(arguments[0]);
	},

	draw: function(ctx, param) {
		if (param.selection) {
			var bounds = new Rectangle(this._size).setCenter(0, 0);
			Item.drawSelectedBounds(bounds, ctx, this._matrix);
		} else {
			ctx.save();
			this._matrix.applyToContext(ctx);
			ctx.drawImage(this._canvas || this._image,
					-this._size.width / 2, -this._size.height / 2);
			ctx.restore();
		}
	}
});

var PlacedSymbol = this.PlacedSymbol = PlacedItem.extend({
	initialize: function(symbol, matrixOrOffset) {
		this.base();
		this.setSymbol(symbol instanceof Symbol ? symbol : new Symbol(symbol));
		this._matrix = matrixOrOffset !== undefined
			? matrixOrOffset instanceof Matrix
				? matrixOrOffset
				: new Matrix().translate(Point.read(arguments, 1))
			: new Matrix();
	},

	getSymbol: function() {
		return this._symbol;
	},

	setSymbol: function(symbol) {
		if (this._symbol)
			delete this._symbol._instances[this._id];
		this._symbol = symbol;
		symbol._instances[this._id] = this;
	},

	clone: function() {
		return this._clone(new PlacedSymbol(this.symbol, this._matrix.clone()));
	},

	_calculateBounds: function(getter, matrix) {
		return this.symbol._definition[getter](matrix);
	},

	draw: function(ctx, param) {
		if (param.selection) {
			Item.drawSelectedBounds(this.symbol._definition.getStrokeBounds(),
					ctx, this._matrix);
		} else {
			ctx.save();
			this._matrix.applyToContext(ctx);
			Item.draw(this.symbol.getDefinition(), ctx, param);
			ctx.restore();
		}
	}

});

HitResult = Base.extend({
	initialize: function(type, item, values) {
		this.type = type;
		this.item = item;
		if (values) {
			Base.each(values, function(value, key) {
				this[key] = value;
			}, this);
		}
	},

	statics: {
		getOptions: function(point, options) {
			return options && options._merged ? options : Base.merge({
				point: Point.read(arguments, 0, 1),
				type: null,
				tolerance: 2,
				fill: !options,
				stroke: !options,
				segments: !options,
				handles: false,
				ends: false,
				center: false,
				bounds: false,
				guides: false,
				selected: false,
				_merged: true
			}, options);
		}
	}
});

var Segment = this.Segment = Base.extend({
	initialize: function(arg0, arg1, arg2, arg3, arg4, arg5) {
		var count = arguments.length,
			createPoint = SegmentPoint.create,
			point, handleIn, handleOut;
		if (count == 0) {
		} else if (count == 1) {
			if (arg0.point) {
				point = arg0.point;
				handleIn = arg0.handleIn;
				handleOut = arg0.handleOut;
			} else {
				point = arg0;
			}
		} else if (count < 6) {
			if (count == 2 && arg1.x === undefined) {
				point = [ arg0, arg1 ];
			} else {
				point = arg0;
				handleIn = arg1;
				handleOut = arg2;
			}
		} else if (count == 6) {
			point = [ arg0, arg1 ];
			handleIn = [ arg2, arg3 ];
			handleOut = [ arg4, arg5 ];
		}
		createPoint(this, '_point', point);
		createPoint(this, '_handleIn', handleIn);
		createPoint(this, '_handleOut', handleOut);
	},

	_changed: function(point) {
		if (!this._path)
			return;
		var curve = this._path._curves && this.getCurve(), other;
		if (curve) {
			curve._changed();
			if (other = (curve[point == this._point
					|| point == this._handleIn && curve._segment1 == this
					? 'getPrevious' : 'getNext']())) {
				other._changed();
			}
		}
		this._path._changed(Change.GEOMETRY);
	},

	getPoint: function() {
		return this._point;
	},

	setPoint: function(point) {
		point = Point.read(arguments);
		this._point.set(point.x, point.y);
	},

	getHandleIn: function() {
		return this._handleIn;
	},

	setHandleIn: function(point) {
		point = Point.read(arguments);
		this._handleIn.set(point.x, point.y);
	},

	getHandleOut: function() {
		return this._handleOut;
	},

	setHandleOut: function(point) {
		point = Point.read(arguments);
		this._handleOut.set(point.x, point.y);
	},

	_isSelected: function(point) {
		var state = this._selectionState;
		return point == this._point ? !!(state & SelectionState.POINT)
			: point == this._handleIn ? !!(state & SelectionState.HANDLE_IN)
			: point == this._handleOut ? !!(state & SelectionState.HANDLE_OUT)
			: false;
	},

	_setSelected: function(point, selected) {
		var path = this._path,
			selected = !!selected, 
			state = this._selectionState || 0,
			selection = [
				!!(state & SelectionState.POINT),
				!!(state & SelectionState.HANDLE_IN),
				!!(state & SelectionState.HANDLE_OUT)
			];
		if (point == this._point) {
			if (selected) {
				selection[1] = selection[2] = false;
			} else {
				var previous = this.getPrevious(),
					next = this.getNext();
				selection[1] = previous && (previous._point.isSelected()
						|| previous._handleOut.isSelected());
				selection[2] = next && (next._point.isSelected()
						|| next._handleIn.isSelected());
			}
			selection[0] = selected;
		} else {
			var index = point == this._handleIn ? 1 : 2;
			if (selection[index] != selected) {
				if (selected)
					selection[0] = false;
				selection[index] = selected;
				path._changed(Change.ATTRIBUTE);
			}
		}
		this._selectionState = (selection[0] ? SelectionState.POINT : 0)
				| (selection[1] ? SelectionState.HANDLE_IN : 0)
				| (selection[2] ? SelectionState.HANDLE_OUT : 0);
		if (path && state != this._selectionState)
			path._updateSelection(this, state, this._selectionState);
	},

	isSelected: function() {
		return this._isSelected(this._point);
	},

	setSelected: function(selected) {
		this._setSelected(this._point, selected);
	},

	getIndex: function() {
		return this._index !== undefined ? this._index : null;
	},

	getPath: function() {
		return this._path || null;
	},

	getCurve: function() {
		if (this._path) {
			var index = this._index;
			if (!this._path._closed && index == this._path._segments.length - 1)
				index--;
			return this._path.getCurves()[index] || null;
		}
		return null;
	},

	getNext: function() {
		var segments = this._path && this._path._segments;
		return segments && (segments[this._index + 1]
				|| this._path._closed && segments[0]) || null;
	},

	getPrevious: function() {
		var segments = this._path && this._path._segments;
		return segments && (segments[this._index - 1]
				|| this._path._closed && segments[segments.length - 1]) || null;
	},

	reverse: function() {
		return new Segment(this._point, this._handleOut, this._handleIn);
	},

	remove: function() {
		return this._path ? !!this._path.removeSegment(this._index) : false;
	},

	toString: function() {
		var parts = [ 'point: ' + this._point ];
		if (!this._handleIn.isZero())
			parts.push('handleIn: ' + this._handleIn);
		if (!this._handleOut.isZero())
			parts.push('handleOut: ' + this._handleOut);
		return '{ ' + parts.join(', ') + ' }';
	},

	_transformCoordinates: function(matrix, coords, change) {
		var point = this._point,
			handleIn =  !change || !this._handleIn.isZero()
					? this._handleIn : null,
			handleOut = !change || !this._handleOut.isZero()
					? this._handleOut : null,
			x = point._x,
			y = point._y,
			i = 2;
		coords[0] = x;
		coords[1] = y;
		if (handleIn) {
			coords[i++] = handleIn._x + x;
			coords[i++] = handleIn._y + y;
		}
		if (handleOut) {
			coords[i++] = handleOut._x + x;
			coords[i++] = handleOut._y + y;
		}
		if (!matrix)
			return;
		matrix._transformCoordinates(coords, 0, coords, 0, i / 2);
		x = coords[0];
		y = coords[1];
		if (change) {
			point._x = x;
			point._y = y;
			i  = 2;
			if (handleIn) {
				handleIn._x = coords[i++] - x;
				handleIn._y = coords[i++] - y;
			}
			if (handleOut) {
				handleOut._x = coords[i++] - x;
				handleOut._y = coords[i++] - y;
			}
		} else {
			if (!handleIn) {
				coords[i++] = x;
				coords[i++] = y;
			}
			if (!handleOut) {
				coords[i++] = x;
				coords[i++] = y;
			}
		}
	}
});

var SegmentPoint = Point.extend({
	set: function(x, y) {
		this._x = x;
		this._y = y;
		this._owner._changed(this);
		return this;
	},

	getX: function() {
		return this._x;
	},

	setX: function(x) {
		this._x = x;
		this._owner._changed(this);
	},

	getY: function() {
		return this._y;
	},

	setY: function(y) {
		this._y = y;
		this._owner._changed(this);
	},

	isZero: function() {
		return this._x == 0 && this._y == 0;
	},

	setSelected: function(selected) {
		this._owner._setSelected(this, selected);
	},

	isSelected: function() {
		return this._owner._isSelected(this);
	},

	statics: {
		create: function(segment, key, pt) {
			var point = new SegmentPoint(SegmentPoint.dont),
				x, y, selected;
			if (!pt) {
				x = y = 0;
			} else if ((x = pt[0]) !== undefined) { 
				y = pt[1];
			} else {
				if ((x = pt.x) === undefined) {
					pt = Point.read(arguments, 2, 1);
					x = pt.x;
				}
				y = pt.y;
				selected = pt.selected;
			}
			point._x = x;
			point._y = y;
			point._owner = segment;
			segment[key] = point;
			if (selected)
				point.setSelected(true);
			return point;
		}
	}
});

var SelectionState = {
	HANDLE_IN: 1,
	HANDLE_OUT: 2,
	POINT: 4
};

var Curve = this.Curve = Base.extend({
	initialize: function(arg0, arg1, arg2, arg3, arg4, arg5, arg6, arg7) {
		var count = arguments.length;
		if (count == 0) {
			this._segment1 = new Segment();
			this._segment2 = new Segment();
		} else if (count == 1) {
			this._segment1 = new Segment(arg0.segment1);
			this._segment2 = new Segment(arg0.segment2);
		} else if (count == 2) {
			this._segment1 = new Segment(arg0);
			this._segment2 = new Segment(arg1);
		} else if (count == 4) {
			this._segment1 = new Segment(arg0, null, arg1);
			this._segment2 = new Segment(arg3, arg2, null);
		} else if (count == 8) {
			var p1 = Point.create(arg0, arg1),
				p2 = Point.create(arg6, arg7);
			this._segment1 = new Segment(p1, null,
					Point.create(arg2, arg3).subtract(p1));
			this._segment2 = new Segment(p2,
					Point.create(arg4, arg5).subtract(p2), null);
		}
	},

	_changed: function() {
		delete this._length;
	},

	getPoint1: function() {
		return this._segment1._point;
	},

	setPoint1: function(point) {
		point = Point.read(arguments);
		this._segment1._point.set(point.x, point.y);
	},

	getPoint2: function() {
		return this._segment2._point;
	},

	setPoint2: function(point) {
		point = Point.read(arguments);
		this._segment2._point.set(point.x, point.y);
	},

	getHandle1: function() {
		return this._segment1._handleOut;
	},

	setHandle1: function(point) {
		point = Point.read(arguments);
		this._segment1._handleOut.set(point.x, point.y);
	},

	getHandle2: function() {
		return this._segment2._handleIn;
	},

	setHandle2: function(point) {
		point = Point.read(arguments);
		this._segment2._handleIn.set(point.x, point.y);
	},

	getSegment1: function() {
		return this._segment1;
	},

	getSegment2: function() {
		return this._segment2;
	},

	getPath: function() {
		return this._path;
	},

	getIndex: function() {
		return this._segment1._index;
	},

	getNext: function() {
		var curves = this._path && this._path._curves;
		return curves && (curves[this._segment1._index + 1]
				|| this._path._closed && curves[0]) || null;
	},

	getPrevious: function() {
		var curves = this._path && this._path._curves;
		return curves && (curves[this._segment1._index - 1]
				|| this._path._closed && curves[curves.length - 1]) || null;
	},

	isSelected: function() {
		return this.getHandle1().isSelected() && this.getHandle2().isSelected();
	},

	setSelected: function(selected) {
		this.getHandle1().setSelected(selected);
		this.getHandle2().setSelected(selected);
	},

	getValues: function(matrix) {
		return Curve.getValues(this._segment1, this._segment2, matrix);
	},

	getPoints: function(matrix) {
		var coords = this.getValues(matrix),
			points = [];
		for (var i = 0; i < 8; i += 2)
			points.push(Point.create(coords[i], coords[i + 1]));
		return points;
	},

	getLength: function() {
		var from = arguments[0],
			to = arguments[1];
			fullLength = arguments.length == 0 || from == 0 && to == 1;
		if (fullLength && this._length != null)
			return this._length;
		var length = Curve.getLength(this.getValues(), from, to);
		if (fullLength)
			this._length = length;
		return length;
	},

	getPart: function(from, to) {
		return new Curve(Curve.getPart(this.getValues(), from, to));
	},

	isLinear: function() {
		return this._segment1._handleOut.isZero()
				&& this._segment2._handleIn.isZero();
	},

	getParameterAt: function(offset, start) {
		return Curve.getParameterAt(this.getValues(), offset,
				start !== undefined ? start : offset < 0 ? 1 : 0);
	},

	getPoint: function(parameter) {
		return Curve.evaluate(this.getValues(), parameter, 0);
	},

	getTangent: function(parameter) {
		return Curve.evaluate(this.getValues(), parameter, 1);
	},

	getNormal: function(parameter) {
		return Curve.evaluate(this.getValues(), parameter, 2);
	},

	getParameter: function(point) {
		point = Point.read(point);
		return Curve.getParameter(this.getValues(), point.x, point.y);
	},

	getCrossings: function(point, matrix, roots) {
		var vals = this.getValues(matrix),
			num = Curve.solveCubic(vals, 1, point.y, roots),
			crossings = 0;
		for (var i = 0; i < num; i++) {
			var t = roots[i];
			if (t >= 0 && t < 1 && Curve.evaluate(vals, t, 0).x > point.x) {
				if (t < Numerical.TOLERANCE && Curve.evaluate(
							this.getPrevious().getValues(matrix), 1, 1).y
						* Curve.evaluate(vals, t, 1).y >= 0)
					continue;
				crossings++;
			}
		}
		return crossings;
	},

	reverse: function() {
		return new Curve(this._segment2.reverse(), this._segment1.reverse());
	},

	clone: function() {
		return new Curve(this._segment1, this._segment2);
	},

	toString: function() {
		var parts = [ 'point1: ' + this._segment1._point ];
		if (!this._segment1._handleOut.isZero())
			parts.push('handle1: ' + this._segment1._handleOut);
		if (!this._segment2._handleIn.isZero())
			parts.push('handle2: ' + this._segment2._handleIn);
		parts.push('point2: ' + this._segment2._point);
		return '{ ' + parts.join(', ') + ' }';
	},

	statics: {
		create: function(path, segment1, segment2) {
			var curve = new Curve(Curve.dont);
			curve._path = path;
			curve._segment1 = segment1;
			curve._segment2 = segment2;
			return curve;
		},

		getValues: function(segment1, segment2, matrix) {
			var p1 = segment1._point,
				h1 = segment1._handleOut,
				h2 = segment2._handleIn,
				p2 = segment2._point,
				coords = [
					p1._x, p1._y,
					p1._x + h1._x, p1._y + h1._y,
					p2._x + h2._x, p2._y + h2._y,
					p2._x, p2._y
				];
			return matrix
					? matrix._transformCoordinates(coords, 0, coords, 0, 4)
					: coords;
		},

		evaluate: function(v, t, type) {
			var p1x = v[0], p1y = v[1],
				c1x = v[2], c1y = v[3],
				c2x = v[4], c2y = v[5],
				p2x = v[6], p2y = v[7],
				x, y;

			if (type == 0 && (t == 0 || t == 1)) {
				x = t == 0 ? p1x : p2x;
				y = t == 0 ? p1y : p2y;
			} else {
				var tMin = Numerical.TOLERANCE;
				if (t < tMin && c1x == p1x && c1y == p1y)
					t = tMin;
				else if (t > 1 - tMin && c2x == p2x && c2y == p2y)
					t = 1 - tMin;
				var cx = 3 * (c1x - p1x),
					bx = 3 * (c2x - c1x) - cx,
					ax = p2x - p1x - cx - bx,

					cy = 3 * (c1y - p1y),
					by = 3 * (c2y - c1y) - cy,
					ay = p2y - p1y - cy - by;

				switch (type) {
				case 0: 
					x = ((ax * t + bx) * t + cx) * t + p1x;
					y = ((ay * t + by) * t + cy) * t + p1y;
					break;
				case 1: 
				case 2: 
					x = (3 * ax * t + 2 * bx) * t + cx;
					y = (3 * ay * t + 2 * by) * t + cy;
					break;
				}
			}
			return type == 2 ? new Point(y, -x) : new Point(x, y);
		},

		subdivide: function(v, t) {
			var p1x = v[0], p1y = v[1],
				c1x = v[2], c1y = v[3],
				c2x = v[4], c2y = v[5],
				p2x = v[6], p2y = v[7];
			if (t === undefined)
				t = 0.5;
			var u = 1 - t,
				p3x = u * p1x + t * c1x, p3y = u * p1y + t * c1y,
				p4x = u * c1x + t * c2x, p4y = u * c1y + t * c2y,
				p5x = u * c2x + t * p2x, p5y = u * c2y + t * p2y,
				p6x = u * p3x + t * p4x, p6y = u * p3y + t * p4y,
				p7x = u * p4x + t * p5x, p7y = u * p4y + t * p5y,
				p8x = u * p6x + t * p7x, p8y = u * p6y + t * p7y;
			return [
				[p1x, p1y, p3x, p3y, p6x, p6y, p8x, p8y], 
				[p8x, p8y, p7x, p7y, p5x, p5y, p2x, p2y] 
			];
		},

		solveCubic: function (v, coord, val, roots) {
			var p1 = v[coord],
				c1 = v[coord + 2],
				c2 = v[coord + 4],
				p2 = v[coord + 6],
				c = 3 * (c1 - p1),
				b = 3 * (c2 - c1) - c,
				a = p2 - p1 - c - b;
			return Numerical.solveCubic(a, b, c, p1 - val, roots,
					Numerical.TOLERANCE);
		},

		getParameter: function(v, x, y) {
			var txs = [],
				tys = [],
				sx = Curve.solveCubic(v, 0, x, txs),
				sy = Curve.solveCubic(v, 1, y, tys),
				tx, ty;
			for (var cx = 0;  sx == -1 || cx < sx;) {
				if (sx == -1 || (tx = txs[cx++]) >= 0 && tx <= 1) {
					for (var cy = 0; sy == -1 || cy < sy;) {
						if (sy == -1 || (ty = tys[cy++]) >= 0 && ty <= 1) {
							if (sx == -1) tx = ty;
							else if (sy == -1) ty = tx;
							if (Math.abs(tx - ty) < Numerical.TOLERANCE)
								return (tx + ty) * 0.5;
						}
					}
					if (sx == -1)
						break;
				}
			}
			return null;
		},

		getPart: function(v, from, to) {
			if (from > 0)
				v = Curve.subdivide(v, from)[1]; 
			if (to < 1)
				v = Curve.subdivide(v, (to - from) / (1 - from))[0]; 
			return v;
		},

		isFlatEnough: function(v) {
			var p1x = v[0], p1y = v[1],
				c1x = v[2], c1y = v[3],
				c2x = v[4], c2y = v[5],
				p2x = v[6], p2y = v[7],

				a = p1y - p2y,
				b = p2x - p1x,
				c = p1x * p2y - p2x * p1y,
				v1 = a * c1x + b * c1y + c,
				v2 = a * c2x + b * c2y + c;
			return Math.abs((v1 * v1 + v2 * v2) / (a * (a * a + b * b))) < 0.005;
		}
	}
}, new function() { 

	function getLengthIntegrand(v) {
		var p1x = v[0], p1y = v[1],
			c1x = v[2], c1y = v[3],
			c2x = v[4], c2y = v[5],
			p2x = v[6], p2y = v[7],

			ax = 9 * (c1x - c2x) + 3 * (p2x - p1x),
			bx = 6 * (p1x + c2x) - 12 * c1x,
			cx = 3 * (c1x - p1x),

			ay = 9 * (c1y - c2y) + 3 * (p2y - p1y),
			by = 6 * (p1y + c2y) - 12 * c1y,
			cy = 3 * (c1y - p1y);

		return function(t) {
			var dx = (ax * t + bx) * t + cx,
				dy = (ay * t + by) * t + cy;
			return Math.sqrt(dx * dx + dy * dy);
		};
	}

	function getIterations(a, b) {
		return Math.max(2, Math.min(16, Math.ceil(Math.abs(b - a) * 32)));
	}

	return {
		statics: true,

		getLength: function(v, a, b) {
			if (a === undefined)
				a = 0;
			if (b === undefined)
				b = 1;
			if (v[0] == v[2] && v[1] == v[3] && v[6] == v[4] && v[7] == v[5]) {
				var dx = v[6] - v[0], 
					dy = v[7] - v[1]; 
				return (b - a) * Math.sqrt(dx * dx + dy * dy);
			}
			var ds = getLengthIntegrand(v);
			return Numerical.integrate(ds, a, b, getIterations(a, b));
		},

		getParameterAt: function(v, offset, start) {
			if (offset == 0)
				return start;
			var forward = offset > 0,
				a = forward ? start : 0,
				b = forward ? 1 : start,
				offset = Math.abs(offset),
				ds = getLengthIntegrand(v),
				rangeLength = Numerical.integrate(ds, a, b,
						getIterations(a, b));
			if (offset >= rangeLength)
				return forward ? b : a;
			var guess = offset / rangeLength,
				length = 0;
			function f(t) {
				var count = getIterations(start, t);
				length += start < t
						? Numerical.integrate(ds, start, t, count)
						: -Numerical.integrate(ds, t, start, count);
				start = t;
				return length - offset;
			}
			return Numerical.findRoot(f, ds,
					forward ? a + guess : b - guess, 
					a, b, 16, Numerical.TOLERANCE);
		}
	};
}, new function() { 

	var maxDepth = 32,
		epsilon = Math.pow(2, -maxDepth - 1);

	var zCubic = [
		[1.0, 0.6, 0.3, 0.1],
		[0.4, 0.6, 0.6, 0.4],
		[0.1, 0.3, 0.6, 1.0]
	];

	var xAxis = new Line(new Point(0, 0), new Point(1, 0));

	function toBezierForm(v, point) {
		var n = 3, 
	 		degree = 5, 
			c = [],
			d = [],
			cd = [],
			w = [];
		for(var i = 0; i <= n; i++) {
			c[i] = v[i].subtract(point);
			if (i < n)
				d[i] = v[i + 1].subtract(v[i]).multiply(n);
		}

		for (var row = 0; row < n; row++) {
			cd[row] = [];
			for (var column = 0; column <= n; column++)
				cd[row][column] = d[row].dot(c[column]);
		}

		for (var i = 0; i <= degree; i++)
			w[i] = new Point(i / degree, 0);

		for (k = 0; k <= degree; k++) {
			var lb = Math.max(0, k - n + 1),
				ub = Math.min(k, n);
			for (var i = lb; i <= ub; i++) {
				var j = k - i;
				w[k].y += cd[j][i] * zCubic[j][i];
			}
		}

		return w;
	}

	function findRoots(w, depth) {
		switch (countCrossings(w)) {
		case 0:
			return [];
		case 1:
			if (depth >= maxDepth)
				return [0.5 * (w[0].x + w[5].x)];
			if (isFlatEnough(w)) {
				var line = new Line(w[0], w[5], true);
				return [ line.vector.getLength(true) <= Numerical.EPSILON
						? line.point.x
						: xAxis.intersect(line).x ];
			}
		}

		var p = [[]],
			left = [],
			right = [];
		for (var j = 0; j <= 5; j++)
		 	p[0][j] = new Point(w[j]);

		for (var i = 1; i <= 5; i++) {
			p[i] = [];
			for (var j = 0 ; j <= 5 - i; j++)
				p[i][j] = p[i - 1][j].add(p[i - 1][j + 1]).multiply(0.5);
		}
		for (var j = 0; j <= 5; j++) {
			left[j]  = p[j][0];
			right[j] = p[5 - j][j];
		}

		return findRoots(left, depth + 1).concat(findRoots(right, depth + 1));
	}

	function countCrossings(v) {
		var crossings = 0,
			prevSign = null;
		for (var i = 0, l = v.length; i < l; i++)  {
			var sign = v[i].y < 0 ? -1 : 1;
			if (prevSign != null && sign != prevSign)
				crossings++;
			prevSign = sign;
		}
		return crossings;
	}

	function isFlatEnough(v) {

		var n = v.length - 1,
			a = v[0].y - v[n].y,
			b = v[n].x - v[0].x,
			c = v[0].x * v[n].y - v[n].x * v[0].y,
			maxAbove = 0,
			maxBelow = 0;
		for (var i = 1; i < n; i++) {
			var val = a * v[i].x + b * v[i].y + c,
				dist = val * val;
			if (val < 0 && dist > maxBelow) {
				maxBelow = dist;
			} else if (dist > maxAbove) {
				maxAbove = dist;
			}
		}
		return Math.abs((maxAbove + maxBelow) / (2 * a * (a * a + b * b)))
				< epsilon;
	}

	return {
		getNearestLocation: function(point, matrix) {
			var w = toBezierForm(this.getPoints(matrix), point);
			var roots = findRoots(w, 0).concat([0, 1]);
			var minDist = Infinity,
				minT,
				minPoint;
			for (var i = 0; i < roots.length; i++) {
				var pt = this.getPoint(roots[i]),
					dist = point.getDistance(pt, true);
				if (dist < minDist) {
					minDist = dist;
					minT = roots[i];
					minPoint = pt;
				}
			}
			return new CurveLocation(this, minT, minPoint, Math.sqrt(minDist));
		},

		getNearestPoint: function(point, matrix) {
			return this.getNearestLocation(point, matrix).getPoint();
		}
	};
});

CurveLocation = Base.extend({
	initialize: function(curve, parameter, point, distance) {
		this._curve = curve;
		this._parameter = parameter;
		this._point = point;
		this._distance = distance;
	},

	getSegment: function() {
		if (!this._segment) {
			var curve = this._curve,
				parameter = this.getParameter();
			if (parameter == 0) {
				this._segment = curve._segment1;
			} else if (parameter == 1) {
				this._segment = curve._segment2;
			} else if (parameter == null) {
				return null;
			} else {
				this._segment = curve.getLength(0, parameter)
					< curve.getLength(parameter, 1)
						? curve._segment1
						: curve._segment2;
			}
		}
		return this._segment;
	},

	getCurve: function() {
		return this._curve;
	},

	getPath: function() {
		return this._curve && this._curve._path;
	},

	getIndex: function() {
		return this._curve && this._curve.getIndex();
	},

	getOffset: function() {
		var path = this._curve && this._curve._path;
		return path && path._getOffset(this);
	},

	getCurveOffset: function() {
		var parameter = this.getParameter();
		return parameter != null && this._curve
				&& this._curve.getLength(0, parameter);
	},

	getParameter: function() {
		if (this._parameter == null && this._curve && this._point)
			this._parameter = this._curve.getParameterAt(this._point);
		return this._parameter;
	},

	getPoint: function() {
		if (!this._point && this._curve && this._parameter != null)
			this._point = this._curve.getPoint(this._parameter);
		return this._point;
	},

	getTangent: function() {
		var parameter = this.getParameter();
		return parameter != null && this._curve
				&& this._curve.getTangent(parameter);
	},

	getNormal: function() {
		var parameter = this.getParameter();
		return parameter != null && this._curve
				&& this._curve.getNormal(parameter);
	},

	getDistance: function() {
		return this._distance;
	},

	toString: function() {
		var parts = [],
			point = this.getPoint();
		if (point)
			parts.push('point: ' + point);
		var index = this.getIndex();
		if (index != null)
			parts.push('index: ' + index);
		var parameter = this.getParameter();
		if (parameter != null)
			parts.push('parameter: ' + Base.formatNumber(parameter));
		if (this._distance != null)
			parts.push('distance: ' + Base.formatNumber(this._distance));
		return '{ ' + parts.join(', ') + ' }';
	}
});

var PathItem = this.PathItem = Item.extend({

});

var Path = this.Path = PathItem.extend({
	initialize: function(segments) {
		this.base();
		this._closed = false;
		this._selectedSegmentState = 0;
		this.setSegments(!segments || !Array.isArray(segments)
				|| typeof segments[0] !== 'object' ? arguments : segments);
	},

	clone: function() {
		var copy = this._clone(new Path(this._segments));
		copy._closed = this._closed;
		if (this._clockwise !== undefined)
			copy._clockwise = this._clockwise;
		return copy;
	},

	_changed: function(flags) {
		Item.prototype._changed.call(this, flags);
		if (flags & ChangeFlag.GEOMETRY) {
			delete this._strokeBounds;
			delete this._handleBounds;
			delete this._roughBounds;
			delete this._length;
			delete this._clockwise;
		} else if (flags & ChangeFlag.STROKE) {
			delete this._strokeBounds;
		}
	},

	getSegments: function() {
		return this._segments;
	},

	setSegments: function(segments) {
		if (!this._segments) {
			this._segments = [];
		} else {
			this._selectedSegmentState = 0;
			this._segments.length = 0;
			if (this._curves)
				delete this._curves;
		}
		this._add(Segment.readAll(segments));
	},

	getFirstSegment: function() {
		return this._segments[0];
	},

	getLastSegment: function() {
		return this._segments[this._segments.length - 1];
	},

	getCurves: function() {
		if (!this._curves) {
			var segments = this._segments,
				length = segments.length;
			if (!this._closed && length > 0)
				length--;
			this._curves = new Array(length);
			for (var i = 0; i < length; i++)
				this._curves[i] = Curve.create(this, segments[i],
					segments[i + 1] || segments[0]);
		}
		return this._curves;
	},

	getFirstCurve: function() {
		return this.getCurves()[0];
	},

	getLastCurve: function() {
		var curves = this.getCurves();
		return curves[curves.length - 1];
	},

	getClosed: function() {
		return this._closed;
	},

	setClosed: function(closed) {
		if (this._closed != (closed = !!closed)) {
			this._closed = closed;
			if (this._curves) {
				var length = this._segments.length,
					i;
				if (!closed && length > 0)
					length--;
				this._curves.length = length;
				if (closed)
					this._curves[i = length - 1] = Curve.create(this,
						this._segments[i], this._segments[0]);
			}
			this._changed(Change.GEOMETRY);
		}
	},

	_transform: function(matrix, flags) {
		if (!matrix.isIdentity()) {
			var coords = new Array(6);
			for (var i = 0, l = this._segments.length; i < l; i++) {
				this._segments[i]._transformCoordinates(matrix, coords, true);
			}
			var fillColor = this.getFillColor(),
				strokeColor = this.getStrokeColor();
			if (fillColor && fillColor.transform)
				fillColor.transform(matrix);
			if (strokeColor && strokeColor.transform)
				strokeColor.transform(matrix);
		}
	},

	_add: function(segs, index) {
		var segments = this._segments,
			curves = this._curves,
			amount = segs.length,
			append = index == null,
			index = append ? segments.length : index,
			fullySelected = this.isFullySelected();
		for (var i = 0; i < amount; i++) {
			var segment = segs[i];
			if (segment._path) {
				segment = segs[i] = new Segment(segment);
			}
			segment._path = this;
			segment._index = index + i;
			if (fullySelected)
				segment._selectionState = SelectionState.POINT;
			if (segment._selectionState)
				this._updateSelection(segment, 0, segment._selectionState);
		}
		if (append) {
			segments.push.apply(segments, segs);
		} else {
			segments.splice.apply(segments, [index, 0].concat(segs));
			for (var i = index + amount, l = segments.length; i < l; i++) {
				segments[i]._index = i;
			}
		}
		if (curves && --index >= 0) {
			curves.splice(index, 0, Curve.create(this, segments[index],
				segments[index + 1]));
			var curve = curves[index + amount];
			if (curve) {
				curve._segment1 = segments[index + amount];
			}
		}
		this._changed(Change.GEOMETRY);
		return segs;
	},

	add: function(segment1 ) {
		return arguments.length > 1 && typeof segment1 !== 'number'
			? this._add(Segment.readAll(arguments))
			: this._add([ Segment.read(arguments) ])[0];
	},

	insert: function(index, segment1 ) {
		return arguments.length > 2 && typeof segment1 !== 'number'
			? this._add(Segment.readAll(arguments, 1), index)
			: this._add([ Segment.read(arguments, 1) ], index)[0];
	},

	addSegment: function(segment) {
		return this._add([ Segment.read(arguments) ])[0];
	},

	insertSegment: function(index, segment) {
		return this._add([ Segment.read(arguments, 1) ], index)[0];
	},

	addSegments: function(segments) {
		return this._add(Segment.readAll(segments));
	},

	insertSegments: function(index, segments) {
		return this._add(Segment.readAll(segments), index);
	},

	removeSegment: function(index) {
		var segments = this.removeSegments(index, index + 1);
		return segments[0] || null;
	},

	removeSegments: function(from, to) {
		from = from || 0;
	 	to = Base.pick(to, this._segments.length);
		var segments = this._segments,
			curves = this._curves,
			last = to >= segments.length,
			removed = segments.splice(from, to - from),
			amount = removed.length;
		if (!amount)
			return removed;
		for (var i = 0; i < amount; i++) {
			var segment = removed[i];
			if (segment._selectionState)
				this._updateSelection(segment, segment._selectionState, 0);
			removed._index = removed._path = undefined;
		}
		for (var i = from, l = segments.length; i < l; i++)
			segments[i]._index = i;
		if (curves) {
			curves.splice(from, amount);
			var curve;
			if (curve = curves[from - 1])
				curve._segment2 = segments[from];
			if (curve = curves[from])
				curve._segment1 = segments[from];
			if (last && this._closed && (curve = curves[curves.length - 1]))
				curve._segment2 = segments[0];
		}
		this._changed(Change.GEOMETRY);
		return removed;
	},

	isFullySelected: function() {
		return this._selected && this._selectedSegmentState
				== this._segments.length * SelectionState.POINT;
	},

	setFullySelected: function(selected) {
		var length = this._segments.length;
		this._selectedSegmentState = selected
				? length * SelectionState.POINT : 0;
		for (var i = 0; i < length; i++)
			this._segments[i]._selectionState = selected
					? SelectionState.POINT : 0;
		this.setSelected(selected);
	},

	_updateSelection: function(segment, oldState, newState) {
		segment._selectionState = newState;
		var total = this._selectedSegmentState += newState - oldState;
		if (total > 0)
			this.setSelected(true);
	},

	flatten: function(maxDistance) {
		var flattener = new PathFlattener(this),
			pos = 0,
			step = flattener.length / Math.ceil(flattener.length / maxDistance),
			end = flattener.length + (this._closed ? -step : step) / 2;
		var segments = [];
		while (pos <= end) {
			segments.push(new Segment(flattener.evaluate(pos, 0)));
			pos += step;
		}
		this.setSegments(segments);
	},

	simplify: function(tolerance) {
		if (this._segments.length > 2) {
			var fitter = new PathFitter(this, tolerance || 2.5);
			this.setSegments(fitter.fit());
		}
	},

	isClockwise: function() {
		if (this._clockwise !== undefined)
			return this._clockwise;
		var sum = 0,
			xPre, yPre;
		function edge(x, y) {
			if (xPre !== undefined)
				sum += (xPre - x) * (y + yPre);
			xPre = x;
			yPre = y;
		}
		for (var i = 0, l = this._segments.length; i < l; i++) {
			var seg1 = this._segments[i],
				seg2 = this._segments[i + 1 < l ? i + 1 : 0],
				point1 = seg1._point,
				handle1 = seg1._handleOut,
				handle2 = seg2._handleIn,
				point2 = seg2._point;
			edge(point1._x, point1._y);
			edge(point1._x + handle1._x, point1._y + handle1._y);
			edge(point2._x + handle2._x, point2._y + handle2._y);
			edge(point2._x, point2._y);
		}
		return sum > 0;
	},

	setClockwise: function(clockwise) {
		if (this.isClockwise() != (clockwise = !!clockwise)) {
			this.reverse();
			this._clockwise = clockwise;
		}
	},

	reverse: function() {
		this._segments.reverse();
		for (var i = 0, l = this._segments.length; i < l; i++) {
			var segment = this._segments[i];
			var handleIn = segment._handleIn;
			segment._handleIn = segment._handleOut;
			segment._handleOut = handleIn;
		}
		if (this._clockwise !== undefined)
			this._clockwise = !this._clockwise;
	},

	join: function(path) {
		if (path) {
			var segments = path._segments,
				last1 = this.getLastSegment(),
				last2 = path.getLastSegment();
			if (last1._point.equals(last2._point))
				path.reverse();
			var first2 = path.getFirstSegment();
			if (last1._point.equals(first2._point)) {
				last1.setHandleOut(first2._handleOut);
				this._add(segments.slice(1));
			} else {
				var first1 = this.getFirstSegment();
				if (first1._point.equals(first2._point))
					path.reverse();
				last2 = path.getLastSegment();
				if (first1._point.equals(last2._point)) {
					first1.setHandleIn(last2._handleIn);
					this._add(segments.slice(0, segments.length - 1), 0);
				} else {
					this._add(segments.slice(0));
				}
			}
			path.remove();
			var first1 = this.getFirstSegment();
			last1 = this.getLastSegment();
			if (last1._point.equals(first1._point)) {
				first1.setHandleIn(last1._handleIn);
				last1.remove();
				this.setClosed(true);
			}
			this._changed(Change.GEOMETRY);
			return true;
		}
		return false;
	},

	getLength: function() {
		if (this._length == null) {
			var curves = this.getCurves();
			this._length = 0;
			for (var i = 0, l = curves.length; i < l; i++)
				this._length += curves[i].getLength();
		}
		return this._length;
	},

	_getOffset: function(location) {
		var index = location && location.getIndex();
		if (index != null) {
			var curves = this.getCurves(),
				offset = 0;
			for (var i = 0; i < index; i++)
				offset += curves[i].getLength();
			var curve = curves[index];
			return offset + curve.getLength(0, location.getParameter());
		}
		return null;
	},

	getLocation: function(point) {
		var curves = this.getCurves();
		for (var i = 0, l = curves.length; i < l; i++) {
			var curve = curves[i];
			var t = curve.getParameter(point);
			if (t != null)
				return new CurveLocation(curve, t);
		}
		return null;
	},

	getLocationAt: function(offset, isParameter) {
		var curves = this.getCurves(),
			length = 0;
		if (isParameter) {
			var index = ~~offset; 
			return new CurveLocation(curves[index], offset - index);
		}
		for (var i = 0, l = curves.length; i < l; i++) {
			var start = length,
				curve = curves[i];
			length += curve.getLength();
			if (length >= offset) {
				return new CurveLocation(curve,
						curve.getParameterAt(offset - start));
			}
		}
		if (offset <= this.getLength())
			return new CurveLocation(curves[curves.length - 1], 1);
		return null;
	},

	getPointAt: function(offset, isParameter) {
		var loc = this.getLocationAt(offset, isParameter);
		return loc && loc.getPoint();
	},

	getTangentAt: function(offset, isParameter) {
		var loc = this.getLocationAt(offset, isParameter);
		return loc && loc.getTangent();
	},

	getNormalAt: function(offset, isParameter) {
		var loc = this.getLocationAt(offset, isParameter);
		return loc && loc.getNormal();
	},

	getNearestLocation: function(point, matrix) {
		var curves = this.getCurves(),
			minDist = Infinity,
			minLoc = null;
		for (var i = 0, l = curves.length; i < l; i++) {
			var loc = curves[i].getNearestLocation(point, matrix);
			if (loc._distance < minDist) {
				minDist = loc._distance;
				minLoc = loc;
			}
		}
		return minLoc;
	},

	getNearestPoint: function(point, matrix) {
		return this.getNearestLocation(point, matrix).getPoint();
	},

	contains: function(point, matrix) {
		point = Point.read(arguments);
		if (!this._closed || !this.getRoughBounds(matrix)._containsPoint(point))
			return false;
		var curves = this.getCurves(),
			crossings = 0,
			roots = [];
		for (var i = 0, l = curves.length; i < l; i++)
			crossings += curves[i].getCrossings(point, matrix, roots);
		return (crossings & 1) == 1;
	},

	_hitTest: function(point, options, matrix) {
		var tolerance = options.tolerance || 0,
			radius = (options.stroke ? this.getStrokeWidth() / 2 : 0) + tolerance,
			loc,
			res;
		var coords = [],
			that = this;
		function checkSegment(segment, ends) {
			segment._transformCoordinates(matrix, coords);
			for (var j = ends || options.segments ? 0 : 2,
					m = !ends && options.handles ? 6 : 2; j < m; j += 2) {
				if (point.getDistance(coords[j], coords[j + 1]) < tolerance)
					return new HitResult(j == 0 ? 'segment'
							: 'handle-' + (j == 2 ? 'in' : 'out'),
							that, { segment: segment });
			}
		}
		if (options.ends && !options.segments && !this._closed) {
			if (res = checkSegment(this.getFirstSegment(), true)
					|| checkSegment(this.getLastSegment(), true))
				return res;
		} else if (options.segments || options.handles) {
			for (var i = 0, l = this._segments.length; i < l; i++) {
				if (res = checkSegment(this._segments[i]))
					return res;
			}
		}
		if (options.stroke && radius > 0)
			loc = this.getNearestLocation(point, matrix);
		if (!(loc && loc._distance <= radius) && options.fill
				&& this.getFillColor() && this.contains(point, matrix))
			return new HitResult('fill', this);
		if (!loc && options.stroke && radius > 0)
			loc = this.getNearestLocation(point, matrix);
		if (loc && loc._distance <= radius)
			return options.stroke
					? new HitResult('stroke', this, { location: loc })
					: new HitResult('fill', this);
	}

}, new function() { 

	function drawHandles(ctx, segments) {
		for (var i = 0, l = segments.length; i < l; i++) {
			var segment = segments[i],
				point = segment._point,
				state = segment._selectionState,
				selected = state & SelectionState.POINT;
			if (selected || (state & SelectionState.HANDLE_IN))
				drawHandle(ctx, point, segment._handleIn);
			if (selected || (state & SelectionState.HANDLE_OUT))
				drawHandle(ctx, point, segment._handleOut);
			ctx.save();
			ctx.beginPath();
			ctx.rect(point._x - 2, point._y - 2, 4, 4);
			ctx.fill();
			if (!selected) {
				ctx.beginPath();
				ctx.rect(point._x - 1, point._y - 1, 2, 2);
				ctx.fillStyle = '#ffffff';
				ctx.fill();
			}
			ctx.restore();
		}
	}

	function drawHandle(ctx, point, handle) {
		if (!handle.isZero()) {
			var handleX = point._x + handle._x,
				handleY = point._y + handle._y;
			ctx.beginPath();
			ctx.moveTo(point._x, point._y);
			ctx.lineTo(handleX, handleY);
			ctx.stroke();
			ctx.beginPath();
			ctx.arc(handleX, handleY, 1.75, 0, Math.PI * 2, true);
			ctx.fill();
		}
	}

	function drawSegments(ctx, path) {
		var segments = path._segments,
			length = segments.length,
			handleOut, outX, outY;

		function drawSegment(i) {
			var segment = segments[i],
				point = segment._point,
				x = point._x,
				y = point._y,
				handleIn = segment._handleIn;
			if (!handleOut) {
				ctx.moveTo(x, y);
			} else {
				if (handleIn.isZero() && handleOut.isZero()) {
					ctx.lineTo(x, y);
				} else {
					ctx.bezierCurveTo(outX, outY,
							handleIn._x + x, handleIn._y + y, x, y);
				}
			}
			handleOut = segment._handleOut;
			outX = handleOut._x + x;
			outY = handleOut._y + y;
		}

		for (var i = 0; i < length; i++)
			drawSegment(i);
		if (path._closed && length > 1)
			drawSegment(0);
	}

	function drawDashes(ctx, path, dashArray, dashOffset) {
		var flattener = new PathFlattener(path),
			from = dashOffset, to,
			i = 0;
		while (from < flattener.length) {
			to = from + dashArray[(i++) % dashArray.length];
			flattener.drawPart(ctx, from, to);
			from = to + dashArray[(i++) % dashArray.length];
		}
	}

	return {
		draw: function(ctx, param) {
			if (!param.compound)
				ctx.beginPath();

			var fillColor = this.getFillColor(),
				strokeColor = this.getStrokeColor(),
				dashArray = this.getDashArray() || [], 
				hasDash = !!dashArray.length;

			if (param.compound || param.selection || this._clipMask || fillColor
					|| strokeColor && !hasDash) {
				drawSegments(ctx, this);
			}

			if (param.selection) {
				ctx.stroke();
				drawHandles(ctx, this._segments);
			} else if (this._clipMask) {
				ctx.clip();
			} else if (!param.compound && (fillColor || strokeColor)) {
				ctx.save();
				this._setStyles(ctx);
				if (!fillColor || !strokeColor)
					ctx.globalAlpha = this._opacity;
				if (fillColor) {
					ctx.fillStyle = fillColor.getCanvasStyle(ctx);
					ctx.fill();
				}
				if (strokeColor) {
					ctx.strokeStyle = strokeColor.getCanvasStyle(ctx);
					if (hasDash) {
						ctx.beginPath();
						drawDashes(ctx, this, dashArray, this.getDashOffset());
					}
					ctx.stroke();
				}
				ctx.restore();
			}
		}
	};
}, new function() { 

	function getFirstControlPoints(rhs) {
		var n = rhs.length,
			x = [], 
			tmp = [], 
			b = 2;
		x[0] = rhs[0] / b;
		for (var i = 1; i < n; i++) {
			tmp[i] = 1 / b;
			b = (i < n - 1 ? 4 : 2) - tmp[i];
			x[i] = (rhs[i] - x[i - 1]) / b;
		}
		for (var i = 1; i < n; i++) {
			x[n - i - 1] -= tmp[n - i] * x[n - i];
		}
		return x;
	};

	var styles = {
		getStrokeWidth: 'lineWidth',
		getStrokeJoin: 'lineJoin',
		getStrokeCap: 'lineCap',
		getMiterLimit: 'miterLimit'
	};

	return {
		_setStyles: function(ctx) {
			for (var i in styles) {
				var style = this._style[i]();
				if (style)
					ctx[styles[i]] = style;
			}
		},

		smooth: function() {
			var segments = this._segments,
				size = segments.length,
				n = size,
				overlap;

			if (size <= 2)
				return;

			if (this._closed) {
				overlap = Math.min(size, 4);
				n += Math.min(size, overlap) * 2;
			} else {
				overlap = 0;
			}
			var knots = [];
			for (var i = 0; i < size; i++)
				knots[i + overlap] = segments[i]._point;
			if (this._closed) {
				for (var i = 0; i < overlap; i++) {
					knots[i] = segments[i + size - overlap]._point;
					knots[i + size + overlap] = segments[i]._point;
				}
			} else {
				n--;
			}
			var rhs = [];

			for (var i = 1; i < n - 1; i++)
				rhs[i] = 4 * knots[i]._x + 2 * knots[i + 1]._x;
			rhs[0] = knots[0]._x + 2 * knots[1]._x;
			rhs[n - 1] = 3 * knots[n - 1]._x;
			var x = getFirstControlPoints(rhs);

			for (var i = 1; i < n - 1; i++)
				rhs[i] = 4 * knots[i]._y + 2 * knots[i + 1]._y;
			rhs[0] = knots[0]._y + 2 * knots[1]._y;
			rhs[n - 1] = 3 * knots[n - 1]._y;
			var y = getFirstControlPoints(rhs);

			if (this._closed) {
				for (var i = 0, j = size; i < overlap; i++, j++) {
					var f1 = (i / overlap);
					var f2 = 1 - f1;
					x[j] = x[i] * f1 + x[j] * f2;
					y[j] = y[i] * f1 + y[j] * f2;
					var ie = i + overlap, je = j + overlap;
					x[je] = x[ie] * f2 + x[je] * f1;
					y[je] = y[ie] * f2 + y[je] * f1;
				}
				n--;
			}
			var handleIn = null;
			for (var i = overlap; i <= n - overlap; i++) {
				var segment = segments[i - overlap];
				if (handleIn)
					segment.setHandleIn(handleIn.subtract(segment._point));
				if (i < n) {
					segment.setHandleOut(
							new Point(x[i], y[i]).subtract(segment._point));
					if (i < n - 1)
						handleIn = new Point(
								2 * knots[i + 1]._x - x[i + 1],
								2 * knots[i + 1]._y - y[i + 1]);
					else
						handleIn = new Point(
								(knots[n]._x + x[n - 1]) / 2,
								(knots[n]._y + y[n - 1]) / 2);
				}
			}
			if (this._closed && handleIn) {
				var segment = this._segments[0];
				segment.setHandleIn(handleIn.subtract(segment._point));
			}
		}
	};
}, new function() { 
	function getCurrentSegment(that) {
		var segments = that._segments;
		if (segments.length == 0)
			throw new Error('Use a moveTo() command first');
		return segments[segments.length - 1];
	}

	return {
		moveTo: function(point) {
			if (!this._segments.length)
				this._add([ new Segment(Point.read(arguments)) ]);
		},

		moveBy: function(point) {
			throw new Error('moveBy() is unsupported on Path items.');
		},

		lineTo: function(point) {
			this._add([ new Segment(Point.read(arguments)) ]);
		},

		cubicCurveTo: function(handle1, handle2, to) {
			handle1 = Point.read(arguments, 0, 1);
			handle2 = Point.read(arguments, 1, 1);
			to = Point.read(arguments, 2, 1);
			var current = getCurrentSegment(this);
			current.setHandleOut(handle1.subtract(current._point));
			this._add([ new Segment(to, handle2.subtract(to)) ]);
		},

		quadraticCurveTo: function(handle, to) {
			handle = Point.read(arguments, 0, 1);
			to = Point.read(arguments, 1, 1);
			var current = getCurrentSegment(this)._point;
			this.cubicCurveTo(
				handle.add(current.subtract(handle).multiply(1/3)),
				handle.add(to.subtract(handle).multiply(1/3)),
				to
			);
		},

		curveTo: function(through, to, parameter) {
			through = Point.read(arguments, 0, 1);
			to = Point.read(arguments, 1, 1);
			var t = Base.pick(parameter, 0.5),
				t1 = 1 - t,
				current = getCurrentSegment(this)._point,
				handle = through.subtract(current.multiply(t1 * t1))
					.subtract(to.multiply(t * t)).divide(2 * t * t1);
			if (handle.isNaN())
				throw new Error(
					'Cannot put a curve through points with parameter = ' + t);
			this.quadraticCurveTo(handle, to);
		},

		arcTo: function(to, clockwise ) {
			var current = getCurrentSegment(this),
				from = current._point,
				through;
			if (clockwise === undefined)
				clockwise = true;
			if (typeof clockwise === 'boolean') {
				to = Point.read(arguments, 0, 1);
				var middle = from.add(to).divide(2),
				through = middle.add(middle.subtract(from).rotate(
						clockwise ? -90 : 90));
			} else {
				through = Point.read(arguments, 0, 1);
				to = Point.read(arguments, 1, 1);
			}
			var l1 = new Line(from.add(through).divide(2),
					through.subtract(from).rotate(90)),
			 	l2 = new Line(through.add(to).divide(2),
					to.subtract(through).rotate(90)),
				center = l1.intersect(l2),
				line = new Line(from, to, true),
				throughSide = line.getSide(through);
			if (!center) {
				if (!throughSide)
					return this.lineTo(to);
				throw new Error("Cannot put an arc through the given points: "
					+ [from, through, to]);
			}
			var vector = from.subtract(center),
				radius = vector.getLength(),
				extent = vector.getDirectedAngle(to.subtract(center)),
				centerSide = line.getSide(center);
			if (centerSide == 0) {
				extent = throughSide * Math.abs(extent);
			} else if (throughSide == centerSide) {
				extent -= 360 * (extent < 0 ? -1 : 1);
			}
			var ext = Math.abs(extent),
				count =  ext >= 360 ? 4 : Math.ceil(ext / 90),
				inc = extent / count,
				half = inc * Math.PI / 360,
				z = 4 / 3 * Math.sin(half) / (1 + Math.cos(half)),
				segments = [];
			for (var i = 0; i <= count; i++) {
				var pt = i < count ? center.add(vector) : to;
				var out = i < count ? vector.rotate(90).multiply(z) : null;
				if (i == 0) {
					current.setHandleOut(out);
				} else {
					segments.push(
						new Segment(pt, vector.rotate(-90).multiply(z), out));
				}
				vector = vector.rotate(inc);
			}
			this._add(segments);
		},

		lineBy: function(vector) {
			vector = Point.read(arguments);
			var current = getCurrentSegment(this);
			this.lineTo(current._point.add(vector));
		},

		curveBy: function(throughVector, toVector, parameter) {
			throughVector = Point.read(throughVector);
			toVector = Point.read(toVector);
			var current = getCurrentSegment(this)._point;
			this.curveTo(current.add(throughVector), current.add(toVector),
					parameter);
		},

		arcBy: function(throughVector, toVector) {
			throughVector = Point.read(throughVector);
			toVector = Point.read(toVector);
			var current = getCurrentSegment(this)._point;
			this.arcBy(current.add(throughVector), current.add(toVector));
		},

		closePath: function() {
			this.setClosed(true);
		}
	};
}, new function() { 

	function getBounds(that, matrix, strokePadding) {
		var segments = that._segments,
			first = segments[0];
		if (!first)
			return null;
		var coords = new Array(6),
			prevCoords = new Array(6);
		if (matrix && matrix.isIdentity())
			matrix = null;
		first._transformCoordinates(matrix, prevCoords, false);
		var min = prevCoords.slice(0, 2),
			max = min.slice(0), 
			tMin = Numerical.TOLERANCE,
			tMax = 1 - tMin;
		function processSegment(segment) {
			segment._transformCoordinates(matrix, coords, false);

			for (var i = 0; i < 2; i++) {
				var v0 = prevCoords[i], 
					v1 = prevCoords[i + 4], 
					v2 = coords[i + 2], 
					v3 = coords[i]; 

				function add(value, t) {
					var padding = 0;
					if (value == null) {
						var u = 1 - t;
						value = u * u * u * v0
								+ 3 * u * u * t * v1
								+ 3 * u * t * t * v2
								+ t * t * t * v3;
						padding = strokePadding ? strokePadding[i] : 0;
					}
					var left = value - padding,
						right = value + padding;
					if (left < min[i])
						min[i] = left;
					if (right > max[i])
						max[i] = right;

				}
				add(v3, null);

				var a = 3 * (v1 - v2) - v0 + v3,
					b = 2 * (v0 + v2) - 4 * v1,
					c = v1 - v0;

				if (a == 0) {
					if (b == 0)
					    continue;
					var t = -c / b;
					if (tMin < t && t < tMax)
						add(null, t);
					continue;
				}

				var q = b * b - 4 * a * c;
				if (q < 0)
					continue;
				var sqrt = Math.sqrt(q),
					f = -0.5 / a,
				 	t1 = (b - sqrt) * f,
					t2 = (b + sqrt) * f;
				if (tMin < t1 && t1 < tMax)
					add(null, t1);
				if (tMin < t2 && t2 < tMax)
					add(null, t2);
			}
			var tmp = prevCoords;
			prevCoords = coords;
			coords = tmp;
		}
		for (var i = 1, l = segments.length; i < l; i++)
			processSegment(segments[i]);
		if (that._closed)
			processSegment(first);
		return Rectangle.create(min[0], min[1],
					max[0] - min[0], max[1] - min[1]);
	}

	function getPenPadding(radius, matrix) {
		if (!matrix)
			return [radius, radius];
		var mx = matrix.createShiftless(),
			hor = mx.transform(new Point(radius, 0)),
			ver = mx.transform(new Point(0, radius)),
			phi = hor.getAngleInRadians(),
			a = hor.getLength(),
			b = ver.getLength();
		var tx = - Math.atan(b * Math.tan(phi)),
			ty = + Math.atan(b / Math.tan(phi)),
			x = a * Math.cos(tx) * Math.cos(phi)
				- b * Math.sin(tx) * Math.sin(phi),
			y = b * Math.sin(ty) * Math.cos(phi)
				+ a * Math.cos(ty) * Math.sin(phi);
		return [Math.abs(x), Math.abs(y)];
	}

	return {
		getBounds: function() {
			var useCache = arguments[0] === undefined;
			if (useCache && this._bounds)
				return this._bounds;
			var bounds = this._createBounds(getBounds(this, arguments[0]));
			if (useCache)
				this._bounds = bounds;
			return bounds;
		},

		getStrokeBounds: function() {
			if (!this._style._strokeColor || !this._style._strokeWidth)
				return this.getBounds.apply(this, arguments);
			var useCache = arguments[0] === undefined;
			if (useCache && this._strokeBounds)
				return this._strokeBounds;
			var matrix = arguments[0], 
				width = this.getStrokeWidth(),
				radius = width / 2,
				padding = getPenPadding(radius, matrix),
				join = this.getStrokeJoin(),
				cap = this.getStrokeCap(),
				miter = this.getMiterLimit() * width / 2,
				segments = this._segments,
				length = segments.length,
				bounds = getBounds(this, matrix, getPenPadding(radius));
			var joinBounds = new Rectangle(new Size(padding).multiply(2));

			function add(point) {
				bounds = bounds.include(matrix
					? matrix.transform(point) : point);
			}

			function addBevelJoin(curve, t) {
				var point = curve.getPoint(t),
					normal = curve.getNormal(t).normalize(radius);
				add(point.add(normal));
				add(point.subtract(normal));
			}

			function addJoin(segment, join) {
				if (join === 'round' || !segment._handleIn.isZero()
						&& !segment._handleOut.isZero()) {
					bounds = bounds.unite(joinBounds.setCenter(matrix
						? matrix.transform(segment._point) : segment._point));
				} else if (join == 'bevel') {
					var curve = segment.getCurve();
					addBevelJoin(curve, 0);
					addBevelJoin(curve.getPrevious(), 1);
				} else if (join == 'miter') {
					var curve2 = segment.getCurve(),
						curve1 = curve2.getPrevious(),
						point = curve2.getPoint(0),
						normal1 = curve1.getNormal(1).normalize(radius),
						normal2 = curve2.getNormal(0).normalize(radius),
						line1 = new Line(point.subtract(normal1),
								new Point(-normal1.y, normal1.x)),
						line2 = new Line(point.subtract(normal2),
								new Point(-normal2.y, normal2.x)),
						corner = line1.intersect(line2);
					if (!corner || point.getDistance(corner) > miter) {
						addJoin(segment, 'bevel');
					} else {
						add(corner);
					}
				}
			}

			function addCap(segment, cap, t) {
				switch (cap) {
				case 'round':
					return addJoin(segment, cap);
				case 'butt':
				case 'square':
					var curve = segment.getCurve(),
						point = curve.getPoint(t),
						normal = curve.getNormal(t).normalize(radius);
					if (cap === 'square')
						point = point.add(normal.y, -normal.x);
					add(point.add(normal));
					add(point.subtract(normal));
					break;
				}
			}

			for (var i = 1, l = length - (this._closed ? 0 : 1); i < l; i++) {
				addJoin(segments[i], join);
			}
			if (this._closed) {
				addJoin(segments[0], join);
			} else {
				addCap(segments[0], cap, 0);
				addCap(segments[length - 1], cap, 1);
			}
			if (useCache)
				this._strokeBounds = bounds;
			return bounds;
		},

		getHandleBounds: function() {
			var matrix = arguments[0],
				useCache = matrix === undefined;
			if (useCache && this._handleBounds)
				return this._handleBounds;
			var coords = new Array(6),
				stroke = arguments[1] / 2 || 0, 
				join = arguments[2] / 2 || 0, 
				open = !this._closed,
				x1 = Infinity,
				x2 = -x1,
				y1 = x1,
				y2 = x2;
			for (var i = 0, l = this._segments.length; i < l; i++) {
				var segment = this._segments[i];
				segment._transformCoordinates(matrix, coords, false);
				for (var j = 0; j < 6; j += 2) {
					var padding = j == 0 ? join : stroke,
						x = coords[j],
						y = coords[j + 1],
						xn = x - padding,
						xx = x + padding,
						yn = y - padding,
						yx = y + padding;
					if (xn < x1) x1 = xn;
					if (xx > x2) x2 = xx;
					if (yn < y1) y1 = yn;
					if (yx > y2) y2 = yx;
				}
			}
			var bounds = Rectangle.create(x1, y1, x2 - x1, y2 - y1);
			if (useCache)
				this._handleBounds = bounds;
			return bounds;
		},

		getRoughBounds: function() {
			var useCache = arguments[0] === undefined;
			if (useCache && this._roughBounds)
				return this._roughBounds;
			var bounds = this.getHandleBounds(arguments[0], this.strokeWidth,
					this.getStrokeJoin() == 'miter'
						? this.strokeWidth * this.getMiterLimit()
						: this.strokeWidth);
			if (useCache)
				this._roughBounds = bounds;
			return bounds;
		}
	};
});

Path.inject({ statics: new function() {
	var kappa = 2 / 3 * (Math.sqrt(2) - 1);

	var ovalSegments = [
		new Segment([0, 0.5], [0, kappa ], [0, -kappa]),
		new Segment([0.5, 0], [-kappa, 0], [kappa, 0 ]),
		new Segment([1, 0.5], [0, -kappa], [0, kappa ]),
		new Segment([0.5, 1], [kappa, 0 ], [-kappa, 0])
	];

	return {
		Line: function() {
			var step = Math.floor(arguments.length / 2);
			return new Path(
				Segment.read(arguments, 0, step),
				Segment.read(arguments, step, step)
			);
		},

		Rectangle: function(rect) {
			rect = Rectangle.read(arguments);
			var left = rect.x,
				top = rect.y
				right = left + rect.width,
				bottom = top + rect.height,
				path = new Path();
			path._add([
				new Segment(Point.create(left, bottom)),
				new Segment(Point.create(left, top)),
				new Segment(Point.create(right, top)),
				new Segment(Point.create(right, bottom))
			]);
			path._closed = true;
			return path;
		},

		RoundRectangle: function(rect, size) {
			if (arguments.length == 2) {
				rect = Rectangle.read(arguments, 0, 1);
				size = Size.read(arguments, 1, 1);
			} else if (arguments.length == 6) {
				rect = Rectangle.read(arguments, 0, 4);
				size = Size.read(arguments, 4, 2);
			}
			size = Size.min(size, rect.getSize(true).divide(2));
			var path = new Path(),
				uSize = size.multiply(kappa * 2),
				bl = rect.getBottomLeft(true),
				tl = rect.getTopLeft(true),
				tr = rect.getTopRight(true),
				br = rect.getBottomRight(true);
			path._add([
				new Segment(bl.add(size.width, 0), null, [-uSize.width, 0]),
				new Segment(bl.subtract(0, size.height), [0, uSize.height], null),

				new Segment(tl.add(0, size.height), null, [0, -uSize.height]),
				new Segment(tl.add(size.width, 0), [-uSize.width, 0], null),

				new Segment(tr.subtract(size.width, 0), null, [uSize.width, 0]),
				new Segment(tr.add(0, size.height), [0, -uSize.height], null),

				new Segment(br.subtract(0, size.height), null, [0, uSize.height]),
				new Segment(br.subtract(size.width, 0), [uSize.width, 0], null)
			]);
			path._closed = true;
			return path;
		},

		Oval: function(rect) {
			rect = Rectangle.read(arguments);
			var path = new Path(),
				point = rect.getPoint(true),
				size = rect.getSize(true),
				segments = new Array(4);
			for (var i = 0; i < 4; i++) {
				var segment = ovalSegments[i];
				segments[i] = new Segment(
					segment._point.multiply(size).add(point),
					segment._handleIn.multiply(size),
					segment._handleOut.multiply(size)
				);
			}
			path._add(segments);
			path._closed = true;
			return path;
		},

		Circle: function(center, radius) {
			if (arguments.length == 3) {
				center = Point.read(arguments, 0, 2);
				radius = arguments[2];
			} else {
				center = Point.read(arguments, 0, 1);
			}
			return Path.Oval(new Rectangle(center.subtract(radius),
					Size.create(radius * 2, radius * 2)));
		},

		Arc: function(from, through, to) {
			var path = new Path();
			path.moveTo(from);
			path.arcTo(through, to);
			return path;
		},

		RegularPolygon: function(center, numSides, radius) {
			center = Point.read(arguments, 0, 1);
			var path = new Path(),
				step = 360 / numSides,
				three = !(numSides % 3),
				vector = new Point(0, three ? -radius : radius),
				offset = three ? -1 : 0.5,
				segments = new Array(numSides);
			for (var i = 0; i < numSides; i++) {
				segments[i] = new Segment(center.add(
					vector.rotate((i + offset) * step)));
			}
			path._add(segments);
			path._closed = true;
			return path;
		},

		Star: function(center, numPoints, radius1, radius2) {
			center = Point.read(arguments, 0, 1);
			numPoints *= 2;
			var path = new Path(),
				step = 360 / numPoints,
				vector = new Point(0, -1),
				segments = new Array(numPoints);
			for (var i = 0; i < numPoints; i++) {
				segments[i] = new Segment(center.add(
					vector.rotate(step * i).multiply(i % 2 ? radius2 : radius1)));
			}
			path._add(segments);
			path._closed = true;
			return path;
		}
	};
}});

var CompoundPath = this.CompoundPath = PathItem.extend({
	initialize: function(paths) {
		this.base();
		this._children = [];
		this._namedChildren = {};
		var items = !paths || !Array.isArray(paths)
				|| typeof paths[0] !== 'object' ? arguments : paths;
		this.addChildren(items);
	},

	insertChild: function(index, item) {
		this.base(index, item);
		if (item._clockwise === undefined)
			item.setClockwise(item._index == 0);
	},

	simplify: function() {
		if (this._children.length == 1) {
			var child = this._children[0];
			child.insertAbove(this);
			this.remove();
			return child;
		}
		return this;
	},

	smooth: function() {
		for (var i = 0, l = this._children.length; i < l; i++)
			this._children[i].smooth();
	},

	draw: function(ctx, param) {
		var l = this._children.length;
		if (l == 0) {
			return;
		}
		var firstChild = this._children[0];
		ctx.beginPath();
		param.compound = true;
		for (var i = 0; i < l; i++)
			Item.draw(this._children[i], ctx, param);
		firstChild._setStyles(ctx);
		var fillColor = firstChild.getFillColor(),
			strokeColor = firstChild.getStrokeColor();
		if (fillColor) {
			ctx.fillStyle = fillColor.getCanvasStyle(ctx);
			ctx.fill();
		}
		if (strokeColor) {
			ctx.strokeStyle = strokeColor.getCanvasStyle(ctx);
			ctx.stroke();
		}
		param.compound = false;
	}
}, new function() { 
	function getCurrentPath(that) {
		if (!that._children.length)
			throw new Error('Use a moveTo() command first');
		return that._children[that._children.length - 1];
	}

	var fields = {
		moveTo: function(point) {
			var path = new Path();
			this.addChild(path);
			path.moveTo.apply(path, arguments);
		},

		moveBy: function(point) {
			this.moveTo(getCurrentPath(this).getLastSegment()._point.add(
					Point.read(arguments)));
		},

		closePath: function() {
			getCurrentPath(this).setClosed(true);
		}
	};

	Base.each(['lineTo', 'cubicCurveTo', 'quadraticCurveTo', 'curveTo',
			'arcTo', 'lineBy', 'curveBy', 'arcBy'], function(key) {
		fields[key] = function() {
			var path = getCurrentPath(this);
			path[key].apply(path, arguments);
		};
	});

	return fields;
});

var PathFlattener = Base.extend({
	initialize: function(path) {
		this.curves = []; 
		this.parts = []; 
		this.length = 0; 
		this.index = 0;

		var segments = path._segments,
			segment1 = segments[0],
			segment2,
			that = this;

		function addCurve(segment1, segment2) {
			var curve = Curve.getValues(segment1, segment2);
			that.curves.push(curve);
			that._computeParts(curve, segment1._index, 0, 1);
		}

		for (var i = 1, l = segments.length; i < l; i++) {
			segment2 = segments[i];
			addCurve(segment1, segment2);
			segment1 = segment2;
		}
		if (path._closed)
			addCurve(segment2, segments[0]);
	},

	_computeParts: function(curve, index, minT, maxT) {
		if ((maxT - minT) > 1 / 32 && !Curve.isFlatEnough(curve)) {
			var curves = Curve.subdivide(curve);
			var halfT = (minT + maxT) / 2;
			this._computeParts(curves[0], index, minT, halfT);
			this._computeParts(curves[1], index, halfT, maxT);
		} else {
			var x = curve[6] - curve[0],
				y = curve[7] - curve[1],
				dist = Math.sqrt(x * x + y * y);
			if (dist > Numerical.TOLERANCE) {
				this.length += dist;
				this.parts.push({
					offset: this.length,
					value: maxT,
					index: index
				});
			}
		}
	},

	getParameterAt: function(offset) {
		var i, j = this.index;
		for (;;) {
			i = j;
			if (j == 0 || this.parts[--j].offset < offset)
				break;
		}
		for (var l = this.parts.length; i < l; i++) {
			var part = this.parts[i];
			if (part.offset >= offset) {
				this.index = i;
				var prev = this.parts[i - 1];
				var prevVal = prev && prev.index == part.index ? prev.value : 0,
					prevLen = prev ? prev.offset : 0;
				return {
					value: prevVal + (part.value - prevVal)
						* (offset - prevLen) /  (part.offset - prevLen),
					index: part.index
				};
			}
		}
		var part = this.parts[this.parts.length - 1];
		return {
			value: 1,
			index: part.index
		};
	},

	evaluate: function(offset, type) {
		var param = this.getParameterAt(offset);
		return Curve.evaluate(this.curves[param.index], param.value, type);
	},

	drawPart: function(ctx, from, to) {
		from = this.getParameterAt(from);
		to = this.getParameterAt(to);
		for (var i = from.index; i <= to.index; i++) {
			var curve = Curve.getPart(this.curves[i],
					i == from.index ? from.value : 0,
					i == to.index ? to.value : 1);
			if (i == from.index)
				ctx.moveTo(curve[0], curve[1]);
			ctx.bezierCurveTo.apply(ctx, curve.slice(2));
		}
	}
});

var PathFitter = Base.extend({
	initialize: function(path, error) {
		this.points = [];
		var segments = path._segments,
			prev;
		for (var i = 0, l = segments.length; i < l; i++) {
			var point = segments[i].point.clone();
			if (!prev || !prev.equals(point)) {
				this.points.push(point);
				prev = point;
			}
		}
		this.error = error;
	},

	fit: function() {
		this.segments = [new Segment(this.points[0])];
		this.fitCubic(0, this.points.length - 1,
				this.points[1].subtract(this.points[0]).normalize(),
				this.points[this.points.length - 2].subtract(
					this.points[this.points.length - 1]).normalize());
		return this.segments;
	},

	fitCubic: function(first, last, tan1, tan2) {
		if (last - first == 1) {
			var pt1 = this.points[first],
				pt2 = this.points[last],
				dist = pt1.getDistance(pt2) / 3;
			this.addCurve([pt1, pt1.add(tan1.normalize(dist)),
					pt2.add(tan2.normalize(dist)), pt2]);
			return;
		}
		var uPrime = this.chordLengthParameterize(first, last),
			maxError = Math.max(this.error, this.error * this.error),
			error,
			split;
		for (var i = 0; i <= 4; i++) {
			var curve = this.generateBezier(first, last, uPrime, tan1, tan2);
			var max = this.findMaxError(first, last, curve, uPrime);
			if (max.error < this.error) {
				this.addCurve(curve);
				return;
			}
			split = max.index;
			if (max.error >= maxError)
				break;
			this.reparameterize(first, last, uPrime, curve);
			maxError = max.error;
		}
		var V1 = this.points[split - 1].subtract(this.points[split]),
			V2 = this.points[split].subtract(this.points[split + 1]),
			tanCenter = V1.add(V2).divide(2).normalize();
		this.fitCubic(first, split, tan1, tanCenter);
		this.fitCubic(split, last, tanCenter.negate(), tan2);
	},

	addCurve: function(curve) {
		var prev = this.segments[this.segments.length - 1];
		prev.setHandleOut(curve[1].subtract(curve[0]));
		this.segments.push(
				new Segment(curve[3], curve[2].subtract(curve[3])));
	},

	generateBezier: function(first, last, uPrime, tan1, tan2) {
		var epsilon = Numerical.EPSILON,
			pt1 = this.points[first],
			pt2 = this.points[last],
		 	C = [[0, 0], [0, 0]],
			X = [0, 0];

		for (var i = 0, l = last - first + 1; i < l; i++) {
			var u = uPrime[i],
				t = 1 - u,
				b = 3 * u * t,
				b0 = t * t * t,
				b1 = b * t,
				b2 = b * u,
				b3 = u * u * u,
				a1 = tan1.normalize(b1),
				a2 = tan2.normalize(b2),
				tmp = this.points[first + i]
					.subtract(pt1.multiply(b0 + b1))
					.subtract(pt2.multiply(b2 + b3));
			C[0][0] += a1.dot(a1);
			C[0][1] += a1.dot(a2);
			C[1][0] = C[0][1];
			C[1][1] += a2.dot(a2);
			X[0] += a1.dot(tmp);
			X[1] += a2.dot(tmp);
		}

		var detC0C1 = C[0][0] * C[1][1] - C[1][0] * C[0][1],
			alpha1, alpha2;
		if (Math.abs(detC0C1) > epsilon) {
			var detC0X  = C[0][0] * X[1]    - C[1][0] * X[0],
				detXC1  = X[0]    * C[1][1] - X[1]    * C[0][1];
			alpha1 = detXC1 / detC0C1;
			alpha2 = detC0X / detC0C1;
		} else {
			var c0 = C[0][0] + C[0][1],
				c1 = C[1][0] + C[1][1];
			if (Math.abs(c0) > epsilon) {
				alpha1 = alpha2 = X[0] / c0;
			} else if (Math.abs(c0) > epsilon) {
				alpha1 = alpha2 = X[1] / c1;
			} else {
				alpha1 = alpha2 = 0.;
			}
		}

		var segLength = pt2.getDistance(pt1);
		epsilon *= segLength;
		if (alpha1 < epsilon || alpha2 < epsilon) {
			alpha1 = alpha2 = segLength / 3;
		}

		return [pt1, pt1.add(tan1.normalize(alpha1)),
				pt2.add(tan2.normalize(alpha2)), pt2];
	},

	reparameterize: function(first, last, u, curve) {
		for (var i = first; i <= last; i++) {
			u[i - first] = this.findRoot(curve, this.points[i], u[i - first]);
		}
	},

	findRoot: function(curve, point, u) {
		var curve1 = [],
			curve2 = [];
		for (var i = 0; i <= 2; i++) {
			curve1[i] = curve[i + 1].subtract(curve[i]).multiply(3);
		}
		for (var i = 0; i <= 1; i++) {
			curve2[i] = curve1[i + 1].subtract(curve1[i]).multiply(2);
		}
		var pt = this.evaluate(3, curve, u),
		 	pt1 = this.evaluate(2, curve1, u),
		 	pt2 = this.evaluate(1, curve2, u),
		 	diff = pt.subtract(point),
			df = pt1.dot(pt1) + diff.dot(pt2);
		if (Math.abs(df) < Numerical.TOLERANCE)
			return u;
		return u - diff.dot(pt1) / df;
	},

	evaluate: function(degree, curve, t) {
		var tmp = curve.slice();
		for (var i = 1; i <= degree; i++) {
			for (var j = 0; j <= degree - i; j++) {
				tmp[j] = tmp[j].multiply(1 - t).add(tmp[j + 1].multiply(t));
			}
		}
		return tmp[0];
	},

	chordLengthParameterize: function(first, last) {
		var u = [0];
		for (var i = first + 1; i <= last; i++) {
			u[i - first] = u[i - first - 1]
					+ this.points[i].getDistance(this.points[i - 1]);
		}
		for (var i = 1, m = last - first; i <= m; i++) {
			u[i] /= u[m];
		}
		return u;
	},

	findMaxError: function(first, last, curve, u) {
		var index = Math.floor((last - first + 1) / 2),
			maxDist = 0;
		for (var i = first + 1; i < last; i++) {
			var P = this.evaluate(3, curve, u[i - first]);
			var v = P.subtract(this.points[i]);
			var dist = v.x * v.x + v.y * v.y; 
			if (dist >= maxDist) {
				maxDist = dist;
				index = i;
			}
		}
		return {
			error: maxDist,
			index: index
		};
	}
});

var TextItem = this.TextItem = Item.extend({
	initialize: function() {
		this.base();
		this._content = '';
		this._characterStyle = CharacterStyle.create(this);
		this.setCharacterStyle(this._project.getCurrentStyle());
		this._paragraphStyle = ParagraphStyle.create(this);
		this.setParagraphStyle();
	},

	_clone: function(copy) {
		copy._content = this._content;
		copy.setCharacterStyle(this._characterStyle);
		copy.setParagraphStyle(this._paragraphStyle);
		return this.base(copy);
	},

	getContent: function() {
		return this._content;
	},

	setContent: function(content) {
		this._changed(Change.CONTENT);
		this._content = '' + content;
	},

	getCharacterStyle: function() {
		return this._characterStyle;
	},

	setCharacterStyle: function(style) {
		this._characterStyle.initialize(style);
	},

	getParagraphStyle: function() {
		return this._paragraphStyle;
	},

	setParagraphStyle: function(style) {
		this._paragraphStyle.initialize(style);
	}
});

var PointText = this.PointText = TextItem.extend({
	initialize: function(point) {
		this.base();
		this._point = Point.read(arguments).clone();
		this._matrix = new Matrix().translate(this._point);
	},

	clone: function() {
		var copy = this._clone(new PointText(this._point));
		copy._matrix.initialize(this._matrix);
		return copy;
	},

	getPoint: function() {
		return LinkedPoint.create(this, 'setPoint',
				this._point.x, this._point.y);
	},

	setPoint: function(point) {
		this.translate(Point.read(arguments).subtract(this._point));
	},

	getPosition: function() {
		return this.getPoint();
	},

	setPosition: function(point) {
		this.setPoint.apply(this, arguments);
	},

	_transform: function(matrix, flags) {
		this._matrix.preConcatenate(matrix);
		matrix._transformPoint(this._point, this._point);
	},

	draw: function(ctx) {
		if (!this._content)
			return;
		ctx.save();
		ctx.font = this.getFontSize() + 'pt ' + this.getFont();
		ctx.textAlign = this.getJustification();
		this._matrix.applyToContext(ctx);

		var fillColor = this.getFillColor();
		var strokeColor = this.getStrokeColor();
		if (!fillColor || !strokeColor)
			ctx.globalAlpha = this._opacity;
		if (fillColor) {
			ctx.fillStyle = fillColor.getCanvasStyle(ctx);
			ctx.fillText(this._content, 0, 0);
		}
		if (strokeColor) {
			ctx.strokeStyle = strokeColor.getCanvasStyle(ctx);
			ctx.strokeText(this._content, 0, 0);
		}
		ctx.restore();
	}
});

var Style = Item.extend({
	initialize: function(style) {
		var clone = style instanceof Style;
		return Base.each(this._defaults, function(value, key) {
			value = style && style[key] || value;
			this[key] = value && clone && value.clone
					? value.clone() : value;
		}, this);
	},

	statics: {
		create: function(item) {
			var style = new this(this.dont);
			style._item = item;
			return style;
		},

		extend: function(src) {
			var styleKey = src._style,
				flags = src._flags || {};
			src._owner.inject(Base.each(src._defaults, function(value, key) {
				var isColor = !!key.match(/Color$/),
					part = Base.capitalize(key),
					set = 'set' + part,
					get = 'get' + part;
				src[set] = function(value) {
					var children = this._item && this._item._children;
					value = isColor ? Color.read(arguments) : value;
					if (children) {
						for (var i = 0, l = children.length; i < l; i++)
							children[i][styleKey][set](value);
					} else {
						var old = this['_' + key];
						if (old != value && !(old && old.equals
									&& old.equals(value))) {
							this['_' + key] = value;
							if (isColor) {
								if (old)
									old._removeOwner(this._item);
								if (value)
									value._addOwner(this._item);
							}
							if (this._item)
								this._item._changed(flags[key] || Change.STYLE);
						}
					}
					return this;
				};
				src[get] = function() {
					var children = this._item && this._item._children,
						style;
					if (!children)
						return this['_' + key];
					for (var i = 0, l = children.length; i < l; i++) {
						var childStyle = children[i][styleKey][get]();
						if (!style) {
							style = childStyle;
						} else if (style != childStyle && !(style
								&& style.equals && style.equals(childStyle))) {
							return undefined;
						}
					}
					return style;
				};
				this[set] = function(value) {
					this[styleKey][set](value);
					return this;
				};
				this[get] = function() {
					return this[styleKey][get]();
				};
			}, {}));
			return this.base(src);
		}
	}
});

var PathStyle = this.PathStyle = Style.extend({
	_defaults: {
		fillColor: undefined,
		strokeColor: undefined,
		strokeWidth: 1,
		strokeCap: 'butt',
		strokeJoin: 'miter',
		miterLimit: 10,
		dashOffset: 0,
		dashArray: []
	},
	_flags: {
		strokeWidth: Change.STROKE,
		strokeCap: Change.STROKE,
		strokeJoin: Change.STROKE,
		miterLimit: Change.STROKE
	},
	_owner: Item,
	_style: '_style'

});

var ParagraphStyle = this.ParagraphStyle = Style.extend({
	_defaults: {
		justification: 'left'
	},
	_owner: TextItem,
	_style: '_paragraphStyle'

});

var CharacterStyle = this.CharacterStyle = PathStyle.extend({
	_defaults: Base.merge(PathStyle.prototype._defaults, {
		fillColor: 'black',
		fontSize: 10,
		font: 'sans-serif'
	}),
	_owner: TextItem,
	_style: '_characterStyle'

});

var Color = this.Color = Base.extend(new function() {

	var components = {
		gray: ['gray'],
		rgb: ['red', 'green', 'blue'],
		hsb: ['hue', 'saturation', 'brightness'],
		hsl: ['hue', 'saturation', 'lightness']
	};

	var colorCache = {},
		colorContext;

	function nameToRgbColor(name) {
		var color = colorCache[name];
		if (color)
			return color.clone();
		if (!colorContext) {
			var canvas = CanvasProvider.getCanvas(Size.create(1, 1));
			colorContext = canvas.getContext('2d');
			colorContext.globalCompositeOperation = 'copy';
		}
		colorContext.fillStyle = 'rgba(0,0,0,0)';
		colorContext.fillStyle = name;
		colorContext.fillRect(0, 0, 1, 1);
		var data = colorContext.getImageData(0, 0, 1, 1).data,
			rgb = [data[0] / 255, data[1] / 255, data[2] / 255];
		return (colorCache[name] = RgbColor.read(rgb)).clone();
	}

	function hexToRgbColor(string) {
		var hex = string.match(/^#?(\w{1,2})(\w{1,2})(\w{1,2})$/);
		if (hex.length >= 4) {
			var rgb = new Array(3);
			for (var i = 0; i < 3; i++) {
				var channel = hex[i + 1];
				rgb[i] = parseInt(channel.length == 1
						? channel + channel : channel, 16) / 255;
			}
			return RgbColor.read(rgb);
		}
	}

	var hsbIndices = [
		[0, 3, 1], 
		[2, 0, 1], 
		[1, 0, 3], 
		[1, 2, 0], 
		[3, 1, 0], 
		[0, 1, 2]  
	];

	var converters = {
		'rgb-hsb': function(color) {
			var r = color._red,
				g = color._green,
				b = color._blue,
				max = Math.max(r, g, b),
				min = Math.min(r, g, b),
				delta = max - min,
				h = delta == 0 ? 0
					:   ( max == r ? (g - b) / delta + (g < b ? 6 : 0)
						: max == g ? (b - r) / delta + 2
						:            (r - g) / delta + 4) * 60, 
				s = max == 0 ? 0 : delta / max,
				v = max; 
			return new HsbColor(h, s, v, color._alpha);
		},

		'hsb-rgb': function(color) {
			var h = (color._hue / 60) % 6, 
				s = color._saturation,
				b = color._brightness,
				i = Math.floor(h), 
				f = h - i,
				i = hsbIndices[i],
				v = [
					b,						
					b * (1 - s),			
					b * (1 - s * f),		
					b * (1 - s * (1 - f))	
				];
			return new RgbColor(v[i[0]], v[i[1]], v[i[2]], color._alpha);
		},

		'rgb-hsl': function(color) {
			var r = color._red,
				g = color._green,
				b = color._blue,
				max = Math.max(r, g, b),
				min = Math.min(r, g, b),
				delta = max - min,
				achromatic = delta == 0,
				h = achromatic ? 0
					:   ( max == r ? (g - b) / delta + (g < b ? 6 : 0)
						: max == g ? (b - r) / delta + 2
						:            (r - g) / delta + 4) * 60, 
				l = (max + min) / 2,
				s = achromatic ? 0 : l < 0.5
						? delta / (max + min)
						: delta / (2 - max - min);
			return new HslColor(h, s, l, color._alpha);
		},

		'hsl-rgb': function(color) {
			var s = color._saturation,
				h = color._hue / 360,
				l = color._lightness,
				t1, t2, c;
			if (s == 0)
				return new RgbColor(l, l, l, color._alpha);
			var t3s = [ h + 1 / 3, h, h - 1 / 3 ],
				t2 = l < 0.5 ? l * (1 + s) : l + s - l * s,
				t1 = 2 * l - t2,
				c = [];
			for (var i = 0; i < 3; i++) {
				var t3 = t3s[i];
				if (t3 < 0) t3 += 1;
				if (t3 > 1) t3 -= 1;
				c[i] = 6 * t3 < 1
					? t1 + (t2 - t1) * 6 * t3
					: 2 * t3 < 1
						? t2
						: 3 * t3 < 2
							? t1 + (t2 - t1) * ((2 / 3) - t3) * 6
							: t1;
			}
			return new RgbColor(c[0], c[1], c[2], color._alpha);
		},

		'rgb-gray': function(color) {
			return new GrayColor(1 - (color._red * 0.2989 + color._green * 0.587
					+ color._blue * 0.114), color._alpha);
		},

		'gray-rgb': function(color) {
			var comp = 1 - color._gray;
			return new RgbColor(comp, comp, comp, color._alpha);
		},

		'gray-hsb': function(color) {
			return new HsbColor(0, 0, 1 - color._gray, color._alpha);
		},

		'gray-hsl': function(color) {
			return new HslColor(0, 0, 1 - color._gray, color._alpha);
		}
	};

	var fields = {
		_readNull: true,

		initialize: function(arg) {
			var isArray = Array.isArray(arg),
				type = this._colorType;
			if (typeof arg === 'object' && !isArray) {
				if (!type) {
					return arg.red !== undefined
						? new RgbColor(arg.red, arg.green, arg.blue, arg.alpha)
						: arg.gray !== undefined
						? new GrayColor(arg.gray, arg.alpha)
						: arg.lightness !== undefined
						? new HslColor(arg.hue, arg.saturation, arg.lightness,
								arg.alpha)
						: arg.hue !== undefined
						? new HsbColor(arg.hue, arg.saturation, arg.brightness,
								arg.alpha)
						: new RgbColor(); 
				} else {
					return Color.read(arguments).convert(type);
				}
			} else if (typeof arg === 'string') {
				var rgbColor = arg.match(/^#[0-9a-f]{3,6}$/i)
						? hexToRgbColor(arg)
						: nameToRgbColor(arg);
				return type
						? rgbColor.convert(type)
						: rgbColor;
			} else {
				var components = isArray ? arg
						: Array.prototype.slice.call(arguments);
				if (!type) {
					if (components.length >= 3)
						return new RgbColor(components);
					return new GrayColor(components);
				} else {
					Base.each(this._components,
						function(name, i) {
							var value = components[i];
							this['_' + name] = value !== undefined
									? value : null;
						},
					this);
				}
			}
		},

		clone: function() {
			var ctor = this.constructor,
				copy = new ctor(ctor.dont),
				components = this._components;
			for (var i = 0, l = components.length; i < l; i++) {
				var key = '_' + components[i];
				copy[key] = this[key];
			}
			return copy;
		},

		convert: function(type) {
			var converter;
			return this._colorType == type
					? this.clone()
					: (converter = converters[this._colorType + '-' + type])
						? converter(this)
						: converters['rgb-' + type](
								converters[this._colorType + '-rgb'](this));
		},

		statics: {
			extend: function(src) {
				src.beans = true;
				if (src._colorType) {
					var comps = components[src._colorType];
					src._components = comps.concat(['alpha']);
					Base.each(comps, function(name) {
						var isHue = name === 'hue',
							part = Base.capitalize(name),
							name = '_' + name;
						this['get' + part] = function() {
							return this[name];
						};
						this['set' + part] = function(value) {
							this[name] = isHue
								? ((value % 360) + 360) % 360
								: Math.min(Math.max(value, 0), 1);
							this._changed();
							return this;
						};
					}, src);
				}
				return this.base(src);
			}
		}
	};

	Base.each(components, function(comps, type) {
		Base.each(comps, function(component) {
			var part = Base.capitalize(component);
			fields['get' + part] = function() {
				return this.convert(type)[component];
			};
			fields['set' + part] = function(value) {
				var color = this.convert(type);
				color[component] = value;
				color = color.convert(this._colorType);
				for (var i = 0, l = this._components.length; i < l; i++) {
					var key = this._components[i];
					this[key] = color[key];
				}
			};
		});
	});

	return fields;
}, {

	_changed: function() {
		this._cssString = null;
		for (var i = 0, l = this._owners && this._owners.length; i < l; i++)
			this._owners[i]._changed(Change.STYLE);
	},

	_addOwner: function(item) {
		if (!this._owners)
			this._owners = [];
		this._owners.push(item);
	},

	_removeOwner: function(item) {
		var index = this._owners ? this._owners.indexOf(item) : -1;
		if (index != -1) {
			this._owners.splice(index, 1);
			if (this._owners.length == 0)
				delete this._owners;
		}
	},

	getType: function() {
		return this._colorType;
	},

	getComponents: function() {
		var length = this._components.length;
		var comps = new Array(length);
		for (var i = 0; i < length; i++)
			comps[i] = this['_' + this._components[i]];
		return comps;
	},

	getAlpha: function() {
		return this._alpha != null ? this._alpha : 1;
	},

	setAlpha: function(alpha) {
		this._alpha = alpha == null ? null : Math.min(Math.max(alpha, 0), 1);
		this._changed();
		return this;
	},

	hasAlpha: function() {
		return this._alpha != null;
	},

	equals: function(color) {
		if (color && color._colorType === this._colorType) {
			for (var i = 0, l = this._components.length; i < l; i++) {
				var component = '_' + this._components[i];
				if (this[component] !== color[component])
					return false;
			}
			return true;
		}
		return false;
	},

	toString: function() {
		var parts = [],
			format = Base.formatNumber;
		for (var i = 0, l = this._components.length; i < l; i++) {
			var component = this._components[i],
				value = this['_' + component];
			if (component === 'alpha' && value == null)
				value = 1;
			parts.push(component + ': ' + format(value));
		}
		return '{ ' + parts.join(', ') + ' }';
	},

	toCssString: function() {
		if (!this._cssString) {
			var color = this.convert('rgb'),
				alpha = color.getAlpha(),
				components = [
					Math.round(color._red * 255),
					Math.round(color._green * 255),
					Math.round(color._blue * 255),
					alpha != null ? alpha : 1
				];
			this._cssString = 'rgba(' + components.join(', ') + ')';
		}
		return this._cssString;
	},

	getCanvasStyle: function() {
		return this.toCssString();
	}

});

var GrayColor = this.GrayColor = Color.extend({

	_colorType: 'gray'
});

var RgbColor = this.RgbColor = this.RGBColor = Color.extend({

	_colorType: 'rgb'
});

var HsbColor = this.HsbColor = this.HSBColor = Color.extend({

	_colorType: 'hsb'
});

var HslColor = this.HslColor = this.HSLColor = Color.extend({

	_colorType: 'hsl'
});

var GradientColor = this.GradientColor = Color.extend({

	initialize: function(gradient, origin, destination, hilite) {
		this.gradient = gradient || new Gradient();
		this.setOrigin(origin);
		this.setDestination(destination);
		if (hilite)
			this.setHilite(hilite);
	},

	clone: function() {
		return new GradientColor(this.gradient, this._origin, this._destination,
				this._hilite);
	},

	getOrigin: function() {
		return this._origin;
	},

	setOrigin: function(origin) {
		origin = Point.read(arguments).clone();
		this._origin = origin;
		if (this._destination)
			this._radius = this._destination.getDistance(this._origin);
		this._changed();
		return this;
	},

	getDestination: function() {
		return this._destination;
	},

	setDestination: function(destination) {
		destination = Point.read(arguments).clone();
		this._destination = destination;
		this._radius = this._destination.getDistance(this._origin);
		this._changed();
		return this;
	},

	getHilite: function() {
		return this._hilite;
	},

	setHilite: function(hilite) {
		hilite = Point.read(arguments).clone();
		var vector = hilite.subtract(this._origin);
		if (vector.getLength() > this._radius) {
			this._hilite = this._origin.add(
					vector.normalize(this._radius - 0.1));
		} else {
			this._hilite = hilite;
		}
		this._changed();
		return this;
	},

	getCanvasStyle: function(ctx) {
		var gradient;
		if (this.gradient.type === 'linear') {
			gradient = ctx.createLinearGradient(this._origin.x, this._origin.y,
					this._destination.x, this._destination.y);
		} else {
			var origin = this._hilite || this._origin;
			gradient = ctx.createRadialGradient(origin.x, origin.y,
					0, this._origin.x, this._origin.y, this._radius);
		}
		for (var i = 0, l = this.gradient._stops.length; i < l; i++) {
			var stop = this.gradient._stops[i];
			gradient.addColorStop(stop._rampPoint, stop._color.toCssString());
		}
		return gradient;
	},

	equals: function(color) {
		return color == this || color && color._colorType === this._colorType
				&& this.gradient.equals(color.gradient)
				&& this._origin.equals(color._origin)
				&& this._destination.equals(color._destination);
	},

	transform: function(matrix) {
		matrix._transformPoint(this._origin, this._origin, true);
		matrix._transformPoint(this._destination, this._destination, true);
		if (this._hilite)
			matrix._transformPoint(this._hilite, this._hilite, true);
		this._radius = this._destination.getDistance(this._origin);
	}
});

var Gradient = this.Gradient = Base.extend({
	initialize: function(stops, type) {
		this.setStops(stops || ['white', 'black']);
		this.type = type || 'linear';
	},

	clone: function() {
		var stops = [];
		for (var i = 0, l = this._stops.length; i < l; i++)
			stops[i] = this._stops[i].clone();
		return new Gradient(stops, this.type);
	},

	getStops: function() {
		return this._stops;
	},

	setStops: function(stops) {
		if (stops.length < 2)
			throw new Error(
					'Gradient stop list needs to contain at least two stops.');
		this._stops = GradientStop.readAll(stops);
		for (var i = 0, l = this._stops.length; i < l; i++) {
			var stop = this._stops[i];
			if (stop._defaultRamp)
				stop.setRampPoint(i / (l - 1));
		}
	},

	equals: function(gradient) {
		if (gradient.type != this.type)
			return false;
		if (this._stops.length == gradient._stops.length) {
			for (var i = 0, l = this._stops.length; i < l; i++) {
				if (!this._stops[i].equals(gradient._stops[i]))
					return false;
			}
			return true;
		}
		return false;
	}
});

var GradientStop = this.GradientStop = Base.extend({
	initialize: function(arg0, arg1) {
		if (arg1 === undefined && Array.isArray(arg0)) {
			this.setColor(arg0[0]);
			this.setRampPoint(arg0[1]);
		} else if (arg0.color) {
			this.setColor(arg0.color);
			this.setRampPoint(arg0.rampPoint);
		} else {
			this.setColor(arg0);
			this.setRampPoint(arg1);
		}
	},

	clone: function() {
		return new GradientStop(this._color.clone(), this._rampPoint);
	},

	getRampPoint: function() {
		return this._rampPoint;
	},

	setRampPoint: function(rampPoint) {
		this._defaultRamp = rampPoint == null;
		this._rampPoint = rampPoint || 0;
	},

	getColor: function() {
		return this._color;
	},

	setColor: function(color) {
		this._color = Color.read(arguments);
	},

	equals: function(stop) {
		return stop == this || stop instanceof GradientStop
				&& this._color.equals(stop._color)
				&& this._rampPoint == stop._rampPoint;
	}
});

var DomElement = {
	getBounds: function(el, viewport) {
		var rect = el.getBoundingClientRect(),
			doc = el.ownerDocument,
			body = doc.body,
			docEl = doc.documentElement,
			x = rect.left - (docEl.clientLeft || body.clientLeft || 0),
			y = rect.top - (docEl.clientTop  || body.clientTop  || 0);
		if (!viewport) {
			var win = DomElement.getViewport(doc);
			x += win.pageXOffset || docEl.scrollLeft || body.scrollLeft;
			y += win.pageYOffset || docEl.scrollTop || body.scrollTop;
		}
		return new Rectangle(x, y, rect.width, rect.height);
	},

	getOffset: function(el, viewport) {
		return this.getBounds(el, viewport).getPoint();
	},

	getSize: function(el) {
		return this.getBounds(el, true).getSize();
	},

	isInvisible: function(el) {
		return this.getSize(el).equals([0, 0]);
	},

	isVisible: function(el) {
		return !this.isInvisible(el) && this.getViewportBounds(el).intersects(
				this.getBounds(el, true));
	},

	getViewport: function(doc) {
		return doc.defaultView || doc.parentWindow;
	},

	getViewportBounds: function(el) {
		var doc = el.ownerDocument,
			view = this.getViewport(doc),
			body = doc.getElementsByTagName(
				doc.compatMode === 'CSS1Compat' ? 'html' : 'body')[0];
		return Rectangle.create(0, 0, 
			view.innerWidth || body.clientWidth,
			view.innerHeight || body.clientHeight
		);
	},

	getComputedStyle: function(el, name) {
		if (el.currentStyle)
			return el.currentStyle[Base.camelize(name)];
		var style = this.getViewport(el.ownerDocument)
				.getComputedStyle(el, null);
		return style ? style.getPropertyValue(Base.hyphenate(name)) : null;
	}
};

var DomEvent = {
	add: function(el, events) {
		for (var type in events) {
			var func = events[type];
			if (el.addEventListener) {
				el.addEventListener(type, func, false);
			} else if (el.attachEvent) {
				el.attachEvent('on' + type, func.bound = function() {
					func.call(el, window.event);
				});
			}
		}
	},

	remove: function(el, events) {
		for (var type in events) {
			var func = events[type];
			if (el.removeEventListener) {
				el.removeEventListener(type, func, false);
			} else if (el.detachEvent) {
				el.detachEvent('on' + type, func.bound);
			}
		}
	},

	getPoint: function(event) {
		var pos = event.targetTouches
				? event.targetTouches.length
					? event.targetTouches[0]
					: event.changedTouches[0]
				: event;
		return Point.create(
			pos.pageX || pos.clientX + document.documentElement.scrollLeft,
			pos.pageY || pos.clientY + document.documentElement.scrollTop
		);
	},

	getTarget: function(event) {
		return event.target || event.srcElement;
	},

	getOffset: function(event, target) {
		return DomEvent.getPoint(event).subtract(DomElement.getOffset(
				target || DomEvent.getTarget(event)));
	},

	preventDefault: function(event) {
		if (event.preventDefault) {
			event.preventDefault();
		} else {
			event.returnValue = false;
		}
	},

	stopPropagation: function(event) {
		if (event.stopPropagation) {
			event.stopPropagation();
		} else {
			event.cancelBubble = true;
		}
	},

	stop: function(event) {
		DomEvent.stopPropagation(event);
		DomEvent.preventDefault(event);
	}
};

DomEvent.requestAnimationFrame = new function() {
	var part = 'equestAnimationFrame',
		request = window['r' + part] || window['webkitR' + part]
			|| window['mozR' + part] || window['oR' + part]
			|| window['msR' + part];
	if (request) {
		request(function(time) {
			if (time == undefined)
				request = null;
		});
	}

	var callbacks = [],
		focused = true,
		timer;

	DomEvent.add(window, {
		focus: function() {
			focused = true;
		},
		blur: function() {
			focused = false;
		}
	});

	return function(callback, element) {
		if (request)
			return request(callback, element);
		callbacks.push([callback, element]);
		if (timer)
			return;
		timer = window.setInterval(function() {
			for (var i = callbacks.length - 1; i >= 0; i--) {
				var entry = callbacks[i],
					func = entry[0],
					el = entry[1];
				if (!el || (PaperScript.getAttribute(el, 'keepalive') == 'true'
						|| focused) && DomElement.isVisible(el)) {
					callbacks.splice(i, 1);
					func(Date.now());
				}
			}
		}, 1000 / 60);
	};
};

var View = this.View = PaperScopeItem.extend({
	_list: 'views',
	_reference: 'view',

	initialize: function(canvas) {
		this.base();
		var size;

		if (typeof canvas === 'string')
			canvas = document.getElementById(canvas);
		if (canvas instanceof HTMLCanvasElement) {
			this._canvas = canvas;
			if (PaperScript.hasAttribute(canvas, 'resize')) {
				var offset = DomElement.getOffset(canvas, true),
					that = this;
				size = DomElement.getViewportBounds(canvas)
						.getSize().subtract(offset);
				canvas.width = size.width;
				canvas.height = size.height;
				DomEvent.add(window, {
					resize: function(event) {
						if (!DomElement.isInvisible(canvas))
							offset = DomElement.getOffset(canvas, true);
						that.setViewSize(DomElement.getViewportBounds(canvas)
								.getSize().subtract(offset));
					}
				});
			} else {
				size = DomElement.isInvisible(canvas)
					? Size.create(parseInt(canvas.getAttribute('width')),
							parseInt(canvas.getAttribute('height')))
					: DomElement.getSize(canvas);
			}
			if (PaperScript.hasAttribute(canvas, 'stats')) {
				this._stats = new Stats();
				var element = this._stats.domElement,
					style = element.style,
					offset = DomElement.getOffset(canvas);
				style.position = 'absolute';
				style.left = offset.x + 'px';
				style.top = offset.y + 'px';
				document.body.appendChild(element);
			}
		} else {
			size = Size.read(arguments, 1);
			if (size.isZero())
				size = new Size(1024, 768);
			this._canvas = CanvasProvider.getCanvas(size);
		}
		this._id = this._canvas.getAttribute('id');
		if (this._id == null)
			this._canvas.setAttribute('id', this._id = 'canvas-' + View._id++);

		View._views[this._id] = this;
		this._viewSize = LinkedSize.create(this, 'setViewSize',
				size.width, size.height);
		this._context = this._canvas.getContext('2d');
		this._matrix = new Matrix();
		this._zoom = 1;

		this._events = this._createEvents();
		DomEvent.add(this._canvas, this._events);
		if (!View._focused)
			View._focused = this;

		this._scope._redrawNotified = false;
	},

	remove: function() {
		if (!this.base())
			return false;
		if (View._focused == this)
			View._focused = null;
		delete View._views[this._id];
		DomEvent.remove(this._canvas, this._events);
		this._canvas = this._events = this._onFrame = null;
		return true;
	},

	_redraw: function() {
		this._redrawNeeded = true;
		if (this._onFrameCallback) {
			this._onFrameCallback(0, true);
		} else {
			this.draw();
		}
	},

	_transform: function(matrix, flags) {
		this._matrix.preConcatenate(matrix);
		this._bounds = null;
		this._inverse = null;
		this._redraw();
	},

	getCanvas: function() {
		return this._canvas;
	},

	getViewSize: function() {
		return this._viewSize;
	},

	setViewSize: function(size) {
		size = Size.read(arguments);
		var delta = size.subtract(this._viewSize);
		if (delta.isZero())
			return;
		this._canvas.width = size.width;
		this._canvas.height = size.height;
		this._viewSize.set(size.width, size.height, true);
		this._bounds = null;
		this._redrawNeeded = true;
		if (this.onResize) {
			this.onResize({
				size: size,
				delta: delta
			});
		}
		this._redraw();
	},

	getBounds: function() {
		if (!this._bounds)
			this._bounds = this._getInverse()._transformBounds(
					new Rectangle(new Point(), this._viewSize));
		return this._bounds;
	},

	getSize: function() {
		return this.getBounds().getSize();
	},

	getCenter: function() {
		return this.getBounds().getCenter();
	},

	setCenter: function(center) {
		this.scrollBy(Point.read(arguments).subtract(this.getCenter()));
	},

	getZoom: function() {
		return this._zoom;
	},

	setZoom: function(zoom) {
		this._transform(new Matrix().scale(zoom / this._zoom, this.getCenter()));
		this._zoom = zoom;
	},

	isVisible: function() {
		return DomElement.isVisible(this._canvas);
	},

	scrollBy: function(point) {
		this._transform(new Matrix().translate(Point.read(arguments).negate()));
	},

	draw: function(checkRedraw) {
		if (checkRedraw && !this._redrawNeeded)
			return false;
		if (this._stats)
			this._stats.update();
		var ctx = this._context,
			size = this._viewSize;
		ctx.clearRect(0, 0, size._width + 1, size._height + 1);

		ctx.save();
		this._matrix.applyToContext(ctx);
		this._scope.project.draw(ctx);
		ctx.restore();
		if (this._redrawNeeded) {
			this._redrawNeeded = false;
			this._scope._redrawNotified = false;
		}
		return true;
	},

	projectToView: function(point) {
		return this._matrix._transformPoint(Point.read(arguments));
	},

	viewToProject: function(point) {
		return this._getInverse()._transformPoint(Point.read(arguments));
	},

	_getInverse: function() {
		if (!this._inverse)
			this._inverse = this._matrix.createInverse();
		return this._inverse;
	},

	getOnFrame: function() {
		return this._onFrame;
	},

	setOnFrame: function(onFrame) {
		this._onFrame = onFrame;
		if (!onFrame) {
			delete this._onFrameCallback;
			return;
		}
		var that = this,
			requested = false,
			before,
			time = 0,
			count = 0;
		this._onFrameCallback = function(param, dontRequest) {
			requested = false;
			if (!that._onFrame)
				return;
			paper = that._scope;
			requested = true;
			if (!dontRequest) {
				DomEvent.requestAnimationFrame(that._onFrameCallback,
						that._canvas);
			}
			var now = Date.now() / 1000,
			 	delta = before ? now - before : 0;
			that._onFrame(Base.merge({
				delta: delta, 
				time: time += delta, 
				count: count++
			}));
			before = now;
			that.draw(true);
		};
		if (!requested)
			this._onFrameCallback();
	},

	onResize: null
}, {
	statics: {
		_views: {},
		_id: 0
	}
}, new function() {
	var tool,
		timer,
		curPoint,
		tempFocus,
		dragging = false;

	function viewToProject(view, event) {
		return view.viewToProject(DomEvent.getOffset(event, view._canvas));
	}

	function updateFocus() {
		if (!View._focused || !View._focused.isVisible()) {
			PaperScope.each(function(scope) {
				for (var i = 0, l = scope.views.length; i < l; i++) {
					var view = scope.views[i];
					if (view.isVisible()) {
						View._focused = tempFocus = view;
						throw Base.stop;
					}
				}
			});
		}
	}

	function mousemove(event) {
		var view;
		if (!dragging) {
		 	view = View._views[DomEvent.getTarget(event).getAttribute('id')];
			if (view) {
				View._focused = tempFocus = view;
			} else if (tempFocus && tempFocus == View._focused) {
				View._focused = null;
				updateFocus();
			}
		}
		if (!(view = view || View._focused) || !(tool = view._scope.tool))
			return;
		var point = event && viewToProject(view, event);
		var onlyMove = !!(!tool.onMouseDrag && tool.onMouseMove);
		if (dragging && !onlyMove) {
			curPoint = point || curPoint;
			if (curPoint && tool.onHandleEvent('mousedrag', curPoint, event)) {
				view.draw(true);
				DomEvent.stop(event);
			}
		} else if ((!dragging || onlyMove)
				&& tool.onHandleEvent('mousemove', point, event)) {
			view.draw(true);
			DomEvent.stop(event);
		}
	}

	function mouseup(event) {
		var view = View._focused;
		if (!view || !dragging)
			return;
		dragging = false;
		curPoint = null;
		if (tool) {
			if (timer != null)
				timer = clearInterval(timer);
			if (tool.onHandleEvent('mouseup', viewToProject(view, event), event)) {
				view.draw(true);
				DomEvent.stop(event);
			}
		}
	}

	function selectstart(event) {
		if (dragging)
			DomEvent.stop(event);
	}

	DomEvent.add(document, {
		mousemove: mousemove,
		mouseup: mouseup,
		touchmove: mousemove,
		touchend: mouseup,
		selectstart: selectstart,
		scroll: updateFocus
	});

	DomEvent.add(window, {
		load: updateFocus
	});

	return {
		_createEvents: function() {
			var view = this;

			function mousedown(event) {
				View._focused = view;
				if (!(tool = view._scope.tool))
					return;
				curPoint = viewToProject(view, event);
				if (tool.onHandleEvent('mousedown', curPoint, event))
					view.draw(true);
				if (tool.eventInterval != null)
					timer = setInterval(mousemove, tool.eventInterval);
				dragging = true;
			}

			return {
				mousedown: mousedown,
				touchstart: mousedown,
				selectstart: selectstart
			};
		},

		statics: {

			updateFocus: updateFocus
		}
	};
});

var Event = this.Event = Base.extend({
	initialize: function(event) {
		this.event = event;
	},

	preventDefault: function() {
		DomEvent.preventDefault(this.event);
	},

	stopPropagation: function() {
		DomEvent.stopPropagation(this.event);
	},

	stop: function() {
		DomEvent.stop(this.event);
	},

	getModifiers: function() {
		return Key.modifiers;
	}
});

var KeyEvent = this.KeyEvent = Event.extend(new function() {
	return {
		initialize: function(down, key, character, event) {
			this.base(event);
			this.type = down ? 'keydown' : 'keyup';
			this.key = key;
			this.character = character;
		},

		toString: function() {
			return '{ type: ' + this.type
					+ ', key: ' + this.key
					+ ', character: ' + this.character
					+ ', modifiers: ' + this.getModifiers()
					+ ' }';
		}
	};
});

var Key = this.Key = new function() {

	var keys = {
		 8: 'backspace',
		13: 'enter',
		16: 'shift',
		17: 'control',
		18: 'option',
		19: 'pause',
		20: 'caps-lock',
		27: 'escape',
		32: 'space',
		35: 'end',
		36: 'home',
		37: 'left',
		38: 'up',
		39: 'right',
		40: 'down',
		46: 'delete',
		91: 'command',
		93: 'command', 
		224: 'command'  
	},

	modifiers = Base.merge({
		shift: false,
		control: false,
		option: false,
		command: false,
		capsLock: false
	}),

	charCodeMap = {}, 
	keyMap = {}, 
	downCode; 

	function handleKey(down, keyCode, charCode, event) {
		var character = String.fromCharCode(charCode),
			key = keys[keyCode] || character.toLowerCase(),
			handler = down ? 'onKeyDown' : 'onKeyUp',
			view = View._focused,
			scope = view && view.isVisible() && view._scope,
			tool = scope && scope.tool;
		keyMap[key] = down;
		if (tool && tool[handler]) {
			var keyEvent = new KeyEvent(down, key, character, event);
			if (tool[handler](keyEvent) === false)
				keyEvent.preventDefault();
			if (view)
				view.draw(true);
		}
	}

	DomEvent.add(document, {
		keydown: function(event) {
			var code = event.which || event.keyCode;
			var key = keys[code], name;
			if (key) {
				if ((name = Base.camelize(key)) in modifiers)
					modifiers[name] = true;
				charCodeMap[code] = 0;
				handleKey(true, code, null, event);
			} else {
				downCode = code;
			}
		},

		keypress: function(event) {
			if (downCode != null) {
				var code = event.which || event.keyCode;
				charCodeMap[downCode] = code;
				handleKey(true, downCode, code, event);
				downCode = null;
			}
		},

		keyup: function(event) {
			var code = event.which || event.keyCode,
				key = keys[code], name;
			if (key && (name = Base.camelize(key)) in modifiers)
				modifiers[name] = false;
			if (charCodeMap[code] != null) {
				handleKey(false, code, charCodeMap[code], event);
				delete charCodeMap[code];
			}
		}
	});

	return {
		modifiers: modifiers,

		isDown: function(key) {
			return !!keyMap[key];
		}
	};
};

var ToolEvent = this.ToolEvent = Event.extend({
	initialize: function(tool, type, event) {
		this.tool = tool;
		this.type = type;
		this.event = event;
	},

	_choosePoint: function(point, toolPoint) {
		return point ? point : toolPoint ? toolPoint.clone() : null;
	},

	getPoint: function() {
		return this._choosePoint(this._point, this.tool._point);
	},

	setPoint: function(point) {
		this._point = point;
	},

	getLastPoint: function() {
		return this._choosePoint(this._lastPoint, this.tool._lastPoint);
	},

	setLastPoint: function(lastPoint) {
		this._lastPoint = lastPoint;
	},

	getDownPoint: function() {
		return this._choosePoint(this._downPoint, this.tool._downPoint);
	},

	setDownPoint: function(downPoint) {
		this._downPoint = downPoint;
	},

	getMiddlePoint: function() {
		if (!this._middlePoint && this.tool._lastPoint) {
			return this.tool._point.add(this.tool._lastPoint).divide(2);
		}
		return this.middlePoint;
	},

	setMiddlePoint: function(middlePoint) {
		this._middlePoint = middlePoint;
	},

	getDelta: function() {
		return !this._delta && this.tool._lastPoint
		 		? this.tool._point.subtract(this.tool._lastPoint)
				: this._delta;
	},

	setDelta: function(delta) {
		this._delta = delta;
	},

	getCount: function() {
		return /^mouse(down|up)$/.test(this.type)
				? this.tool._downCount
				: this.tool._count;
	},

	setCount: function(count) {
		this.tool[/^mouse(down|up)$/.test(this.type) ? 'downCount' : 'count']
			= count;
	},

	getItem: function() {
		if (!this._item) {
			var result = this.tool._scope.project.hitTest(this.getPoint());
			if (result) {
				var item = result.item,
					parent = item._parent;
				while ((parent instanceof Group && !(parent instanceof Layer))
						|| parent instanceof CompoundPath) {
					item = parent;
					parent = parent._parent;
				}
				this._item = item;
			}
		}
		return this._item;
	},
	setItem: function(item) {
		this._item = item;
	},

	toString: function() {
		return '{ type: ' + this.type
				+ ', point: ' + this.getPoint()
				+ ', count: ' + this.getCount()
				+ ', modifiers: ' + this.getModifiers()
				+ ' }';
	}
});

var Tool = this.Tool = PaperScopeItem.extend({
	_list: 'tools',
	_reference: 'tool',

	initialize: function() {
		this.base();
		this._firstMove = true;
		this._count = 0;
		this._downCount = 0;
	},

	eventInterval: null,

	getMinDistance: function() {
		return this._minDistance;
	},

	setMinDistance: function(minDistance) {
		this._minDistance = minDistance;
		if (this._minDistance != null && this._maxDistance != null
				&& this._minDistance > this._maxDistance) {
			this._maxDistance = this._minDistance;
		}
	},

	getMaxDistance: function() {
		return this._maxDistance;
	},

	setMaxDistance: function(maxDistance) {
		this._maxDistance = maxDistance;
		if (this._minDistance != null && this._maxDistance != null
				&& this._maxDistance < this._minDistance) {
			this._minDistance = maxDistance;
		}
	},

	getFixedDistance: function() {
		return this._minDistance == this._maxDistance
			? this._minDistance : null;
	},

	setFixedDistance: function(distance) {
		this._minDistance = distance;
		this._maxDistance = distance;
	},

	updateEvent: function(type, pt, minDistance, maxDistance, start,
			needsChange, matchMaxDistance) {
		if (!start) {
			if (minDistance != null || maxDistance != null) {
				var minDist = minDistance != null ? minDistance : 0;
				var vector = pt.subtract(this._point);
				var distance = vector.getLength();
				if (distance < minDist)
					return false;
				var maxDist = maxDistance != null ? maxDistance : 0;
				if (maxDist != 0) {
					if (distance > maxDist) {
						pt = this._point.add(vector.normalize(maxDist));
					} else if (matchMaxDistance) {
						return false;
					}
				}
			}
			if (needsChange && pt.equals(this._point))
				return false;
		}
		this._lastPoint = start && type == 'mousemove' ? pt : this._point;
		this._point = pt;
		switch (type) {
		case 'mousedown':
			this._lastPoint = this._downPoint;
			this._downPoint = this._point;
			this._downCount++;
			break;
		case 'mouseup':
			this._lastPoint = this._downPoint;
			break;
		}
		this._count = start ? 0 : this._count + 1;
		return true;
	},

	onHandleEvent: function(type, pt, event) {
		paper = this._scope;
		var called = false;
		switch (type) {
		case 'mousedown':
			this.updateEvent(type, pt, null, null, true, false, false);
			if (this.onMouseDown) {
				this.onMouseDown(new ToolEvent(this, type, event));
				called = true;
			}
			break;
		case 'mousedrag':
			var needsChange = false,
				matchMaxDistance = false;
			while (this.updateEvent(type, pt, this.minDistance,
					this.maxDistance, false, needsChange, matchMaxDistance)) {
				if (this.onMouseDrag) {
					this.onMouseDrag(new ToolEvent(this, type, event));
					called = true;
				}
				needsChange = true;
				matchMaxDistance = true;
			}
			break;
		case 'mouseup':
			if ((this._point.x != pt.x || this._point.y != pt.y)
					&& this.updateEvent('mousedrag', pt, this.minDistance,
							this.maxDistance, false, false, false)) {
				if (this.onMouseDrag) {
					this.onMouseDrag(new ToolEvent(this, type, event));
					called = true;
				}
			}
			this.updateEvent(type, pt, null, this.maxDistance, false,
					false, false);
			if (this.onMouseUp) {
				this.onMouseUp(new ToolEvent(this, type, event));
				called = true;
			}
			this.updateEvent(type, pt, null, null, true, false, false);
			this._firstMove = true;
			break;
		case 'mousemove':
			while (this.updateEvent(type, pt, this.minDistance,
					this.maxDistance, this._firstMove, true, false)) {
				if (this.onMouseMove) {
					this.onMouseMove(new ToolEvent(this, type, event));
					called = true;
				}
				this._firstMove = false;
			}
			break;
		}
		return called;
	}
});

var CanvasProvider = {
	canvases: [],
	getCanvas: function(size) {
		if (this.canvases.length) {
			var canvas = this.canvases.pop();
			if ((canvas.width != size.width)
					|| (canvas.height != size.height)) {
				canvas.width = size.width;
				canvas.height = size.height;
			} else {
				canvas.getContext('2d').clearRect(0, 0,
						size.width + 1, size.height + 1);
			}
			return canvas;
		} else {
			var canvas = document.createElement('canvas');
			canvas.width = size.width;
			canvas.height = size.height;
			return canvas;
		}
	},

	returnCanvas: function(canvas) {
		this.canvases.push(canvas);
	}
};

var Numerical = new function() {

	var abscissas = [
		[  0.5773502691896257645091488],
		[0,0.7745966692414833770358531],
		[  0.3399810435848562648026658,0.8611363115940525752239465],
		[0,0.5384693101056830910363144,0.9061798459386639927976269],
		[  0.2386191860831969086305017,0.6612093864662645136613996,0.9324695142031520278123016],
		[0,0.4058451513773971669066064,0.7415311855993944398638648,0.9491079123427585245261897],
		[  0.1834346424956498049394761,0.5255324099163289858177390,0.7966664774136267395915539,0.9602898564975362316835609],
		[0,0.3242534234038089290385380,0.6133714327005903973087020,0.8360311073266357942994298,0.9681602395076260898355762],
		[  0.1488743389816312108848260,0.4333953941292471907992659,0.6794095682990244062343274,0.8650633666889845107320967,0.9739065285171717200779640],
		[0,0.2695431559523449723315320,0.5190961292068118159257257,0.7301520055740493240934163,0.8870625997680952990751578,0.9782286581460569928039380],
		[  0.1252334085114689154724414,0.3678314989981801937526915,0.5873179542866174472967024,0.7699026741943046870368938,0.9041172563704748566784659,0.9815606342467192506905491],
		[0,0.2304583159551347940655281,0.4484927510364468528779129,0.6423493394403402206439846,0.8015780907333099127942065,0.9175983992229779652065478,0.9841830547185881494728294],
		[  0.1080549487073436620662447,0.3191123689278897604356718,0.5152486363581540919652907,0.6872929048116854701480198,0.8272013150697649931897947,0.9284348836635735173363911,0.9862838086968123388415973],
		[0,0.2011940939974345223006283,0.3941513470775633698972074,0.5709721726085388475372267,0.7244177313601700474161861,0.8482065834104272162006483,0.9372733924007059043077589,0.9879925180204854284895657],
		[  0.0950125098376374401853193,0.2816035507792589132304605,0.4580167776572273863424194,0.6178762444026437484466718,0.7554044083550030338951012,0.8656312023878317438804679,0.9445750230732325760779884,0.9894009349916499325961542]
	];

	var weights = [
		[1],
		[0.8888888888888888888888889,0.5555555555555555555555556],
		[0.6521451548625461426269361,0.3478548451374538573730639],
		[0.5688888888888888888888889,0.4786286704993664680412915,0.2369268850561890875142640],
		[0.4679139345726910473898703,0.3607615730481386075698335,0.1713244923791703450402961],
		[0.4179591836734693877551020,0.3818300505051189449503698,0.2797053914892766679014678,0.1294849661688696932706114],
		[0.3626837833783619829651504,0.3137066458778872873379622,0.2223810344533744705443560,0.1012285362903762591525314],
		[0.3302393550012597631645251,0.3123470770400028400686304,0.2606106964029354623187429,0.1806481606948574040584720,0.0812743883615744119718922],
		[0.2955242247147528701738930,0.2692667193099963550912269,0.2190863625159820439955349,0.1494513491505805931457763,0.0666713443086881375935688],
		[0.2729250867779006307144835,0.2628045445102466621806889,0.2331937645919904799185237,0.1862902109277342514260976,0.1255803694649046246346943,0.0556685671161736664827537],
		[0.2491470458134027850005624,0.2334925365383548087608499,0.2031674267230659217490645,0.1600783285433462263346525,0.1069393259953184309602547,0.0471753363865118271946160],
		[0.2325515532308739101945895,0.2262831802628972384120902,0.2078160475368885023125232,0.1781459807619457382800467,0.1388735102197872384636018,0.0921214998377284479144218,0.0404840047653158795200216],
		[0.2152638534631577901958764,0.2051984637212956039659241,0.1855383974779378137417166,0.1572031671581935345696019,0.1215185706879031846894148,0.0801580871597602098056333,0.0351194603317518630318329],
		[0.2025782419255612728806202,0.1984314853271115764561183,0.1861610000155622110268006,0.1662692058169939335532009,0.1395706779261543144478048,0.1071592204671719350118695,0.0703660474881081247092674,0.0307532419961172683546284],
		[0.1894506104550684962853967,0.1826034150449235888667637,0.1691565193950025381893121,0.1495959888165767320815017,0.1246289712555338720524763,0.0951585116824927848099251,0.0622535239386478928628438,0.0271524594117540948517806]
	];

	var abs = Math.abs,
		sqrt = Math.sqrt,
		cos = Math.cos,
		PI = Math.PI;

	return {
		TOLERANCE: 10e-6,
		EPSILON: 10e-12,

		integrate: function(f, a, b, n) {
			var x = abscissas[n - 2],
				w = weights[n - 2],
				A = 0.5 * (b - a),
				B = A + a,
				i = 0,
				m = (n + 1) >> 1,
				sum = n & 1 ? w[i++] * f(B) : 0; 
			while (i < m) {
				var Ax = A * x[i];
				sum += w[i++] * (f(B + Ax) + f(B - Ax));
			}
			return A * sum;
		},

		findRoot: function(f, df, x, a, b, n, tolerance) {
			for (var i = 0; i < n; i++) {
				var fx = f(x),
					dx = fx / df(x);
				if (abs(dx) < tolerance)
					return x;
				var nx = x - dx;
				if (fx > 0) {
					b = x;
					x = nx <= a ? 0.5 * (a + b) : nx;
				} else {
					a = x;
					x = nx >= b ? 0.5 * (a + b) : nx;
				}
			}
		},

		solveQuadratic: function(a, b, c, roots, tolerance) {
			if (abs(a) < tolerance) {
				if (abs(b) >= tolerance) {
					roots[0] = -c / b;
					return 1;
				}
				if (abs(c) < tolerance)
					return -1; 
				return 0; 
			}
			var q = b * b - 4 * a * c;
			if (q < 0)
				return 0; 
			q = sqrt(q);
			if (b < 0)
				q = -q;
			q = (b + q) * -0.5;
			var n = 0;
			if (abs(q) >= tolerance)
				roots[n++] = c / q;
			if (abs(a) >= tolerance)
				roots[n++] = q / a;
			return n; 
		},

		solveCubic: function(a, b, c, d, roots, tolerance) {
			if (abs(a) < tolerance)
				return Numerical.solveQuadratic(b, c, d, roots, tolerance);
			b /= a;
			c /= a;
			d /= a;
			var Q = (b * b - 3 * c) / 9,
				R = (2 * b * b * b - 9 * b * c + 27 * d) / 54,
				Q3 = Q * Q * Q,
				R2 = R * R;
			b /= 3; 
			if (R2 < Q3) { 
				var theta = Math.acos(R / sqrt(Q3)),
					q = -2 * sqrt(Q);
				roots[0] = q * cos(theta / 3) - b;
				roots[1] = q * cos((theta + 2 * PI) / 3) - b;
				roots[2] = q * cos((theta - 2 * PI) / 3) - b;
				return 3;
			} else { 
				var A = -Math.pow(abs(R) + sqrt(R2 - Q3), 1 / 3);
				if (R < 0) A = -A;
				var B = (abs(A) < tolerance) ? 0 : Q / A;
				roots[0] = (A + B) - b;
				return 1;
			}
			return 0;
		}
	};
};

var BlendMode = {
	process: function(blendMode, srcContext, dstContext, alpha, offset) {
		var srcCanvas = srcContext.canvas,
			dstData = dstContext.getImageData(offset.x, offset.y,
					srcCanvas.width, srcCanvas.height),
			dst  = dstData.data,
			src  = srcContext.getImageData(0, 0,
					srcCanvas.width, srcCanvas.height).data,
			min = Math.min,
			max = Math.max,
			abs = Math.abs,
			sr, sg, sb, sa, 
			br, bg, bb, ba, 
			dr, dg, db;     

		function getLum(r, g, b) {
			return 0.2989 * r + 0.587 * g + 0.114 * b;
		}

		function setLum(r, g, b, l) {
			var d = l - getLum(r, g, b);
			dr = r + d;
			dg = g + d;
			db = b + d;
			var l = getLum(dr, dg, db),
				mn = min(dr, dg, db),
				mx = max(dr, dg, db);
			if (mn < 0) {
				var lmn = l - mn;
				dr = l + (dr - l) * l / lmn;
				dg = l + (dg - l) * l / lmn;
				db = l + (db - l) * l / lmn;
			}
			if (mx > 255) {
				var ln = 255 - l, mxl = mx - l;
				dr = l + (dr - l) * ln / mxl;
				dg = l + (dg - l) * ln / mxl;
				db = l + (db - l) * ln / mxl;
			}
		}

		function getSat(r, g, b) {
			return max(r, g, b) - min(r, g, b);
		}

		function setSat(r, g, b, s) {
			var col = [r, g, b],
				mx = max(r, g, b), 
				mn = min(r, g, b), 
				md; 
			mn = mn == r ? 0 : mn == g ? 1 : 2;
			mx = mx == r ? 0 : mx == g ? 1 : 2;
			md = min(mn, mx) == 0 ? max(mn, mx) == 1 ? 2 : 1 : 0;
			if (col[mx] > col[mn]) {
				col[md] = (col[md] - col[mn]) * s / (col[mx] - col[mn]);
				col[mx] = s;
			} else {
				col[md] = col[mx] = 0;
			}
			col[mn] = 0;
			dr = col[0];
			dg = col[1];
			db = col[2];
		}

		var modes = {
			multiply: function() {
				dr = br * sr / 255;
				dg = bg * sg / 255;
				db = bb * sb / 255;
			},

			screen: function() {
				dr = 255 - (255 - br) * (255 - sr) / 255;
				dg = 255 - (255 - bg) * (255 - sg) / 255;
				db = 255 - (255 - bb) * (255 - sb) / 255;
			},

			overlay: function() {
				dr = br < 128 ? 2 * br * sr / 255 : 255 - 2 * (255 - br) * (255 - sr) / 255;
				dg = bg < 128 ? 2 * bg * sg / 255 : 255 - 2 * (255 - bg) * (255 - sg) / 255;
				db = bb < 128 ? 2 * bb * sb / 255 : 255 - 2 * (255 - bb) * (255 - sb) / 255;
			},

			'soft-light': function() {
				var t = sr * br / 255;
				dr = t + br * (255 - (255 - br) * (255 - sr) / 255 - t) / 255;
				t = sg * bg / 255;
				dg = t + bg * (255 - (255 - bg) * (255 - sg) / 255 - t) / 255;
				t = sb * bb / 255;
				db = t + bb * (255 - (255 - bb) * (255 - sb) / 255 - t) / 255;
			},

			'hard-light': function() {
				dr = sr < 128 ? 2 * sr * br / 255 : 255 - 2 * (255 - sr) * (255 - br) / 255;
				dg = sg < 128 ? 2 * sg * bg / 255 : 255 - 2 * (255 - sg) * (255 - bg) / 255;
				db = sb < 128 ? 2 * sb * bb / 255 : 255 - 2 * (255 - sb) * (255 - bb) / 255;
			},

			'color-dodge': function() {
				dr = sr == 255 ? sr : min(255, br * 255 / (255 - sr));
				dg = sg == 255 ? sg : min(255, bg * 255 / (255 - sg));
				db = sb == 255 ? sb : min(255, bb * 255 / (255 - sb));
			},

			'color-burn': function() {
				dr = sr == 0 ? 0 : max(255 - ((255 - br) * 255) / sr, 0);
				dg = sg == 0 ? 0 : max(255 - ((255 - bg) * 255) / sg, 0);
				db = sb == 0 ? 0 : max(255 - ((255 - bb) * 255) / sb, 0);
			},

			darken: function() {
				dr = br < sr ? br : sr;
				dg = bg < sg ? bg : sg;
				db = bb < sb ? bb : sb;
			},

			lighten: function() {
				dr = br > sr ? br : sr;
				dg = bg > sg ? bg : sg;
				db = bb > sb ? bb : sb;
			},

			difference: function() {
				dr = br - sr;
				if (dr < 0)
					dr = -dr;
				dg = bg - sg;
				if (dg < 0)
					dg = -dg;
				db = bb - sb;
				if (db < 0)
					db = -db;
			},

			exclusion: function() {
				dr = br + sr * (255 - br - br) / 255;
				dg = bg + sg * (255 - bg - bg) / 255;
				db = bb + sb * (255 - bb - bb) / 255;
			},

			hue: function() {
				setSat(sr, sg, sb, getSat(br, bg, bb));
				setLum(dr, dg, db, getLum(br, bg, bb));
			},

			saturation: function() {
				setSat(br, bg, bb, getSat(sr, sg, sb));
				setLum(dr, dg, db, getLum(br, bg, bb));
			},

			luminosity: function() {
				setLum(br, bg, bb, getLum(sr, sg, sb));
			},

			color: function() {
				setLum(sr, sg, sb, getLum(br, bg, bb));
			},

			add: function() {
				dr = min(br + sr, 255);
				dg = min(bg + sg, 255);
				db = min(bb + sb, 255);
			},

			subtract: function() {
				dr = max(br - sr, 0);
				dg = max(bg - sg, 0);
				db = max(bb - sb, 0);
			},

			average: function() {
				dr = (br + sr) / 2;
				dg = (bg + sg) / 2;
				db = (bb + sb) / 2;
			},

			negation: function() {
				dr = 255 - abs(255 - sr - br);
				dg = 255 - abs(255 - sg - bg);
				db = 255 - abs(255 - sb - bb);
			}
		};

		var process = modes[blendMode];
		if (!process)
			return;

		for (var i = 0, l = dst.length; i < l; i += 4) {
			sr = src[i];
			br = dst[i];
			sg = src[i + 1];
			bg = dst[i + 1];
			sb = src[i + 2];
			bb = dst[i + 2];
			sa = src[i + 3];
			ba = dst[i + 3];
			process();
			var a1 = sa * alpha / 255,
				a2 = 1 - a1;
			dst[i] = a1 * dr + a2 * br;
			dst[i + 1] = a1 * dg + a2 * bg;
			dst[i + 2] = a1 * db + a2 * bb;
			dst[i + 3] = sa * alpha + a2 * ba;
		}
		dstContext.putImageData(dstData, offset.x, offset.y);
	}
};

var PaperScript = this.PaperScript = new function() {
var parse_js=new function(){function W(a,b,c){var d=[];for(var e=0;e<a.length;++e)d.push(b.call(c,a[e],e));return d}function V(c){return/^[a-z_$][a-z0-9_$]*$/i.test(c)&&c!="this"&&!M(d,c)&&!M(b,c)&&!M(a,c)}function U(a,b){var c={};a===!0&&(a={});for(var d in b)M(b,d)&&(c[d]=a&&M(a,d)?a[d]:b[d]);return c}function T(a,b){return b<1?"":Array(b+1).join(a)}function S(a,b){function z(a){var b=a[0],c=r[b];if(!c)throw new Error("Can't find generator for \""+b+'"');y.push(a);var d=c.apply(b,a.slice(1));y.pop();return d}function x(a){var b=a[0],c=a[1];c!=null&&(b=k([g(b),"=",m(c,"seq")]));return b}function w(a){return a?a.length==0?"{}":"{"+e+j(function(){return u(a).join(e)})+e+h("}"):";"}function v(a){var b=a.length;return b==0?"{}":"{"+e+W(a,function(a,d){var f=a[1].length>0,g=j(function(){return h(a[0]?k(["case",z(a[0])+":"]):"default:")},.5)+(f?e+j(function(){return u(a[1]).join(e)}):"");!c&&f&&d<b-1&&(g+=";");return g}).join(e)+e+h("}")}function u(a,b){for(var d=[],e=a.length-1,f=0;f<=e;++f){var g=a[f],i=z(g);i!=";"&&(!c&&f==e&&(g[0]=="while"&&O(g[2])||L(g[0],["for","for-in"])&&O(g[4])||g[0]=="if"&&O(g[2])&&!g[3]||g[0]=="if"&&g[3]&&O(g[3])?i=i.replace(/;*\s*$/,";"):i=i.replace(/;+\s*$/,"")),d.push(i))}return b?d:W(d,h)}function t(a,b,c,d){var e=d||"function";a&&(e+=" "+g(a)),e+="("+l(W(b,g))+")";return k([e,w(c)])}function s(a){if(a[0]=="do")return z(["block",[a]]);var b=a;for(;;){var c=b[0];if(c=="if"){if(!b[3])return z(["block",[a]]);b=b[3]}else if(c=="while"||c=="do")b=b[2];else if(c=="for"||c=="for-in")b=b[4];else break}return z(a)}function q(a){var b=a.toString(10),c=[b.replace(/^0\./,".")],d;Math.floor(a)===a?(c.push("0x"+a.toString(16).toLowerCase(),"0"+a.toString(8)),(d=/^(.*?)(0+)$/.exec(a))&&c.push(d[1]+"e"+d[2].length)):(d=/^0?\.(0+)(.*)$/.exec(a))&&c.push(d[2]+"e-"+(d[1].length+d[2].length),b.substr(b.indexOf(".")));return n(c)}function o(a){if(a[0]=="function"||a[0]=="object"){var b=J(y),c=b.pop(),d=b.pop();while(d){if(d[0]=="stat")return!0;if((d[0]=="seq"||d[0]=="call"||d[0]=="dot"||d[0]=="sub"||d[0]=="conditional")&&d[1]===c||(d[0]=="binary"||d[0]=="assign"||d[0]=="unary-postfix")&&d[2]===c)c=d,d=b.pop();else return!1}}return!M(P,a[0])}function n(a){if(a.length==1)return a[0];if(a.length==2){var b=a[1];a=a[0];return a.length<=b.length?a:b}return n([a[0],n(a.slice(1))])}function m(a){var b=z(a);for(var c=1;c<arguments.length;++c){var d=arguments[c];if(d instanceof Function&&d(a)||a[0]==d)return"("+b+")"}return b}function l(a){return a.join(","+f)}function k(a){if(c)return a.join(" ");var b=[];for(var d=0;d<a.length;++d){var e=a[d+1];b.push(a[d]),e&&(/[a-z0-9_\x24]$/i.test(a[d].toString())&&/^[a-z0-9_\x24]/i.test(e.toString())||/[\+\-]$/.test(a[d].toString())&&/^[\+\-]/.test(e.toString()))&&b.push(" ")}return b.join("")}function j(a,b){b==null&&(b=1),d+=b;try{return a.apply(null,J(arguments,1))}finally{d-=b}}function h(a){a==null&&(a=""),c&&(a=T(" ",b.indent_start+d*b.indent_level)+a);return a}function g(a){return a.toString()}b=U(b,{indent_start:0,indent_level:4,quote_keys:!1,space_colon:!1,beautify:!1});var c=!!b.beautify,d=0,e=c?"\n":"",f=c?" ":"",r={string:Q,num:q,name:g,toplevel:function(a){return u(a).join(e)},splice:function(a){var b=y[y.length-2][0];return M(R,b)?w.apply(this,arguments):W(u(a,!0),function(a,b){return b>0?h(a):a}).join(e)},block:w,"var":function(a){return"var "+l(W(a,x))+";"},"const":function(a){return"const "+l(W(a,x))+";"},"try":function(a,b,c){var d=["try",w(a)];b&&d.push("catch","("+b[0]+")",w(b[1])),c&&d.push("finally",w(c));return k(d)},"throw":function(a){return k(["throw",z(a)])+";"},"new":function(a,b){b=b.length>0?"("+l(W(b,z))+")":"";return k(["new",m(a,"seq","binary","conditional","assign",function(a){var b=N(),c={};try{b.with_walkers({call:function(){throw c},"function":function(){return this}},function(){b.walk(a)})}catch(d){if(d===c)return!0;throw d}})+b])},"switch":function(a,b){return k(["switch","("+z(a)+")",v(b)])},"break":function(a){var b="break";a!=null&&(b+=" "+g(a));return b+";"},"continue":function(a){var b="continue";a!=null&&(b+=" "+g(a));return b+";"},conditional:function(a,b,c){return k([m(a,"assign","seq","conditional"),"?",m(b,"seq"),":",m(c,"seq")])},assign:function(a,b,c){a&&a!==!0?a+="=":a="=";return k([z(b),a,m(c,"seq")])},dot:function(a){var b=z(a),c=1;a[0]=="num"?/\./.test(a[1])||(b+="."):o(a)&&(b="("+b+")");while(c<arguments.length)b+="."+g(arguments[c++]);return b},call:function(a,b){var c=z(a);o(a)&&(c="("+c+")");return c+"("+l(W(b,function(a){return m(a,"seq")}))+")"},"function":t,defun:t,"if":function(a,b,c){var d=["if","("+z(a)+")",c?s(b):z(b)];c&&d.push("else",z(c));return k(d)},"for":function(a,b,c,d){var e=["for"];a=(a!=null?z(a):"").replace(/;*\s*$/,";"+f),b=(b!=null?z(b):"").replace(/;*\s*$/,";"+f),c=(c!=null?z(c):"").replace(/;*\s*$/,"");var g=a+b+c;g=="; ; "&&(g=";;"),e.push("("+g+")",z(d));return k(e)},"for-in":function(a,b,c,d){return k(["for","("+(a?z(a).replace(/;+$/,""):z(b)),"in",z(c)+")",z(d)])},"while":function(a,b){return k(["while","("+z(a)+")",z(b)])},"do":function(a,b){return k(["do",z(b),"while","("+z(a)+")"])+";"},"return":function(a){var b=["return"];a!=null&&b.push(z(a));return k(b)+";"},binary:function(a,b,c){var d=z(b),e=z(c);if(L(b[0],["assign","conditional","seq"])||b[0]=="binary"&&B[a]>B[b[1]])d="("+d+")";if(L(c[0],["assign","conditional","seq"])||c[0]=="binary"&&B[a]>=B[c[1]]&&(c[1]!=a||!L(a,["&&","||","*"])))e="("+e+")";return k([d,a,e])},"unary-prefix":function(a,b){var c=z(b);b[0]=="num"||b[0]=="unary-prefix"&&!M(i,a+b[1])||!o(b)||(c="("+c+")");return a+(p(a.charAt(0))?" ":"")+c},"unary-postfix":function(a,b){var c=z(b);b[0]=="num"||b[0]=="unary-postfix"&&!M(i,a+b[1])||!o(b)||(c="("+c+")");return c+a},sub:function(a,b){var c=z(a);o(a)&&(c="("+c+")");return c+"["+z(b)+"]"},object:function(a){return a.length==0?"{}":"{"+e+j(function(){return W(a,function(a){if(a.length==3)return h(t(a[0],a[1][2],a[1][3],a[2]));var d=a[0],e=z(a[1]);b.quote_keys?d=Q(d):(typeof d=="number"||!c&&+d+""==d)&&parseFloat(d)>=0?d=q(+d):V(d)||(d=Q(d));return h(k(c&&b.space_colon?[d,":",e]:[d+":",e]))}).join(","+e)})+e+h("}")},regexp:function(a,b){return"/"+a+"/"+b},array:function(a){return a.length==0?"[]":k(["[",l(W(a,function(a){return!c&&a[0]=="atom"&&a[1]=="undefined"?"":m(a,"seq")})),"]"])},stat:function(a){return z(a).replace(/;*\s*$/,";")},seq:function(){return l(W(J(arguments),z))},label:function(a,b){return k([g(a),":",z(b)])},"with":function(a,b){return k(["with","("+z(a)+")",z(b)])},atom:function(a){return g(a)}},y=[];return z(a)}function Q(a){var b=0,c=0;a=a.replace(/[\\\b\f\n\r\t\x22\x27]/g,function(a){switch(a){case"\\":return"\\\\";case"\b":return"\\b";case"\f":return"\\f";case"\n":return"\\n";case"\r":return"\\r";case"\t":return"\\t";case'"':++b;return'"';case"'":++c;return"'"}return a});return b>c?"'"+a.replace(/\x27/g,"\\'")+"'":'"'+a.replace(/\x22/g,'\\"')+'"'}function O(a){return!a||a[0]=="block"&&(!a[1]||a[1].length==0)}function N(){function g(a,b){var c={},e;for(e in a)M(a,e)&&(c[e]=d[e],d[e]=a[e]);var f=b();for(e in c)M(c,e)&&(c[e]?d[e]=c[e]:delete d[e]);return f}function f(a){if(a==null)return null;try{e.push(a);var b=a[0],f=d[b];if(f){var g=f.apply(a,a.slice(1));if(g!=null)return g}f=c[b];return f.apply(a,a.slice(1))}finally{e.pop()}}function b(a){var b=[this[0]];a!=null&&b.push(W(a,f));return b}function a(a){return[this[0],W(a,function(a){var b=[a[0]];a.length>1&&(b[1]=f(a[1]));return b})]}var c={string:function(a){return[this[0],a]},num:function(a){return[this[0],a]},name:function(a){return[this[0],a]},toplevel:function(a){return[this[0],W(a,f)]},block:b,splice:b,"var":a,"const":a,"try":function(a,b,c){return[this[0],W(a,f),b!=null?[b[0],W(b[1],f)]:null,c!=null?W(c,f):null]},"throw":function(a){return[this[0],f(a)]},"new":function(a,b){return[this[0],f(a),W(b,f)]},"switch":function(a,b){return[this[0],f(a),W(b,function(a){return[a[0]?f(a[0]):null,W(a[1],f)]})]},"break":function(a){return[this[0],a]},"continue":function(a){return[this[0],a]},conditional:function(a,b,c){return[this[0],f(a),f(b),f(c)]},assign:function(a,b,c){return[this[0],a,f(b),f(c)]},dot:function(a){return[this[0],f(a)].concat(J(arguments,1))},call:function(a,b){return[this[0],f(a),W(b,f)]},"function":function(a,b,c){return[this[0],a,b.slice(),W(c,f)]},defun:function(a,b,c){return[this[0],a,b.slice(),W(c,f)]},"if":function(a,b,c){return[this[0],f(a),f(b),f(c)]},"for":function(a,b,c,d){return[this[0],f(a),f(b),f(c),f(d)]},"for-in":function(a,b,c,d){return[this[0],f(a),f(b),f(c),f(d)]},"while":function(a,b){return[this[0],f(a),f(b)]},"do":function(a,b){return[this[0],f(a),f(b)]},"return":function(a){return[this[0],f(a)]},binary:function(a,b,c){return[this[0],a,f(b),f(c)]},"unary-prefix":function(a,b){return[this[0],a,f(b)]},"unary-postfix":function(a,b){return[this[0],a,f(b)]},sub:function(a,b){return[this[0],f(a),f(b)]},object:function(a){return[this[0],W(a,function(a){return a.length==2?[a[0],f(a[1])]:[a[0],f(a[1]),a[2]]})]},regexp:function(a,b){return[this[0],a,b]},array:function(a){return[this[0],W(a,f)]},stat:function(a){return[this[0],f(a)]},seq:function(){return[this[0]].concat(W(J(arguments),f))},label:function(a,b){return[this[0],a,f(b)]},"with":function(a,b){return[this[0],f(a),f(b)]},atom:function(a){return[this[0],a]}},d={},e=[];return{walk:f,with_walkers:g,parent:function(){return e[e.length-2]},stack:function(){return e}}}function M(a,b){return Object.prototype.hasOwnProperty.call(a,b)}function L(a,b){for(var c=b.length;--c>=0;)if(b[c]===a)return!0;return!1}function K(a){return a.split("")}function J(a,b){return Array.prototype.slice.call(a,b||0)}function I(a){var b={};for(var c=0;c<a.length;++c)b[a[c]]=!0;return b}function H(a){a instanceof Function&&(a=a());for(var b=1,c=arguments.length;--c>0;++b)arguments[b]();return a}function G(a){var b=J(arguments,1);return function(){return a.apply(this,b.concat(J(arguments)))}}function F(a,b,c){function bk(a){try{++d.in_loop;return a()}finally{--d.in_loop}}function bi(a){var b=bg(a),c=d.token.value;if(e("operator")&&M(A,c)){if(bh(b)){g();return p("assign",A[c],b,bi(a))}i("Invalid assignment")}return b}function bh(a){if(!b)return!0;switch(a[0]){case"dot":case"sub":case"new":case"call":return!0;case"name":return a[1]!="this"}}function bg(a){var b=bf(a);if(e("operator","?")){g();var c=bj(!1);m(":");return p("conditional",b,c,bj(!1,a))}return b}function bf(a){return be(Y(!0),0,a)}function be(a,b,c){var f=e("operator")?d.token.value:null;f&&f=="in"&&c&&(f=null);var h=f!=null?B[f]:null;if(h!=null&&h>b){g();var i=be(Y(!0),h,c);return be(p("binary",f,a,i),b,c)}return a}function bd(a,b,c){(b=="++"||b=="--")&&!bh(c)&&i("Invalid use of "+b+" operator");return p(a,b,c)}function bc(a,b){if(e("punc",".")){g();return bc(p("dot",a,bb()),b)}if(e("punc","[")){g();return bc(p("sub",a,H(bj,G(m,"]"))),b)}if(b&&e("punc","(")){g();return bc(p("call",a,Z(")")),!0)}return b&&e("operator")&&M(z,d.token.value)?H(G(bd,"unary-postfix",d.token.value,a),g):a}function bb(){switch(d.token.type){case"name":case"operator":case"keyword":case"atom":return H(d.token.value,g);default:k()}}function ba(){switch(d.token.type){case"num":case"string":return H(d.token.value,g)}return bb()}function _(){var a=!0,c=[];while(!e("punc","}")){a?a=!1:m(",");if(!b&&e("punc","}"))break;var f=d.token.type,h=ba();f!="name"||h!="get"&&h!="set"||!!e("punc",":")?(m(":"),c.push([h,bj(!1)])):c.push([bb(),P(!1),h])}g();return p("object",c)}function $(){return p("array",Z("]",!b,!0))}function Z(a,b,c){var d=!0,f=[];while(!e("punc",a)){d?d=!1:m(",");if(b&&e("punc",a))break;e("punc",",")&&c?f.push(["atom","undefined"]):f.push(bj(!1))}g();return f}function X(){var a=Y(!1),b;e("punc","(")?(g(),b=Z(")")):b=[];return bc(p("new",a,b),!0)}function W(){return p("const",U())}function V(a){return p("var",U(a))}function U(a){var b=[];for(;;){e("name")||k();var c=d.token.value;g(),e("operator","=")?(g(),b.push([c,bj(!1,a)])):b.push([c]);if(!e("punc",","))break;g()}return b}function T(){var a=R(),b,c;if(e("keyword","catch")){g(),m("("),e("name")||i("Name expected");var f=d.token.value;g(),m(")"),b=[f,R()]}e("keyword","finally")&&(g(),c=R()),!b&&!c&&i("Missing catch/finally blocks");return p("try",a,b,c)}function R(){m("{");var a=[];while(!e("punc","}"))e("eof")&&k(),a.push(t());g();return a}function Q(){var a=q(),b=t(),c;e("keyword","else")&&(g(),c=t());return p("if",a,b,c)}function O(a){var b=a[0]=="var"?p("name",a[1][0]):a;g();var c=bj();m(")");return p("for-in",a,b,c,bk(t))}function N(a){m(";");var b=e("punc",";")?null:bj();m(";");var c=e("punc",")")?null:bj();m(")");return p("for",a,b,c,bk(t))}function K(){m("(");var a=null;if(!e("punc",";")){a=e("keyword","var")?(g(),V(!0)):bj(!0,!0);if(e("operator","in"))return O(a)}return N(a)}function I(a){var b;n()||(b=e("name")?d.token.value:null),b!=null?(g(),L(b,d.labels)||i("Label "+b+" without matching loop or statement")):d.in_loop==0&&i(a+" not inside a loop or switch"),o();return p(a,b)}function F(){return p("stat",H(bj,o))}function w(a){d.labels.push(a);var c=d.token,e=t();b&&!M(C,e[0])&&k(c),d.labels.pop();return p("label",a,e)}function s(a){return c?function(){var b=d.token,c=a.apply(this,arguments);c[0]=r(c[0],b,h());return c}:a}function r(a,b,c){return a instanceof E?a:new E(a,b,c)}function q(){m("(");var a=bj();m(")");return a}function p(){return J(arguments)}function o(){e("punc",";")?g():n()||k()}function n(){return!b&&(d.token.nlb||e("eof")||e("punc","}"))}function m(a){return l("punc",a)}function l(a,b){if(e(a,b))return g();j(d.token,"Unexpected token "+d.token.type+", expected "+a)}function k(a){a==null&&(a=d.token),j(a,"Unexpected token: "+a.type+" ("+a.value+")")}function j(a,b){i(b,a.line,a.col)}function i(a,b,c,e){var f=d.input.context();u(a,b!=null?b:f.tokline,c!=null?c:f.tokcol,e!=null?e:f.tokpos)}function h(){return d.prev}function g(){d.prev=d.token,d.peeked?(d.token=d.peeked,d.peeked=null):d.token=d.input();return d.token}function f(){return d.peeked||(d.peeked=d.input())}function e(a,b){return v(d.token,a,b)}var d={input:typeof a=="string"?x(a,!0):a,token:null,prev:null,peeked:null,in_function:0,in_loop:0,labels:[]};d.token=g();var t=s(function(){e("operator","/")&&(d.peeked=null,d.token=d.input(!0));switch(d.token.type){case"num":case"string":case"regexp":case"operator":case"atom":return F();case"name":return v(f(),"punc",":")?w(H(d.token.value,g,g)):F();case"punc":switch(d.token.value){case"{":return p("block",R());case"[":case"(":return F();case";":g();return p("block");default:k()};case"keyword":switch(H(d.token.value,g)){case"break":return I("break");case"continue":return I("continue");case"debugger":o();return p("debugger");case"do":return function(a){l("keyword","while");return p("do",H(q,o),a)}(bk(t));case"for":return K();case"function":return P(!0);case"if":return Q();case"return":d.in_function==0&&i("'return' outside of function");return p("return",e("punc",";")?(g(),null):n()?null:H(bj,o));case"switch":return p("switch",q(),S());case"throw":return p("throw",H(bj,o));case"try":return T();case"var":return H(V,o);case"const":return H(W,o);case"while":return p("while",q(),bk(t));case"with":return p("with",q(),t());default:k()}}}),P=s(function(a){var b=e("name")?H(d.token.value,g):null;a&&!b&&k(),m("(");return p(a?"defun":"function",b,function(a,b){while(!e("punc",")"))a?a=!1:m(","),e("name")||k(),b.push(d.token.value),g();g();return b}(!0,[]),function(){++d.in_function;var a=d.in_loop;d.in_loop=0;var b=R();--d.in_function,d.in_loop=a;return b}())}),S=G(bk,function(){m("{");var a=[],b=null;while(!e("punc","}"))e("eof")&&k(),e("keyword","case")?(g(),b=[],a.push([bj(),b]),m(":")):e("keyword","default")?(g(),m(":"),b=[],a.push([null,b])):(b||k(),b.push(t()));g();return a}),Y=s(function(a){if(e("operator","new")){g();return X()}if(e("operator")&&M(y,d.token.value))return bd("unary-prefix",H(d.token.value,g),Y(a));if(e("punc")){switch(d.token.value){case"(":g();return bc(H(bj,G(m,")")),a);case"[":g();return bc($(),a);case"{":g();return bc(_(),a)}k()}if(e("keyword","function")){g();return bc(P(!1),a)}if(M(D,d.token.type)){var b=d.token.type=="regexp"?p("regexp",d.token.value[0],d.token.value[1]):p(d.token.type,d.token.value);return bc(H(b,g),a)}k()}),bj=s(function(a,b){arguments.length==0&&(a=!0);var c=bi(b);if(a&&e("punc",",")){g();return p("seq",c,bj(!0,b))}return c});return p("toplevel",function(a){while(!e("eof"))a.push(t());return a}([]))}function E(a,b,c){this.name=a,this.start=b,this.end=c}function x(b){function P(a){if(a)return I();y(),v();var b=g();if(!b)return x("eof");if(o(b))return C();if(b=='"'||b=="'")return F();if(M(l,b))return x("punc",h());if(b==".")return L();if(b=="/")return K();if(M(e,b))return J();if(b=="\\"||q(b))return N();B("Unexpected character '"+b+"'")}function O(a,b){try{return b()}catch(c){if(c===w)B(a);else throw c}}function N(){var b=A(r);return M(a,b)?M(i,b)?x("operator",b):M(d,b)?x("atom",b):x("keyword",b):x("name",b)}function L(){h();return o(g())?C("."):x("punc",".")}function K(){h();var a=f.regex_allowed;switch(g()){case"/":f.comments_before.push(G()),f.regex_allowed=a;return P();case"*":f.comments_before.push(H()),f.regex_allowed=a;return P()}return f.regex_allowed?I():J("/")}function J(a){function b(a){if(!g())return a;var c=a+g();if(M(i,c)){h();return b(c)}return a}return x("operator",b(a||h()))}function I(){return O("Unterminated regular expression",function(){var a=!1,b="",c,d=!1;while(c=h(!0))if(a)b+="\\"+c,a=!1;else if(c=="[")d=!0,b+=c;else if(c=="]"&&d)d=!1,b+=c;else{if(c=="/"&&!d)break;c=="\\"?a=!0:b+=c}var e=A(function(a){return M(m,a)});return x("regexp",[b,e])})}function H(){h();return O("Unterminated multiline comment",function(){var a=t("*/",!0),b=f.text.substring(f.pos,a),c=x("comment2",b,!0);f.pos=a+2,f.line+=b.split("\n").length-1,f.newline_before=b.indexOf("\n")>=0;return c})}function G(){h();var a=t("\n"),b;a==-1?(b=f.text.substr(f.pos),f.pos=f.text.length):(b=f.text.substring(f.pos,a),f.pos=a);return x("comment1",b,!0)}function F(){return O("Unterminated string constant",function(){var a=h(),b="";for(;;){var c=h(!0);if(c=="\\")c=D();else if(c==a)break;b+=c}return x("string",b)})}function E(a){var b=0;for(;a>0;--a){var c=parseInt(h(!0),16);isNaN(c)&&B("Invalid hex-character pattern in string"),b=b<<4|c}return b}function D(){var a=h(!0);switch(a){case"n":return"\n";case"r":return"\r";case"t":return"\t";case"b":return"\b";case"v":return"";case"f":return"\f";case"0":return"
