<!doctype html>
<html itemscope="" itemtype="http://schema.org/SearchResultsPage" lang="vi">
    <head>
        <meta charset="UTF-8">
        <meta content="origin" name="referrer">
        <meta content="/images/branding/googleg/1x/googleg_standard_color_128dp.png" itemprop="image">
        <title>code mau token gooogle - Tìm trên Google</title>
        <script nonce="N4ljJHxWoJx3pKoWtd5YIw">
            (function() {
                var b = window.addEventListener;
                window.addEventListener = function(a, c, d) {
                    "unload" !== a && b(a, c, d)
                }
                ;
            }
            ).call(this);
            (function() {
                var _g = {
                    kEI: 'Ny0hZajKHuSv2roPysWswAY',
                    kEXPI: '31',
                    kBL: 'niYV',
                    kOPI: 89978449
                };
                (function() {
                    var a;
                    (null == (a = window.google) ? 0 : a.stvsc) ? google.kEI = _g.kEI : window.google = _g;
                }
                ).call(this);
            }
            )();
            (function() {
                google.sn = 'web';
                google.kHL = 'vi';
            }
            )();
            (function() {
                var h = this || self;
                function l() {
                    return void 0 !== window.google && void 0 !== window.google.kOPI && 0 !== window.google.kOPI ? window.google.kOPI : null
                }
                ;var m, n = [];
                function p(a) {
                    for (var b; a && (!a.getAttribute || !(b = a.getAttribute("eid"))); )
                        a = a.parentNode;
                    return b || m
                }
                function q(a) {
                    for (var b = null; a && (!a.getAttribute || !(b = a.getAttribute("leid"))); )
                        a = a.parentNode;
                    return b
                }
                function r(a) {
                    /^http:/i.test(a) && "https:" === window.location.protocol && (google.ml && google.ml(Error("a"), !1, {
                        src: a,
                        glmm: 1
                    }),
                    a = "");
                    return a
                }
                function t(a, b, c, d, k) {
                    var e = "";
                    -1 === b.search("&ei=") && (e = "&ei=" + p(d),
                    -1 === b.search("&lei=") && (d = q(d)) && (e += "&lei=" + d));
                    d = "";
                    var g = -1 === b.search("&cshid=") && "slh" !== a
                      , f = [];
                    f.push(["zx", Date.now().toString()]);
                    h._cshid && g && f.push(["cshid", h._cshid]);
                    c = c();
                    null != c && f.push(["opi", c.toString()]);
                    for (c = 0; c < f.length; c++) {
                        if (0 === c || 0 < c)
                            d += "&";
                        d += f[c][0] + "=" + f[c][1]
                    }
                    return "/" + (k || "gen_204") + "?atyp=i&ct=" + String(a) + "&cad=" + (b + e + d)
                }
                ;m = google.kEI;
                google.getEI = p;
                google.getLEI = q;
                google.ml = function() {
                    return null
                }
                ;
                google.log = function(a, b, c, d, k, e) {
                    e = void 0 === e ? l : e;
                    c || (c = t(a, b, e, d, k));
                    if (c = r(c)) {
                        a = new Image;
                        var g = n.length;
                        n[g] = a;
                        a.onerror = a.onload = a.onabort = function() {
                            delete n[g]
                        }
                        ;
                        a.src = c
                    }
                }
                ;
                google.logUrl = function(a, b) {
                    b = void 0 === b ? l : b;
                    return t("", a, b)
                }
                ;
            }
            ).call(this);
            (function() {
                google.y = {};
                google.sy = [];
                google.x = function(a, b) {
                    if (a)
                        var c = a.id;
                    else {
                        do
                            c = Math.random();
                        while (google.y[c])
                    }
                    google.y[c] = [a, b];
                    return !1
                }
                ;
                google.sx = function(a) {
                    google.sy.push(a)
                }
                ;
                google.lm = [];
                google.plm = function(a) {
                    google.lm.push.apply(google.lm, a)
                }
                ;
                google.lq = [];
                google.load = function(a, b, c) {
                    google.lq.push([[a], b, c])
                }
                ;
                google.loadAll = function(a, b) {
                    google.lq.push([a, b])
                }
                ;
                google.bx = !1;
                google.lx = function() {}
                ;
                var d = [];
                google.fce = function(a, b, c, e) {
                    d.push([a, b, c, e])
                }
                ;
                google.qce = d;
            }
            ).call(this);
            google.f = {};
            (function() {
                document.documentElement.addEventListener("submit", function(b) {
                    var a;
                    if (a = b.target) {
                        var c = a.getAttribute("data-submitfalse");
                        a = "1" === c || "q" === c && !a.elements.q.value ? !0 : !1
                    } else
                        a = !1;
                    a && (b.preventDefault(),
                    b.stopPropagation())
                }, !0);
                document.documentElement.addEventListener("click", function(b) {
                    var a;
                    a: {
                        for (a = b.target; a && a !== document.documentElement; a = a.parentElement)
                            if ("A" === a.tagName) {
                                a = "1" === a.getAttribute("data-nohref");
                                break a
                            }
                        a = !1
                    }
                    a && b.preventDefault()
                }, !0);
            }
            ).call(this);
            (function() {
                google.hs = {
                    h: true,
                    nhs: false,
                    sie: false
                };
            }
            )();
            (function() {
                google.c = {
                    bfrt: false,
                    bfrte: true,
                    bofr: true,
                    btfi: false,
                    c4t: true,
                    cap: 2000,
                    csp: false,
                    di: false,
                    fla: false,
                    fli: false,
                    frt: false,
                    frvt: true,
                    gl: false,
                    idt: 16,
                    inpp: 98,
                    irsf: false,
                    lhc: false,
                    linp: true,
                    llt: false,
                    lsb: true,
                    mais: false,
                    pbph: false,
                    raf: false,
                    si: true,
                    sidt: 200,
                    sxs: false,
                    taf: true,
                    timl: false,
                    upb: false,
                    vis: true,
                    wfo: true,
                    wh0: false,
                    whu: false
                };
            }
            )();
            (function() {
                var h = this || self;
                var k = window.performance;
                function l(a, b, d) {
                    a: {
                        for (var c = a; c && c !== b; c = c.parentElement)
                            if ("hidden" === c.style.overflow || "G-EXPANDABLE-CONTENT" === c.tagName && "hidden" === getComputedStyle(c).getPropertyValue("overflow")) {
                                b = c;
                                break a
                            }
                        b = null
                    }
                    if (!b)
                        return !1;
                    a = d(a);
                    d = d(b);
                    return a.bottom < d.top || a.top >= d.bottom || a.right < d.left || a.left >= d.right
                }
                function m(a) {
                    return "none" === a.style.display ? !0 : document.defaultView && document.defaultView.getComputedStyle ? (a = document.defaultView.getComputedStyle(a),
                    !!a && ("hidden" === a.visibility || "0px" === a.height && "0px" === a.width)) : !1
                }
                function n(a, b, d, c, e) {
                    var f = e(a)
                      , w = f.left + (d ? 0 : window.pageXOffset)
                      , p = f.top + (d ? 0 : window.pageYOffset)
                      , q = f.width
                      , r = f.height
                      , g = 0;
                    if (!b && 0 >= r && 0 >= q)
                        return g;
                    b = window.innerHeight || document.documentElement.clientHeight;
                    0 > p + r ? g = 2 : p >= b && (g = 4);
                    if (0 > w + q || w >= (window.innerWidth || document.documentElement.clientWidth))
                        g |= 8;
                    else if (c) {
                        f = f.left;
                        if (!d)
                            for (; a && a !== c; a = a.parentElement)
                                f += a.scrollLeft;
                        c = e(c);
                        if (f + q < c.left || f >= c.right)
                            g |= 8
                    }
                    g || (g = 1,
                    p + r > b && (g |= 4));
                    return g
                }
                ;var t = google.c.gl
                  , u = google.c.sxs
                  , v = google.c.wfo;
                function x(a, b, d, c) {
                    a.addEventListener ? a.addEventListener(b, d, c || !1) : a.attachEvent && a.attachEvent("on" + b, d)
                }
                function y(a, b, d, c) {
                    "addEventListener"in a ? a.removeEventListener(b, d, c || !1) : a.attachEvent && a.detachEvent("on" + b, d)
                }
                ;google.c.iim = google.c.iim || {};
                function z(a) {
                    a && h.google.aft(a.target)
                }
                var A;
                function B() {
                    y(document.documentElement, "load", A, !0);
                    y(document.documentElement, "error", A, !0)
                }
                ;google.timers = {};
                google.startTick = function(a) {
                    google.timers[a] = {
                        t: {
                            start: Date.now()
                        },
                        e: {},
                        m: {}
                    }
                }
                ;
                google.tick = function(a, b, d) {
                    google.timers[a] || google.startTick(a);
                    d = void 0 !== d ? d : Date.now();
                    b instanceof Array || (b = [b]);
                    for (var c = 0, e; e = b[c++]; )
                        google.timers[a].t[e] = d
                }
                ;
                google.c.e = function(a, b, d) {
                    google.timers[a].e[b] = d
                }
                ;
                google.c.b = function(a, b) {
                    b = google.timers[b || "load"].m;
                    b[a] && google.ml(Error("a"), !1, {
                        m: a
                    });
                    b[a] = !0
                }
                ;
                google.c.u = function(a, b) {
                    var d = google.timers[b || "load"]
                      , c = d.m;
                    if (c[a]) {
                        c[a] = !1;
                        for (a in c)
                            if (c[a])
                                return !1;
                        google.csiReport(d, u && "load2" === b ? "all2" : "all");
                        return !0
                    }
                    b = "";
                    for (var e in c)
                        b += e + ":" + c[e] + ";";
                    google.ml(Error("b"), !1, {
                        m: a,
                        b: !1 === c[a],
                        s: b
                    });
                    return !1
                }
                ;
                google.rll = function(a, b, d) {
                    function c(e) {
                        d(e);
                        y(a, "load", c);
                        y(a, "error", c)
                    }
                    x(a, "load", c);
                    b && x(a, "error", c)
                }
                ;
                h.google.aft = function(a) {
                    a.setAttribute("data-iml", String(Date.now()))
                }
                ;
                google.startTick("load");
                var C = google.timers.load;
                if (!google.stvsc)
                    a: {
                        var D = C.t;
                        if (k) {
                            var E = k.timing;
                            if (E) {
                                var F = E.navigationStart
                                  , G = E.responseStart;
                                if (G > F && G <= D.start) {
                                    D.start = G;
                                    C.wsrt = G - F;
                                    break a
                                }
                            }
                            k.now && (C.wsrt = Math.floor(k.now()))
                        }
                    }
                v && google.c.b("pr", "load");
                google.c.b("xe", "load");
                var H;
                if (null == (H = google.stvsc) ? 0 : H.start)
                    google.timers.load.t.start = google.stvsc.start;
                function I(a) {
                    if ("hidden" === document.visibilityState) {
                        google.c.fh = a;
                        var b;
                        window.performance && window.performance.timing && (b = Math.floor(window.performance.timing.navigationStart + a));
                        google.tick("load", "fht", b);
                        return !0
                    }
                    return !1
                }
                function J(a) {
                    I(a.timeStamp) && y(document, "visibilitychange", J, !0)
                }
                google.c.fh = Infinity;
                x(document, "visibilitychange", J, !0);
                I(0);
                t && (A = z,
                x(document.documentElement, "load", A, !0),
                google.c.glu = B);
                google.cv = function(a, b, d, c) {
                    if (!a || !b && m(a))
                        return 0;
                    if (!a.getBoundingClientRect)
                        return 1;
                    var e = function(f) {
                        return f.getBoundingClientRect()
                    };
                    return !b && l(a, c, e) ? 0 : n(a, b, d, c, e)
                }
                ;
            }
            ).call(this);
            (function() {
                var g = this || self;
                function h(a) {
                    try {
                        a()
                    } catch (b) {
                        google.ml(b, !1)
                    }
                }
                google.caft = function(a, b) {
                    null === google.aftq ? h(a) : (google.aftq = google.aftq || [],
                    google.aftq.push(a),
                    b && window.setTimeout(function() {
                        google.aftq && (google.aftq = google.aftq.filter(function(c) {
                            return a !== c
                        }),
                        h(a))
                    }, b))
                }
                ;
                function m() {
                    return window.performance && window.performance.navigation && window.performance.navigation.type
                }
                ;var q = google.c.bfrt
                  , aa = google.c.csp
                  , ba = google.c.lhc
                  , ca = google.c.pbph
                  , t = google.c.sxs
                  , u = google.c.taf
                  , v = google.c.btfi
                  , w = google.c.frt
                  , x = google.c.frvt
                  , y = google.c.timl
                  , z = google.c.upb;
                function A(a) {
                    return "/gen_204?s=" + google.sn + "&t=" + a + "&atyp=csi&ei=" + google.kEI
                }
                ;function B() {
                    var a;
                    null == (a = C("cap")) || a.sendNow();
                    var b;
                    null == (b = C("aft")) || b.sendNow();
                    var c;
                    null == (c = C("all")) || c.sendNow();
                    a = window;
                    "addEventListener"in a ? a.removeEventListener("pagehide", B, !1) : a.attachEvent && a.detachEvent("onpagehide", B)
                }
                var D = {};
                function E(a) {
                    z && (D[a] = new PendingGetBeacon(A(a) + "&inc=1"))
                }
                function C(a) {
                    if (z)
                        return D[a]
                }
                ;var da = window.location
                  , ea = "aft afti aftr afts cbs cbt fht frt frts frvt hct prt sct".split(" ");
                function F(a) {
                    return (a = da.search.match(new RegExp("[?&]" + a + "=(\\d+)"))) ? Number(a[1]) : -1
                }
                function G(a, b) {
                    var c = google.timers[b || "load"];
                    b = c.m;
                    if (!b || !b.prs) {
                        var d = m() ? 0 : F("qsubts");
                        0 < d && (b = F("fbts"),
                        0 < b && (c.t.start = Math.max(d, b)));
                        var e = c.t
                          , f = e.start;
                        b = {
                            wsrt: c.wsrt || 0
                        };
                        if (f)
                            for (var r = 0, n; n = ea[r++]; ) {
                                var k = e[n];
                                k && (b[n] = Math.max(k - f, 0))
                            }
                        0 < d && (b.gsasrt = c.t.start - d);
                        d = c.e;
                        c = A(a) + "&rt=";
                        e = "";
                        for (var p in b)
                            c += "" + e + p + "." + b[p],
                            e = ",";
                        for (var l in d)
                            c += "&" + l + "=" + d[l];
                        p = c;
                        l = "";
                        c = [];
                        g._cshid && c.push(["cshid", g._cshid]);
                        d = void 0 !== window.google && void 0 !== window.google.kOPI && 0 !== window.google.kOPI ? window.google.kOPI : null;
                        null != d && c.push(["opi", d.toString()]);
                        for (d = 0; d < c.length; d++) {
                            if (0 === d || 0 < d)
                                l += "&";
                            l += c[d][0] + "=" + c[d][1]
                        }
                        c = p + l;
                        2 === m() && (c += "&bb=1");
                        1 === m() && (c += "&r=1");
                        "gsasrt"in b && (b = F("qsd"),
                        0 < b && (c += "&qsd=" + b));
                        b = c;
                        (a = C(a)) ? (a.setURL(b),
                        a.sendNow()) : "function" === typeof navigator.sendBeacon ? navigator.sendBeacon(b, "") : google.log("", "", b)
                    }
                }
                ;function H(a) {
                    a && google.tick("load", "cbs", a);
                    google.tick("load", "cbt");
                    G("cap")
                }
                ;var I = "src bsrc url ll image img-url".split(" ");
                function fa(a) {
                    for (var b = 0; b < I.length; ++b)
                        if (a.getAttribute("data-" + I[b]))
                            return !0;
                    return !1
                }
                function ha(a) {
                    var b;
                    if (aa)
                        a: {
                            for (b = a.parentElement; b; b = b.parentElement) {
                                var c = getComputedStyle(b);
                                if ("hidden" === c.overflowY && "auto" === c.overflowX) {
                                    b = b.parentElement;
                                    break a
                                }
                            }
                            b = null
                        }
                    else
                        for (b = a; b && "center_col" !== b.id; )
                            b = b.parentElement;
                    if ((c = a.parentElement) && ("G-IMG" === c.tagName || c.classList.contains("uhHOwf")) && (c.style.height || c.style.width)) {
                        var d = c.getBoundingClientRect()
                          , e = a.getBoundingClientRect();
                        if (d.height <= e.height || d.width <= e.width)
                            a = c
                    }
                    return google.cv(a, !1, void 0, b)
                }
                google.c.iim = google.c.iim || {};
                var J = window.performance;
                var K = window.innerHeight || document.documentElement.clientHeight, L = 0, M = 0, N = 0, O = 0, ia = 0, la = 0, P = 0, Q = 0, ma = 0, na = 0, R = !0, S = !0, T = -1, U, V = t ? "load2" : "load";
                function W(a, b, c, d) {
                    var e = google.timers[V].t[a];
                    e && (c || d && null != b && b < e) || google.tick(V, a, b)
                }
                function X(a, b, c) {
                    var d = "1" === a.getAttribute("data-frt");
                    w && d && (W("frt", c, !1, !0),
                    ++O,
                    Y());
                    b && (x && d && (W("frvt", c, !1, !0),
                    ++la),
                    W("aft", c, !1, !0),
                    W("afti", c, !1, !0),
                    ++Q,
                    R || (T = K),
                    Y());
                    y && W("iml", c, !1, !0);
                    ++M;
                    a.setAttribute("data-frt", "0");
                    (y || b || q && d) && oa()
                }
                function oa() {
                    var a = Q === P
                      , b = O === N;
                    a = q ? a && b : a;
                    a = y ? M === L : a;
                    !S && a && google.c.u("il", V)
                }
                function Y() {
                    if (!R) {
                        var a = Q === P
                          , b = O === N
                          , c = x && la === ia;
                        a && (google.c.e(V, "aft", "1"),
                        google.c.e(V, "aftp", String(Math.round(T))));
                        if (a && b) {
                            U && clearTimeout(U);
                            var d;
                            null == (d = C("cap")) || d.deactivate();
                            G(t ? "aft2" : "aft", V);
                            if (!t && google.c.c4t && J && J.mark && J.timing) {
                                var e = google.timers.load;
                                d = e.wsrt;
                                e = e.t.aft;
                                d && 0 < d && e && 0 < e && (e -= J.timing.navigationStart,
                                0 < e && (J.mark("SearchAFTStart", {
                                    startTime: d
                                }),
                                J.mark("trigger:SearchAFTEnd", {
                                    startTime: e
                                })))
                            }
                        }
                        "hidden" === document.visibilityState && google.c.e(V, "hddn", "1");
                        if (!t && null !== google.aftq && (2 === google.fevent || 3 === google.fevent ? google.fevent : 1) & ((a ? 1 : 0) | (c || b ? 2 : 0))) {
                            google.tick("load", "aftqf", Date.now());
                            var f;
                            for (a = 0; b = null == (f = google.aftq) ? void 0 : f[a++]; )
                                h(b);
                            google.aftq = null
                        }
                    }
                }
                function pa() {
                    R && !google.c.bofr && (R = !1,
                    R || (google.c.e(V, "ima", String(P)),
                    google.c.e(V, "imad", String(ma)),
                    google.c.e(V, "imac", String(na)),
                    google.c.e(V, "imf", String(N)),
                    document.getElementsByClassName("Ib7Efc").length && google.c.e(V, "ddl", "1")),
                    Y())
                }
                function qa(a, b) {
                    0 === b || b & 8 || (a.setAttribute("data-frt", "1"),
                    w && ++N)
                }
                function ra(a, b, c) {
                    var d = a.getAttribute("data-atf");
                    if (d)
                        return c = Number(d),
                        b && !a.hasAttribute("data-frt") && qa(a, c),
                        c;
                    var e = "string" !== typeof a.src || !a.src
                      , f = !!a.getAttribute("data-bsrc")
                      , r = !!a.getAttribute("data-deferred")
                      , n = !r && fa(a);
                    n && a.setAttribute("data-lzy_", "1");
                    d = ha(a);
                    a.setAttribute("data-atf", String(d));
                    var k = !!(d & 1);
                    e = (e || a.complete) && !r && !f && !(k && n);
                    f = !ba && Number(a.getAttribute("data-iml")) || 0;
                    ++L;
                    if (e && !f || a.hasAttribute("data-noaft"))
                        a.setAttribute("data-frt", "0"),
                        ++M,
                        k && ++na;
                    else {
                        var p = d & 4
                          , l = v && p && f && T < K;
                        if (l) {
                            var ja = a.getBoundingClientRect().top + window.pageYOffset;
                            !c || 0 > c || ja < c ? T = k ? K : ja : l = !1
                        }
                        k && (++P,
                        r && ++ma);
                        b && qa(a, d);
                        x && k && b && ++ia;
                        l && (W("aft", f, !1, !0),
                        W("aftb", f, !1, !0));
                        if (e && f)
                            X(a, k, v ? 0 : f);
                        else {
                            k && (!u && !c || p || c && (0 > c || c >= K)) && (T = K);
                            var ka = a.src;
                            google.rll(a, !0, function() {
                                (r || n) && ka && ka === a.src ? google.rll(a, !0, function() {
                                    X(a, k, Date.now())
                                }) : X(a, k, Date.now())
                            })
                        }
                    }
                    return d
                }
                if (z && "function" === typeof window.PendingGetBeacon) {
                    E("cap");
                    E("aft");
                    E("all");
                    if (ca) {
                        var Z = window;
                        Z.addEventListener ? Z.addEventListener("pagehide", B, !1) : Z.attachEvent && Z.attachEvent("onpagehide", B)
                    }
                    google.c.lpb = C("all")
                }
                if (0 < google.c.cap && !t)
                    a: {
                        var sa = google.c.cap;
                        if (window.performance && window.performance.timing && "navigationStart"in window.performance.timing) {
                            var ta = window.performance.now()
                              , ua = sa - ta;
                            if (0 < ua) {
                                U = setTimeout(H, ua, Math.floor(window.performance.timing.navigationStart + ta));
                                break a
                            }
                            H()
                        }
                        U = void 0
                    }
                google.c.wh = Math.floor(window.innerHeight || document.documentElement.clientHeight);
                google.c.e(V, "wh", String(google.c.wh));
                google.c.b("il", V);
                if (google.c.sxs) {
                    var va = google.c.setup;
                    google.c.setup = function(a) {
                        va(a);
                        return ra(a)
                    }
                } else
                    google.c.setup = ra;
                google.c.ubr = function(a, b, c, d) {
                    u && T < K ? (T = c || -1,
                    W("aft", b)) : 0 > T && (c && (T = c),
                    v && W("aft", b));
                    a || W("afts", b, !0);
                    d || (W("aft", b, !0),
                    a && S ? (W("prt", b),
                    y && W("iml", b, !0),
                    S = !1,
                    pa(),
                    oa(),
                    google.c.setup = function() {
                        return 0
                    }
                    ,
                    google.c.ubr = function() {}
                    ) : pa())
                }
                ;
            }
            ).call(this);
            (function() {
                var b = [function() {
                    google.tick && google.tick("load", "dcl")
                }
                ];
                google.dclc = function(a) {
                    b.length ? b.push(a) : a()
                }
                ;
                function c() {
                    for (var a = b.shift(); a; )
                        a(),
                        a = b.shift()
                }
                window.addEventListener ? (document.addEventListener("DOMContentLoaded", c, !1),
                window.addEventListener("load", c, !1)) : window.attachEvent && window.attachEvent("onload", c);
            }
            ).call(this);
            (function() {
                var b = [];
                google.jsc = {
                    xx: b,
                    x: function(a) {
                        b.push(a)
                    },
                    mm: [],
                    m: function(a) {
                        google.jsc.mm.length || (google.jsc.mm = a)
                    }
                };
            }
            ).call(this);
            (function() {
                var e = this || self;
                var f = {};
                function w(a, c) {
                    if (null === c)
                        return !1;
                    if ("contains"in a && 1 == c.nodeType)
                        return a.contains(c);
                    if ("compareDocumentPosition"in a)
                        return a == c || !!(a.compareDocumentPosition(c) & 16);
                    for (; c && a != c; )
                        c = c.parentNode;
                    return c == a
                }
                ;var y = function(a, c) {
                    return function(d) {
                        d || (d = window.event);
                        return c.call(a, d)
                    }
                }
                  , z = "undefined" != typeof navigator && /Macintosh/.test(navigator.userAgent)
                  , E = function() {
                    this._mouseEventsPrevented = !0
                };
                var F = function(a) {
                    this.g = a;
                    this.h = []
                }
                  , G = function(a) {
                    for (var c = 0; c < a.h.length; ++c) {
                        var d = a.g
                          , b = a.h[c];
                        d.removeEventListener ? d.removeEventListener(b.eventType, b.s, b.capture) : d.detachEvent && d.detachEvent("on" + b.eventType, b.s)
                    }
                    a.h = []
                };
                var H = e._jsa || {};
                H._cfc = void 0;
                H._aeh = void 0;
                var I = function() {
                    this.h = this.g = null
                }
                  , K = function(a, c) {
                    var d = J;
                    d.g = a;
                    d.h = c;
                    return d
                };
                I.prototype.i = function() {
                    var a = this.g;
                    this.g && this.g != this.h ? this.g = this.g.__owner || this.g.parentNode : this.g = null;
                    return a
                }
                ;
                var L = function() {
                    var a;
                    this.j = a = void 0 === a ? [] : a;
                    this.g = 0;
                    this.h = null;
                    this.l = !1
                }
                  , N = function(a, c) {
                    var d = M;
                    d.j = a;
                    d.g = 0;
                    d.h = c;
                    d.l = !1;
                    return d
                };
                L.prototype.i = function() {
                    if (this.l)
                        return J.i();
                    if (this.g != this.j.length) {
                        var a = this.j[this.g];
                        this.g++;
                        a != this.h && a && a.__owner && (this.l = !0,
                        K(a.__owner, this.h));
                        return a
                    }
                    return null
                }
                ;
                var J = new I
                  , M = new L;
                var Q = function() {
                    this.v = [];
                    this.g = [];
                    this.h = [];
                    this.l = {};
                    this.i = null;
                    this.j = [];
                    P(this, "_custom")
                }
                  , R = function(a) {
                    return String.prototype.trim ? a.trim() : a.replace(/^\s+/, "").replace(/\s+$/, "")
                }
                  , ia = function(a, c) {
                    return function m(b, g) {
                        g = void 0 === g ? !0 : g;
                        var l = c;
                        if ("_custom" == l) {
                            l = b.detail;
                            if (!l || !l._type)
                                return;
                            l = l._type
                        }
                        var k = l;
                        "click" == k && (z && b.metaKey || !z && b.ctrlKey || 2 == b.which || null == b.which && 4 == b.button || b.shiftKey) ? k = "clickmod" : "keydown" == k && !b.a11ysc && (k = "maybe_click");
                        var u = b.srcElement || b.target;
                        l = S(k, b, u, "", null);
                        var aa = b.path ? N(b.path, this) : b.composedPath ? N(b.composedPath(), this) : K(u, this);
                        for (var r; r = aa.i(); ) {
                            var h = r;
                            var p = void 0;
                            r = h;
                            var q = k
                              , ba = b;
                            var n = r.__jsaction;
                            if (!n) {
                                var x;
                                n = null;
                                "getAttribute"in r && (n = r.getAttribute("jsaction"));
                                if (x = n) {
                                    n = f[x];
                                    if (!n) {
                                        n = {};
                                        for (var A = x.split(ca), da = A ? A.length : 0, B = 0; B < da; B++) {
                                            var v = A[B];
                                            if (v) {
                                                var C = v.indexOf(":")
                                                  , O = -1 != C
                                                  , fa = O ? R(v.substr(0, C)) : ea;
                                                v = O ? R(v.substr(C + 1)) : v;
                                                n[fa] = v
                                            }
                                        }
                                        f[x] = n
                                    }
                                    r.__jsaction = n
                                } else
                                    n = ha,
                                    r.__jsaction = n
                            }
                            "maybe_click" == q && n.click ? (p = q,
                            q = "click") : "clickkey" == q ? q = "click" : "click" != q || n.click || (q = "clickonly");
                            p = H._cfc && n.click ? H._cfc(r, ba, n, q, p) : {
                                eventType: p ? p : q,
                                action: n[q] || "",
                                event: null,
                                ignore: !1
                            };
                            l = S(p.eventType, p.event || b, u, p.action || "", h, l.timeStamp);
                            if (p.ignore || p.action)
                                break
                        }
                        l && "touchend" == l.eventType && (l.event._preventMouseEvents = E);
                        if (p && p.action) {
                            if ("mouseenter" == k || "mouseleave" == k || "pointerenter" == k || "pointerleave" == k)
                                if (u = b.relatedTarget,
                                !("mouseover" == b.type && "mouseenter" == k || "mouseout" == b.type && "mouseleave" == k || "pointerover" == b.type && "pointerenter" == k || "pointerout" == b.type && "pointerleave" == k) || u && (u === h || w(h, u)))
                                    l.action = "",
                                    l.actionElement = null;
                                else {
                                    k = {};
                                    for (var t in b)
                                        "function" !== typeof b[t] && "srcElement" !== t && "target" !== t && (k[t] = b[t]);
                                    k.type = "mouseover" == b.type ? "mouseenter" : "mouseout" == b.type ? "mouseleave" : "pointerover" == b.type ? "pointerenter" : "pointerleave";
                                    k.target = k.srcElement = h;
                                    k.bubbles = !1;
                                    l.event = k;
                                    l.targetElement = h
                                }
                        } else
                            l.action = "",
                            l.actionElement = null;
                        h = l;
                        a.i && !h.event.a11ysgd && (t = S(h.eventType, h.event, h.targetElement, h.action, h.actionElement, h.timeStamp),
                        "clickonly" == t.eventType && (t.eventType = "click"),
                        a.i(t, !0));
                        if (h.actionElement || "maybe_click" == h.eventType) {
                            if (a.i) {
                                if (!h.actionElement || "A" != h.actionElement.tagName || "click" != h.eventType && "clickmod" != h.eventType || (b.preventDefault ? b.preventDefault() : b.returnValue = !1),
                                (b = a.i(h)) && g) {
                                    m.call(this, b, !1);
                                    return
                                }
                            } else {
                                if ((g = e.document) && !g.createEvent && g.createEventObject)
                                    try {
                                        var D = g.createEventObject(b)
                                    } catch (la) {
                                        D = b
                                    }
                                else
                                    D = b;
                                h.event = D;
                                a.j.push(h)
                            }
                            H._aeh && H._aeh(h)
                        }
                    }
                }
                  , S = function(a, c, d, b, g, m) {
                    return {
                        eventType: a,
                        event: c,
                        targetElement: d,
                        action: b,
                        actionElement: g,
                        timeStamp: m || Date.now()
                    }
                }
                  , ja = function(a, c) {
                    return function(d) {
                        var b = a
                          , g = c
                          , m = !1;
                        "mouseenter" == b ? b = "mouseover" : "mouseleave" == b ? b = "mouseout" : "pointerenter" == b ? b = "pointerover" : "pointerleave" == b && (b = "pointerout");
                        if (d.addEventListener) {
                            if ("focus" == b || "blur" == b || "error" == b || "load" == b || "toggle" == b)
                                m = !0;
                            d.addEventListener(b, g, m)
                        } else
                            d.attachEvent && ("focus" == b ? b = "focusin" : "blur" == b && (b = "focusout"),
                            g = y(d, g),
                            d.attachEvent("on" + b, g));
                        return {
                            eventType: b,
                            s: g,
                            capture: m
                        }
                    }
                }
                  , P = function(a, c) {
                    if (!a.l.hasOwnProperty(c)) {
                        var d = ia(a, c)
                          , b = ja(c, d);
                        a.l[c] = d;
                        a.v.push(b);
                        for (d = 0; d < a.g.length; ++d) {
                            var g = a.g[d];
                            g.h.push(b.call(null, g.g))
                        }
                        "click" == c && P(a, "keydown")
                    }
                };
                Q.prototype.s = function(a) {
                    return this.l[a]
                }
                ;
                var W = function(a, c) {
                    var d = new F(c);
                    a: {
                        for (var b = 0; b < a.g.length; b++)
                            if (T(a.g[b].g, c)) {
                                c = !0;
                                break a
                            }
                        c = !1
                    }
                    if (c)
                        return a.h.push(d),
                        d;
                    U(a, d);
                    a.g.push(d);
                    V(a);
                    return d
                }
                  , V = function(a) {
                    for (var c = a.h.concat(a.g), d = [], b = [], g = 0; g < a.g.length; ++g) {
                        var m = a.g[g];
                        X(m, c) ? (d.push(m),
                        G(m)) : b.push(m)
                    }
                    for (g = 0; g < a.h.length; ++g)
                        m = a.h[g],
                        X(m, c) ? d.push(m) : (b.push(m),
                        U(a, m));
                    a.g = b;
                    a.h = d
                }
                  , U = function(a, c) {
                    var d = c.g;
                    ka && (d.style.cursor = "pointer");
                    for (d = 0; d < a.v.length; ++d)
                        c.h.push(a.v[d].call(null, c.g))
                }
                  , Y = function(a, c) {
                    a.i = c;
                    a.j && (0 < a.j.length && c(a.j),
                    a.j = null)
                }
                  , X = function(a, c) {
                    for (var d = 0; d < c.length; ++d)
                        if (c[d].g != a.g && T(c[d].g, a.g))
                            return !0;
                    return !1
                }
                  , T = function(a, c) {
                    for (; a != c && c.parentNode; )
                        c = c.parentNode;
                    return a == c
                }
                  , ka = "undefined" != typeof navigator && /iPhone|iPad|iPod/.test(navigator.userAgent)
                  , ca = /\s*;\s*/
                  , ea = "click"
                  , ha = {};
                var Z = new Q;
                W(Z, window.document.documentElement);
                P(Z, "click");
                P(Z, "focus");
                P(Z, "focusin");
                P(Z, "blur");
                P(Z, "focusout");
                P(Z, "error");
                P(Z, "load");
                P(Z, "auxclick");
                P(Z, "change");
                P(Z, "copy");
                P(Z, "dblclick");
                P(Z, "beforeinput");
                P(Z, "input");
                P(Z, "keyup");
                P(Z, "keydown");
                P(Z, "keypress");
                P(Z, "mousedown");
                P(Z, "mouseenter");
                P(Z, "mouseleave");
                P(Z, "mouseout");
                P(Z, "mouseover");
                P(Z, "mouseup");
                P(Z, "paste");
                P(Z, "pointerenter");
                P(Z, "pointerleave");
                P(Z, "touchstart");
                P(Z, "touchmove");
                P(Z, "touchend");
                P(Z, "touchcancel");
                P(Z, "transitioncancel");
                P(Z, "transitionend");
                P(Z, "transitionrun");
                P(Z, "transitionstart");
                P(Z, "dragover");
                P(Z, "dragenter");
                P(Z, "dragleave");
                P(Z, "drop");
                P(Z, "dragstart");
                P(Z, "dragend");
                P(Z, "speech");
                (function(a) {
                    google.jsad = function(c) {
                        Y(a, c)
                    }
                    ;
                    google.jsaac = function(c) {
                        return W(a, c)
                    }
                    ;
                    google.jsarc = function(c) {
                        G(c);
                        for (var d = !1, b = 0; b < a.g.length; ++b)
                            if (a.g[b] === c) {
                                a.g.splice(b, 1);
                                d = !0;
                                break
                            }
                        if (!d)
                            for (d = 0; d < a.h.length; ++d)
                                if (a.h[d] === c) {
                                    a.h.splice(d, 1);
                                    break
                                }
                        V(a)
                    }
                }
                )(Z);
                e.gws_wizbind = function(a) {
                    return {
                        trigger: function(c) {
                            var d = a.s(c.type);
                            d || (P(a, c.type),
                            d = a.s(c.type));
                            var b = c.target || c.srcElement;
                            d && d.call(b.ownerDocument.documentElement, c)
                        },
                        bind: function(c) {
                            Y(a, c)
                        }
                    }
                }(Z);
            }
            ).call(this);
            (function() {
                window._skwEvts = [];
            }
            )();
            (function() {
                window.google.erd = {
                    jsr: 1,
                    bv: 1879,
                    sd: true,
                    de: true
                };
            }
            )();
            (function() {
                var sdo = false;
                var mei = 10;
                var h = this || self;
                var k, l = null != (k = h.mei) ? k : 1, n, p = null != (n = h.sdo) ? n : !0, q = 0, r, t = google.erd, v = t.jsr;
                google.ml = function(a, b, d, m, e) {
                    e = void 0 === e ? 2 : e;
                    b && (r = a && a.message);
                    void 0 === d && (d = {});
                    d.cad = "ple_" + google.ple + ".aple_" + google.aple;
                    if (google.dl)
                        return google.dl(a, e, d),
                        null;
                    if (0 > v) {
                        window.console && console.error(a, d);
                        if (-2 === v)
                            throw a;
                        b = !1
                    } else
                        b = !a || !a.message || "Error loading script" === a.message || q >= l && !m ? !1 : !0;
                    if (!b)
                        return null;
                    q++;
                    d = d || {};
                    b = encodeURIComponent;
                    var c = "/gen_204?atyp=i&ei=" + b(google.kEI);
                    google.kEXPI && (c += "&jexpid=" + b(google.kEXPI));
                    c += "&srcpg=" + b(google.sn) + "&jsr=" + b(t.jsr) + "&bver=" + b(t.bv);
                    var f = a.lineNumber;
                    void 0 !== f && (c += "&line=" + f);
                    var g = a.fileName;
                    g && (0 < g.indexOf("-extension:/") && (e = 3),
                    c += "&script=" + b(g),
                    f && g === window.location.href && (f = document.documentElement.outerHTML.split("\n")[f],
                    c += "&cad=" + b(f ? f.substring(0, 300) : "No script found.")));
                    google.ple && 1 === google.ple && (e = 2);
                    c += "&jsel=" + e;
                    for (var u in d)
                        c += "&",
                        c += b(u),
                        c += "=",
                        c += b(d[u]);
                    c = c + "&emsg=" + b(a.name + ": " + a.message);
                    c = c + "&jsst=" + b(a.stack || "N/A");
                    12288 <= c.length && (c = c.substr(0, 12288));
                    a = c;
                    m || google.log(0, "", a);
                    return a
                }
                ;
                window.onerror = function(a, b, d, m, e) {
                    r !== a && (a = e instanceof Error ? e : Error(a),
                    void 0 === d || "lineNumber"in a || (a.lineNumber = d),
                    void 0 === b || "fileName"in a || (a.fileName = b),
                    google.ml(a, !1, void 0, !1, "SyntaxError" === a.name || "SyntaxError" === a.message.substring(0, 11) || -1 !== a.message.indexOf("Script error") ? 3 : 0));
                    r = null;
                    p && q >= l && (window.onerror = null)
                }
                ;
            }
            )();
            var h = "function" == typeof Object.defineProperties ? Object.defineProperty : function(a, b, c) {
                if (a == Array.prototype || a == Object.prototype)
                    return a;
                a[b] = c.value;
                return a
            }
              , k = function(a) {
                a = ["object" == typeof globalThis && globalThis, a, "object" == typeof window && window, "object" == typeof self && self, "object" == typeof global && global];
                for (var b = 0; b < a.length; ++b) {
                    var c = a[b];
                    if (c && c.Math == Math)
                        return c
                }
                throw Error("a");
            }
              , l = k(this)
              , m = function(a, b) {
                if (b)
                    a: {
                        var c = l;
                        a = a.split(".");
                        for (var d = 0; d < a.length - 1; d++) {
                            var e = a[d];
                            if (!(e in c))
                                break a;
                            c = c[e]
                        }
                        a = a[a.length - 1];
                        d = c[a];
                        b = b(d);
                        b != d && null != b && h(c, a, {
                            configurable: !0,
                            writable: !0,
                            value: b
                        })
                    }
            };
            m("String.prototype.startsWith", function(a) {
                return a ? a : function(b, c) {
                    if (null == this)
                        throw new TypeError("The 'this' value for String.prototype.startsWith must not be null or undefined");
                    if (b instanceof RegExp)
                        throw new TypeError("First argument to String.prototype.startsWith must not be a regular expression");
                    var d = this + "";
                    b += "";
                    var e = d.length
                      , g = b.length;
                    c = Math.max(0, Math.min(c | 0, d.length));
                    for (var f = 0; f < g && c < e; )
                        if (d[c++] != b[f++])
                            return !1;
                    return f >= g
                }
            });
            google.arwt = function(a) {
                a.href = document.getElementById(a.id.substring(a.id.startsWith("vcs") ? 3 : 1)).href;
                return !0
            }
            ;
            (function() {
                google.eufsv = true;
                (function() {
                    var f = function(a) {
                        var b = a.url;
                        a = a.j;
                        this.h = b;
                        this.l = a;
                        a = /[?&]dsh=1(&|$)/.test(b);
                        this.i = !a && /[?&]ae=1(&|$)/.test(b);
                        this.v = !a && /[?&]ae=2(&|$)/.test(b);
                        if ((this.g = /[?&]adurl=([^&]*)/.exec(b)) && this.g[1]) {
                            try {
                                var d = decodeURIComponent(this.g[1])
                            } catch (c) {
                                d = null
                            }
                            this.s = d
                        }
                    }
                      , k = function(a, b) {
                        return a.i && a.s || a.v ? 1 == b ? a.i ? a.s : h(a, "&dct=1") : 2 == b ? h(a, "&ri=2") : h(a, "&ri=16") : a.h
                    }
                      , h = function(a, b) {
                        return a.g ? a.h.slice(0, a.g.index) + b + a.h.slice(a.g.index) : a.h + b
                    }
                      , m = function(a) {
                        a = a.l;
                        var b = encodeURIComponent
                          , d = "";
                        a.platform && (d += "&uap=" + b(a.platform));
                        a.platformVersion && (d += "&uapv=" + b(a.platformVersion));
                        a.uaFullVersion && (d += "&uafv=" + b(a.uaFullVersion));
                        a.architecture && (d += "&uaa=" + b(a.architecture));
                        a.model && (d += "&uam=" + b(a.model));
                        a.bitness && (d += "&uab=" + b(a.bitness));
                        a.fullVersionList && (d += "&uafvl=" + b(a.fullVersionList.map(function(c) {
                            return b(c.brand) + ";" + b(c.version)
                        }).join("|")));
                        "undefined" !== typeof a.wow64 && (d += "&uaw=" + Number(a.wow64));
                        return d
                    };
                    var n = function(a) {
                        this.g = a
                    };
                    n.prototype.toString = function() {
                        return this.g.toString()
                    }
                    ;
                    var p = function(a) {
                        return a instanceof n && a.constructor === n ? a.g : "type_error:SafeUrl"
                    }
                      , q = {}
                      , r = new n("about:invalid#zClosurez",q);
                    var t = /^((market|itms|intent|itms-appss):\/\/)/i;
                    var u = "function" === typeof URL;
                    function v(a) {
                        a: if (u) {
                            try {
                                var b = new URL(a)
                            } catch (d) {
                                b = "https:";
                                break a
                            }
                            b = b.protocol
                        } else
                            b: {
                                b = document.createElement("a");
                                try {
                                    b.href = a
                                } catch (d) {
                                    b = void 0;
                                    break b
                                }
                                b = b.protocol;
                                b = ":" === b || "" === b ? "https:" : b
                            }
                        if ("javascript:" !== b)
                            return a
                    }
                    ;var w = function(a) {
                        this.B = a
                    };
                    function x(a) {
                        return new w(function(b) {
                            return b.substr(0, a.length + 1).toLowerCase() === a + ":"
                        }
                        )
                    }
                    var y = [x("data"), x("http"), x("https"), x("mailto"), x("ftp"), new w(function(a) {
                        return /^[^:]*([/?#]|$)/.test(a)
                    }
                    )];
                    var z = function() {
                        var a = {
                            A: google.eufsv
                        }
                          , b = this;
                        a = (void 0 === a ? {} : a).A;
                        this.g = null;
                        a && navigator.userAgentData && navigator.userAgentData.getHighEntropyValues && (a = navigator.userAgentData.getHighEntropyValues("platform platformVersion uaFullVersion architecture model bitness fullVersionList wow64".split(" "))) && a.then(function(d) {
                            b.g = d
                        })
                    };
                    z.prototype.handle = function(a) {
                        if (a.hasAttribute("data-ohref"))
                            var b = a.getAttribute("data-ohref");
                        else
                            b = a.href,
                            a.setAttribute("data-ohref", b);
                        var d = b;
                        var c = {
                            j: this.g
                        };
                        c = new f({
                            url: d,
                            j: (void 0 === c ? {} : c).j
                        });
                        if (c.i && c.s || c.v)
                            if (navigator.sendBeacon) {
                                d = navigator;
                                var g = d.sendBeacon
                                  , l = "&act=1&ri=1";
                                c.i && c.l && (l += m(c));
                                c = g.call(d, h(c, l), "") ? k(c, 1) : k(c, 2)
                            } else
                                c = k(c, 0);
                        else
                            c = d;
                        c = c instanceof n || !t.test(c) ? c : new n(c,q);
                        b != c && (b = c instanceof n ? p(c) : v(c),
                        void 0 !== b && (a.href = b))
                    }
                    ;
                    function B(a, b) {
                        var d = /[?&]adurl=/.exec(b);
                        return d ? "" + b.slice(0, d.index + 1) + a + "&" + b.slice(d.index + 1) : "" + b + (-1 === b.indexOf("?") ? "?" : "&") + a
                    }
                    function C(a, b) {
                        a = a.href;
                        var d = /[?&]nis=([^&]*)/.exec(a);
                        return d && d[1] === b ? a : d ? a.replace(/([?&])nis=([^&]*)/, function(c, g) {
                            return g + "nis=" + b
                        }) : B("nis=" + b, a)
                    }
                    function D() {
                        var a;
                        return !(null == (a = document.featurePolicy) || !a.allowedFeatures().includes("attribution-reporting"))
                    }
                    ;function E(a) {
                        a && -1 != a.indexOf("&sph") && (google.cufph = -1 != a.indexOf("ctype=") ? a.replace(/(.*ctype=)(\d+)(.*)/, "$1331$3") : a + "&ctype=331",
                        google.vcmd = "clicked")
                    }
                    ;var F = new z;
                    google.ausb = function(a) {
                        if (!a)
                            return google.ml(Error("a"), !1),
                            !0;
                        if (a.hasAttribute("data-impdclcc"))
                            try {
                                var b = a.hasAttribute("attributionsourceid") && a.hasAttribute("attributiondestination") ? "2" : a.hasAttribute("attributionsrc") ? D() ? "6" : "5" : D() ? "7" : "8";
                                var d = C(a, b);
                                var c = void 0 === c ? y : c;
                                a: {
                                    b = c;
                                    b = void 0 === b ? y : b;
                                    for (c = 0; c < b.length; ++c) {
                                        var g = b[c];
                                        if (g instanceof w && g.B(d)) {
                                            var l = new n(d,q);
                                            break a
                                        }
                                    }
                                    l = void 0
                                }
                                var e = l || r;
                                var A = e instanceof n ? p(e) : v(e);
                                void 0 !== A && (a.href = A)
                            } catch (G) {}
                        a.getAttribute("data-sbv2") && ((google.eplfdd || google.ellfdd) && "_blank" !== a.target && (google.iutaicc ? (e = a.hasAttribute("data-ohref") ? a.getAttribute("data-ohref") : a.href,
                        e = new f({
                            url: e,
                            j: F.g
                        }),
                        e = e.l ? h(e, m(e)) : e.h,
                        E(e)) : (e = a.hasAttribute("data-ohref") ? a.getAttribute("data-ohref") : a.href,
                        E(e))),
                        F.handle(a));
                        return !0
                    }
                    ;
                }
                ).call(this);
            }
            )();
            (function() {
                var f = function(a) {
                    var b = 0;
                    return function() {
                        return b < a.length ? {
                            done: !1,
                            value: a[b++]
                        } : {
                            done: !0
                        }
                    }
                };
                var g = this || self;
                var h = function(a, b) {
                    if (b = "label" + (null != b ? "=" + encodeURIComponent(String(b)) : "")) {
                        var c = a.indexOf("#");
                        0 > c && (c = a.length);
                        var d = a.indexOf("?");
                        if (0 > d || d > c) {
                            d = c;
                            var e = ""
                        } else
                            e = a.substring(d + 1, c);
                        a = [a.slice(0, d), e, a.slice(c)];
                        c = a[1];
                        a[1] = b ? c ? c + "&" + b : b : c;
                        b = a[0] + (a[1] ? "?" + a[1] : "") + a[2]
                    } else
                        b = a;
                    return b
                };
                function k(a) {
                    for (; a && a != document.documentElement; a = a.parentElement)
                        if ("A" == a.tagName)
                            return a;
                    return null
                }
                function l() {
                    if ("visible" === document.visibilityState)
                        google.ellfdd && m(),
                        google.vcmd = "",
                        google.cufph = "";
                    else if ("hidden" === document.visibilityState && google.cufph && google.vcmd) {
                        if (google.ellfdd)
                            try {
                                var a = JSON.parse(window.localStorage.getItem("uha") || "[]");
                                a.push(google.cufph + "," + google.vcmd);
                                window.localStorage.setItem("uha", JSON.stringify(a))
                            } catch (b) {
                                navigator && null != navigator.sendBeacon && navigator.sendBeacon(h(google.cufph, -1 != google.vcmd.indexOf("pagehide") ? "hph_v2" : "noph_v2"))
                            }
                        google.eplfdd && navigator && null != navigator.sendBeacon && navigator.sendBeacon(h(google.cufph, -1 != google.vcmd.indexOf("pagehide") ? "hph" : "noph"))
                    }
                }
                function n() {
                    google.cufph && google.vcmd && (google.vcmd += "+pagehide")
                }
                function p() {
                    m()
                }
                function m() {
                    try {
                        var a = JSON.parse(window.localStorage.getItem("uha") || "[]");
                        if (0 !== a.length) {
                            if (navigator && null != navigator.sendBeacon)
                                for (var b = 0; b < a.length; b++) {
                                    var c = a[b].split(",");
                                    if (2 === c.length) {
                                        var d = "undefined" != typeof Symbol && Symbol.iterator && c[Symbol.iterator];
                                        if (d)
                                            var e = d.call(c);
                                        else if ("number" == typeof c.length)
                                            e = {
                                                next: f(c)
                                            };
                                        else
                                            throw Error("a`" + String(c));
                                        var r = e.next().value
                                          , t = e.next().value;
                                        navigator.sendBeacon(h(r, -1 != t.indexOf("pagehide") ? "hph_v2" : "noph_v2"))
                                    }
                                }
                            window.localStorage.removeItem("uha")
                        }
                    } catch (v) {}
                }
                function q(a) {
                    if (a = k(a.target))
                        switch (a.getAttribute("data-agdh")) {
                        case "arwt":
                            google.arwt(a);
                            break;
                        case "fvd3vc":
                            g.J4LCUe(a);
                            break;
                        case "EdKoMd":
                            (0,
                            google.f.LmvwCb)(a)
                        }
                    return !0
                }
                function u(a) {
                    return "Enter" === a.key ? q(a) : !0
                }
                ;window.document.documentElement.addEventListener("mousedown", q, !0);
                window.document.documentElement.addEventListener("touchstart", q, !0);
                google.iokefur && window.document.documentElement.addEventListener("keydown", u, !0);
                window.document.documentElement.addEventListener("click", function(a) {
                    var b = k(a.target);
                    if (b)
                        switch (b.getAttribute("data-agch")) {
                        case "ausb":
                            google.ausb(b);
                            break;
                        case "HJ3bqe":
                            window.YvikHb(a, b);
                            break;
                        case "cqUJI":
                            (0,
                            google.f.DfwaCb)(b)
                        }
                    return !0
                }, !0);
                google.eplfdd && google.ellfdd ? (window.document.addEventListener("visibilitychange", l, !0),
                window.addEventListener("pagehide", n, !0),
                window.addEventListener("load", p, !0)) : google.eplfdd ? (window.document.addEventListener("visibilitychange", l, !0),
                window.addEventListener("pagehide", n, !0)) : google.ellfdd && (window.document.addEventListener("visibilitychange", l, !0),
                window.addEventListener("pagehide", n, !0),
                window.addEventListener("load", p, !0));
            }
            ).call(this);
            /*CSH_START*/
            /*CSH_END*/
        </script>
        <style>
            html,body,h1,input,select {
                font-family: arial,sans-serif
            }

            body,h1 {
                font-size: 14px;
            }

            h1 {
                font-weight: normal;
                margin: 0;
                padding: 0
            }

            h3 {
                font-weight: normal;
                margin: 0;
                padding: 0;
                font-size: 20px;
                line-height: 1.3
            }

            body {
                margin: 0;
                background: #fff;
                color: #202124;
            }

            a {
                color: #1a0dab;
                text-decoration: none;
                -webkit-tap-highlight-color: rgba(0,0,0,.1)
            }

            a:visited {
                color: #681da8
            }

            a:hover {
                text-decoration: underline
            }

            a:hover h3 {
                text-decoration: underline
            }

            a.a-no-hover-decoration:hover,a.a-no-hover-decoration:hover h3 {
                text-decoration: none
            }

            cite,cite a:link,cite a:visited {
                color: #4d5156;
                font-style: normal
            }

            button {
                margin: 0
            }

            ol li {
                list-style: none
            }

            ol,ul,li {
                margin: 0;
                padding: 0
            }

            input {
                font-size: 14px
            }

            em {
                font-weight: bold;
                font-style: normal
            }

            .aCOpRe em,.yXK7lf em {
                color: #5f6368;
            }

            .aCOpRe a em {
                color: inherit
            }

            @-webkit-keyframes qs-timer {
                0% {
                }
            }

            html:not(.zAoYTe) [tabindex] {
                outline: 0
            }

            html:not(.zAoYTe) [href],html:not(.zAoYTe) button,html:not(.zAoYTe) iframe,html:not(.zAoYTe) input,html:not(.zAoYTe) select,html:not(.zAoYTe) textarea {
                outline: 0
            }

            html:not(.zAoYTe) .F0azHf {
                outline: 0
            }

            .z1asCe {
                display: inline-block;
                fill: currentColor;
                height: 24px;
                line-height: 24px;
                position: relative;
                width: 24px
            }

            .z1asCe svg {
                display: block;
                height: 100%;
                width: 100%
            }

            :root {
            }

            .ynAwRc {
                color: #1a0dab
            }

            a:visited .ynAwRc,a:visited.ynAwRc {
                color: #681da8
            }

            .JIFdL {
                color: #1a0dab
            }

            .zIamNc {
                color: #202124;
                font-family: arial,sans-serif;
                font-size: 12px;
                font-weight: 400;
                line-height: 20px
            }

            .NUnG9d {
                color: #202124;
                font-family: arial,sans-serif;
                font-size: 12px;
                font-weight: 400;
                line-height: 16px
            }

            .kqEaA {
                color: #70757a;
                font-family: arial,sans-serif;
                font-size: 14px;
                font-weight: 400;
                line-height: 22px
            }

            .vJtJab {
                color: #1a0dab;
                font-family: arial,sans-serif;
                font-size: 14px;
                font-weight: 400;
                line-height: 22px
            }

            .hWgrdb {
                font-style: italic
            }

            .q8U8x {
                font-family: Google Sans,arial,sans-serif;
                font-weight: 400
            }

            .Z5bgrc {
                font-family: arial,sans-serif-medium,sans-serif;
                font-weight: 500
            }

            .l97dzf {
                font-weight: 400
            }

            .N8MDs {
                font-family: arial,sans-serif-light,sans-serif
            }

            .z8gr9e {
                color: #4d5156
            }

            .KHW3x {
                color: #fff
            }

            .ZYHQ7e {
                color: #70757a
            }

            .x2sBq {
                color: #d93025
            }

            .tGXccd {
                color: #188038
            }

            .OvuNCb {
                color: #e37400
            }

            .yNSCTe {
                color: #202124
            }

            .XEI2lf {
                color: #fff
            }

            .u2fAP {
                color: #3c4043
            }

            .Q7PwXb {
                text-decoration: none
            }

            .NyOyWb {
                text-overflow: clip;
                overflow: hidden
            }

            .U2GSdd {
                height: calc(16px*2);
                display: -webkit-box;
                -webkit-box-orient: vertical;
                -webkit-line-clamp: 2;
                overflow: hidden;
                white-space: normal
            }

            .GnYZ5c {
                height: calc(16px*3);
                display: -webkit-box;
                -webkit-box-orient: vertical;
                -webkit-line-clamp: 3;
                overflow: hidden;
                white-space: normal
            }

            .potOpf {
                max-height: calc(24px*2);
                display: -webkit-box;
                -webkit-box-orient: vertical;
                -webkit-line-clamp: 2;
                overflow: hidden;
                white-space: normal
            }

            .n4krj {
                height: calc(22px*2);
                display: -webkit-box;
                -webkit-box-orient: vertical;
                -webkit-line-clamp: 2;
                overflow: hidden;
                white-space: normal
            }

            .NnEaBd {
                text-align: right
            }

            .xLQxIf {
                text-transform: capitalize
            }

            .uKdaQe {
                text-transform: lowercase
            }

            .MUmB9 {
                text-transform: none
            }

            .iUh30 {
                font-size: 12px;
                line-height: 1.3
            }

            .f {
                color: #70757a;
                line-height: 1.58
            }

            .g {
                font-family: arial,sans-serif;
                font-size: 14px;
            }

            .g {
                line-height: 1.58;
                text-align: left
            }

            .g {
                width: 600px;
                margin-top: 0;
                margin-bottom: 30px;
            }

            .iUh30 {
                padding-top: 1px;
            }

            .vk_arc {
                border-top: 1px solid #dadce0;
                cursor: pointer;
                height: 0;
                margin-bottom: -19px;
                overflow: hidden;
                padding: 20px 0;
                text-align: center
            }

            .vk_ard {
                top: -11px
            }

            .vk_aru {
                bottom: -6px
            }

            .vk_ard,.vk_aru {
                background-color: #ebebeb;
                margin-left: auto;
                margin-right: auto;
                position: relative;
                height: 6px;
                width: 64px
            }

            .vk_ard:after,.vk_ard:before,.vk_aru:after,.vk_aru:before {
                content: ' ';
                height: 0;
                left: 0;
                position: absolute;
                width: 0;
                border-left: 32px solid rgba(255,255,255,0);
                border-right: 32px solid rgba(255,255,255,0)
            }

            .vk_ard:before {
                border-top: 16px solid #ebebeb;
                top: 6px
            }

            .vk_aru:before {
                border-bottom: 16px solid #ebebeb;
                bottom: 6px
            }

            .vk_ard:after {
                top: 0;
                border-top: 16px solid #fff
            }

            .vk_aru:after {
                bottom: 0;
                border-bottom: 16px solid #fff
            }

            .jC7Epd.vk_ard,.jC7Epd.vk_aru {
                background-color: #202124
            }

            .jC7Epd.vk_ard:before {
                border-top-color: #202124
            }

            .jC7Epd.vk_aru:before {
                border-bottom-color: #202124
            }

            .xpdclps,.xpdxpnd {
                overflow: hidden
            }

            .xpdclps,.xpdxpnd {
                -webkit-transition: max-height 0.3s
            }

            .xpdxpnd,.xpdopen .xpdclps,.xpdopen .xpdxpnd.xpdnoxpnd {
                max-height: 0
            }

            .xpdopen .xpdxpnd {
                max-height: none
            }

            .xpdopen .xpdbox .xpdxpnd,.xpdopen .xpdbox.xpdopen .xpdclps {
                max-height: 0
            }

            .xpdopen .xpdbox.xpdopen .xpdxpnd,.xpdopen .xpdbox .xpdclps {
                max-height: none
            }

            .xpdclose .k5nfEc {
                display: none
            }

            .fp-i .SzDvzc {
                display: none
            }

            .fp-f {
                bottom: 0;
                height: auto;
                left: 0;
                position: fixed !important;
                right: 0;
                top: 0;
                width: auto;
                z-index: 127
            }

            .fp-h:not(.fp-nh):not(.goog-modalpopup-bg):not(.goog-modalpopup) {
                display: none !important
            }

            .fp-zh.fp-h:not(.fp-nh):not(.goog-modalpopup-bg):not(.goog-modalpopup) {
                display: block !important;
                height: 0;
                overflow: hidden;
                transform: translate3d(0,0,0);
                transform: translate3d(0,0,0)
            }

            .fp-i .fp-c {
                display: block;
                min-height: 100vh
            }

            li.fp-c {
                list-style: none
            }

            .fp-w {
                box-sizing: border-box;
                left: 0;
                margin-left: auto;
                margin-right: auto;
                max-width: 1217px;
                right: 0
            }

            .ellip {
                overflow: hidden;
                text-overflow: ellipsis;
                white-space: nowrap
            }

            .tF2Cxc {
                position: relative
            }

            .Jb0Zif .BDNLRc {
                margin: 16px 16px -11px
            }

            .RUXr2d {
                display: inline
            }

            .MTB56 {
                margin-right: 12px;
                vertical-align: middle
            }

            .Pthbuf {
                display: flex;
                align-items: center
            }

            .m164Nd {
                vertical-align: middle;
                display: inline-block
            }

            .qpGQpf {
                clear: both;
                padding-top: 6px
            }

            .tcPEUc .MTB56 {
                display: none
            }

            .aCOpRe {
                line-height: 1.58;
                word-wrap: break-word
            }

            .aCOpRe sup {
                line-height: 0.9
            }

            .yuRUbf {
                font-weight: normal;
                font-size: small;
                line-height: 1.58;
            }

            .IsZvec {
                max-width: 48em;
                color: #4d5156;
                line-height: 1.58
            }

            .uo4vr {
                color: #70757a;
                line-height: 1.58
            }

            .IjZ7ze {
                display: inline-block;
                color: #70757a;
                font-size: 12px;
                line-height: 1.34;
                white-space: nowrap
            }

            .FyYA1e {
                margin: 5px 0
            }

            .P1usbc {
                display: table;
                white-space: nowrap;
                margin: 5px 0;
                line-height: 1.58;
                color: #70757a;
            }

            .G1Rrjc {
                display: table-cell;
                padding-left: 15px;
                vertical-align: baseline
            }

            .i4vd5e {
                display: table-cell
            }

            .VNLkW {
                display: table-row;
                vertical-align: top
            }

            .h7mcFf {
                color: #70757a
            }

            .k6DEPe {
                display: table-row;
                width: 100%
            }

            .TXwUJf {
                color: #70757a
            }

            .PcHvNb {
                position: absolute
            }

            .N3nEGc {
                background-color: #fff;
                float: left;
                margin-top: 4px
            }

            .wEQKyf.N3nEGc {
                float: right;
                margin: 7px 0 5px 12px
            }

            .wEQKyf.Ik9SRc.N3nEGc {
                margin: 2px 0 0 0
            }

            .Ixi80c {
                margin-top: 0
            }

            .i0PvJb {
                background-color: #000
            }

            .mWTy7c {
                border-top-left-radius: 2px;
                bottom: 0;
                font-size: 11px;
                padding: 1px 3px;
                position: absolute;
                right: 0;
                background-color: rgba(0,0,0,.7);
                color: #fff
            }

            .rGhul {
                display: block;
                position: relative;
                overflow: hidden
            }

            .rGhul:focus {
                outline-style: solid;
                outline-width: 2px
            }

            .vYWbhc {
                margin-top: 0
            }

            .TbwUpd a.fl {
                font-size: 12px
            }

            .TQc1id .qLRx3b {
                font-size: 14px;
                line-height: 1.58
            }

            .TbwUpd {
                display: inline-block;
                padding-bottom: 2px;
                padding-top: 1px;
                -webkit-text-size-adjust: none
            }

            .NJjxre {
                position: absolute;
                left: 0;
                top: 0
            }

            .M8OgIe .VWCdhc.Mjve0e .TbwUpd {
                width: max-content
            }

            #rhs {
                margin-left: var(--rhs-margin);
                flex: 0 auto;
                width: var(--rhs-width);
                position: relative;
                padding-bottom: 15px;
                transition: opacity 0.3s
            }

            #rhs .scrt.VjDLd,#rhs table.VjDLd {
                border: 0
            }

            #rhs .VjDLd {
                border: 1px solid #f8f9fa;
                padding-left: 17px;
                padding-right: 16px;
                position: relative;
                box-sizing: border-box
            }

            .s6JM6d .SwlyWb {
                display: none
            }

            #rhs.rhstc4 .VjDLd {
                width: var(--rhs-width)
            }

            #rhs.rhstc5 .VjDLd {
                width: 457px
            }

            .rhstc4 .nmrhhd {
                background: none !important;
                display: none !important
            }

            .rhstc5 .SwlyWb {
                background: none !important;
                display: none !important
            }

            .GLcBOb {
                color: #70757a;
                font-size: 14px;
                font-family: Google Sans,arial,sans-serif;
                border-bottom: 1px solid #ebebeb;
                position: relative;
                z-index: 126
            }

            .IC1Ck {
                position: relative;
                white-space: nowrap;
                align-items: baseline;
                display: flex;
                -ms-flex-pack: justify;
                float: left;
                justify-content: space-between;
                min-width: calc(var(--center-abs-margin) + 652px);
            }

            .MUFPAc {
                display: inline;
                margin-left: calc(var(--center-abs-margin) + -11px);
            }

            .MbEPDb {
                margin-left: -4px;
                vertical-align: text-bottom
            }

            .hdtb-mitem .GOE98c,.hdtb-mitem a,.hdtb-mitem.hdtb-msel,.t2vtad {
                color: #5f6368;
                text-decoration: none;
                display: inline-block;
                padding: 0 12px;
                padding: 8px 16px 8px 16px;
                padding: 17px 12px 11px 10px
            }

            .hdtb-mitem {
                height: 16px;
                line-height: 16px;
                margin: 0 1px;
                display: inline-block
            }

            .hdtb-mitem a:active {
                color: #1a73e8
            }

            .hdtb-mitem.hdtb-msel {
                color: #1a73e8;
            }

            .cCvmNd .hdtb-mitem.hdtb-msel {
                border-bottom: none
            }

            .hdtb-mitem.hdtb-msel:hover {
                cursor: pointer
            }

            .hdtb-mitem.hdtb-msel:active {
                background: none
            }

            .hdtb-mitem a {
                color: #5f6368
            }

            .t2vtad {
                border: 1px solid transparent;
                text-align: center;
                border-radius: 2px;
                line-height: 19px;
                cursor: pointer;
                margin-left: -1px;
                padding: 4px 11px;
                margin-right: -11px;
            }

            .t2vtad:not(.hdtb-tl-sel):hover {
                box-shadow: 0 1px 1px rgba(0,0,0,0.1);
                -webkit-transition: all 0.0s;
                background-color: #f8f9fa;
                background-image: -webkit-linear-gradient(top,#f8f9fa,#f8f9fa);
                background-image: -webkit-gradient(linear,left top,left bottom,from(#f8f9fa),to(#f8f9fa));
                border: 1px solid #dadce0;
                color: #202124
            }

            .t2vtad:active,.t2vtad:not(.hdtb-tl-sel):hover:active {
                background-color: #f8f9fa;
                background-image: -webkit-linear-gradient(top,#f8f9fa,#f8f9fa);
                background-image: -webkit-gradient(linear,left top,left bottom,from(#f8f9fa),to(#f8f9fa));
                box-shadow: inset 0 1px 2px rgba(0,0,0,0.1)
            }

            .YTDezd {
                background: #1a73e8;
                height: 3px;
                margin-top: 11px
            }

            .bmaJhd {
                margin-right: 5px;
                vertical-align: text-bottom
            }

            .v7W49e {
                margin-top: 6px
            }

            [dir='ltr'],[dir='rtl'] {
                unicode-bidi: -webkit-isolate;
                unicode-bidi: isolate
            }

            bdo[dir='ltr'],bdo[dir='rtl'] {
                unicode-bidi: bidi-override;
                unicode-bidi: -webkit-isolate-override;
                unicode-bidi: isolate-override
            }

            .GyAeWb {
                display: flex;
                justify-content: flex-start;
                flex-wrap: wrap;
                max-width: calc(var(--center-abs-margin) + var(--center-width) + var(--rhs-margin) + var(--rhs-width) + var(--lhs-refinements-width));
            }

            .srp {
                --center-abs-margin: 180px;
                --center-width: 652px;
                --rhs-margin: 76px;
                --rhs-width: 372px;
                --lhs-refinements-width: 0px;
            }

            @media (min-width: 1475px) and (max-width:1675px) {
                .srp {
                    --center-abs-margin:calc(25vw + -188.75px)
                }
            }

            @media (min-width: 1675px) {
                .srp {
                    --center-abs-margin:230px
                }
            }

            @media (min-width: 1124px) and (max-width:1300px) {
                .srp {
                    --center-abs-margin:calc((100vw - 1068px)/2)
                }
            }

            @media (max-width: 1124px) {
                .srp {
                    --center-abs-margin:28px
                }
            }

            .eqAnXb {
                font-size: medium;
                font-weight: normal;
            }

            .main {
                min-width: calc(var(--center-abs-margin) + var(--center-width) + var(--rhs-margin) + var(--rhs-width) + var(--lhs-refinements-width));
                width: 100%;
            }

            .s6JM6d {
                width: var(--center-width);
                position: relative;
                margin-left: var(--center-abs-margin);
                flex: 0 auto;
            }

            .KpqFHb {
                --center-width: 1100px;
                --rhs-margin: 0px;
                --rhs-width: 0px
            }

            .e9EfHf {
                font-family: arial,sans-serif;
                clear: both;
                margin-left: 0;
                padding-top: 20px;
                box-sizing: border-box;
                position: relative;
                min-height: 100vh;
            }

            .dodTBe {
                height: 65px
            }

            .appbar {
                background: #fff;
                position: relative;
                -webkit-box-sizing: border-box;
                margin-left: var(--center-abs-margin);
            }
        </style>
    </head>
    <body jsmodel="hspDDf " class="srp" jscontroller="Eox39d" marginheight="3" topmargin="3" jsaction="rcuQ6b:npT2md" id="gsr">
        <style>
            .wYq63b {
                display: flex;
                left: 0;
                position: absolute;
                top: 0;
                z-index: 1001
            }

            .S6VXfe {
                align-items: center;
                background-color: #fff;
                border-radius: 0 2px 2px 0;
                box-shadow: 0 2px 2px 0 rgba(0,0,0,.16),0 0 0 1px rgba(0,0,0,.08);
                display: flex;
                margin: 80px auto 8px 0;
                overflow: hidden
            }

            .gyPpGe,.gyPpGe:visited,.qlVNAd {
                border: 2px solid rgba(0,0,0,.16);
                border-radius: 2px;
                color: #681da8;
                cursor: pointer;
                display: inline-block;
                font-size: 14px;
                line-height: 20px;
                margin: 6px 11px;
                min-height: 32px;
                text-decoration: underline;
                text-align: center;
                width: 106px
            }

            .gyPpGe:not(:focus) {
                clip: rect(1px,1px,1px,1px);
                overflow: hidden;
                position: absolute;
                padding: 0
            }

            .kur4we {
                display: none
            }

            a.oBa0Fe {
                color: #70757a;
                float: right;
                font-style: italic;
                -webkit-tap-highlight-color: rgba(0,0,0,0);
                tap-highlight-color: rgba(0,0,0,0)
            }

            a.aciXEb {
                padding: 0 5px;
            }

            .CvDJxb {
                min-width: 1124px;
                width: 100%;
                z-index: 128;
                position: absolute;
                top: 20px;
                margin-top: 6px;
            }

            .tsf {
                width: calc(var(--center-abs-margin) + 652px);
            }

            .Q3DXx {
                display: flex
            }

            .Q3DXx.yIbDgf {
                justify-content: space-between
            }

            .Q3DXx #gb,.Q3DXx #gb>div {
                float: none
            }

            .sfbg {
                background: #fff;
                height: 69px;
                left: 0;
                position: absolute;
                width: 100%
            }

            .minidiv .sfbg {
                height: 72px;
                overflow: hidden;
                background: #fff;
                box-shadow: 0 1px 6px 0 rgba(32, 33, 36, 0.28)
            }

            .A8SBwf,.IormK {
                width: 692px;
                padding-left: 27px
            }

            .A8SBwf {
                margin: 0 auto;
                margin-left: calc(var(--center-abs-margin) - 47px);
                position: relative;
            }

            .RNNXgb {
                display: flex;
                z-index: 3;
                min-height: 44px;
                background: #fff;
                border: 1px solid transparent;
                box-shadow: 0 2px 5px 1px rgba(64,60,67,.16);
                border-radius: 24px;
                margin: 0 auto;
                width: 690px;
            }

            .emcav .RNNXgb {
                border-bottom-left-radius: 0;
                border-bottom-right-radius: 0;
                box-shadow: 0 2px 8px 1px rgba(64,60,67,.24);
                border-color: rgba(223,225,229,0)
            }

            .minidiv .emcav .RNNXgb {
                border-bottom-left-radius: 0;
                border-bottom-right-radius: 0;
                box-shadow: 0 1px 6px rgba(32,33,36,.28);
                border-color: rgba(223,225,229,0);
            }

            .RNNXgb:hover,.sbfc .RNNXgb {
                background-color: #fff;
                box-shadow: 0 2px 8px 1px rgba(64,60,67,.24);
                border-color: rgba(223,225,229,0)
            }

            .minidiv .RNNXgb:hover,.minidiv .sbfc .RNNXgb {
                border-color: rgba(223,225,229,0);
                box-shadow: 0 1px 6px rgba(32,33,36,.28)
            }

            .SDkEP {
                flex: 1;
                display: flex;
                padding: 5px 4px 0 14px;
            }

            .logo {
                position: absolute;
                left: -139px;
                padding: 4px 28px 0 30px;
                top: 6px;
            }

            .iblpc span {
                display: none
            }

            .sbfc .iblpc span,.emcav .iblpc span {
                display: block
            }

            .iblpc {
                display: flex;
                align-items: center;
                padding-right: 6px;
                margin-top: -7px
            }

            .sbfc .iblpc,.emcav .iblpc {
                padding-right: 14px;
                margin-left: -1px
            }

            .sbfc.A8SBwf,.emcav.A8SBwf {
                padding-left: 0;
                width: 719px
            }

            .sbfc .RNNXgb,.emcav .RNNXgb {
                width: 717px
            }

            @media (min-width: 0) {
                .emcav.A8SBwf.h3L8Ub {
                    width:calc(var(--center-width) + var(--rhs-margin) + var(--rhs-width) + 47px)
                }

                .emcav.h3L8Ub .RNNXgb {
                    width: calc(var(--center-width) + var(--rhs-margin) + var(--rhs-width) + 45px)
                }
            }

            @media (max-width: 1300px) {
                .emcav.A8SBwf.h3L8Ub {
                    width:calc(var(--rhs-margin) + var(--rhs-width) + var(--center-width) + -105px)
                }

                .emcav.h3L8Ub .RNNXgb {
                    width: calc(var(--rhs-margin) + var(--rhs-width) + var(--center-width) + -107px)
                }
            }

            .iblpc {
                display: flex;
                align-items: center;
                padding-right: 6px;
                margin-top: -7px;
                height: 46px
            }

            .M8H8pb {
                position: absolute;
                top: 0;
                left: 0;
                right: 0;
                padding: inherit;
                width: inherit
            }

            @media (max-width: 1300px) {
                .A8SBwf {
                    margin-left:calc(var(--center-abs-margin) + 105px)
                }
            }

            @media (max-width: 1300px) {
                .A8SBwf,.IormK {
                    width:540px
                }

                .RNNXgb {
                    width: 538px
                }

                .sbfc.A8SBwf,.emcav.A8SBwf {
                    width: 567px
                }

                .sbfc .RNNXgb,.emcav .RNNXgb {
                    width: 565px
                }
            }

            #logo {
                overflow: hidden;
                position: relative;
                display: block;
            }

            .jfN4p {
                border: 0
            }

            .CcAdNb {
                margin: auto
            }

            .QCzoEc {
                color: #9aa0a6
            }

            .gLFyf,.YacQv {
                font: 16px arial,sans-serif;
                line-height: 34px;
                font-size: 16px;
                flex: 100%;
                line-height: 39px
            }

            textarea.gLFyf,.YacQv {
                font-family: arial,sans-serif;
                font: 16px arial,sans-serif;
                line-height: 22px;
                margin-bottom: 8px;
                overflow-x: hidden
            }

            textarea.gLFyf {
                white-space: nowrap;
                overflow: hidden
            }

            .minidiv .gLFyf,.minidiv .YacQv {
                font-size: 14px;
                line-height: 22px;
                min-height: 22px !important;
            }

            .gLFyf {
                resize: none;
                background-color: transparent;
                border: none;
                margin: 0;
                padding: 0 0 3px;
                color: rgba(0,0,0,.87);
                word-wrap: break-word;
                outline: none;
                display: flex;
                -webkit-tap-highlight-color: transparent
            }

            .a4bIc {
                display: flex;
                flex-wrap: wrap;
                flex: 1;
                margin-top: 6px
            }

            .YacQv {
                color: transparent;
                white-space: pre;
                position: absolute;
                pointer-events: none
            }

            .YacQv span {
                text-decoration: #d93025 dotted underline
            }

            .gLFyf.i4ySpb {
                display: block;
                position: absolute
            }

            .Sxjlmb {
                white-space: nowrap;
                margin: 20px;
                font-size: 14px;
                font-weight: bold;
                line-height: normal;
                color: #fff
            }

            .qfY0Jf {
                font-weight: normal;
                border: 1px solid #fff;
                border-radius: 3px;
                padding: 1px 3px 0 3px
            }

            .dRYYxd {
                display: flex;
                flex: 0 0 auto;
                margin-top: -5px;
                align-items: stretch;
                flex-direction: row;
                height: 44px
            }

            .BKRPef {
                background: transparent;
                align-items: center;
                flex: 1 0 auto;
                flex-direction: row;
                display: flex;
                cursor: pointer
            }

            .vOY7J {
                background: transparent;
                border: 0;
                align-items: center;
                flex: 1 0 auto;
                cursor: pointer;
                display: none;
                height: 100%;
                line-height: 44px;
                outline: none;
                padding: 0 12px
            }

            .M2vV3 {
                display: flex
            }

            .ExCKkf {
                height: 100%;
                color: #70757a;
                vertical-align: middle;
                outline: none
            }

            .BKRPef {
                padding-right: 4px
            }

            .ACRAdd {
                border-left: 1px solid #dadce0;
                height: 65%
            }

            .ACRAdd {
                display: none
            }

            .ACRAdd.M2vV3 {
                display: block
            }

            .Umvnrc {
                flex: 1 0 auto;
                display: flex;
                cursor: pointer;
                align-items: center;
                border: 0;
                background: transparent;
                outline: none;
                padding: 0 8px;
                width: 24px;
                line-height: 44px
            }

            .ly0Ckb {
                background: url('//www.gstatic.com/inputtools/images/tia.png') no-repeat center;
                height: 24px;
                width: 24px;
                vertical-align: middle
            }

            .yAnw3c {
                visibility: hidden
            }

            .XDyW0e {
                flex: 1 0 auto;
                display: flex;
                cursor: pointer;
                align-items: center;
                border: 0;
                background: transparent;
                outline: none;
                padding: 0 8px;
                width: 24px;
                line-height: 44px
            }

            .goxjub {
                height: 24px;
                width: 24px;
                vertical-align: middle
            }

            .nDcEnd {
                flex: 1 0 auto;
                display: flex;
                cursor: pointer;
                align-items: center;
                border: 0;
                background: transparent;
                outline: none;
                padding: 0 8px;
                width: 24px;
                line-height: 44px
            }

            .Gdd5U {
                height: 24px;
                width: 24px;
                vertical-align: middle
            }

            .Tg7LZd {
                height: 44px;
                width: 44px;
                background: transparent;
                border: none;
                cursor: pointer;
                flex: 0 0 auto;
                padding: 0;
            }

            .Tg7LZd {
                flex: 0 0 auto;
                padding-right: 13px
            }

            html:not(.zAoYTe) .Tg7LZd:focus {
                outline: none
            }

            .zgAlFc {
                background: none;
                color: #4285f4;
                height: 24px;
                width: 24px;
                margin: auto
            }

            .UUbT9 {
                position: absolute;
                text-align: left;
                z-index: 989;
                cursor: default;
                -webkit-user-select: none;
                width: 100%;
                margin-top: -1px;
            }

            .aajZCb {
                display: flex;
                flex-direction: column;
                list-style-type: none;
                margin: 0;
                padding: 0;
                overflow: hidden;
                background: #fff;
                border-radius: 0 0 24px 24px;
                box-shadow: 0 9px 8px -3px rgba(64,60,67,.24),8px 0 8px -7px rgba(64,60,67,.24),-8px 0 8px -7px rgba(64,60,67,.24);
                border: 0;
                padding-bottom: 4px;
            }

            .minidiv .aajZCb {
                box-shadow: 0 4px 6px rgba(32,33,36,.28);
                border-bottom-left-radius: 16px;
                border-bottom-right-radius: 16px
            }

            .mkHrUc {
                display: flex;
            }

            .erkvQe {
                padding-bottom: 16px;
                flex: auto;
                overflow-x: hidden
            }

            .RjPuVb {
                height: 1px;
                margin: 0 26px 0 0;
            }

            .S3nFnd .RjPuVb,.S3nFnd .aajZCb {
                flex: 0 0 auto
            }

            .xtSCL {
                border-top: 1px solid #e8eaed;
                margin: 0 14px;
                padding-bottom: 4px
            }

            #shJ2Vb {
                display: none
            }

            .OBMEnb {
                padding: 0;
                margin: 0
            }

            .OBMEnb:not(:first-child) {
                padding-top: 8px
            }

            .G43f7e {
                display: flex;
                flex-direction: column;
                min-width: 0;
                padding: 0;
                margin: 0
            }

            #ynRric {
                display: none
            }

            .ynRric {
                list-style-type: none;
                flex-direction: column;
                color: #70757a;
                font-family: Google Sans,arial,sans-serif-medium,sans-serif;
                font-size: 14px;
                margin: 0 20px 0 16px;
                padding: 8px 0 8px 0;
                line-height: 16px;
                width: 100%
            }

            .ynRric {
                letter-spacing: 0;
                text-transform: none
            }

            .sbct {
                display: flex;
                flex-direction: column;
                min-width: 0;
                max-height: none;
                padding: 0;
            }

            .eIPGRd {
                flex: auto;
                display: flex;
                align-items: center;
                margin: 0 20px 0 14px
            }

            .pcTkSc {
                display: flex;
                flex: auto;
                flex-direction: column;
                min-width: 0;
                max-height: none;
                padding: 6px 0
            }

            .sbic {
                display: flex;
                align-items: center;
                margin-right: 14px;
            }

            .ClJ9Yb {
                line-height: 12px;
                font-size: 13px;
                color: #70757a;
                margin-top: 2px;
                padding-right: 8px
            }

            .wM6W7d {
                display: flex;
                font-size: 16px;
                color: #212121;
                flex: auto;
                align-items: center;
                word-break: break-word;
                padding-right: 8px
            }

            .wM6W7d span {
                flex: auto
            }

            .AQZ9Vd {
                display: flex;
                align-self: stretch;
            }

            .TfeWfb {
                display: none
            }

            .xAmryf {
                display: none
            }

            .DJbVFb .a5RLac {
                line-height: 24px;
                font-size: 20px;
                font-family: arial,sans-serif;
                padding-top: 16px;
                color: #4d5156;
                margin-bottom: auto
            }

            .DJbVFb .wM6W7d span {
                color: #202124;
                line-height: 36px;
                font-weight: 400;
                font-size: 28px;
                font-family: Google Sans,arial,sans-serif
            }

            .iQxPRb {
                display: flex;
                gap: 2px
            }

            #bgeLZd {
                display: none
            }

            .xAmryf {
                box-sizing: border-box;
                align-items: center;
                height: 40px;
                border-radius: 8px;
                display: flex;
                color: #4d5156;
                border: 1px solid #dadce0;
                background-color: #fff;
                line-height: 22px
            }

            .jtAOgd {
                white-space: nowrap;
                font-family: Google Sans,arial,sans-serif;
                font-size: 14px;
                margin: 0 14px
            }

            .TfeWfb {
                gap: 12px 6px;
                overflow-x: auto;
                -ms-overflow-style: none;
                scrollbar-width: none
            }

            .TfeWfb::-webkit-scrollbar {
                display: none
            }

            #YMXe {
                display: none
            }

            .MagqMc .ZFiwCf {
                background-color: #fff;
                border: 1px solid #dadce0;
                width: 100%
            }

            .MagqMc.U48fD {
                padding: 0;
                margin-top: 16px
            }

            .MagqMc .Bi9oQd {
                display: none
            }

            .MagqMc {
                padding: 0
            }

            .MagqMc:hover .LGwnxb {
                color: #202124
            }

            .U48fD {
                -webkit-tap-highlight-color: transparent;
                cursor: pointer;
                display: block;
                line-height: 18px;
                text-overflow: ellipsis;
                white-space: nowrap;
                padding: 16px;
                padding-top: 0;
                margin-top: 24px;
                position: relative
            }

            .ZFiwCf {
                display: flex;
                align-items: center;
                justify-content: center;
                position: relative;
                margin: 0 auto;
                font-size: 14px;
                font-family: arial,sans-serif;
                font-weight: 400;
                width: 100%;
                max-width: 300px;
                height: 36px;
                border-radius: 18px;
                background-color: #f1f3f4
            }

            .ZFiwCf:hover {
                background-color: #D8D7DC
            }

            .Bi9oQd {
                background-color: #dadce0;
                margin-top: 18px;
                position: absolute;
                border: 0;
                height: 1px;
                left: 0;
                width: 100%
            }

            .w2fKdd svg {
                width: auto
            }

            .w2fKdd {
                color: #70757a
            }

            .LGwnxb {
                overflow: hidden;
                text-overflow: ellipsis;
                white-space: nowrap;
                width: auto;
                padding-left: 0;
                padding-right: 8px;
                max-width: 200px;
                color: #202124
            }

            .LGwnxb:empty {
                padding-right: 0
            }

            .LGwnxb span,.LGwnxb div {
                overflow: hidden;
                text-overflow: ellipsis;
                white-space: nowrap;
                width: auto
            }

            @media (hover: hover) {
                .sbai {
                    visibility:hidden
                }

                .sbhl .sbai {
                    visibility: inherit
                }
            }

            #mitGyb {
                display: none
            }

            .ZDHp {
                position: relative;
                margin: 20px;
                display: flex
            }

            .ZDHp .SHFPkb {
                margin-bottom: 12px
            }

            .o6OF0 .SHFPkb {
                line-height: 40px;
                font-family: Google Sans,arial,sans-serif;
                font-weight: 400;
                display: block;
                color: #202124;
                white-space: nowrap;
                text-overflow: ellipsis;
                overflow: hidden
            }

            .o6OF0 .HrUlUc,.o6OF0 .PnfqLc {
                font-family: arial,sans-serif;
                font-weight: 400;
                max-height: 72px;
                color: #4d5156
            }

            .ZDHp .HrUlUc,.ZDHp .PnfqLc {
                font-size: 18px;
                line-height: 24px
            }

            .o6OF0 .bTSf5c {
                font-family: arial,sans-serif;
                font-weight: 400;
                color: #4d5156
            }

            .ZDHp .bTSf5c {
                line-height: 22px;
                font-size: 14px;
                margin-bottom: 6px
            }

            .ZDHp .HrUlUc,.ZDHp .PnfqLc {
                overflow: hidden;
                display: -webkit-box;
                -webkit-line-clamp: 3;
                -webkit-box-orient: vertical
            }

            .Vlt3wb {
                font-style: normal;
                font-family: arial,sans-serif;
                font-weight: 400;
                font-size: 14px;
                line-height: 22px;
                padding-top: 8px;
                margin-top: 12px;
                color: #4d5156;
                border-top: 1px solid #dadce0;
                display: flex;
                width: 100%
            }

            .Tnv2td {
                position: absolute;
                top: 0;
                right: 0
            }

            .z76Rnb {
                padding: 6px;
                width: 24px;
                height: 24px;
                background-color: #fff;
                color: #70757a;
                border-radius: 9999px;
                border: 1px solid #dadce0;
                cursor: pointer
            }

            .kZtr1b {
                display: flex;
                flex-direction: column;
                flex-grow: 1;
                min-width: 0
            }

            .XAFD5c {
                width: 200px;
                height: 200px;
                background-color: #fff;
                border-radius: 20px;
                margin-left: 20px;
                flex-shrink: 0;
                background-position: center;
                background-repeat: no-repeat;
                background-size: contain
            }

            .o6OF0 .xAmryf {
                font-family: Google Sans,arial,sans-serif;
                margin: 0;
                height: 38px;
                background-color: #fff;
                border-radius: 100px;
                border: 1px solid #dadce0;
                color: #4d5156;
                align-items: center;
                text-align: center;
                flex: none;
                cursor: pointer
            }

            .AsqS6c {
                display: block;
                margin: 20px
            }

            .gfT7kc {
                display: flex;
                flex-grow: 1;
                max-width: 100%
            }

            .cJpYle {
                display: flex;
                padding-right: 20px;
                flex-grow: 1;
                max-width: 50%;
                box-sizing: border-box
            }

            .gTtFDd {
                display: flex;
                padding-left: 20px;
                border-left: 1px solid #dadce0;
                flex-grow: 1;
                max-width: 50%;
                box-sizing: border-box
            }

            .AsqS6c .SHFPkb,.AsqS6c .bTSf5c,.AsqS6c .PnfqLc {
                padding-right: 0;
                margin-bottom: 10px
            }

            .AsqS6c .bTSf5c,.AsqS6c .PnfqLc {
                -webkit-line-clamp: 2;
                line-height: 24px;
                font-size: 16px;
                overflow: hidden;
                display: -webkit-box;
                -webkit-box-orient: vertical
            }

            .AsqS6c .HrUlUc {
                line-height: 22px;
                font-size: 14px;
                overflow: hidden;
                text-overflow: ellipsis;
                white-space: nowrap
            }

            .AsqS6c .XAFD5c {
                width: 100px;
                height: 100px;
                background-color: #fff;
                border-radius: 16px;
                background-position: center;
                background-repeat: no-repeat
            }

            #TN4rFf {
                display: none
            }

            .IDVnvc {
                display: inline-block;
                max-width: 223px;
                border-radius: 12px;
                height: 178px;
                margin: -2px -10px 2px 10px
            }

            .OBMEnb:only-child .IDVnvc {
                margin-right: calc(25% - 113px)
            }

            .cRV9hb {
                width: 90px;
                padding: 6px
            }

            .cRV9hb .pcTkSc {
                font-family: arial,sans-serif;
                overflow: hidden;
                margin-top: 4px;
                padding: 0
            }

            .cRV9hb .pcTkSc .wM6W7d {
                font-size: 14px;
                line-height: 18px;
                padding: 0;
                color: #202124
            }

            .cRV9hb .pcTkSc .ClJ9Yb {
                line-height: 16px;
                font-size: 12px;
                display: none;
                display: flex
            }

            .cRV9hb .pcTkSc .wM6W7d span,.cRV9hb .pcTkSc .ClJ9Yb span {
                overflow: hidden;
                text-overflow: ellipsis;
                -webkit-box-orient: vertical;
                display: -webkit-box;
                white-space: normal
            }

            .cRV9hb .pcTkSc .wM6W7d span {
                -webkit-line-clamp: 2
            }

            .cRV9hb .pcTkSc .ClJ9Yb span {
                -webkit-line-clamp: 2
            }

            .aVbWac {
                background: #fff;
                border-radius: 12px;
                height: 90px
            }

            @media (max-width: 1300px) {
                .A8SBwf:not(.h3L8Ub) .IDVnvc {
                    height:167px
                }

                .A8SBwf:not(.h3L8Ub) .cRV9hb {
                    width: 79px
                }

                .A8SBwf:not(.h3L8Ub) .aVbWac {
                    height: 79px
                }

                .A8SBwf:not(.h3L8Ub) .aVbWac .sbic.vYOkbe {
                    height: 79px;
                    width: 79px
                }
            }

            .MG7lrf {
                font-size: 8pt;
                margin-top: -16px;
                position: absolute;
                right: 16px;
            }

            .c58wS {
                display: flex;
                margin-right: -14px;
                position: relative;
                z-index: 99
            }
        </style>
        <div id="_Ny0hZajKHuSv2roPysWswAY_1"></div>
        <noscript>
            <style>
                table,div,span,p {
                    display: none
                }
            </style>
            <meta content="0;url=/search?q=code+mau+token+gooogle&amp;sca_esv=571531489&amp;gbv=1&amp;sei=Ny0hZajKHuSv2roPysWswAY" http-equiv="refresh">
            <div style="display:block">
                Xin vui lòng nhấn <a href="/search?q=code+mau+token+gooogle&amp;sca_esv=571531489&amp;gbv=1&amp;sei=Ny0hZajKHuSv2roPysWswAY">vào đây</a>
                nếu bạn không được chuyển đi trong vòng vài giây.
            </div>
        </noscript>
        <style>
            @font-face {
                font-family: 'Google Sans';
                font-style: normal;
                font-weight: 400;
                font-display: optional;
                src: url(//fonts.gstatic.com/s/googlesans/v14/4UaGrENHsxJlGDuGo1OIlL3Kwp5MKg.woff2)format('woff2');
                unicode-range: U+0301,U+0400-045F,U+0490-0491,U+04B0-04B1,U+2116;
            }

            @font-face {
                font-family: 'Google Sans';
                font-style: normal;
                font-weight: 400;
                font-display: optional;
                src: url(//fonts.gstatic.com/s/googlesans/v14/4UaGrENHsxJlGDuGo1OIlL3Nwp5MKg.woff2)format('woff2');
                unicode-range: U+0370-03FF;
            }

            @font-face {
                font-family: 'Google Sans';
                font-style: normal;
                font-weight: 400;
                font-display: optional;
                src: url(//fonts.gstatic.com/s/googlesans/v14/4UaGrENHsxJlGDuGo1OIlL3Bwp5MKg.woff2)format('woff2');
                unicode-range: U+0102-0103,U+0110-0111,U+0128-0129,U+0168-0169,U+01A0-01A1,U+01AF-01B0,U+0300-0301,U+0303-0304,U+0308-0309,U+0323,U+0329,U+1EA0-1EF9,U+20AB;
            }

            @font-face {
                font-family: 'Google Sans';
                font-style: normal;
                font-weight: 400;
                font-display: optional;
                src: url(//fonts.gstatic.com/s/googlesans/v14/4UaGrENHsxJlGDuGo1OIlL3Awp5MKg.woff2)format('woff2');
                unicode-range: U+0100-02AF,U+0304,U+0308,U+0329,U+1E00-1E9F,U+1EF2-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF;
            }

            @font-face {
                font-family: 'Google Sans';
                font-style: normal;
                font-weight: 400;
                font-display: optional;
                src: url(//fonts.gstatic.com/s/googlesans/v14/4UaGrENHsxJlGDuGo1OIlL3Owp4.woff2)format('woff2');
                unicode-range: U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+0304,U+0308,U+0329,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD;
            }
        </style>
        <script nonce="N4ljJHxWoJx3pKoWtd5YIw">
            (function() {
                var w = ["Google Sans", [400]];
                (function() {
                    if (document.fonts && document.fonts.load)
                        for (var a = 0; a < w.length; a += 2)
                            for (var d = w[a], e = w[a + 1], b = 0, c = void 0; c = e[b]; ++b)
                                document.fonts.load(c + " 10pt " + d).catch(function() {})
                }
                )();
            }
            )();
        </script>
        <h2 class="bNg8Rb OhScic zsYMMe BBwThe" style="clip:rect(1px,1px,1px,1px);height:1px;overflow:hidden;position:absolute;white-space:nowrap;width:1px;z-index:-1000;-webkit-user-select:none">Liên kết hỗ trợ truy cập</h2>
        <div jscontroller="EufiNb" class="wYq63b">
            <div class="S6VXfe">
                <a jsname="BKxS1e" class="gyPpGe" role="link" tabindex="0" jsaction="i3viod" data-ved="0ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ67oDCAU">Bỏ qua để đến phần nội dung chính</a>
                <a jsname="PwyVob" class="o8xTWc kur4we gyPpGe" href="#" role="link" jsaction="xoizsc">Tắt chế độ cuộn liên tục</a>
                <a jsname="BzS6B" class="wxIowe kur4we gyPpGe" href="#" role="link" jsaction="XZ94se">Bật chế độ cuộn liên tục</a>
                <span id="tsuid_3"></span>
                <a jsname="KI37ad" class="gyPpGe" href="https://support.google.com/websearch/answer/181196?hl=vi" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;url=https://support.google.com/websearch/answer/181196%3Fhl%3Dvi&amp;ved=0ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQwcMDCAc&amp;bl=niYV&amp;opi=89978449">Hỗ trợ truy cập</a>
                <div data-async-context="async_id:duf3-78;authority:0;card_id:;entry_point:0;feature_id:;ftoe:0;header:0;is_jobs_spam_form:0;open:0;preselect_answer_index:-1;suggestions:;suggestions_subtypes:;suggestions_types:;surface:0;title:;type:78">
                    <div jscontroller="EkevXb" style="display:none" jsaction="rcuQ6b:npT2md"></div>
                    <div id="duf3-78" data-jiis="up" data-async-type="duffy3" data-async-context-required="type,open,feature_id,async_id,entry_point,authority,card_id,ftoe,title,header,suggestions,surface,suggestions_types,suggestions_subtypes,preselect_answer_index,is_jobs_spam_form" class="yp" data-ved="0ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ-0EICA"></div>
                    <a jsname="JUypV" class="gyPpGe" data-async-trigger="duf3-78" role="link" tabindex="0" jsaction="trigger.szjOR">Phản hồi về hỗ trợ truy cập</a>
                </div>
            </div>
        </div>
        <div class="CvDJxb" jscontroller="tIj4fb" jsaction="rcuQ6b:npT2md;" id="searchform">
            <div style="margin-top:-20px" class="sfbg"></div>
            <div class="Q3DXx yIbDgf">
                <form class="tsf" action="/search" id="tsf" autocomplete="off" data-submitfalse="q" method="GET" name="f" role="search">
                    <div jsmodel="ZrDSAb vNzKHd" jsdata="MuIEvd;_;ANVEfE">
                        <div jscontroller="cnjECf" jsmodel="VYkzu kjkykd a4L2gc LM7wx BFDhle gx0hCb TnHSdd L97mud " class="A8SBwf" data-adhe="false" data-alt="true" data-ehswwf="false" data-hp="false" data-mof="false" jsdata="LVplcb;_;" jsaction="lX6RWd:w3Wsmc;ocDSvd:duwfG;DR74Fd:KyvVPe;DkpM0b:d3sQLd;IQOavd:dFyQEf;XzZZPe:jI3wzf;Aghsf:AVsnlb;iHd9U:Q7Cnrc;f5hEHe:G0jgYd;vmxUb:j3bJnb;nTzfpf:YPRawb;R2c5O:LuRugf;qiCkJd:ANdidc;htNNz:SNIJTd;NOg9L:HLgh3;uGoIkd:epUokb;zLdLw:eaGBS;H9muVd:J4e6lb;djyPCf:nMeUJf;hBEIVb:nUZ9le;rcuQ6b:npT2md">
                            <div class="logo">
                                <a href="https://www.google.com/webhp?hl=vi&amp;sa=X&amp;ved=0ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQPAgJ" title="Đến trang chủ Google" id="logo" data-hveid="9">
                                    <img class="jfN4p" src="/images/branding/googlelogo/2x/googlelogo_color_92x30dp.png" style="background:none" alt="Google" height="30" width="92">
                                </a>
                            </div>
                            <div class="RNNXgb" jsname="RNNXgb">
                                <div class="SDkEP">
                                    <div class="iblpc" jsname="uFMOof">
                                        <div class="CcAdNb">
                                            <span class="QCzoEc z1asCe MZy1Rb" style="height:20px;line-height:20px;width:20px">
                                                <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                    <path d="M15.5 14h-.79l-.28-.27A6.471 6.471 0 0 0 16 9.5 6.5 6.5 0 1 0 9.5 16c1.61 0 3.09-.59 4.23-1.57l.27.28v.79l5 4.99L20.49 19l-4.99-5zm-6 0C7.01 14 5 11.99 5 9.5S7.01 5 9.5 5 14 7.01 14 9.5 11.99 14 9.5 14z"></path>
                                                </svg>
                                            </span>
                                        </div>
                                    </div>
                                    <div jscontroller="vZr2rb" class="a4bIc" data-hpmde="false" data-mnr="4" jsname="gLFyf" jsaction="h5M12e;input:d3sQLd;blur:jI3wzf;keydown:uYT2Vb">
                                        <div jsname="vdLsw" class="YacQv"></div>
                                        <div jsname="aJyGR" jscontroller="xMclgd" class="gLFyf i4ySpb" data-promo-open-duration="2000" jsaction="rcuQ6b:npT2md">
                                            <g-snackbar jsname="nH91he" jscontroller="OZLguc" style="display:none" data-dismiss="" jsshadow="" jsaction="rcuQ6b:npT2md">
                                                <div jsname="sM5MNb" aria-live="polite" class="jhZvod">
                                                    <div jsname="Ng57nc" class="Wu0v9b v0rrvd" data-ved="0ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ4G8ICw">
                                                        <div class="b77HKf">
                                                            <div class="rIxsve" jsslot="">
                                                                <span class="Txngnb wHYlTd yUTMj Sxjlmb">
                                                                    Nhấn <span class="qfY0Jf">/</span>
                                                                    để chuyển tới hộp tìm kiếm
                                                                </span>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                            </g-snackbar>
                                        </div>
                                        <textarea jsname="yZiJbe" class="gLFyf" jsaction="paste:puy29d; mouseenter:MJEKMe; mouseleave:iFHZnf;" id="APjFqb" maxlength="2048" name="q" rows="1" aria-activedescendant="" aria-autocomplete="both" aria-controls="Alh6id" aria-expanded="false" aria-haspopup="both" aria-owns="Alh6id" autocapitalize="off" autocomplete="off" autocorrect="off" role="combobox" spellcheck="false" type="search" value="code mau token gooogle" aria-label="Tìm kiếm" data-ved="0ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ39UDCAw">code mau token gooogle</textarea>
                                    </div>
                                    <div class="dRYYxd">
                                        <div jscontroller="PymCCe" jsname="RP0xob" class="BKRPef">
                                            <div class="M2vV3 vOY7J" tabindex="0" jsname="pkjasb" aria-label="Xóa" role="button" jsaction="AVsnlb;rcuQ6b:npT2md" data-ved="0ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ05YFCA0">
                                                <span class="ExCKkf z1asCe rzyADb" jsname="itVqKe">
                                                    <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                        <path d="M19 6.41L17.59 5 12 10.59 6.41 5 5 6.41 10.59 12 5 17.59 6.41 19 12 13.41 17.59 19 19 17.59 13.41 12z"></path>
                                                    </svg>
                                                </span>
                                            </div>
                                            <span jsname="s1VaRe" class="ACRAdd M2vV3"></span>
                                        </div>
                                        <div jscontroller="Y9t9Sc" class="Umvnrc" aria-label="Công cụ nhập" role="button" tabindex="0" jsaction="h5M12e;rcuQ6b:npT2md">
                                            <span class="ly0Ckb">
                                                <img class="yAnw3c" src="/tia/tia.png" tia_disable_swap="true" tia_field_name="q" jsname="JyIpdf">
                                            </span>
                                        </div>
                                        <div jscontroller="unV4T" jsname="F7uqIe" class="XDyW0e" aria-label="Tìm kiếm bằng giọng nói" role="button" tabindex="0" jsaction="h5M12e;rcuQ6b:npT2md" data-ved="0ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQvs8DCA4">
                                            <svg class="goxjub" focusable="false" viewbox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                                <path fill="#4285f4" d="m12 15c1.66 0 3-1.31 3-2.97v-7.02c0-1.66-1.34-3.01-3-3.01s-3 1.34-3 3.01v7.02c0 1.66 1.34 2.97 3 2.97z"></path>
                                                <path fill="#34a853" d="m11 18.08h2v3.92h-2z"></path>
                                                <path fill="#fbbc05" d="m7.05 16.87c-1.27-1.33-2.05-2.83-2.05-4.87h2c0 1.45 0.56 2.42 1.47 3.38v0.32l-1.15 1.18z"></path>
                                                <path fill="#ea4335" d="m12 16.93a4.97 5.25 0 0 1 -3.54 -1.55l-1.41 1.49c1.26 1.34 3.02 2.13 4.95 2.13 3.87 0 6.99-2.92 6.99-7h-1.99c0 2.92-2.24 4.93-5 4.93z"></path>
                                            </svg>
                                        </div>
                                        <div jscontroller="lpsUAf" jsname="R5mgy" class="nDcEnd" data-base-lens-url="https://lens.google.com" data-checkerboard-transparent-images-background-enabled="false" data-convert-transparent-images="true" data-downscaling-enabled="true" data-downscaling-max-longest-edge-pixels="1000" data-encoding-compression-ratio="0.4" data-image-processor-enabled="true" data-is-images-mode="false" data-is-send-dimensions-in-body-enabled="false" data-preferred-mime-type="image/jpeg" data-propagated-experiment-ids="72276982," data-transparent-image-background-color="#fff" data-transparent-image-checkerboard-color="#fff" data-upload-path="/v3/upload?ssb=1&amp;cpe=1&amp;ifg204=1&amp;" aria-label="Tìm kiếm bằng hình ảnh" role="button" tabindex="0" jsaction="rcuQ6b:npT2md;h5M12e" data-ved="0ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQhqEICA8">
                                            <svg class="Gdd5U" focusable="false" viewbox="0 0 192 192" xmlns="http://www.w3.org/2000/svg">
                                                <rect fill="none" height="192" width="192"></rect>
                                                <g>
                                                    <circle fill="#34a853" cx="144.07" cy="144" r="16"></circle>
                                                    <circle fill="#4285f4" cx="96.07" cy="104" r="24"></circle>
                                                    <path fill="#ea4335" d="M24,135.2c0,18.11,14.69,32.8,32.8,32.8H96v-16l-40.1-0.1c-8.8,0-15.9-8.19-15.9-17.9v-18H24V135.2z"></path>
                                                    <path fill="#fbbc05" d="M168,72.8c0-18.11-14.69-32.8-32.8-32.8H116l20,16c8.8,0,16,8.29,16,18v30h16V72.8z"></path>
                                                    <path fill="#4285f4" d="M112,24l-32,0L68,40H56.8C38.69,40,24,54.69,24,72.8V92h16V74c0-9.71,7.2-18,16-18h80L112,24z"></path>
                                                </g>
                                            </svg>
                                        </div>
                                    </div>
                                </div>
                                <button jsname="Tg7LZd" class="Tg7LZd" aria-label="Tìm kiếm" type="submit" data-ved="0ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ4dUDCBA">
                                    <div class="zgAlFc">
                                        <span class="z1asCe MZy1Rb">
                                            <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                <path d="M15.5 14h-.79l-.28-.27A6.471 6.471 0 0 0 16 9.5 6.5 6.5 0 1 0 9.5 16c1.61 0 3.09-.59 4.23-1.57l.27.28v.79l5 4.99L20.49 19l-4.99-5zm-6 0C7.01 14 5 11.99 5 9.5S7.01 5 9.5 5 14 7.01 14 9.5 11.99 14 9.5 14z"></path>
                                            </svg>
                                        </span>
                                    </div>
                                </button>
                            </div>
                            <div jscontroller="Dvn7fe" class="UUbT9 EyBRub" style="display:none" jsname="UUbT9" jsaction="mouseout:ItzDCd;mouseleave:MWfikb;hBEIVb:nUZ9le;YMFC3:VKssTb;vklu5c:k02QY;ldyIye:CmVOgc" data-ved="0ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ4tUDCBE">
                                <div class="RjPuVb" jsname="RjPuVb"></div>
                                <div class="aajZCb" jsname="aajZCb">
                                    <div class="xtSCL"></div>
                                    <div class="mkHrUc" id="Alh6id" role="presentation">
                                        <div class="erkvQe" jsname="erkvQe"></div>
                                        <div class="rLrQHf" jsname="tovEib" role="presentation"></div>
                                    </div>
                                    <div jsname="E80e9e" class="OBMEnb" id="shJ2Vb" role="presentation">
                                        <ul jsname="bw4e9b" class="G43f7e" role="listbox"></ul>
                                    </div>
                                    <div class="ynRric" id="ynRric" role="presentation"></div>
                                    <li data-view-type="1" class="sbct" id="YMXe" role="presentation">
                                        <div class="eIPGRd">
                                            <div class="sbic">
                                                <div class="j0GJWd" style="display:none">
                                                    <div>
                                                        <img class="uHGFVd AZNDm" alt="" style="display:none">
                                                    </div>
                                                    <div class="iQxPRb">
                                                        <img class="uHGFVd EOLKOc" alt="" style="display:none">
                                                        <img class="uHGFVd EOLKOc" alt="" style="display:none">
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="pcTkSc">
                                                <div class="lnnVSe" aria-atomic="true" role="option">
                                                    <div class="wM6W7d">
                                                        <span></span>
                                                    </div>
                                                    <div class="ClJ9Yb">
                                                        <span></span>
                                                    </div>
                                                    <div class="a5RLac">
                                                        <span></span>
                                                    </div>
                                                </div>
                                                <div class="Sz7Lee MagqMc U48fD" style="display:none" aria-label="Xem thêm" role="button" tabindex="0">
                                                    <hr class="Bi9oQd" aria-hidden="true">
                                                    <div class="ZFiwCf">
                                                        <span class="LGwnxb">Xem thêm</span>
                                                        <span class="w2fKdd z1asCe lYxQe" style="height:20px;line-height:20px;width:20px">
                                                            <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                <path d="M12 4l-1.41 1.41L16.17 11H4v2h12.17l-5.58 5.59L12 20l8-8z"></path>
                                                            </svg>
                                                        </span>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="AQZ9Vd" aria-atomic="true" role="button">
                                                <div class="sbai" role="presentation">Xoá</div>
                                            </div>
                                        </div>
                                        <div class="TfeWfb"></div>
                                    </li>
                                    <div class="xAmryf" id="bgeLZd">
                                        <span class="jtAOgd"></span>
                                    </div>
                                    <li data-view-type="8" class="sbct" id="mitGyb" role="presentation">
                                        <div class="eIPGRd hdt0ld">
                                            <div class="sbic"></div>
                                            <div class="pcTkSc">
                                                <div>
                                                    <div class="wM6W7d">
                                                        <span></span>
                                                    </div>
                                                    <div class="ClJ9Yb">
                                                        <span></span>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="AQZ9Vd" aria-atomic="true" role="button">
                                                <div class="sbai" role="presentation">Xoá</div>
                                            </div>
                                        </div>
                                    </li>
                                    <div class="ZDHp" id="fU0xAb" role="presentation" style="display:none">
                                        <div class="kZtr1b">
                                            <div class="lnnVSe" aria-atomic="true" role="option">
                                                <div class="SHFPkb"></div>
                                                <div class="bTSf5c"></div>
                                                <div class="PnfqLc"></div>
                                                <div class="HrUlUc"></div>
                                            </div>
                                            <div class="Tnv2td" aria-atomic="true" role="button" style="display:none">
                                                <span class="z76Rnb z1asCe JKu1je">
                                                    <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                        <path d="M3 9v6h4l5 5V4L7 9H3zm13.5 3c0-1.77-1.02-3.29-2.5-4.03v8.05c1.48-.73 2.5-2.25 2.5-4.02zM14 3.23v2.06c2.89.86 5 3.54 5 6.71s-2.11 5.85-5 6.71v2.06c4.01-.91 7-4.49 7-8.77s-2.99-7.86-7-8.77z"></path>
                                                    </svg>
                                                </span>
                                            </div>
                                            <div class="xAmryf" id="bgeLZd">
                                                <span class="jtAOgd"></span>
                                            </div>
                                            <div class="TfeWfb" role="presentation" style="display:none"></div>
                                            <div class="Vlt3wb" style="display:none"></div>
                                        </div>
                                        <span class="XAFD5c" style="display:none"></span>
                                        <div class="j0GJWd" style="display:none">
                                            <div>
                                                <img class="uHGFVd AZNDm" alt="" style="display:none">
                                            </div>
                                            <div class="iQxPRb">
                                                <img class="uHGFVd EOLKOc" alt="" style="display:none">
                                                <img class="uHGFVd EOLKOc" alt="" style="display:none">
                                            </div>
                                        </div>
                                    </div>
                                    <div class="AsqS6c" id="GTYqfc" role="presentation" style="display:none">
                                        <div class="gfT7kc">
                                            <div class="cJpYle">
                                                <div class="lnnVSe" aria-atomic="true" role="option">
                                                    <div class="SHFPkb"></div>
                                                    <div class="bTSf5c"></div>
                                                    <div class="PnfqLc"></div>
                                                    <div class="HrUlUc"></div>
                                                </div>
                                                <div class="Tnv2td" aria-atomic="true" role="button" style="display:none">
                                                    <span class="z76Rnb z1asCe JKu1je">
                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                            <path d="M3 9v6h4l5 5V4L7 9H3zm13.5 3c0-1.77-1.02-3.29-2.5-4.03v8.05c1.48-.73 2.5-2.25 2.5-4.02zM14 3.23v2.06c2.89.86 5 3.54 5 6.71s-2.11 5.85-5 6.71v2.06c4.01-.91 7-4.49 7-8.77s-2.99-7.86-7-8.77z"></path>
                                                        </svg>
                                                    </span>
                                                </div>
                                                <span class="XAFD5c" style="display:none"></span>
                                            </div>
                                            <div class="gTtFDd">
                                                <div class="lnnVSe" aria-atomic="true" role="option">
                                                    <div class="SHFPkb"></div>
                                                    <div class="bTSf5c"></div>
                                                    <div class="PnfqLc"></div>
                                                    <div class="HrUlUc"></div>
                                                </div>
                                                <div class="Tnv2td" aria-atomic="true" role="button" style="display:none">
                                                    <span class="z76Rnb z1asCe JKu1je">
                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                            <path d="M3 9v6h4l5 5V4L7 9H3zm13.5 3c0-1.77-1.02-3.29-2.5-4.03v8.05c1.48-.73 2.5-2.25 2.5-4.02zM14 3.23v2.06c2.89.86 5 3.54 5 6.71s-2.11 5.85-5 6.71v2.06c4.01-.91 7-4.49 7-8.77s-2.99-7.86-7-8.77z"></path>
                                                        </svg>
                                                    </span>
                                                </div>
                                                <span class="XAFD5c" style="display:none"></span>
                                            </div>
                                        </div>
                                        <div class="Vlt3wb" style="display:none"></div>
                                    </div>
                                    <div class="xAmryf" id="bgeLZd">
                                        <span class="jtAOgd"></span>
                                    </div>
                                    <div class="TfeWfb" role="presentation" style="display:none"></div>
                                    <li class="IDVnvc" data-view-type="6" id="TN4rFf" role="presentation">
                                        <div class="cRV9hb">
                                            <div class="aVbWac">
                                                <div class="sbic"></div>
                                            </div>
                                            <div class="pcTkSc" role="presentation">
                                                <div class="lnnVSe" aria-atomic="true" role="option">
                                                    <div class="wM6W7d">
                                                        <span></span>
                                                    </div>
                                                    <div class="ClJ9Yb">
                                                        <span></span>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </li>
                                </div>
                                <div jscontroller="OqGDve" jsname="JUypV">
                                    <div class="MG7lrf" jsname="kAiEt" data-async-context="async_id:duf3-46;authority:0;card_id:;entry_point:0;feature_id:;ftoe:0;header:0;is_jobs_spam_form:0;open:0;preselect_answer_index:-1;suggestions:;suggestions_subtypes:;suggestions_types:;surface:0;title:;type:46">
                                        <div jscontroller="EkevXb" style="display:none" jsaction="rcuQ6b:npT2md"></div>
                                        <div id="duf3-46" data-jiis="up" data-async-type="duffy3" data-async-context-required="type,open,feature_id,async_id,entry_point,authority,card_id,ftoe,title,header,suggestions,surface,suggestions_types,suggestions_subtypes,preselect_answer_index,is_jobs_spam_form" class="yp" data-ved="0ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ-0EIEw"></div>
                                        <a class="oBa0Fe aciXEb" href="#" id="sbfblt" data-async-trigger="duf3-46" aria-label="Gửi ý kiến phản hồi về kết quả này" role="button" jsaction="trigger.szjOR" data-ved="0ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQtw8IFA">Báo cáo các gợi ý không phù hợp</a>
                                    </div>
                                </div>
                            </div>
                            <div jsname="mvaK7d" class="M8H8pb" data-ved="0ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ4d8ICBU"></div>
                        </div>
                        <div style="background:url(/images/searchbox/desktop_searchbox_sprites318_hr.webp)"></div>
                        <script nonce="N4ljJHxWoJx3pKoWtd5YIw">
                            (function() {
                                var a = this || self;
                                var c = document.querySelector("form");
                                if (c) {
                                    var d = function(b) {
                                        "Enter" !== b.key || b.shiftKey || (b.preventDefault(),
                                        c.submit && c.submit())
                                    };
                                    c.addEventListener("keydown", d);
                                    a.sbmlhf = d
                                }
                                ;
                            }
                            ).call(this);
                        </script>
                    </div>
                    <div id="tophf">
                        <input name="sca_esv" value="571531489" type="hidden">
                        <input value="Ny0hZajKHuSv2roPysWswAY" name="ei" type="hidden">
                        <input value="AO6bgOgAAAAAZSE7R-cbZtqdpLIM9xn4AtKkV58YnvY2" disabled="true" name="iflsig" type="hidden">
                    </div>
                </form>
                <div class="Q3DXx">
                    <div class="c58wS">
                        <div id="_Ny0hZajKHuSv2roPysWswAY_5" jscontroller="vTw9Fc" jsname="gRWMdb" data-triggering-tag="UMK4Dc" jsaction="fj1r1d:qiause"></div>
                    </div>
                    <div id="_Ny0hZajKHuSv2roPysWswAY_7"></div>
                </div>
            </div>
        </div>
        <div id="gac_scont"></div>
        <span class="kpshf line gsr bilit big mdm" style="display:none"></span>
        <div class="main" id="main">
            <div jsmodel=" ROaKxe" class="e9EfHf" id="cnt">
                <div class="dodTBe" id="sfcnt"></div>
                <style>
                    .YrbPuc {
                        color: #70757a;
                        font-family: arial,sans-serif;
                        font-size: 14px;
                        font-weight: 400;
                        line-height: 22px
                    }

                    .oPWl9c {
                        color: #70757a;
                        font-family: arial,sans-serif;
                        font-size: 12px;
                        font-weight: 400;
                        line-height: 20px
                    }

                    .BjWz4c {
                        color: #70757a;
                        font-family: arial,sans-serif;
                        font-size: 12px;
                        font-weight: 400;
                        line-height: 16px
                    }

                    .cj1ht {
                        color: #4d5156;
                        font-family: arial,sans-serif;
                        font-size: 12px;
                        font-weight: 400;
                        line-height: 16px
                    }

                    sentinel {
                    }

                    .SGNhVe {
                        font-family: Google Sans,arial,sans-serif;
                        font-size: 48px;
                        letter-spacing: 0;
                        line-height: 56px
                    }

                    .EX5Zne {
                        font-family: Google Sans,arial,sans-serif;
                        font-size: 36px;
                        line-height: 40px
                    }

                    .JgzqYd {
                        font-family: Google Sans,arial,sans-serif;
                        font-size: 28px;
                        line-height: 36px
                    }

                    .aTI8gc {
                        font-family: Google Sans,arial,sans-serif;
                        font-size: 28px;
                        font-weight: 500;
                        line-height: 36px
                    }

                    .IFnjPb {
                        font-family: Google Sans,arial,sans-serif;
                        font-size: 22px;
                        font-weight: 400;
                        line-height: 28px
                    }

                    .pb3iw {
                        font-family: Google Sans,arial,sans-serif;
                        font-size: 18px;
                        font-weight: 400;
                        line-height: 24px
                    }

                    .ILxcde {
                        font-family: Google Sans,arial,sans-serif;
                        font-size: 16px;
                        font-weight: 400;
                        line-height: 24px
                    }

                    .MBeuO {
                        font-family: arial,sans-serif;
                        font-size: 20px;
                        font-weight: 400
                    }

                    .MBeuO {
                        line-height: 24px
                    }

                    .tNxQIb {
                        font-family: arial,sans-serif;
                        font-size: 16px;
                        font-weight: 400;
                        line-height: 24px
                    }

                    .ZwRhJd {
                        font-family: arial,sans-serif;
                        font-size: 14px;
                        line-height: 18px
                    }

                    .NNMgCf {
                        font-family: arial,sans-serif;
                        font-size: 16px;
                        line-height: 24px
                    }

                    .Pqkn2e {
                        font-family: arial,sans-serif;
                        font-size: 16px;
                        line-height: 22px
                    }

                    .wHYlTd {
                        font-family: arial,sans-serif;
                        font-size: 14px;
                        line-height: 22px
                    }

                    .ApHyTb {
                        font-family: arial,sans-serif;
                        font-size: 12px;
                        line-height: 16px
                    }

                    .sjVJQd {
                        font-family: Google Sans,arial,sans-serif-medium,sans-serif;
                        font-size: 14px;
                        font-weight: 400;
                        line-height: 20px
                    }

                    .k1U36b {
                        font-size: 12px
                    }

                    sentinel {
                    }

                    .TGyDA {
                        height: 66px;
                        display: -css3-box;
                        -css3-box-orient: vertical;
                        -css3-line-clamp: 3;
                        overflow: hidden;
                        white-space: normal
                    }

                    .yUTMj {
                        font-family: arial,sans-serif;
                        font-weight: 400
                    }

                    .VDgVie {
                        text-align: center
                    }

                    .TUOsUe {
                        text-align: left
                    }

                    .AraNOb {
                        -webkit-text-decoration: underline;
                        text-decoration: underline
                    }

                    .BBwThe {
                        font-weight: 700
                    }

                    .RiJqbb {
                        font-family: Google Sans,arial,sans-serif-medium,sans-serif;
                        font-weight: 500
                    }

                    .SlP8xc {
                        text-transform: none
                    }

                    .n9iHLc {
                        text-transform: uppercase
                    }

                    .OSrXXb {
                        overflow: hidden;
                        text-overflow: ellipsis
                    }

                    .cHaqb {
                        overflow: hidden;
                        text-overflow: ellipsis;
                        white-space: nowrap
                    }

                    .RES9jf {
                        color: #202124
                    }

                    .GS5rRd {
                        color: #1a0dab
                    }

                    .GS5rRd:visited {
                        color: #681da8
                    }

                    sentinel {
                    }

                    .OhScic {
                        margin: 0px
                    }

                    .zsYMMe {
                        padding: 0px
                    }

                    .bNg8Rb {
                        clip: rect(1px,1px,1px,1px);
                        height: 1px;
                        overflow: hidden;
                        position: absolute;
                        white-space: nowrap;
                        width: 1px;
                        z-index: -1000;
                        user-select: none;
                        -webkit-user-select: none;
                        -moz-user-select: none;
                        -ms-user-select: none
                    }

                    sentinel {
                    }

                    .s6JM6d .eYa01b {
                        width: 148px
                    }

                    .s6JM6d .KtfA8c {
                        width: 204px
                    }

                    .s6JM6d .APo4S {
                        margin-left: 10px;
                        margin-right: 10px
                    }

                    .s6JM6d .THlyec {
                        margin-left: -10px;
                        margin-right: -10px;
                        min-width: 672px
                    }

                    @media (max-width: calc((var(--sds-ref-layout--desktop-page-grid-col-width ) + var(--sds-ref-layout--desktop-page-grid-gap )) * 12 - var(--sds-ref-layout--desktop-page-grid-gap ))) {
                        .s6JM6d .THlyec {
                            min-width:unset;
                            width: 100%
                        }
                    }

                    .M8OgIe .hhv4Fb {
                        margin-left: -38px;
                        margin-right: -38px
                    }

                    .M8OgIe .JL6v7b {
                        margin-left: 38px;
                        margin-right: 38px;
                        padding-left: 0;
                        padding-right: 0
                    }

                    .M8OgIe .TRty9d {
                        width: 316px
                    }

                    .TQc1id .zLsiYe {
                        margin-left: -21px;
                        padding-left: 0
                    }

                    sentinel {
                    }

                    .zJUuqf {
                        margin-bottom: 4px
                    }

                    .AB4Wff {
                        margin-left: 16px
                    }

                    .v0rrvd {
                        padding-bottom: 16px
                    }

                    @-webkit-keyframes g-snackbar-show {
                        from {
                            pointer-events: none;
                            -webkit-transform: translateY(0);
                            transform: translateY(0)
                        }

                        to {
                            -webkit-transform: translateY(-100%);
                            transform: translateY(-100%)
                        }
                    }

                    @keyframes g-snackbar-show {
                        from {
                            pointer-events: none;
                            -webkit-transform: translateY(0);
                            transform: translateY(0)
                        }

                        to {
                            -webkit-transform: translateY(-100%);
                            transform: translateY(-100%)
                        }
                    }

                    @-webkit-keyframes g-snackbar-hide {
                        from {
                            -webkit-transform: translateY(-100%);
                            transform: translateY(-100%)
                        }

                        to {
                            -webkit-transform: translateY(0);
                            transform: translateY(0)
                        }
                    }

                    @keyframes g-snackbar-hide {
                        from {
                            -webkit-transform: translateY(-100%);
                            transform: translateY(-100%)
                        }

                        to {
                            -webkit-transform: translateY(0);
                            transform: translateY(0)
                        }
                    }

                    @-webkit-keyframes g-snackbar-show-content {
                        from {
                            opacity: 0
                        }
                    }

                    @keyframes g-snackbar-show-content {
                        from {
                            opacity: 0
                        }
                    }

                    @-webkit-keyframes g-snackbar-hide-content {
                        to {
                            opacity: 0
                        }
                    }

                    @keyframes g-snackbar-hide-content {
                        to {
                            opacity: 0
                        }
                    }

                    .LH3wG,.jhZvod {
                        bottom: 0;
                        height: 0;
                        position: fixed;
                        z-index: 999
                    }

                    .Ox8Cyd {
                        height: 0;
                        position: fixed;
                        z-index: 999
                    }

                    .E7Hdgb {
                        box-sizing: border-box;
                        visibility: hidden;
                        display: inline-block
                    }

                    .yK6jqe,.Wu0v9b {
                        box-sizing: border-box;
                        visibility: hidden
                    }

                    .rTYTNb {
                        -webkit-animation: g-snackbar-hide .4s cubic-bezier(0.4,0,0.2,1) both;
                        animation: g-snackbar-hide .4s cubic-bezier(0.4,0,0.2,1) both;
                        visibility: inherit
                    }

                    .UewPMd {
                        -webkit-animation: g-snackbar-show .5s cubic-bezier(0.4,0,0.2,1) both;
                        animation: g-snackbar-show .5s cubic-bezier(0.4,0,0.2,1) both;
                        visibility: inherit
                    }

                    .b77HKf {
                        background-color: #323232;
                        padding: 0 24px
                    }

                    .rIxsve {
                        -webkit-box-align: center;
                        -webkit-align-items: center;
                        align-items: center;
                        box-align: center;
                        display: box;
                        display: -webkit-box;
                        display: -webkit-flex;
                        display: flex
                    }

                    .rTYTNb .rIxsve {
                        -webkit-animation: g-snackbar-hide-content .35s cubic-bezier(0.4,0,0.2,1) both;
                        animation: g-snackbar-hide-content .35s cubic-bezier(0.4,0,0.2,1) both
                    }

                    .UewPMd .rIxsve {
                        -webkit-animation: g-snackbar-show-content .35s cubic-bezier(0.4,0,0.2,1) .15s both;
                        animation: g-snackbar-show-content .35s cubic-bezier(0.4,0,0.2,1) .15s both
                    }

                    .Txngnb.Txngnb {
                        line-height: 20px
                    }

                    .Txngnb {
                        box-flex: 1;
                        color: #fff;
                        -webkit-box-flex: 1;
                        -webkit-flex: 1 1 auto;
                        flex: 1 1 auto;
                        margin: 14px 0;
                        word-break: break-word
                    }

                    .sHFNYd {
                        margin-right: -8px
                    }

                    @media (min-width: 569px) and (min-height:569px) {
                        .LH3wG,.jhZvod {
                            text-align:center
                        }

                        .Wu0v9b,.yK6jqe {
                            display: inline-block;
                            max-width: 568px;
                            min-width: 288px;
                            text-align: left
                        }

                        .b77HKf {
                            border-radius: 8px
                        }

                        .sHFNYd {
                            margin-left: 40px
                        }
                    }

                    .V9O1Yd .rIxsve {
                        display: block;
                        padding: 8px 0
                    }

                    .V9O1Yd .sHFNYd {
                        margin-left: 0
                    }

                    .V9O1Yd .sHFNYd g-flat-button {
                        padding-left: 0
                    }

                    .jhZvod {
                        left: 16px;
                        right: auto
                    }

                    .LH3wG,.Ox8Cyd {
                        left: 0;
                        right: 0
                    }

                    .yK6jqe,.Wu0v9b,.E7Hdgb {
                        position: relative
                    }

                    .G9jore {
                        position: absolute;
                        top: -24px;
                        bottom: -24px;
                        left: -24px;
                        right: -24px
                    }

                    sentinel {
                    }
                </style>
                <script nonce="N4ljJHxWoJx3pKoWtd5YIw">
                    (function() {
                        google.tick("load", "sct");
                    }
                    ).call(this);
                </script>
                <div data-st-cnt="ee" id="easter-egg"></div>
                <style>
                    .yg51vc {
                        background: #fff;
                        height: 47px;
                        position: relative;
                        padding: 0;
                        z-index: 126;
                        white-space: nowrap;
                    }

                    .iJddsb {
                        display: inline-block;
                        fill: currentColor
                    }

                    .iJddsb img,.iJddsb svg {
                        display: block;
                        height: 100%;
                        width: 100%
                    }

                    .pdswFd {
                        float: right;
                        position: relative;
                        right: 17px;
                        z-index: 3
                    }

                    .pdswFd .hdtb-mitem {
                        display: inline-block
                    }

                    .fFI3rb {
                        padding: 13px 6px 8px 12px;
                        border-radius: 8px
                    }

                    .F75bid {
                        color: #5f6368;
                        display: inline-block
                    }

                    .NkCsjc {
                        position: relative;
                        display: block;
                        outline: none
                    }

                    .S7TGef {
                        font-size: 14px;
                        height: 24px;
                        line-height: 24px;
                        margin-right: 1px;
                        white-space: nowrap;
                        display: inline
                    }

                    .S7TGef,.BpGBNe {
                        font-weight: bold;
                        color: #202124
                    }

                    #lb .S7TGef,#lb .BpGBNe {
                        color: #4285f4
                    }

                    .MmOzS {
                        vertical-align: middle;
                        padding-bottom: 2px;
                        padding-left: 4px
                    }

                    .Lj8KXd {
                        background-color: transparent;
                        top: 0;
                        width: 100%;
                        white-space: nowrap;
                        height: 22px;
                        position: absolute;
                        -webkit-transition: top 220ms ease-in-out;
                    }

                    .p4DDCd {
                        display: none
                    }

                    .pkWBse {
                        box-shadow: 0 2px 10px 0 rgba(0,0,0,0.2)
                    }

                    .pkWBse {
                        border-radius: 8px
                    }

                    .UjBGL {
                        display: block
                    }

                    .CcNe6e {
                        cursor: pointer;
                        display: inline-block
                    }

                    .iRQHZe {
                        position: absolute
                    }

                    .Qaqu5 {
                        position: relative
                    }

                    .shnMoc.CcNe6e {
                        display: block
                    }

                    .v4Zpbe.CcNe6e {
                        display: -webkit-box;
                        display: -webkit-flex;
                        display: flex;
                        height: 100%;
                        width: 100%
                    }

                    sentinel {
                    }

                    .PBn44e {
                        border-radius: 8px
                    }

                    .yTik0 {
                        border: none;
                        display: block;
                        outline: none
                    }

                    .wplJBd {
                        white-space: nowrap
                    }

                    .JM22S::-webkit-scrollbar {
                        width: 8px
                    }

                    .JM22S::-webkit-scrollbar-thumb {
                        background-color: #bababa;
                        border-right: 4px solid #fff
                    }

                    .iQXTJe {
                        padding: 5px 0
                    }

                    sentinel {
                    }

                    .Zt0a5e.LGiluc {
                        border-top-color: #dadce0
                    }

                    .Zt0a5e.LGiluc,.Zt0a5e.EpPYLd[disabled] {
                        color: rgba(0,0,0,0.26)!important
                    }

                    .CjiZvb,.GZnQqe.EpPYLd:active {
                        background-color: rgba(0,0,0,0.1)
                    }

                    .EpPYLd {
                        display: block;
                        position: relative
                    }

                    .YpcDnf {
                        padding: 0 16px;
                        vertical-align: middle
                    }

                    .YpcDnf.HG1dvd {
                        padding: 0
                    }

                    .HG1dvd>* {
                        padding: 0 16px
                    }

                    .WtV5nd .YpcDnf {
                        padding-left: 28px
                    }

                    .Zt0a5e .YpcDnf {
                        line-height: 48px
                    }

                    .GZnQqe .YpcDnf {
                        line-height: 23px
                    }

                    .EpPYLd:hover {
                        cursor: pointer
                    }

                    .EpPYLd,.CB8nDe:hover {
                        cursor: default
                    }

                    .LGiluc,.EpPYLd[disabled] {
                        pointer-events: none;
                        cursor: default
                    }

                    .LGiluc {
                        border-top: 1px solid;
                        height: 0;
                        margin: 5px 0
                    }

                    .Zt0a5e.CB8nDe {
                        background: no-repeat left 8px center
                    }

                    .Zt0a5e.CB8nDe {
                        background-image: url(https://ssl.gstatic.com/images/icons/material/system/1x/done_black_16dp.png)
                    }

                    .GZnQqe.CB8nDe {
                        background: no-repeat left center
                    }

                    .GZnQqe.CB8nDe {
                        background-image: url(https://ssl.gstatic.com/ui/v1/menu/checkmark2.png)
                    }

                    .GZnQqe.LGiluc,.GZnQqe.EpPYLd[disabled] {
                        color: #dadce0!important
                    }

                    .GZnQqe.LGiluc {
                        border-top-color: #dadce0
                    }

                    sentinel {
                    }

                    .gTMtLb {
                        z-index: 1001;
                        position: absolute;
                        top: -1000px
                    }

                    @keyframes ghost-card-shimmering {
                        0% {
                            transform: translateX(-100%)
                        }

                        100% {
                            transform: translateX(100%)
                        }
                    }
                </style>
                <div jscontroller="HYSCof" class="gke0pe" id="top_nav" jsdata="Z1JpA;_;ANVEfM" jsaction="rcuQ6b:npT2md">
                    <h2 class="bNg8Rb OhScic zsYMMe BBwThe" style="clip:rect(1px,1px,1px,1px);height:1px;overflow:hidden;position:absolute;white-space:nowrap;width:1px;z-index:-1000;-webkit-user-select:none">Chế độ tìm kiếm</h2>
                    <div class="GLcBOb" role="navigation" id="hdtb">
                        <div class="yg51vc" id="pTwnEc">
                            <div class="IC1Ck" id="hdtb-msb">
                                <div>
                                    <div class="MUFPAc">
                                        <div class="hdtb-mitem hdtb-msel" aria-current="page">
                                            <span>
                                                <span class="bmaJhd iJddsb" style="height:16px;width:16px">
                                                    <svg focusable="false" viewbox="0 0 24 24">
                                                        <path fill="#34a853" d="M10 2v2a6 6 0 0 1 6 6h2a8 8 0 0 0-8-8"></path>
                                                        <path fill="#ea4335" d="M10 4V2a8 8 0 0 0-8 8h2c0-3.3 2.7-6 6-6"></path>
                                                        <path fill="#fbbc04" d="M4 10H2a8 8 0 0 0 8 8v-2c-3.3 0-6-2.69-6-6"></path>
                                                        <path fill="#4285f4" d="M22 20.59l-5.69-5.69A7.96 7.96 0 0 0 18 10h-2a6 6 0 0 1-6 6v2c1.85 0 3.52-.64 4.88-1.68l5.69 5.69L22 20.59"></path>
                                                    </svg>
                                                </span>
                                                Tất cả<div class="YTDezd"></div>
                                            </span>
                                        </div>
                                        <div class="hdtb-mitem">
                                            <a href="/search?q=code+mau+token+google&amp;sca_esv=571531489&amp;tbm=isch&amp;source=lnms&amp;sa=X&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ_AUoAXoECAEQAw" data-hveid="CAEQAw">
                                                <span class="bmaJhd iJddsb" style="height:16px;width:16px">
                                                    <svg focusable="false" viewbox="0 0 24 24">
                                                        <path d="M14 13l4 5H6l4-4 1.79 1.78L14 13zm-6.01-2.99A2 2 0 0 0 8 6a2 2 0 0 0-.01 4.01zM22 5v14a3 3 0 0 1-3 2.99H5c-1.64 0-3-1.36-3-3V5c0-1.64 1.36-3 3-3h14c1.65 0 3 1.36 3 3zm-2.01 0a1 1 0 0 0-1-1H5a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h7v-.01h7a1 1 0 0 0 1-1V5"></path>
                                                    </svg>
                                                </span>
                                                Hình ảnh
                                            </a>
                                        </div>
                                        <div class="hdtb-mitem">
                                            <a href="/search?q=code+mau+token+google&amp;sca_esv=571531489&amp;tbm=vid&amp;source=lnms&amp;sa=X&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ_AUoAnoECAEQBA" data-hveid="CAEQBA">
                                                <span class="bmaJhd iJddsb" style="height:16px;width:16px">
                                                    <svg focusable="false" viewbox="0 0 24 24">
                                                        <path d="M10 16.5l6-4.5-6-4.5v9zM5 20h14a1 1 0 0 0 1-1V5a1 1 0 0 0-1-1H5a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1zm14.5 2H5a3 3 0 0 1-3-3V4.4A2.4 2.4 0 0 1 4.4 2h15.2A2.4 2.4 0 0 1 22 4.4v15.1a2.5 2.5 0 0 1-2.5 2.5"></path>
                                                    </svg>
                                                </span>
                                                Video
                                            </a>
                                        </div>
                                        <div class="hdtb-mitem">
                                            <a href="/search?q=code+mau+token+google&amp;sca_esv=571531489&amp;tbm=bks&amp;source=lnms&amp;sa=X&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ_AUoA3oECAEQBQ" data-hveid="CAEQBQ">
                                                <span class="bmaJhd iJddsb" style="height:16px;width:16px">
                                                    <svg focusable="false" viewbox="0 0 24 24">
                                                        <path d="M18 2H6a2 2 0 0 0-2 2v16c0 1.1.9 2 2 2h12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm0 18H6V4h2v8l2.5-1.5L13 12V4h5v16"></path>
                                                    </svg>
                                                </span>
                                                Sách
                                            </a>
                                        </div>
                                        <div class="hdtb-mitem">
                                            <a href="/search?q=code+mau+token+google&amp;sca_esv=571531489&amp;tbm=nws&amp;source=lnms&amp;sa=X&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ_AUoBHoECAEQBg" data-hveid="CAEQBg">
                                                <span class="bmaJhd iJddsb" style="height:16px;width:16px">
                                                    <svg focusable="false" viewbox="0 0 24 24">
                                                        <path d="M12 11h6v2h-6v-2zm-6 6h12v-2H6v2zm0-4h4V7H6v6zm16-7.22v12.44c0 1.54-1.34 2.78-3 2.78H5c-1.64 0-3-1.25-3-2.78V5.78C2 4.26 3.36 3 5 3h14c1.64 0 3 1.25 3 2.78zM19.99 12V5.78c0-.42-.46-.78-1-.78H5c-.54 0-1 .36-1 .78v12.44c0 .42.46.78 1 .78h14c.54 0 1-.36 1-.78V12zM12 9h6V7h-6v2"></path>
                                                    </svg>
                                                </span>
                                                Tin tức
                                            </a>
                                        </div>
                                    </div>
                                    <span class="hdtb-mitem" jscontroller="nabPbb" data-ffp="false" jsaction="KyPa0e:Y0y4c;BVfjhf:VFzweb;wjOG7e:gDkf4c;">
                                        <g-popup jsname="V68bde" jscontroller="DPreE" jsaction="A05xBd:IYtByb;EOZ57e:WFrRFb;" jsdata="mVjAjf;_;ANVEfk">
                                            <div jsname="oYxtQd" class="CcNe6e" aria-expanded="false" aria-haspopup="true" role="button" tabindex="0" jsaction="WFrRFb;keydown:uYT2Vb">
                                                <div jsname="LgbsSe" class="GOE98c">
                                                    <span class="MbEPDb z1asCe SaPW2b" style="height:16px;line-height:16px;width:16px">
                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                            <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                        </svg>
                                                    </span>
                                                    Thêm
                                                </div>
                                            </div>
                                            <div jsname="V68bde" class="UjBGL pkWBse iRQHZe" style="display:none;z-index:200" id="_Ny0hZajKHuSv2roPysWswAY_18"></div>
                                        </g-popup>
                                    </span>
                                </div>
                                <div>
                                    <div class="t2vtad" id="hdtb-tls" aria-controls="hdtbMenus" aria-expanded="false" role="button" tabindex="0" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ2x96BAgBEA0">Công cụ</div>
                                </div>
                            </div>
                            <ol class="pdswFd" role="none">
                                <li class="hdtb-mitem">
                                    <div class="nr7I6e">
                                        <span jscontroller="nabPbb" data-ffp="false" jsaction="KyPa0e:Y0y4c;BVfjhf:VFzweb;wjOG7e:gDkf4c;">
                                            <g-popup jsname="V68bde" jscontroller="DPreE" jsaction="A05xBd:IYtByb;EOZ57e:WFrRFb;" jsdata="mVjAjf;_;ANVEfk">
                                                <div jsname="oYxtQd" class="CcNe6e" aria-expanded="false" aria-haspopup="true" role="button" tabindex="0" jsaction="WFrRFb;keydown:uYT2Vb">
                                                    <div jsname="LgbsSe" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ7KcKegQIARAP">
                                                        <g-dropdown-button class="fFI3rb NkCsjc">
                                                            <g-dropdown-menu-button-caption class="S7TGef BBwThe" style="font-weight:normal" jscontroller="EbPKJf" data-ddph="" jsaction="rcuQ6b:npT2md">
                                                                <span jsname="vs0Yb">
                                                                    <div class="F75bid">
                                                                        Tìm kiếm an toàn
                                                                        <span class="MmOzS z1asCe K1bG5d" style="height:20px;line-height:20px;width:20px">
                                                                            <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                <path d="M7 10l5 5 5-5z"></path>
                                                                            </svg>
                                                                        </span>
                                                                    </div>
                                                                </span>
                                                            </g-dropdown-menu-button-caption>
                                                        </g-dropdown-button>
                                                    </div>
                                                </div>
                                                <div jsname="V68bde" class="UjBGL pkWBse iRQHZe" style="display:none;z-index:200" id="_Ny0hZajKHuSv2roPysWswAY_25"></div>
                                            </g-popup>
                                        </span>
                                    </div>
                                </li>
                            </ol>
                        </div>
                        <div class="Lj8KXd p4DDCd" data-st-cnt="stb" id="hdtbMenus" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ3B96BAgBEBc">
                            <div class="muaC1e" id="tn_1"></div>
                        </div>
                    </div>
                </div>
                <div id="before-appbar"></div>
                <div class="gTMtLb fp-nh" id="lb"></div>
                <div class="appbar" data-st-cnt="top" id="appbar">
                    <div jscontroller="rlTQBf" data-st-tgt="top" jsaction="rcuQ6b:npT2md">
                        <style>
                            .WE0UJf.NyYcvd {
                                height: 43px
                            }

                            .LHJvCe {
                                color: #70757a;
                                display: flex;
                                justify-content: space-between;
                                -webkit-transition: all 220ms ease-in-out;
                                line-height: 43px;
                                min-width: 652px;
                                position: absolute;
                                top: 0
                            }

                            #result-stats {
                                overflow: hidden;
                                text-overflow: ellipsis;
                                white-space: nowrap;
                                font-family: Google Sans,arial,sans-serif;
                                padding-top: 0;
                                padding-bottom: 0;
                                padding-right: 8px;
                            }

                            @keyframes loading-pulse {
                                from {
                                    opacity: 0.2
                                }

                                to {
                                    opacity: 1
                                }
                            }

                            .OvQkSb {
                                border-radius: 9999px
                            }

                            sentinel {
                            }
                        </style>
                        <div id="extabar">
                            <div style="position:relative">
                                <div class="WE0UJf NyYcvd" id="slim_appbar">
                                    <div class="LHJvCe">
                                        <div id="result-stats">
                                            Khoảng 3.990.000 kết quả<nobr>(0,31 giây)&nbsp;</nobr>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div jscontroller="sYEX8b" jsname="GGAcbc" class="AeB7Sc" data-cssl="/setprefs?hl=vi&amp;prev=https://www.google.com/search?q%3Dcode%2Bmau%2Btoken%2Bgooogle%26oq%3Dcode%2Bmau%2Btoken%2Bgooogle%26gs_lcrp%3DEgZjaHJvbWUyBggAEEUYOdIBCDQxMTFqMGoxqAIAsAIA%26sourceid%3Dchrome%26ie%3DUTF-8%26pccc%3D1&amp;sig=0_xDO3A9IdJDyLMySgNKVsRhDATyU%3D&amp;cs=2" data-eif="1" data-escd="1" id="spic_1" aria-label="Cài đặt nhanh" role="dialog" tabindex="-1" jsaction="rcuQ6b:npT2md;Lhx8ef:hZ2GLc;UVNdjb;keydown:mivSOc" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQzNQJegQIBRAB"></div>
                    </div>
                </div>
                <div id="_Ny0hZajKHuSv2roPysWswAY_9"></div>
                <div data-spl="/setprefs?hl=vi&amp;prev=https://www.google.com/search?q%3Dcode%2Bmau%2Btoken%2Bgooogle%26oq%3Dcode%2Bmau%2Btoken%2Bgooogle%26gs_lcrp%3DEgZjaHJvbWUyBggAEEUYOdIBCDQxMTFqMGoxqAIAsAIA%26sourceid%3Dchrome%26ie%3DUTF-8%26pccc%3D1&amp;sig=0_xDO3A9IdJDyLMySgNKVsRhDATyU%3D&amp;cs=2" id="YUIDDb" style="display:none"></div>
                <div data-iatvcap="1" data-st-cnt="atvcap" id="atvcap"></div>
                <div class="GyAeWb" id="rcnt">
                    <div class="s6JM6d" id="center_col">
                        <style>
                            .rsGxI.Ww4FFb,.Ww4FFb {
                                background-color: #fff;
                                border-size: 0px;
                                border-radius: 0px;
                                box-shadow: 0px
                            }

                            .Ww4FFb .mnr-c,.mnr-c .Ww4FFb,.Ww4FFb .Ww4FFb {
                                box-shadow: none;
                                margin-bottom: 0px
                            }

                            .vt6azd {
                                margin: 0px 0px 8px;
                                margin: 0px 0px 30px;
                            }

                            .gL9Hy {
                                font-size: 18px
                            }

                            .spell_orig {
                                font-size: 15px
                            }

                            .p64x9c {
                                padding-top: 6px;
                                margin: 5px 0 30px 0
                            }

                            .card-section.KDCVqf {
                                font-size: medium
                            }

                            .tF2Cxc.asEBEc {
                                margin-bottom: 30px
                            }

                            .N54PNb {
                                position: relative
                            }

                            .cvP2Ce {
                                contain: layout paint;
                                overflow: hidden;
                            }

                            .kb0PBd {
                                display: block;
                                flex: 0 0 auto
                            }

                            .byrV5b {
                                -webkit-box-align: center;
                                -webkit-align-items: center;
                                align-items: center;
                                display: -webkit-box;
                                display: -webkit-flex;
                                display: flex;
                                -webkit-box-orient: horizontal;
                                -webkit-box-direction: normal;
                                -webkit-flex-direction: row;
                                flex-direction: row
                            }

                            .sBJG1d {
                                display: -webkit-box;
                                display: -webkit-flex;
                                display: flex;
                                -webkit-box-orient: horizontal;
                                -webkit-box-direction: normal;
                                -webkit-flex-direction: row;
                                flex-direction: row;
                                -webkit-box-pack: center;
                                -webkit-justify-content: center;
                                justify-content: center
                            }

                            .kDmHO {
                                -webkit-box-align: center;
                                -webkit-align-items: center;
                                align-items: center;
                                display: -webkit-box;
                                display: -webkit-flex;
                                display: flex;
                                -webkit-box-orient: vertical;
                                -webkit-box-direction: normal;
                                -webkit-flex-direction: column;
                                flex-direction: column
                            }

                            .lR4vec {
                                display: -webkit-box;
                                display: -webkit-flex;
                                display: flex;
                                -webkit-box-orient: vertical;
                                -webkit-box-direction: normal;
                                -webkit-flex-direction: column;
                                flex-direction: column;
                                -webkit-box-pack: center;
                                -webkit-justify-content: center;
                                justify-content: center
                            }

                            .xTEyc {
                                -webkit-box-align: start;
                                -webkit-align-items: start;
                                align-items: start;
                                display: -webkit-box;
                                display: -webkit-flex;
                                display: flex;
                                -webkit-box-orient: horizontal;
                                -webkit-box-direction: normal;
                                -webkit-flex-direction: row;
                                flex-direction: row
                            }

                            .OjFzvd {
                                display: -webkit-box;
                                display: -webkit-flex;
                                display: flex;
                                -webkit-box-orient: horizontal;
                                -webkit-box-direction: normal;
                                -webkit-flex-direction: row;
                                flex-direction: row;
                                -webkit-box-pack: start;
                                -webkit-justify-content: start;
                                justify-content: start
                            }

                            .YIPhrb {
                                -webkit-box-align: start;
                                -webkit-align-items: start;
                                align-items: start;
                                display: -webkit-box;
                                display: -webkit-flex;
                                display: flex;
                                -webkit-box-orient: vertical;
                                -webkit-box-direction: normal;
                                -webkit-flex-direction: column;
                                flex-direction: column
                            }

                            .BToiNc {
                                display: -webkit-box;
                                display: -webkit-flex;
                                display: flex;
                                -webkit-box-orient: vertical;
                                -webkit-box-direction: normal;
                                -webkit-flex-direction: column;
                                flex-direction: column;
                                -webkit-box-pack: start;
                                -webkit-justify-content: start;
                                justify-content: start
                            }

                            .E4bmEc .Va021 {
                                -webkit-box-flex: 1;
                                -webkit-flex: 1 1 100%;
                                flex: 1 1 100%
                            }

                            .E4bmEc .Y76LGf {
                                -webkit-box-flex: 1;
                                -webkit-flex: 1 1 calc(50% - 4px);
                                flex: 1 1 calc(50% - 4px)
                            }

                            sentinel {
                            }

                            a:hover h3.LC20lb {
                                text-decoration: underline
                            }

                            .M8OgIe .dG2XIf .fm06If .LC20lb,.n6SJS h3.LC20lb {
                                overflow: hidden;
                                text-overflow: ellipsis;
                                white-space: nowrap;
                                width: 100%
                            }

                            .LC20lb {
                                display: inline-block;
                                line-height: 1.3;
                                margin-bottom: 3px;
                            }

                            .DKV0Md {
                                padding-top: 4px;
                                padding-top: 5px;
                            }

                            .DKV0Md {
                                margin-top: 18px;
                            }

                            .VjDLd .TieM1d .tjvcx,.IVvPP .tjvcx,.kno-kp .tjvcx,.VjDLd .kp-wholepage-osrp .tjvcx,#rhs .ss6qqb .tjvcx,#rhs .trNcde .tjvcx {
                                display: inline-block;
                                height: 19px;
                                overflow-y: hidden
                            }

                            .TbwUpd.ojE3Fb {
                                display: flex;
                                padding: 0;
                                align-items: center;
                                padding-bottom: 0
                            }

                            .GvPZzd {
                                font-size: 12px;
                                line-height: 18px;
                            }

                            .VuuXrf {
                                color: #202124;
                                font-size: 14px;
                                display: block;
                                line-height: 20px;
                                white-space: nowrap;
                            }

                            .DDKf1c {
                                margin-right: 12px;
                            }

                            .UnOTSe img {
                                border: 1px solid #ecedef;
                                background-color: #f1f3f4;
                                border-radius: 50%;
                            }

                            .Vwoesf:not(.oRVWZ) {
                                display: inline-block
                            }

                            .Vwoesf {
                                vertical-align: middle
                            }

                            .XNo5Ab.XNo5Ab {
                                display: block;
                            }

                            .Jj3Uob {
                                color: #0060f0;
                            }

                            .ob9lvb {
                                color: #4d5156
                            }

                            .dyjrff {
                                color: #4d5156
                            }

                            .B6fmyf {
                                position: absolute;
                                top: 0;
                                height: 0;
                                visibility: hidden;
                                white-space: nowrap
                            }

                            .B6fmyf.Mg1HEd {
                                height: auto
                            }

                            .eFM0qc {
                                display: inline-flex;
                                padding-bottom: 2px;
                                padding-top: 1px;
                                padding-left: 2px;
                                visibility: visible;
                                align-items: center
                            }

                            .eFM0qc.BCF2pd {
                                align-items: center;
                                display: flex;
                                padding-top: 0;
                                padding-bottom: 0;
                                padding-left: 0;
                            }

                            .csDOgf {
                                display: inline;
                                visibility: visible
                            }

                            .csDOgf.BCF2pd.ezY6nb,.csDOgf.L48a4c {
                                height: 18px
                            }

                            .csDOgf {
                                margin-left: 8px;
                                position: relative
                            }

                            .csDOgf.L48a4c {
                                margin-top: 16px
                            }

                            .IjabWd {
                                margin-left: 2px
                            }

                            .xTFaxe {
                                top: 2px
                            }

                            .xTFaxe {
                                color: #4d5156
                            }

                            .D6lY4c {
                                height: 22px;
                                width: 22px;
                                position: absolute;
                                border-radius: 11px
                            }

                            .iTPLzd {
                                cursor: pointer;
                                top: 0;
                                line-height: 16px
                            }

                            .iTPLzd {
                                left: 0;
                                width: 28px
                            }

                            .iTPLzd {
                                z-index: 1
                            }

                            sentinel {
                            }

                            .rNSxBe {
                                padding-bottom: 20px
                            }

                            sentinel {
                            }

                            .eY4mx {
                                padding-left: 12px
                            }

                            sentinel {
                            }

                            .lUn2nc {
                                padding-right: 12px
                            }

                            sentinel {
                            }

                            .yXK7lf em {
                                color: #5f6368
                            }

                            .yXK7lf a:visited em,.yXK7lf a em {
                                color: inherit
                            }

                            .W8l4ac {
                                padding-top: 0;
                                margin-bottom: 0
                            }

                            .yDYNvb.lyLwlc {
                                color: #4d5156
                            }

                            .lEBKkf {
                                display: -webkit-box;
                                -webkit-box-orient: vertical;
                                overflow: hidden
                            }

                            .gEBHYd {
                                padding-top: 0;
                                margin-bottom: 0
                            }

                            .lhLbod {
                                color: #70757a;
                            }

                            .H9lube {
                                background-color: #f1f3f4;
                                border: 1px solid #ecedef;
                                border-radius: 50%;
                                display: inline-flex;
                                justify-content: center;
                                align-items: center;
                                height: 26px;
                                width: 26px;
                                margin-right: 12px;
                                vertical-align: middle;
                            }

                            .fJOpI.H9lube {
                                background-color: #e2eeff;
                                border: 1px solid #e2eeff
                            }

                            .eqA2re.NjwKYd {
                                margin-right: 0
                            }
                        </style>
                        <div id="taw">
                            <div id="oFNiHe" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQL3oECAcQAg">
                                <p class="p64x9c card-section KDCVqf" aria-level="3" role="heading" id="fprs">
                                    <span class="gL9Hy">Đang hiển thị kết quả cho</span>
                                    <a id="fprsl" class="gL9Hy" href="/search?sca_esv=571531489&amp;q=code+mau+token+google&amp;spell=1&amp;sa=X&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQkeECKAB6BAgIEAE" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQkeECKAB6BAgIEAE">
                                        code mau token 
                                        <b>
                                            <i>google</i>
                                        </b>
                                    </a>
                                    <script nonce="N4ljJHxWoJx3pKoWtd5YIw">
                                        (function() {
                                            var q = 'code mau token google';
                                            var fprsl = document.getElementById('fprsl');
                                            fprsl.onclick = function(e) {
                                                var orig = document.getElementsByName('q')[0].value;
                                                if (google.ac && google.ac.ou) {
                                                    google.ac.ou(q);
                                                } else {
                                                    document.getElementsByName('q')[0].value = q;
                                                }
                                                document.getElementById("fprs").outerHTML = '';
                                                document.title = document.title.replace(orig, q);
                                                google.log('', '&ved=' + fprsl.dataset['ved'], '', fprsl);
                                                e.preventDefault();
                                            }
                                            ;
                                        }
                                        )();
                                    </script>
                                    <br>
                                    <span class="spell_orig">Tìm kiếm thay thế cho</span>
                                    <a class="spell_orig" href="/search?sca_esv=571531489&amp;q=code+mau+token+gooogle&amp;nfpr=1&amp;sa=X&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQvgUoAXoECAgQAg">code mau token gooogle</a>
                                    <br>
                                </p>
                            </div>
                            <div id="tvcap"></div>
                        </div>
                        <div class="eqAnXb" id="res" role="main">
                            <div id="topstuff"></div>
                            <div id="search">
                                <div data-hveid="CAcQBA" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQGnoECAcQBA">
                                    <h1 class="bNg8Rb OhScic zsYMMe BBwThe" style="clip:rect(1px,1px,1px,1px);height:1px;overflow:hidden;position:absolute;white-space:nowrap;width:1px;z-index:-1000;-webkit-user-select:none">Kết quả tìm kiếm</h1>
                                    <div class="v7W49e" eid="Ny0hZajKHuSv2roPysWswAY" data-async-context="query:code%20mau%20token%20google" id="rso">
                                        <h2 class="bNg8Rb OhScic zsYMMe BBwThe" style="clip:rect(1px,1px,1px,1px);height:1px;overflow:hidden;position:absolute;white-space:nowrap;width:1px;z-index:-1000;-webkit-user-select:none">Kết quả chính</h2>
                                        <div class="MjjYud">
                                            <div jscontroller="SC7lYd" class="g Ww4FFb vt6azd tF2Cxc asEBEc" lang="vi" style="width:600px" jsaction="QyLbLe:OMITjf;ewaord:qsYrDe;xd28Mb:A6j43c" data-hveid="CAoQAA" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFSgAegQIChAA">
                                                <div class="N54PNb BToiNc cvP2Ce" data-snc="ih6Jnb_wBlsFe">
                                                    <div class="kb0PBd cvP2Ce jGGQ5e" data-snf="x5WNvb" data-snhf="0">
                                                        <div class="yuRUbf">
                                                            <div>
                                                                <span jscontroller="msmzHf" jsaction="rcuQ6b:npT2md;PYDNKe:bLV6Bd;mLt3mc">
                                                                    <a jsname="UWckNb" href="https://support.haravan.com/support/solutions/articles/42000087477-c%C3%A1ch-l%E1%BA%A5y-m%C3%A3-google-api-key" jscontroller="M9mgyc" jsaction="rcuQ6b:npT2md" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFnoECAkQAQ" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://support.haravan.com/support/solutions/articles/42000087477-c%25C3%25A1ch-l%25E1%25BA%25A5y-m%25C3%25A3-google-api-key&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFnoECAkQAQ">
                                                                        <br>
                                                                        <h3 class="LC20lb MBeuO DKV0Md">Cách lấy mã Google API Key</h3>
                                                                        <div class="notranslate TbwUpd NJjxre iUh30 ojE3Fb">
                                                                            <span class="DDKf1c">
                                                                                <div class="eqA2re UnOTSe Vwoesf" aria-hidden="true">
                                                                                    <img class="XNo5Ab" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAMAAABF0y+mAAAAXVBMVEVHcEwlwW8lwW8lwW8lwW8lwW8lwW8lwW8dwGslwW8lwW8lwW8lwW8lwW8ewGwBvGD///8VvmdLx4DE7NT2/vt40pwCuVk2w3Td9Oez5sjK7tlZyodBxHmS27Cl4bwcr5CdAAAADXRSTlMADtW/nmbthvwxSCR2SJX01gAAAOBJREFUKJG10tuygyAMBVA89TLaCkSQi9b+/2ceTdCmlNfut7ImTNxUiB+nr//Gd9qBExfM/bIup3HsTqu/7cI0B2qPzLCnX2peQnh5+ETaBRYdty3oGTjSoDLWO6XcplfJELeRq55wxMWgGOKtKgaHZ3KyXr6Rbl2iwzMJdvpGM+HhuhbQaL2oUT6t1hzbE80HNoi3MvaIDS0ZbMJILaRq6RPAHzWBM67U+36Zn+eY6qvOF2tT13JH6imtc+R+PSIAFVvzP0n20NyEqG7cGpFlOLntqtyO6eHRPZq+IMX8AyHmGxSKzk/3AAAAAElFTkSuQmCC" style="height:26px;width:26px" alt="">
                                                                                </div>
                                                                            </span>
                                                                            <div>
                                                                                <span class="VuuXrf">Haravan</span>
                                                                                <div class="byrV5b">
                                                                                    <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                        https://support.haravan.com<span class="dyjrff ob9lvb" role="text">› solutions › articles › 4...</span>
                                                                                    </cite>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                    </a>
                                                                </span>
                                                                <div class="B6fmyf byrV5b Mg1HEd">
                                                                    <div class="TbwUpd iUh30 ojE3Fb">
                                                                        <span class="DDKf1c">
                                                                            <div class="eqA2re UnOTSe" style="height:26px;width:26px"></div>
                                                                        </span>
                                                                        <div>
                                                                            <span class="VuuXrf">Haravan</span>
                                                                            <div class="byrV5b">
                                                                                <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                    https://support.haravan.com<span class="dyjrff ob9lvb" role="text">› solutions › articles › 4...</span>
                                                                                </cite>
                                                                                <div class="eFM0qc BCF2pd iUh30"></div>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                    <div class="csDOgf BCF2pd L48a4c">
                                                                        <div jscontroller="exgaYe" data-bsextraheight="0" data-isdesktop="true" jsdata="l7Bhpb;_;ANVEf4 cECq7c;_;ANVEf8" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ2esEegQICRAJ">
                                                                            <div role="button" tabindex="0" jsaction="RvIhPd" jsname="I3kE2c" class="iTPLzd rNSxBe lUn2nc" style="position:absolute" aria-label="Thông tin về kết quả này">
                                                                                <span jsname="czHhOd" class="D6lY4c mBswFe">
                                                                                    <span jsname="Bil8Ae" class="xTFaxe z1asCe" style="height:18px;line-height:18px;width:18px" jsportable="sass-ported">
                                                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                            <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                                                        </svg>
                                                                                    </span>
                                                                                </span>
                                                                            </div>
                                                                            <span jsname="zOVa8" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQh-4GegQICRAK"></span>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="1" data-snf="nke7rc">
                                                        <div class="VwiC3b yXK7lf lyLwlc yDYNvb W8l4ac lEBKkf" style="-webkit-line-clamp:2">
                                                            <span class="lhLbod gEBHYd">
                                                                <span>18 thg 11, 2022</span>
                                                                — 
                                                            </span>
                                                            <span>
                                                                1. Tạo <em>Google</em>
                                                                App · 2. Tạo giấy giới thiệu · 3. Tạo <em>Google</em>
                                                                API cho <em>Google</em>
                                                                Maps · 4. Tạo API để đăng nhập bằng tài khoản <em>Google</em>
                                                                ...
                                                            </span>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="2" data-snf="mCCBcf">
                                                        <div class="fG8Fp uo4vr"></div>
                                                    </div>
                                                </div>
                                            </div>
                                            <span id="z9PoV"></span>
                                            <script nonce="N4ljJHxWoJx3pKoWtd5YIw">
                                                (function() {
                                                    var uer = false;
                                                    var eid = 'z9PoV';
                                                    (function() {
                                                        var a = google.c.wh0
                                                          , b = google.c.frt
                                                          , c = google.c.frvt
                                                          , d = google.c.whu;
                                                        var e = uer
                                                          , f = Date.now()
                                                          , g = google.c.sxs ? "load2" : "load";
                                                        if (google.timers && google.timers[g].t) {
                                                            var h = 0;
                                                            if (eid) {
                                                                var k = document.getElementById(eid);
                                                                k && (h = Math.floor(k.getBoundingClientRect().top + window.pageYOffset))
                                                            }
                                                            b && google.tick(g, "frt", f);
                                                            c && google.tick(g, "frvt", f);
                                                            google.tick(g, "frts", f);
                                                            h && google.c.e(g, "frtp", String(h));
                                                            d && !google.c.wh && (google.c.wh = Math.floor(window.innerHeight || document.documentElement.clientHeight));
                                                            var l = google.c.wh, m;
                                                            m = a && !l ? !1 : h >= l;
                                                            for (var n = document.getElementsByTagName("img"), p = 0, q = void 0; q = n[p++]; )
                                                                google.c.setup(q, !0, h);
                                                            google.c.bofr = !1;
                                                            m && google.c.ubr(!1, f, h, !e)
                                                        }
                                                        ;
                                                    }
                                                    ).call(this);
                                                }
                                                )();
                                            </script>
                                        </div>
                                        <div class="MjjYud">
                                            <div jscontroller="SC7lYd" class="g Ww4FFb vt6azd tF2Cxc asEBEc" lang="vi" style="width:600px" jsaction="QyLbLe:OMITjf;ewaord:qsYrDe;xd28Mb:A6j43c" data-hveid="CAwQAA" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFSgAegQIDBAA">
                                                <div class="N54PNb BToiNc cvP2Ce" data-snc="ih6Jnb_FxjAsf">
                                                    <div class="kb0PBd cvP2Ce jGGQ5e" data-snf="x5WNvb" data-snhf="0">
                                                        <div class="yuRUbf">
                                                            <div>
                                                                <span jscontroller="msmzHf" jsaction="rcuQ6b:npT2md;PYDNKe:bLV6Bd;mLt3mc">
                                                                    <a jsname="UWckNb" href="https://viblo.asia/p/thao-tac-voi-google-drive-api-znmMd050Mr69" jscontroller="M9mgyc" jsaction="rcuQ6b:npT2md" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFnoECAsQAQ" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://viblo.asia/p/thao-tac-voi-google-drive-api-znmMd050Mr69&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFnoECAsQAQ">
                                                                        <br>
                                                                        <h3 class="LC20lb MBeuO DKV0Md">Thao tác với Google Drive API</h3>
                                                                        <div class="notranslate TbwUpd NJjxre iUh30 ojE3Fb">
                                                                            <span class="DDKf1c">
                                                                                <div class="eqA2re UnOTSe Vwoesf" aria-hidden="true">
                                                                                    <img class="XNo5Ab" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAMAAABF0y+mAAAALVBMVEVHcEz///9Yisd4n9GbuN2zyeVkksuEqNXQ3/Bfjspxm89qls2Cp9T///9RhsbBbjkPAAAADnRSTlMAAv63PiDTcBHwm7VcBc6HIQAAAADaSURBVCiRdZKLFoQgCESB1dJq5/8/d1HBR7XTyQI8eIciJqYqZi53eZhKTEEke6EWOYsEqpuJNuCaixewEVmLFgzVzV0Z2qYrCDKP8ACO90g3RYEkj5MAsfPqegK7G9mB0wotEYzP2IOlDX+DWEb35S8t07BefsIqpZBKsbDN/Lvq7C3cSnGOrjGPCkUNElCLFduvadpN+8j1l5RbLaeRW5BK22nIk6LUU+Nrsdi/fVi34m6utdSYdfnmhkN8t1LgYghhSSz/4kTf8+nz0Jh9xEPDUJSH/rid9APurgl6gy/N8gAAAABJRU5ErkJggg==" style="height:26px;width:26px" alt="">
                                                                                </div>
                                                                            </span>
                                                                            <div>
                                                                                <span class="VuuXrf">Viblo</span>
                                                                                <div class="byrV5b">
                                                                                    <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                        https://viblo.asia<span class="dyjrff ob9lvb" role="text">› ...</span>
                                                                                    </cite>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                    </a>
                                                                </span>
                                                                <div class="B6fmyf byrV5b Mg1HEd">
                                                                    <div class="TbwUpd iUh30 ojE3Fb">
                                                                        <span class="DDKf1c">
                                                                            <div class="eqA2re UnOTSe" style="height:26px;width:26px"></div>
                                                                        </span>
                                                                        <div>
                                                                            <span class="VuuXrf">Viblo</span>
                                                                            <div class="byrV5b">
                                                                                <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                    https://viblo.asia<span class="dyjrff ob9lvb" role="text">› ...</span>
                                                                                </cite>
                                                                                <div class="eFM0qc BCF2pd iUh30"></div>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                    <div class="csDOgf BCF2pd L48a4c">
                                                                        <div jscontroller="exgaYe" data-bsextraheight="0" data-isdesktop="true" jsdata="l7Bhpb;_;ANVEfw cECq7c;_;ANVEf0" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ2esEegQICxAJ">
                                                                            <div role="button" tabindex="0" jsaction="RvIhPd" jsname="I3kE2c" class="iTPLzd rNSxBe lUn2nc" style="position:absolute" aria-label="Thông tin về kết quả này">
                                                                                <span jsname="czHhOd" class="D6lY4c mBswFe">
                                                                                    <span jsname="Bil8Ae" class="xTFaxe z1asCe" style="height:18px;line-height:18px;width:18px" jsportable="sass-ported">
                                                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                            <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                                                        </svg>
                                                                                    </span>
                                                                                </span>
                                                                            </div>
                                                                            <span jsname="zOVa8" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQh-4GegQICxAK"></span>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="1" data-snf="nke7rc">
                                                        <div class="VwiC3b yXK7lf lyLwlc yDYNvb W8l4ac lEBKkf" style="-webkit-line-clamp:2">
                                                            <span>
                                                                Việc sử dụng gem <em>google</em>
                                                                -api-client giúp chúng ta không cần phải thao tác trực tiếp với <em>token</em>
                                                                ... Bài viết trên đã mô tả các bước thực hiện, có <em>code mẫu</em>
                                                                cũng như ...
                                                            </span>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="2" data-snf="mCCBcf">
                                                        <div class="fG8Fp uo4vr"></div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="MjjYud">
                                            <div jscontroller="SC7lYd" class="g Ww4FFb vt6azd tF2Cxc asEBEc" lang="vi" style="width:600px" jsaction="QyLbLe:OMITjf;ewaord:qsYrDe;xd28Mb:A6j43c" data-hveid="CBIQAA" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFSgAegQIEhAA">
                                                <div class="N54PNb BToiNc cvP2Ce" data-snc="ih6Jnb_BQuIwe">
                                                    <div class="kb0PBd cvP2Ce jGGQ5e" data-snf="x5WNvb" data-snhf="0">
                                                        <div class="yuRUbf">
                                                            <div>
                                                                <span jscontroller="msmzHf" jsaction="rcuQ6b:npT2md;PYDNKe:bLV6Bd;mLt3mc">
                                                                    <a jsname="UWckNb" href="https://g.suite.vn/index.php?rp=/knowledgebase/8/huong-dan-tao-g-suite-transfer-token.html" jscontroller="M9mgyc" jsaction="rcuQ6b:npT2md" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFnoECBAQAQ" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://g.suite.vn/index.php%3Frp%3D/knowledgebase/8/huong-dan-tao-g-suite-transfer-token.html&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFnoECBAQAQ">
                                                                        <br>
                                                                        <h3 class="LC20lb MBeuO DKV0Md">Hướng dẫn tạo G Suite Transfer Token - Kiến thức chung</h3>
                                                                        <div class="notranslate TbwUpd NJjxre iUh30 ojE3Fb">
                                                                            <span class="H9lube fJOpI">
                                                                                <div class="eqA2re NjwKYd Vwoesf" aria-hidden="true">
                                                                                    <span class="Jj3Uob XNo5Ab z1asCe" style="height:18px;line-height:18px;width:18px" jsportable="sass-ported">
                                                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                            <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 17.93c-3.95-.49-7-3.85-7-7.93 0-.62.08-1.21.21-1.79L9 15v1c0 1.1.9 2 2 2v1.93zm6.9-2.54c-.26-.81-1-1.39-1.9-1.39h-1v-3c0-.55-.45-1-1-1H8v-2h2c.55 0 1-.45 1-1V7h2c1.1 0 2-.9 2-2v-.41c2.93 1.19 5 4.06 5 7.41 0 2.08-.8 3.97-2.1 5.39z"></path>
                                                                                        </svg>
                                                                                    </span>
                                                                                </div>
                                                                            </span>
                                                                            <div>
                                                                                <span class="VuuXrf">suite.vn</span>
                                                                                <div class="byrV5b">
                                                                                    <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                        https://g.suite.vn<span class="dyjrff ob9lvb" role="text">› huong-dan-tao-g-suite-transfer-token</span>
                                                                                    </cite>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                    </a>
                                                                </span>
                                                                <div class="B6fmyf byrV5b Mg1HEd">
                                                                    <div class="TbwUpd iUh30 ojE3Fb">
                                                                        <span class="H9lube fJOpI">
                                                                            <div class="eqA2re NjwKYd" style="height:18px;width:18px"></div>
                                                                        </span>
                                                                        <div>
                                                                            <span class="VuuXrf">suite.vn</span>
                                                                            <div class="byrV5b">
                                                                                <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                    https://g.suite.vn<span class="dyjrff ob9lvb" role="text">› huong-dan-tao-g-suite-transfer-token</span>
                                                                                </cite>
                                                                                <div class="eFM0qc BCF2pd iUh30"></div>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                    <div class="csDOgf BCF2pd L48a4c">
                                                                        <div jscontroller="exgaYe" data-bsextraheight="0" data-isdesktop="true" jsdata="l7Bhpb;_;ANVEgA cECq7c;_;ANVEgI" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ2esEegQIEBAJ">
                                                                            <div role="button" tabindex="0" jsaction="RvIhPd" jsname="I3kE2c" class="iTPLzd rNSxBe lUn2nc" style="position:absolute" aria-label="Thông tin về kết quả này">
                                                                                <span jsname="czHhOd" class="D6lY4c mBswFe">
                                                                                    <span jsname="Bil8Ae" class="xTFaxe z1asCe" style="height:18px;line-height:18px;width:18px" jsportable="sass-ported">
                                                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                            <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                                                        </svg>
                                                                                    </span>
                                                                                </span>
                                                                            </div>
                                                                            <span jsname="zOVa8" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQh-4GegQIEBAK"></span>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="1" data-snf="nke7rc">
                                                        <div class="VwiC3b yXK7lf lyLwlc yDYNvb W8l4ac lEBKkf" style="-webkit-line-clamp:2">
                                                            <span>
                                                                Để tạo được Transfer <em>Token</em>
                                                                bạn cần làm theo các bước sau: Bước 1: Truy cập trang https://admin.<em>google</em>
                                                                .com/TransferToken. Bước 2: Đăng nhập với tài khoản ...
                                                            </span>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="2" data-snf="mCCBcf">
                                                        <div class="fG8Fp uo4vr"></div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="MjjYud">
                                            <div jscontroller="SC7lYd" class="g Ww4FFb vt6azd tF2Cxc asEBEc" lang="vi" style="width:600px" jsaction="QyLbLe:OMITjf;ewaord:qsYrDe;xd28Mb:A6j43c" data-hveid="CBMQAA" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFSgAegQIExAA">
                                                <div class="N54PNb BToiNc cvP2Ce" data-snc="ih6Jnb_XhzCwf">
                                                    <div class="kb0PBd cvP2Ce jGGQ5e" data-snf="x5WNvb" data-snhf="0">
                                                        <div class="yuRUbf">
                                                            <div>
                                                                <span jscontroller="msmzHf" jsaction="rcuQ6b:npT2md;PYDNKe:bLV6Bd;mLt3mc">
                                                                    <a jsname="UWckNb" href="https://viblo.asia/p/tim-hieu-doi-chut-ve-oauth2-eW65GvMLlDO" jscontroller="M9mgyc" jsaction="rcuQ6b:npT2md" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFnoECA8QAQ" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://viblo.asia/p/tim-hieu-doi-chut-ve-oauth2-eW65GvMLlDO&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFnoECA8QAQ">
                                                                        <br>
                                                                        <h3 class="LC20lb MBeuO DKV0Md">Tìm hiểu đôi chút về OAuth2</h3>
                                                                        <div class="notranslate TbwUpd NJjxre iUh30 ojE3Fb">
                                                                            <span class="DDKf1c">
                                                                                <div class="eqA2re UnOTSe Vwoesf" aria-hidden="true">
                                                                                    <img class="XNo5Ab" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAMAAABF0y+mAAAALVBMVEVHcEz///9Yisd4n9GbuN2zyeVkksuEqNXQ3/Bfjspxm89qls2Cp9T///9RhsbBbjkPAAAADnRSTlMAAv63PiDTcBHwm7VcBc6HIQAAAADaSURBVCiRdZKLFoQgCESB1dJq5/8/d1HBR7XTyQI8eIciJqYqZi53eZhKTEEke6EWOYsEqpuJNuCaixewEVmLFgzVzV0Z2qYrCDKP8ACO90g3RYEkj5MAsfPqegK7G9mB0wotEYzP2IOlDX+DWEb35S8t07BefsIqpZBKsbDN/Lvq7C3cSnGOrjGPCkUNElCLFduvadpN+8j1l5RbLaeRW5BK22nIk6LUU+Nrsdi/fVi34m6utdSYdfnmhkN8t1LgYghhSSz/4kTf8+nz0Jh9xEPDUJSH/rid9APurgl6gy/N8gAAAABJRU5ErkJggg==" style="height:26px;width:26px" alt="">
                                                                                </div>
                                                                            </span>
                                                                            <div>
                                                                                <span class="VuuXrf">Viblo</span>
                                                                                <div class="byrV5b">
                                                                                    <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                        https://viblo.asia<span class="dyjrff ob9lvb" role="text">› ...</span>
                                                                                    </cite>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                    </a>
                                                                </span>
                                                                <div class="B6fmyf byrV5b Mg1HEd">
                                                                    <div class="TbwUpd iUh30 ojE3Fb">
                                                                        <span class="DDKf1c">
                                                                            <div class="eqA2re UnOTSe" style="height:26px;width:26px"></div>
                                                                        </span>
                                                                        <div>
                                                                            <span class="VuuXrf">Viblo</span>
                                                                            <div class="byrV5b">
                                                                                <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                    https://viblo.asia<span class="dyjrff ob9lvb" role="text">› ...</span>
                                                                                </cite>
                                                                                <div class="eFM0qc BCF2pd iUh30"></div>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                    <div class="csDOgf BCF2pd L48a4c">
                                                                        <div jscontroller="exgaYe" data-bsextraheight="0" data-isdesktop="true" jsdata="l7Bhpb;_;ANVEgE cECq7c;_;ANVEgM" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ2esEegQIDxAJ">
                                                                            <div role="button" tabindex="0" jsaction="RvIhPd" jsname="I3kE2c" class="iTPLzd rNSxBe lUn2nc" style="position:absolute" aria-label="Thông tin về kết quả này">
                                                                                <span jsname="czHhOd" class="D6lY4c mBswFe">
                                                                                    <span jsname="Bil8Ae" class="xTFaxe z1asCe" style="height:18px;line-height:18px;width:18px" jsportable="sass-ported">
                                                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                            <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                                                        </svg>
                                                                                    </span>
                                                                                </span>
                                                                            </div>
                                                                            <span jsname="zOVa8" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQh-4GegQIDxAK"></span>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="1" data-snf="nke7rc">
                                                        <div class="VwiC3b yXK7lf lyLwlc yDYNvb W8l4ac lEBKkf" style="-webkit-line-clamp:2">
                                                            <span>
                                                                Access <em>token</em>
                                                                chỉ được sử dụng một lần duy nhất, khi nó hết hiệu lực Client sẽ phải gửi lại yêu cầu đến Authorization server để lấy một mã access <em>token</em>
                                                                mới.
                                                            </span>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="2" data-snf="mCCBcf">
                                                        <div class="fG8Fp uo4vr"></div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="MjjYud">
                                            <span class="oUAcPd" id="fld_1"></span>
                                            <script nonce="N4ljJHxWoJx3pKoWtd5YIw">
                                                (function() {
                                                    var uer = false;
                                                    var eid = 'fld_1';
                                                    (function() {
                                                        var a = google.c.wh0
                                                          , b = google.c.whu;
                                                        var c = uer
                                                          , d = Date.now()
                                                          , e = google.c.sxs ? "load2" : "load";
                                                        if (google.timers && google.timers[e].t) {
                                                            var f = 0;
                                                            if (eid) {
                                                                var g = document.getElementById(eid);
                                                                g && (f = Math.floor(g.getBoundingClientRect().top + window.pageYOffset))
                                                            }
                                                            b && !google.c.wh && (google.c.wh = Math.floor(window.innerHeight || document.documentElement.clientHeight));
                                                            var h = google.c.wh, k;
                                                            k = a && !h ? !1 : f >= h;
                                                            for (var l = document.getElementsByTagName("img"), m = 0, n = void 0; n = l[m++]; )
                                                                google.c.setup(n, !1, f);
                                                            k && google.c.ubr(!1, d, f, !c)
                                                        }
                                                        ;
                                                    }
                                                    ).call(this);
                                                }
                                                )();
                                            </script>
                                            <style>
                                                .ULSxyf {
                                                    margin-bottom: 44px
                                                }

                                                .hlcw0c {
                                                    margin-bottom: 44px
                                                }

                                                .z3HNkc {
                                                    background-image: url("data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 23.44 19'><polygon fill='%23dadce0' points='10,15.27 16.18,19 14.54,11.97 20,7.24 12.81,6.63 10,0 7.19,6.63 0,7.24 5.46,11.97 3.82,19'/></svg>");
                                                    background-repeat: repeat-x;
                                                    display: inline-block;
                                                    overflow: hidden;
                                                    position: relative
                                                }

                                                .z3HNkc span {
                                                    background-image: url("data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 23.44 19'><polygon fill='%23fbbc04' points='10,15.27 16.18,19 14.54,11.97 20,7.24 12.81,6.63 10,0 7.19,6.63 0,7.24 5.46,11.97 3.82,19'/></svg>");
                                                    background-repeat: repeat-x;
                                                    display: block
                                                }

                                                .aNmOgc .z3HNkc span {
                                                    background-color: currentcolor;
                                                    background-image: unset;
                                                    -webkit-mask-image: url("data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 23.44 19'><polygon points='10,15.27 16.18,19 14.54,11.97 20,7.24 12.81,6.63 10,0 7.19,6.63 0,7.24 5.46,11.97 3.82,19'/></svg>");
                                                    mask-image: url("data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 23.44 19'><polygon points='10,15.27 16.18,19 14.54,11.97 20,7.24 12.81,6.63 10,0 7.19,6.63 0,7.24 5.46,11.97 3.82,19'/></svg>");
                                                    -webkit-mask-repeat: repeat-x;
                                                    mask-repeat: repeat-x;
                                                    -webkit-mask-size: 14px 11.4px;
                                                    mask-size: 14px 11.4px
                                                }

                                                .z3HNkc.YMYLUd span {
                                                    background-color: currentcolor;
                                                    background-image: unset;
                                                    -webkit-mask-image: url("data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 23.44 19'><polygon points='10,15.27 16.18,19 14.54,11.97 20,7.24 12.81,6.63 10,0 7.19,6.63 0,7.24 5.46,11.97 3.82,19'/></svg>");
                                                    mask-image: url("data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 23.44 19'><polygon points='10,15.27 16.18,19 14.54,11.97 20,7.24 12.81,6.63 10,0 7.19,6.63 0,7.24 5.46,11.97 3.82,19'/></svg>");
                                                    -webkit-mask-repeat: repeat-x;
                                                    mask-repeat: repeat-x;
                                                    -webkit-mask-size: 14px 11.4px;
                                                    mask-size: 14px 11.4px
                                                }

                                                .z3HNkc,.z3HNkc span {
                                                    background-size: 14px 11.4px;
                                                    height: 11.4px;
                                                    width: 68px
                                                }

                                                sentinel {
                                                }

                                                .oIk2Cb {
                                                    margin: 0
                                                }

                                                .y6Uyqe {
                                                    margin-left: -8px;
                                                    margin-right: -8px;
                                                    padding: 6px 0 0 0
                                                }

                                                .kfsfbe.kfsfbe {
                                                    padding: 0 0 8px
                                                }

                                                .adDDi {
                                                    display: flex;
                                                    position: relative;
                                                    flex-wrap: wrap;
                                                    padding: 0 0 12px;
                                                    margin: 0 0
                                                }

                                                .T6zPgb {
                                                    min-width: 0
                                                }

                                                .YC72Wc {
                                                    max-width: calc(100% - 22px)
                                                }

                                                .mgAbYb {
                                                    display: block;
                                                    white-space: nowrap
                                                }

                                                .YR2tRd {
                                                    position: relative;
                                                    align-self: center;
                                                    height: 22px
                                                }

                                                .EIaa9b {
                                                    display: flex
                                                }

                                                .AJLUJb {
                                                    display: flex;
                                                    flex: 1;
                                                    flex-direction: column
                                                }

                                                .gduDCb {
                                                    margin-left: 12px
                                                }

                                                sentinel {
                                                }

                                                .R0xfCb {
                                                    margin-bottom: 4px;
                                                    margin-top: 4px
                                                }

                                                .k8XOCe {
                                                    align-items: center;
                                                    background-color: #f1f3f4;
                                                    border-radius: 100px;
                                                    box-sizing: border-box;
                                                    display: flex;
                                                    max-height: none;
                                                    min-height: 48px;
                                                    padding-left: 17px;
                                                    padding-right: 17px;
                                                    position: relative
                                                }

                                                .k8XOCe:hover,.k8XOCe:active {
                                                    color: #202124
                                                }

                                                .s75CSd {
                                                    -webkit-box-orient: vertical;
                                                    color: #202124;
                                                    display: -webkit-box;
                                                    flex: 1;
                                                    font-size: 16px;
                                                    -webkit-line-clamp: 2;
                                                    max-width: 227px;
                                                    overflow-wrap: break-word;
                                                    overflow: hidden
                                                }

                                                .aXBZVd {
                                                    background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='24' height='24' viewBox='0 0 24 24'%3E%3Cpath fill='rgba(0,0,0,.54)' d='M20.49 19l-5.73-5.73C15.53 12.2 16 10.91 16 9.5 16 5.91 13.09 3 9.5 3S3 5.91 3 9.5 5.91 16 9.5 16c1.41 0 2.7-.47 3.77-1.24L19 20.49 20.49 19zM5 9.5C5 7.01 7.01 5 9.5 5S14 7.01 14 9.5 11.99 14 9.5 14 5 11.99 5 9.5z'/%3E%3C/svg%3E");
                                                    background-position: center;
                                                    background-repeat: no-repeat;
                                                    background-size: 20px;
                                                    height: 20px;
                                                    padding: 10px;
                                                    width: 20px
                                                }

                                                .VCOFK {
                                                    margin-left: 8px;
                                                    margin-right: 8px
                                                }

                                                sentinel {
                                                }

                                                .s8bAkb {
                                                    padding-bottom: 0px;
                                                    padding-top: 0px
                                                }

                                                sentinel {
                                                }

                                                .unhzXb {
                                                    border-radius: 4px
                                                }

                                                sentinel {
                                                }

                                                .r2fjmd {
                                                    margin-bottom: 0px;
                                                    margin-top: 0px
                                                }

                                                sentinel {
                                                }

                                                .u60jwe {
                                                    margin-right: 0px
                                                }

                                                sentinel {
                                                }

                                                .z1asCe.kQdGHd,.WqQeqc.kQdGHd {
                                                    position: absolute
                                                }

                                                .WZH4jc {
                                                    text-align: center
                                                }

                                                .WZH4jc .VknLRd {
                                                    pointer-events: none
                                                }

                                                .WZH4jc .VknLRd:hover,.WZH4jc .VknLRd:hover h3 {
                                                    text-decoration: none
                                                }

                                                .WZH4jc .GNJvt {
                                                    background: #f1f3f4;
                                                    border: 1px solid rgba(255,255,255,0);
                                                    box-sizing: border-box;
                                                    cursor: pointer;
                                                    font-size: 14px;
                                                    line-height: 20px;
                                                    pointer-events: auto;
                                                    position: relative;
                                                    width: 300px;
                                                    padding: 7px 11px;
                                                    margin: 0;
                                                    flex-direction: row-reverse;
                                                    align-items: center;
                                                    display: flex;
                                                    justify-content: center;
                                                    margin-left: auto;
                                                    margin-right: auto;
                                                    height: 36px;
                                                    border-radius: 18px
                                                }

                                                .WZH4jc .VknLRd:hover .GNJvt {
                                                    background: #D8D7DC
                                                }

                                                .WZH4jc .kQdGHd {
                                                    position: relative;
                                                    left: 0
                                                }

                                                .WZH4jc .OTvAmd {
                                                    display: block
                                                }

                                                .WZH4jc .RVQdVd {
                                                    line-height: 20px;
                                                    margin-right: 8px
                                                }

                                                .KXbwLb {
                                                    background-color: #dadce0;
                                                    border: 0;
                                                    height: 1px;
                                                    left: 0;
                                                    margin-top: 18px;
                                                    position: absolute;
                                                    width: 100%
                                                }

                                                .QjmzCd {
                                                    text-align: center;
                                                    margin: 25px 0;
                                                    height: 30px
                                                }

                                                .w7LJsc {
                                                    height: 45px;
                                                    margin-bottom: 28px
                                                }

                                                .GNJvt {
                                                    display: block;
                                                    background-color: #f1f3f4;
                                                    text-align: center;
                                                    font-size: 14px;
                                                    color: #202124;
                                                    border-radius: 20px;
                                                    height: 24px;
                                                    line-height: 24px;
                                                    border: 1px solid rgba(255,255,255,0);
                                                    padding: 8px 13px;
                                                    margin: 16px 16px 40px 16px;
                                                }

                                                .RVQdVd {
                                                    line-height: 24px
                                                }

                                                .kQdGHd {
                                                    color: #70757a;
                                                    left: 13px;
                                                    position: absolute
                                                }

                                                .GNJvt:active {
                                                    background: #e6e6e6
                                                }

                                                .VknLRd {
                                                    -webkit-tap-highlight-color: transparent;
                                                    display: block
                                                }

                                                .ipz2Oe {
                                                    position: relative
                                                }
                                            </style>
                                            <div jscontroller="SC7lYd" class="g Ww4FFb vt6azd tF2Cxc asEBEc" lang="vi" style="width:600px" jsaction="QyLbLe:OMITjf;ewaord:qsYrDe;xd28Mb:A6j43c" data-hveid="CCgQAA" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFSgAegQIKBAA">
                                                <div class="N54PNb BToiNc cvP2Ce" data-snc="ih6Jnb_HWiU2e">
                                                    <div class="kb0PBd cvP2Ce jGGQ5e" data-snf="x5WNvb" data-snhf="0">
                                                        <div class="yuRUbf">
                                                            <div>
                                                                <span jscontroller="msmzHf" jsaction="rcuQ6b:npT2md;PYDNKe:bLV6Bd;mLt3mc">
                                                                    <a jsname="UWckNb" href="http://manuals.ts24.com.vn/support/solutions/articles/16000145545-t%E1%BA%A1o-access-token" jscontroller="M9mgyc" jsaction="rcuQ6b:npT2md" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFnoECBoQAQ" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=http://manuals.ts24.com.vn/support/solutions/articles/16000145545-t%25E1%25BA%25A1o-access-token&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFnoECBoQAQ">
                                                                        <br>
                                                                        <h3 class="LC20lb MBeuO DKV0Md">Tạo Access Token - Hướng dẫn sử dụng</h3>
                                                                        <div class="notranslate TbwUpd NJjxre iUh30 ojE3Fb">
                                                                            <span class="DDKf1c">
                                                                                <div class="eqA2re UnOTSe Vwoesf" aria-hidden="true">
                                                                                    <img class="XNo5Ab" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAMAAABF0y+mAAAAXVBMVEVHcEwlwW8lwW8lwW8lwW8lwW8lwW8lwW8dwGslwW8lwW8lwW8lwW8lwW8ewGwBvGD///8VvmdLx4DE7NT2/vt40pwCuVk2w3Td9Oez5sjK7tlZyodBxHmS27Cl4bwcr5CdAAAADXRSTlMADtW/nmbthvwxSCR2SJX01gAAAOBJREFUKJG10tuygyAMBVA89TLaCkSQi9b+/2ceTdCmlNfut7ImTNxUiB+nr//Gd9qBExfM/bIup3HsTqu/7cI0B2qPzLCnX2peQnh5+ETaBRYdty3oGTjSoDLWO6XcplfJELeRq55wxMWgGOKtKgaHZ3KyXr6Rbl2iwzMJdvpGM+HhuhbQaL2oUT6t1hzbE80HNoi3MvaIDS0ZbMJILaRq6RPAHzWBM67U+36Zn+eY6qvOF2tT13JH6imtc+R+PSIAFVvzP0n20NyEqG7cGpFlOLntqtyO6eHRPZq+IMX8AyHmGxSKzk/3AAAAAElFTkSuQmCC" style="height:26px;width:26px" alt="">
                                                                                </div>
                                                                            </span>
                                                                            <div>
                                                                                <span class="VuuXrf">TS24</span>
                                                                                <div class="byrV5b">
                                                                                    <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                        http://manuals.ts24.com.vn<span class="dyjrff ob9lvb" role="text">› solutions › articles › 16...</span>
                                                                                    </cite>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                    </a>
                                                                </span>
                                                                <div class="B6fmyf byrV5b Mg1HEd">
                                                                    <div class="TbwUpd iUh30 ojE3Fb">
                                                                        <span class="DDKf1c">
                                                                            <div class="eqA2re UnOTSe" style="height:26px;width:26px"></div>
                                                                        </span>
                                                                        <div>
                                                                            <span class="VuuXrf">TS24</span>
                                                                            <div class="byrV5b">
                                                                                <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                    http://manuals.ts24.com.vn<span class="dyjrff ob9lvb" role="text">› solutions › articles › 16...</span>
                                                                                </cite>
                                                                                <div class="eFM0qc BCF2pd iUh30"></div>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                    <div class="csDOgf BCF2pd L48a4c">
                                                                        <div jscontroller="exgaYe" data-bsextraheight="0" data-isdesktop="true" jsdata="l7Bhpb;_;ANVEgY cECq7c;_;ANVEgg" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ2esEegQIGhAJ">
                                                                            <div role="button" tabindex="0" jsaction="RvIhPd" jsname="I3kE2c" class="iTPLzd rNSxBe lUn2nc" style="position:absolute" aria-label="Thông tin về kết quả này">
                                                                                <span jsname="czHhOd" class="D6lY4c mBswFe">
                                                                                    <span jsname="Bil8Ae" class="xTFaxe z1asCe" style="height:18px;line-height:18px;width:18px" jsportable="sass-ported">
                                                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                            <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                                                        </svg>
                                                                                    </span>
                                                                                </span>
                                                                            </div>
                                                                            <span jsname="zOVa8" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQh-4GegQIGhAK"></span>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="1" data-snf="nke7rc">
                                                        <div class="VwiC3b yXK7lf lyLwlc yDYNvb W8l4ac lEBKkf" style="-webkit-line-clamp:2">
                                                            <span>
                                                                Lập hồ sơ từ <em>Google</em>
                                                                Forms | Tải tập tin <em>mẫu</em>
                                                                về Drive · Lập hồ sơ từ <em>Google</em>
                                                                ... (*) Chuỗi mã Access <em>Token</em>
                                                                này chỉ xuất hiện 1 lần duy nhất; sau khi đóng bảng ...
                                                            </span>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="2" data-snf="mCCBcf">
                                                        <div class="fG8Fp uo4vr"></div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="MjjYud">
                                            <div jscontroller="SC7lYd" class="g Ww4FFb vt6azd tF2Cxc asEBEc" lang="vi" style="width:600px" jsaction="QyLbLe:OMITjf;ewaord:qsYrDe;xd28Mb:A6j43c" data-hveid="CDAQAA" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFSgAegQIMBAA">
                                                <div class="N54PNb BToiNc cvP2Ce" data-snc="ih6Jnb_vyVcFf">
                                                    <div class="kb0PBd cvP2Ce jGGQ5e" data-snf="x5WNvb" data-snhf="0">
                                                        <div class="yuRUbf">
                                                            <div>
                                                                <span jscontroller="msmzHf" jsaction="rcuQ6b:npT2md;PYDNKe:bLV6Bd;mLt3mc">
                                                                    <a jsname="UWckNb" href="https://duthanhduoc.com/blog/p5-giai-ngo-authentication-OAuth2" jscontroller="M9mgyc" jsaction="rcuQ6b:npT2md" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFnoECCIQAQ" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://duthanhduoc.com/blog/p5-giai-ngo-authentication-OAuth2&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFnoECCIQAQ">
                                                                        <br>
                                                                        <h3 class="LC20lb MBeuO DKV0Md">[P5] Giải ngố authentication: OAuth 2.0</h3>
                                                                        <div class="notranslate TbwUpd NJjxre iUh30 ojE3Fb">
                                                                            <span class="H9lube">
                                                                                <div class="eqA2re NjwKYd Vwoesf" aria-hidden="true">
                                                                                    <img class="XNo5Ab" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAMAAABEpIrGAAAANlBMVEVHcEz/OGD/OGD/OGDyNl33N17JMlFoKDRSJy+DKzwGIh8AIh2dLkThNVgjIyQ4JSmyMEoTIyHettbgAAAABXRSTlMAQdH/+9TDsAgAAADOSURBVHgB3JJLEsQgCEST8FUE9f6XHeIik81k9ukqFORhu3Db9gN+6tizj/Ag3LcDHnVs8EevAogQc8sViWgldAdYRLUwFFVJcZFM+AZgteZhzCzWR3M1yRhfgCIrtQYgVpKX2qCY3CysOmgt4DpzznukXdUvMCwA4gQiOPnZneQOnNe5pc2o6qsk77NdAGp6Npu4WgBqBcYMvoCkB/cYq7We3DwDLoBr9DlHzvbz2C16zCQvgBDQCVKOy5KyfOOH+YwCBQSzHsHMSzD7AwCw8xFBj0eQZQAAAABJRU5ErkJggg==" style="height:18px;width:18px" alt="">
                                                                                </div>
                                                                            </span>
                                                                            <div>
                                                                                <span class="VuuXrf">Dư Thanh Được</span>
                                                                                <div class="byrV5b">
                                                                                    <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                        https://duthanhduoc.com<span class="dyjrff ob9lvb" role="text">› blog › p5-giai-ngo-authent...</span>
                                                                                    </cite>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                    </a>
                                                                </span>
                                                                <div class="B6fmyf byrV5b Mg1HEd">
                                                                    <div class="TbwUpd iUh30 ojE3Fb">
                                                                        <span class="H9lube">
                                                                            <div class="eqA2re NjwKYd" style="height:18px;width:18px"></div>
                                                                        </span>
                                                                        <div>
                                                                            <span class="VuuXrf">Dư Thanh Được</span>
                                                                            <div class="byrV5b">
                                                                                <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                    https://duthanhduoc.com<span class="dyjrff ob9lvb" role="text">› blog › p5-giai-ngo-authent...</span>
                                                                                </cite>
                                                                                <div class="eFM0qc BCF2pd iUh30"></div>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                    <div class="csDOgf BCF2pd L48a4c">
                                                                        <div jscontroller="exgaYe" data-bsextraheight="0" data-isdesktop="true" jsdata="l7Bhpb;_;ANVEg4 cECq7c;_;ANVEg8" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ2esEegQIIhAJ">
                                                                            <div role="button" tabindex="0" jsaction="RvIhPd" jsname="I3kE2c" class="iTPLzd rNSxBe lUn2nc" style="position:absolute" aria-label="Thông tin về kết quả này">
                                                                                <span jsname="czHhOd" class="D6lY4c mBswFe">
                                                                                    <span jsname="Bil8Ae" class="xTFaxe z1asCe" style="height:18px;line-height:18px;width:18px" jsportable="sass-ported">
                                                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                            <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                                                        </svg>
                                                                                    </span>
                                                                                </span>
                                                                            </div>
                                                                            <span jsname="zOVa8" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQh-4GegQIIhAK"></span>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="1" data-snf="nke7rc">
                                                        <div class="VwiC3b yXK7lf lyLwlc yDYNvb W8l4ac lEBKkf" style="-webkit-line-clamp:2">
                                                            <span class="lhLbod gEBHYd">
                                                                <span>20 thg 6, 2023</span>
                                                                — 
                                                            </span>
                                                            <span>
                                                                Server sẽ lấy được giá trị <em>code</em>
                                                                thông qua query và tiến hành gọi lên <em>Google</em>
                                                                API để lấy thông tin id_token và access_token . Server sẽ lấy thông ...
                                                            </span>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="2" data-snf="mCCBcf">
                                                        <div class="fG8Fp uo4vr"></div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="MjjYud">
                                            <div jscontroller="SC7lYd" class="g Ww4FFb vt6azd tF2Cxc asEBEc" lang="vi" style="width:600px" jsaction="QyLbLe:OMITjf;ewaord:qsYrDe;xd28Mb:A6j43c" data-hveid="CC4QAA" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFSgAegQILhAA">
                                                <div class="N54PNb BToiNc cvP2Ce" data-snc="ih6Jnb_MrWAff">
                                                    <div class="kb0PBd cvP2Ce jGGQ5e" data-snf="x5WNvb" data-snhf="0">
                                                        <div class="yuRUbf">
                                                            <div>
                                                                <span jscontroller="msmzHf" jsaction="rcuQ6b:npT2md;PYDNKe:bLV6Bd;mLt3mc">
                                                                    <a jsname="UWckNb" href="https://autoitvn.com/threads/get-access_token-authorization-oauth-2-0-ho-tro-tuong-tac-google-apis-nhu-gmail-youtube.631/" jscontroller="M9mgyc" jsaction="rcuQ6b:npT2md" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFnoECCAQAQ" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://autoitvn.com/threads/get-access_token-authorization-oauth-2-0-ho-tro-tuong-tac-google-apis-nhu-gmail-youtube.631/&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFnoECCAQAQ">
                                                                        <br>
                                                                        <h3 class="LC20lb MBeuO DKV0Md">UDF - Get access_token - Authorization (oAuth 2.0) hỗ trợ ...</h3>
                                                                        <div class="notranslate TbwUpd NJjxre iUh30 ojE3Fb">
                                                                            <span class="DDKf1c">
                                                                                <div class="eqA2re UnOTSe Vwoesf" aria-hidden="true">
                                                                                    <img class="XNo5Ab" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAMAAABEpIrGAAAA7VBMVEUAYpYAYZUAXpIYeq8jjcMuodkhisAqmNAAZpo5sesdgrcnk8oIaZ4AYpUAZ5sAYZYAX5UAaJssfKkldaI9gakUeacpg64cfqsFcaGErsaKlJZfm75xor5FirGq0+3D4PTF0OTrlJivyNj+lZX0jZDlztPCnKumtbxLTk3b5+2Uq7axwcqnqKe/w8SYzvH+//98v+r/JCH/1dP/i4v/AAD/n53omZ9nqMeMnaTB0Niap62IiIatr7C/wMGAg4Os1eT/ZWT/dnb+Ojrup6yYu9AAXJNaWlecm5mtvcWUw9+LoLrSnqm+vcvPvMOZsr/0HH/2AAABAklEQVR4AczPxVYEMRAF0PcyljmdieDuzhZd4/r/uLu70xTurLlxT+EfosJnn8dKpD5PJT6vJxL36u73G+JkAhmFP6goHf21gUYpwz83EMwhh98Za4w2Bp/R4Znz3tNJwTsC9Lw7hgWO8mMF3qZIXBzjSQwCPkvuZSOcGTJWfLIp8V5lgK2YoC+iIGTxfYf05FhYOyF8rkoeOPIkDklHHvljt8kQq/28uywVOpujsJfIO4LA/fTSyd29OVbl8SHCrIHw5W11bcNS2oerSkcKRsf6m8Yn6tp6e3rbJyfLPYQeCCH4oC2cJoKzOiDooKE1njg40kmRztPI8SkJPIx+YBQAAOIANv8McO6bAAAAAElFTkSuQmCC" style="height:26px;width:26px" alt="">
                                                                                </div>
                                                                            </span>
                                                                            <div>
                                                                                <span class="VuuXrf">autoitvn.com</span>
                                                                                <div class="byrV5b">
                                                                                    <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                        https://autoitvn.com<span class="dyjrff ob9lvb" role="text">› ... › Chia sẻ mã nguồn</span>
                                                                                    </cite>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                    </a>
                                                                </span>
                                                                <div class="B6fmyf byrV5b Mg1HEd">
                                                                    <div class="TbwUpd iUh30 ojE3Fb">
                                                                        <span class="DDKf1c">
                                                                            <div class="eqA2re UnOTSe" style="height:26px;width:26px"></div>
                                                                        </span>
                                                                        <div>
                                                                            <span class="VuuXrf">autoitvn.com</span>
                                                                            <div class="byrV5b">
                                                                                <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                    https://autoitvn.com<span class="dyjrff ob9lvb" role="text">› ... › Chia sẻ mã nguồn</span>
                                                                                </cite>
                                                                                <div class="eFM0qc BCF2pd iUh30"></div>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                    <div class="csDOgf BCF2pd L48a4c">
                                                                        <div jscontroller="exgaYe" data-bsextraheight="0" data-isdesktop="true" jsdata="l7Bhpb;_;ANVEgw cECq7c;_;ANVEg0" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ2esEegQIIBAJ">
                                                                            <div role="button" tabindex="0" jsaction="RvIhPd" jsname="I3kE2c" class="iTPLzd rNSxBe lUn2nc" style="position:absolute" aria-label="Thông tin về kết quả này">
                                                                                <span jsname="czHhOd" class="D6lY4c mBswFe">
                                                                                    <span jsname="Bil8Ae" class="xTFaxe z1asCe" style="height:18px;line-height:18px;width:18px" jsportable="sass-ported">
                                                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                            <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                                                        </svg>
                                                                                    </span>
                                                                                </span>
                                                                            </div>
                                                                            <span jsname="zOVa8" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQh-4GegQIIBAK"></span>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="1" data-snf="nke7rc">
                                                        <div class="VwiC3b yXK7lf lyLwlc yDYNvb W8l4ac lEBKkf" style="-webkit-line-clamp:2">
                                                            <span class="lhLbod gEBHYd">
                                                                <span>29 thg 11, 2016</span>
                                                                — 
                                                            </span>
                                                            <span>
                                                                ... <em>google</em>
                                                                .com/identity/protocols/OAuth2WebServer. Cơ bản là ta phải Tạo Credentials &gt;oAuth Client ID &gt;Exchange <em>Code</em>
                                                                &gt;Access <em>Token</em>
                                                                *** Các ...
                                                            </span>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="2" data-snf="mCCBcf">
                                                        <div class="fG8Fp uo4vr"></div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="MjjYud">
                                            <div jscontroller="SC7lYd" class="g Ww4FFb vt6azd tF2Cxc asEBEc" lang="vi" style="width:600px" jsaction="QyLbLe:OMITjf;ewaord:qsYrDe;xd28Mb:A6j43c" data-hveid="CC0QAA" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFSgAegQILRAA">
                                                <div class="N54PNb BToiNc cvP2Ce" data-snc="ih6Jnb_BOOP0b">
                                                    <div class="kb0PBd cvP2Ce jGGQ5e" data-snf="x5WNvb" data-snhf="0">
                                                        <div class="yuRUbf">
                                                            <div>
                                                                <span jscontroller="msmzHf" jsaction="rcuQ6b:npT2md;PYDNKe:bLV6Bd;mLt3mc">
                                                                    <a jsname="UWckNb" href="https://developers.google.com/search/apis/indexing-api/v3/core-errors?hl=vi" jscontroller="M9mgyc" jsaction="rcuQ6b:npT2md" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFnoECCkQAQ" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://developers.google.com/search/apis/indexing-api/v3/core-errors%3Fhl%3Dvi&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFnoECCkQAQ">
                                                                        <br>
                                                                        <h3 class="LC20lb MBeuO DKV0Md">Lỗi gặp phải khi sử dụng API Lập chỉ mục</h3>
                                                                        <div class="notranslate TbwUpd NJjxre iUh30 ojE3Fb">
                                                                            <span class="DDKf1c">
                                                                                <div class="eqA2re UnOTSe Vwoesf" aria-hidden="true">
                                                                                    <img class="XNo5Ab" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAMAAABF0y+mAAAAw1BMVEVHcEz////////9/f39/f79/f33+Pj////b3d74+fny8/P19vYAAAD////w8fH////////9/f3///8+fu7ZRCpBmEtNnVXaTDbbUz79/Pz0uCtIm1EqdO2FqPJplvDqpJ282MDifG87l0DW4fvXOBWqzrDvurbt8v55oPLkjIH00Mx0sHuRvpVpq3BrrHL2wEn51Y/4zHbw6eP4uBf86MP0sw6EpvJEhdRSie50prrFrCrsrqfqkSrssavxrDPP48yyx/Yvv4yqAAAAEnRSTlMAWZFT48ytmAumbmsCSV/Uv52LM4rJAAABN0lEQVQokY2SiXKCMBCGEUHBW5qQhGgRKopn7zq9ff+n6mZLNIAz7T/OZDdf8rO7xrL+p749Gg5Hdv8CsoOT7ApqBCU1TNYOKmrX2DpereJ1hf56LhhhjBHCFqazh0lCOOeMwW8e44Z3Nk0Y52TO+ZyQxDRGT7hH3kUQiDjRRSnWVMEH4+ShUnGzcH16/CKfl9pxYb2LomehNvLp9AWULyF2ATqw3kfRLZ6eXKEmNxA7f0Fti/BaCaC2HWNBUTjThRwBqnWsW3mTIS1aWYJtrlvBIWQ0DCne/T4Un8QhWL6K9hIo3e1pKg+TqdrxjcHv4G4o4YhMX43BW11MspRKKSlNM0y7+g9tYSpm281mO8NJBa3zU2hV52owy+oIE4lO+fl5/gkL36s93N7Adx3H9Qe9GioOlNMflcoty3IDwqwAAAAASUVORK5CYII=" style="height:26px;width:26px" alt="">
                                                                                </div>
                                                                            </span>
                                                                            <div>
                                                                                <span class="VuuXrf">Google</span>
                                                                                <div class="byrV5b">
                                                                                    <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                        https://developers.google.com<span class="dyjrff ob9lvb" role="text">› apis › core-errors</span>
                                                                                    </cite>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                    </a>
                                                                </span>
                                                                <div class="B6fmyf byrV5b Mg1HEd">
                                                                    <div class="TbwUpd iUh30 ojE3Fb">
                                                                        <span class="DDKf1c">
                                                                            <div class="eqA2re UnOTSe" style="height:26px;width:26px"></div>
                                                                        </span>
                                                                        <div>
                                                                            <span class="VuuXrf">Google</span>
                                                                            <div class="byrV5b">
                                                                                <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                    https://developers.google.com<span class="dyjrff ob9lvb" role="text">› apis › core-errors</span>
                                                                                </cite>
                                                                                <div class="eFM0qc BCF2pd iUh30"></div>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                    <div class="csDOgf BCF2pd L48a4c">
                                                                        <div jscontroller="exgaYe" data-bsextraheight="0" data-isdesktop="true" jsdata="l7Bhpb;_;ANVEhA cECq7c;_;ANVEhE" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ2esEegQIKRAJ">
                                                                            <div role="button" tabindex="0" jsaction="RvIhPd" jsname="I3kE2c" class="iTPLzd rNSxBe lUn2nc" style="position:absolute" aria-label="Thông tin về kết quả này">
                                                                                <span jsname="czHhOd" class="D6lY4c mBswFe">
                                                                                    <span jsname="Bil8Ae" class="xTFaxe z1asCe" style="height:18px;line-height:18px;width:18px" jsportable="sass-ported">
                                                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                            <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                                                        </svg>
                                                                                    </span>
                                                                                </span>
                                                                            </div>
                                                                            <span jsname="zOVa8" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQh-4GegQIKRAK"></span>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="1" data-snf="nke7rc">
                                                        <div class="VwiC3b yXK7lf lyLwlc yDYNvb W8l4ac lEBKkf" style="-webkit-line-clamp:2">
                                                            <span>
                                                                Hãy khám phá danh sách thông báo và nội dung mô tả lỗi liên quan đến API Lập chỉ mục, ngoài các lỗi chính áp dụng cho mọi API của <em>Google</em>
                                                                .
                                                            </span>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="2" data-snf="mCCBcf">
                                                        <div class="fG8Fp uo4vr"></div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="MjjYud">
                                            <div jscontroller="SC7lYd" class="g Ww4FFb vt6azd tF2Cxc asEBEc" lang="vi" style="width:600px" jsaction="QyLbLe:OMITjf;ewaord:qsYrDe;xd28Mb:A6j43c" data-hveid="CCwQAA" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFSgAegQILBAA">
                                                <div class="N54PNb BToiNc cvP2Ce" data-snc="ih6Jnb_ihz1Ze">
                                                    <div class="kb0PBd cvP2Ce jGGQ5e" data-snf="x5WNvb" data-snhf="0">
                                                        <div class="yuRUbf">
                                                            <div>
                                                                <span jscontroller="msmzHf" jsaction="rcuQ6b:npT2md;PYDNKe:bLV6Bd;mLt3mc">
                                                                    <a jsname="UWckNb" href="https://wiki.matbao.net/token-la-gi-nen-dau-tu-tien-dien-tu-coin-hay-token/" jscontroller="M9mgyc" jsaction="rcuQ6b:npT2md" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFnoECB0QAQ" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://wiki.matbao.net/token-la-gi-nen-dau-tu-tien-dien-tu-coin-hay-token/&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFnoECB0QAQ">
                                                                        <br>
                                                                        <h3 class="LC20lb MBeuO DKV0Md">Token là gì? Hướng dẫn cách cài đặt Token đơn giản nhất</h3>
                                                                        <div class="notranslate TbwUpd NJjxre iUh30 ojE3Fb">
                                                                            <span class="DDKf1c">
                                                                                <div class="eqA2re UnOTSe Vwoesf" aria-hidden="true">
                                                                                    <img class="XNo5Ab" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAMAAABF0y+mAAAAZlBMVEVHcEz0dSD0ciDzbyH0cSHzbyH0cCHzbyHzaiHzViHzbyHzbCHzbyHzayH0cCHzayH0dSDtGiTtGiTtHCTtHCTtGiTtGyTtHSTtFiTtGSTtFyTtGyTtGyPtGiTuHSPuJCPxSyLtFiSX9pSgAAAAInRSTlMAJ2Gi0eK1c0EG/1DyisgdMmO65//2154uyiKtUTuUeBCE3rA8vQAAAR5JREFUeAFlkQUShDAQBBsL7u7w/09eKtnzLqdZy/DGcT0/UGEU80cYJE88hy/STIRoPsgTISuUKvSPQQmC9yyoZLr+UH7X+SXUTdv1wziVQWb3qqRMq74T5kUpI+2aClZdNLSiNz8CUruJdsOOZmrEKqAwMqU+EGoj+9yBzBbGLwensaNLaQpztos3gyl1iaTrjvBufMo+EV8sRh4iXb6I7VD2/5e+uKRyt6fwgcsuM/f8t7RKOYzciW/f2BChVNAZLjiixKBsSGF2cRvXAOVQSZy+5ykdpEzsJjRHc+mlBBWzWLdiaOe4Upk2mVfBZl0fy119d0J8xRKYYUG4Wp39XW/12IrqJ96s3RfNxSf7/FbDxi9lvQ5tO6znAsIDfC8dqjfmh44AAAAASUVORK5CYII=" style="height:26px;width:26px" alt="">
                                                                                </div>
                                                                            </span>
                                                                            <div>
                                                                                <span class="VuuXrf">matbao.net</span>
                                                                                <div class="byrV5b">
                                                                                    <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                        https://wiki.matbao.net<span class="dyjrff ob9lvb" role="text">› Hóa đơn điện tử</span>
                                                                                    </cite>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                    </a>
                                                                </span>
                                                                <div class="B6fmyf byrV5b Mg1HEd">
                                                                    <div class="TbwUpd iUh30 ojE3Fb">
                                                                        <span class="DDKf1c">
                                                                            <div class="eqA2re UnOTSe" style="height:26px;width:26px"></div>
                                                                        </span>
                                                                        <div>
                                                                            <span class="VuuXrf">matbao.net</span>
                                                                            <div class="byrV5b">
                                                                                <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                    https://wiki.matbao.net<span class="dyjrff ob9lvb" role="text">› Hóa đơn điện tử</span>
                                                                                </cite>
                                                                                <div class="eFM0qc BCF2pd iUh30"></div>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                    <div class="csDOgf BCF2pd L48a4c">
                                                                        <div jscontroller="exgaYe" data-bsextraheight="0" data-isdesktop="true" jsdata="l7Bhpb;_;ANVEgo cECq7c;_;ANVEgs" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ2esEegQIHRAJ">
                                                                            <div role="button" tabindex="0" jsaction="RvIhPd" jsname="I3kE2c" class="iTPLzd rNSxBe lUn2nc" style="position:absolute" aria-label="Thông tin về kết quả này">
                                                                                <span jsname="czHhOd" class="D6lY4c mBswFe">
                                                                                    <span jsname="Bil8Ae" class="xTFaxe z1asCe" style="height:18px;line-height:18px;width:18px" jsportable="sass-ported">
                                                                                        <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                            <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                                                        </svg>
                                                                                    </span>
                                                                                </span>
                                                                            </div>
                                                                            <span jsname="zOVa8" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQh-4GegQIHRAK"></span>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="1" data-snf="nke7rc">
                                                        <div class="VwiC3b yXK7lf lyLwlc yDYNvb W8l4ac lEBKkf" style="-webkit-line-clamp:2">
                                                            <span>
                                                                <em>Token</em>
                                                                là một loại tiền điện tử (tiền mã hóa) được tạo ra và hoạt động dựa trên một nền tảng blockchain có sẵn. Đây chỉ là định nghĩa về <em>Token</em>
                                                                . Để thực sự hiểu ...
                                                            </span>
                                                        </div>
                                                    </div>
                                                    <div class="kb0PBd cvP2Ce" data-sncf="2" data-snf="mCCBcf">
                                                        <div class="fG8Fp uo4vr">
                                                            <span aria-hidden="true" class="z3HNkc" aria-label="Được đánh giá 5,0 trên 5," role="img">
                                                                <span style="width:70px"></span>
                                                            </span>
                                                            <span>Xếp hạng: 5</span>
                                                            · ‎<span>2 phiếu bầu</span>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="hlcw0c">
                                            <div class="MjjYud">
                                                <div jscontroller="SC7lYd" class="g Ww4FFb vt6azd tF2Cxc asEBEc" lang="vi" style="width:600px" jsaction="QyLbLe:OMITjf;ewaord:qsYrDe;xd28Mb:A6j43c" data-hveid="CCsQAA" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFSgAegQIKxAA">
                                                    <div class="N54PNb BToiNc cvP2Ce" data-snc="ih6Jnb_rxnlnc">
                                                        <div class="kb0PBd cvP2Ce jGGQ5e" data-snf="x5WNvb" data-snhf="0">
                                                            <div class="yuRUbf">
                                                                <div>
                                                                    <span jscontroller="msmzHf" jsaction="rcuQ6b:npT2md;PYDNKe:bLV6Bd;mLt3mc">
                                                                        <a jsname="UWckNb" href="https://bkhost.vn/blog/oauth-2/" jscontroller="M9mgyc" jsaction="rcuQ6b:npT2md" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFnoECBsQAQ" ping="/url?sa=t&amp;source=web&amp;rct=j&amp;opi=89978449&amp;url=https://bkhost.vn/blog/oauth-2/&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQFnoECBsQAQ">
                                                                            <br>
                                                                            <h3 class="LC20lb MBeuO DKV0Md">OAuth 2 là gì? Vai trò và cách thức hoạt động của OAuth 2.0</h3>
                                                                            <div class="notranslate TbwUpd NJjxre iUh30 ojE3Fb">
                                                                                <span class="DDKf1c">
                                                                                    <div class="eqA2re UnOTSe Vwoesf" aria-hidden="true">
                                                                                        <img class="XNo5Ab" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAMAAABF0y+mAAAAaVBMVEVHcEzsHiTfJivsHiTsHiTsHiTsHiTsHiTsFBzrAADrAg/wT1P+8/P95uf5ubvwWl70gYP2nqD3q6z////1i47ya2771NXtKjDuNTrsHiTsHiTsHiRjZmdjZmdjZmdjZmdjZmdjZmdjZmd/ip02AAAAI3RSTlMAEwn/8WRO1P//////////////////////l0VVQIVYMHQXrPpkFGoAAAD/SURBVHgBfJAFAsMgDABZQ4XgpPP//3Mks/rhHBqlTps0imlgE93uSqY7kv1bDkYYpIcAKLUWOVjnKyHikJzLaLJzBUE3vUh6E81IVMyZyA9Qpf7IS74QBZHgiOxMZl5fRNZVCWEqGQ9YpeMTYCXlWOaCcxlsrMedEwnZzGQxvCtX6Xm3Xby2OKIx8bJLHZrVnW4YWV6pLsOf9MylXDF5n5Hry00i9I8tcu9Tm09sNWzDUt2P5K5Vwunx3KB7lS4WRgADIBDLMQe+/451b08bHgd+oeZ84QGkU15OZ+JmRZozqRWkrFQ9xJjNI1wSY9YUkrJenzp9HgjOpBM9wskIkEkb3ztJs50AAAAASUVORK5CYII=" style="height:26px;width:26px" alt="">
                                                                                    </div>
                                                                                </span>
                                                                                <div>
                                                                                    <span class="VuuXrf">BKHOST</span>
                                                                                    <div class="byrV5b">
                                                                                        <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                            https://bkhost.vn<span class="dyjrff ob9lvb" role="text">› Blog</span>
                                                                                        </cite>
                                                                                    </div>
                                                                                </div>
                                                                            </div>
                                                                        </a>
                                                                    </span>
                                                                    <div class="B6fmyf byrV5b Mg1HEd">
                                                                        <div class="TbwUpd iUh30 ojE3Fb">
                                                                            <span class="DDKf1c">
                                                                                <div class="eqA2re UnOTSe" style="height:26px;width:26px"></div>
                                                                            </span>
                                                                            <div>
                                                                                <span class="VuuXrf">BKHOST</span>
                                                                                <div class="byrV5b">
                                                                                    <cite class="qLRx3b tjvcx GvPZzd cHaqb" role="text">
                                                                                        https://bkhost.vn<span class="dyjrff ob9lvb" role="text">› Blog</span>
                                                                                    </cite>
                                                                                    <div class="eFM0qc BCF2pd iUh30"></div>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                        <div class="csDOgf BCF2pd L48a4c">
                                                                            <div jscontroller="exgaYe" data-bsextraheight="0" data-isdesktop="true" jsdata="l7Bhpb;_;ANVEgc cECq7c;_;ANVEgk" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ2esEegQIGxAJ">
                                                                                <div role="button" tabindex="0" jsaction="RvIhPd" jsname="I3kE2c" class="iTPLzd rNSxBe lUn2nc" style="position:absolute" aria-label="Thông tin về kết quả này">
                                                                                    <span jsname="czHhOd" class="D6lY4c mBswFe">
                                                                                        <span jsname="Bil8Ae" class="xTFaxe z1asCe" style="height:18px;line-height:18px;width:18px" jsportable="sass-ported">
                                                                                            <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                                <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                                                            </svg>
                                                                                        </span>
                                                                                    </span>
                                                                                </div>
                                                                                <span jsname="zOVa8" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQh-4GegQIGxAK"></span>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                        <div class="kb0PBd cvP2Ce" data-sncf="1" data-snf="nke7rc">
                                                            <div class="VwiC3b yXK7lf lyLwlc yDYNvb W8l4ac lEBKkf" style="-webkit-line-clamp:2">
                                                                <span class="lhLbod gEBHYd">
                                                                    <span>30 thg 7, 2022</span>
                                                                    — 
                                                                </span>
                                                                <span>
                                                                    Ở quy trình ngầm định này, Access <em>token</em>
                                                                    được Authorization Server trả lại dưới dạng callback URI biểu <em>mẫu</em>
                                                                    . Authorization <em>Code</em>
                                                                    Grant with Proof ...
                                                                </span>
                                                            </div>
                                                        </div>
                                                        <div class="kb0PBd cvP2Ce" data-sncf="2" data-snf="mCCBcf">
                                                            <div class="fG8Fp uo4vr">
                                                                <span aria-hidden="true" class="z3HNkc" aria-label="Được đánh giá 5,0 trên 5," role="img">
                                                                    <span style="width:70px"></span>
                                                                </span>
                                                                <span>Xếp hạng: 5</span>
                                                                · ‎<span>74.316 phiếu bầu</span>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div id="bottomads"></div>
                        <div id="botstuff">
                            <div data-hveid="CAIQAA" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQCHoECAIQAA">
                                <div></div>
                                <div id="bres">
                                    <div class="ULSxyf">
                                        <div class="MjjYud">
                                            <div data-abe="" data-hveid="CBUQAA" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ26YDegQIFRAA">
                                                <div class="oIk2Cb">
                                                    <div class="kfsfbe adDDi">
                                                        <div class="T6zPgb YC72Wc">
                                                            <div aria-level="2" role="heading">
                                                                <span class="mgAbYb OSrXXb RES9jf IFnjPb">Nội dung tìm kiếm khác</span>
                                                            </div>
                                                        </div>
                                                        <span class="YR2tRd">
                                                            <div jscontroller="exgaYe" data-bsextraheight="0" data-isdesktop="true" jsdata="l7Bhpb;_;ANVEgQ cECq7c;_;ANVEgU" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ2esEegQIFRAC">
                                                                <div jsaction="KyPa0e:RvIhPd;wjOG7e:edHC5b;al5F3e:edHC5b;">
                                                                    <div role="button" tabindex="0" jsaction="RvIhPd" jsname="I3kE2c" class="iTPLzd rNSxBe lUn2nc eY4mx" style="padding-right:5px;position:absolute" aria-label="Thông tin về kết quả này">
                                                                        <span jsname="czHhOd" class="D6lY4c IjabWd">
                                                                            <span jsname="Bil8Ae" class="xTFaxe z1asCe" style="height:18px;line-height:18px;width:18px" jsportable="sass-ported">
                                                                                <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                                    <path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"></path>
                                                                                </svg>
                                                                            </span>
                                                                        </span>
                                                                    </div>
                                                                    <span jsname="zOVa8" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQh-4GegQIFRAD"></span>
                                                                </div>
                                                                <g-snackbar jsname="t1F84b" jscontroller="OZLguc" style="display:none" jsshadow="" jsaction="rcuQ6b:npT2md">
                                                                    <div jsname="sM5MNb" aria-live="polite" class="LH3wG">
                                                                        <div jsname="Ng57nc" class="yK6jqe" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ4G96BAgVEAQ">
                                                                            <div class="b77HKf">
                                                                                <div class="rIxsve" jsslot="">
                                                                                    <span class="Txngnb wHYlTd yUTMj">Giờ đây, bạn sẽ thấy nhiều nội dung tiếng Anh hơn.</span>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                </g-snackbar>
                                                            </div>
                                                        </span>
                                                    </div>
                                                    <div class="y6Uyqe">
                                                        <div class="EIaa9b">
                                                            <div class="AJLUJb">
                                                                <div data-hveid="CCEQAA">
                                                                    <a class="k8XOCe R0xfCb VCOFK s8bAkb" href="/search?sca_esv=571531489&amp;q=Share+Google+Map+API+key+free&amp;sa=X&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ1QJ6BAghEAE">
                                                                        <div class="aXBZVd unhzXb"></div>
                                                                        <div class="s75CSd u60jwe r2fjmd AB4Wff">
                                                                            <b>Share Google Map API key free</b>
                                                                        </div>
                                                                    </a>
                                                                </div>
                                                                <div data-hveid="CBgQAA">
                                                                    <a class="k8XOCe R0xfCb VCOFK s8bAkb" href="/search?sca_esv=571531489&amp;q=Google+map+API+key+free+for+testing&amp;sa=X&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ1QJ6BAgYEAE">
                                                                        <div class="aXBZVd unhzXb"></div>
                                                                        <div class="s75CSd u60jwe r2fjmd AB4Wff">
                                                                            <b>Google map API key free for testing</b>
                                                                        </div>
                                                                    </a>
                                                                </div>
                                                                <div data-hveid="CB4QAA">
                                                                    <a class="k8XOCe R0xfCb VCOFK s8bAkb" href="/search?sca_esv=571531489&amp;q=C%C3%A1ch+l%E1%BA%A5y+API+key&amp;sa=X&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ1QJ6BAgeEAE">
                                                                        <div class="aXBZVd unhzXb"></div>
                                                                        <div class="s75CSd u60jwe r2fjmd AB4Wff">
                                                                            <b>Cách lấy API key</b>
                                                                        </div>
                                                                    </a>
                                                                </div>
                                                                <div data-hveid="CBwQAA">
                                                                    <a class="k8XOCe R0xfCb VCOFK s8bAkb" href="/search?sca_esv=571531489&amp;q=Google+API+Console&amp;sa=X&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ1QJ6BAgcEAE">
                                                                        <div class="aXBZVd unhzXb"></div>
                                                                        <div class="s75CSd u60jwe r2fjmd AB4Wff">
                                                                            <b>Google API Console</b>
                                                                        </div>
                                                                    </a>
                                                                </div>
                                                            </div>
                                                            <div class="AJLUJb">
                                                                <div data-hveid="CBkQAA">
                                                                    <a class="k8XOCe R0xfCb VCOFK s8bAkb" href="/search?sca_esv=571531489&amp;q=Google+API+key&amp;sa=X&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ1QJ6BAgZEAE">
                                                                        <div class="aXBZVd unhzXb"></div>
                                                                        <div class="s75CSd u60jwe r2fjmd AB4Wff">
                                                                            <b>Google API key</b>
                                                                        </div>
                                                                    </a>
                                                                </div>
                                                                <div data-hveid="CB8QAA">
                                                                    <a class="k8XOCe R0xfCb VCOFK s8bAkb" href="/search?sca_esv=571531489&amp;q=Get+API+key+Google+Map&amp;sa=X&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ1QJ6BAgfEAE">
                                                                        <div class="aXBZVd unhzXb"></div>
                                                                        <div class="s75CSd u60jwe r2fjmd AB4Wff">
                                                                            <b>Get API key Google Map</b>
                                                                        </div>
                                                                    </a>
                                                                </div>
                                                                <div data-hveid="CBYQAA">
                                                                    <a class="k8XOCe R0xfCb VCOFK s8bAkb" href="/search?sca_esv=571531489&amp;q=API+key+ChatGPT&amp;sa=X&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ1QJ6BAgWEAE">
                                                                        <div class="aXBZVd unhzXb"></div>
                                                                        <div class="s75CSd u60jwe r2fjmd AB4Wff">
                                                                            <b>API key ChatGPT</b>
                                                                        </div>
                                                                    </a>
                                                                </div>
                                                                <div data-hveid="CBcQAA">
                                                                    <a class="k8XOCe R0xfCb VCOFK s8bAkb" href="/search?sca_esv=571531489&amp;q=OAuth2+Spring+Boot&amp;sa=X&amp;ved=2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ1QJ6BAgXEAE">
                                                                        <div class="aXBZVd unhzXb"></div>
                                                                        <div class="s75CSd u60jwe r2fjmd AB4Wff">
                                                                            <b>OAuth2 Spring Boot</b>
                                                                        </div>
                                                                    </a>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div jscontroller="ogmBcd" jsname="BRTknd" jsmodel="oWVrne" class="sdjuGf" jsdata="A7MAsf;_;ANVEfU" jsaction="rcuQ6b:npT2md;Jl3rxb:VimORe;BqPbQ:p5vRo;Kf5VV:CYKeQe;lQkSke:fj32se;aLHH2d:XV6jYd;LYjNec:cyaZJ;QEvNdb:teMyNc;K6ldnc:vK2xWc;xHsTDe:PoQGh">
                                    <div jscontroller="Gg40M" jsaction="rcuQ6b:npT2md;yFBEId:dNTL7c;AnqxQb:dNTL7c;aLHH2d:yTpwFc">
                                        <div jsname="TCyEnb" aria-owns="rhs"></div>
                                        <div jsname="nZDdGd" tabindex="0"></div>
                                    </div>
                                    <div jsname="sgxt2d" data-graft-type="insert" id="arc-srp_1" data-jiis="up" data-async-type="arc" data-async-context-required="arc_id,q" class="yp" data-async-rclass="search" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQxK8CegQIAhAC"></div>
                                    <div jsname="GDPwke" class="WtZO4e"></div>
                                    <div class="WZH4jc w7LJsc" jscontroller="bpec7b" data-dt="1" jsaction="AnqxQb:eFvKib;q8sV4d:eFvKib;Rlvoif:eFvKib;yFBEId:eFvKib">
                                        <div jsname="b6rISd" class="QjmzCd" style="display:none" role="progressbar" aria-label="Đang tải..." aria-live="polite" data-hveid="CAIQAw" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ66oDegQIAhAD"></div>
                                        <h1 class="bNg8Rb OhScic zsYMMe BBwThe" style="clip:rect(1px,1px,1px,1px);height:1px;overflow:hidden;position:absolute;white-space:nowrap;width:1px;z-index:-1000;-webkit-user-select:none">Page Navigation</h1>
                                        <a class="T7sFge sW9g3e VknLRd" href="/search?q=code+mau+token+google&amp;sca_esv=571531489&amp;ei=Ny0hZajKHuSv2roPysWswAY&amp;start=10&amp;sa=N" style="transform:scale(1)" jsname="oHxHid" jsaction="qBEZuc" aria-label="Kết quả khác" data-ve-view="" role="button" data-hveid="CAIQBA" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQqq4CegQIAhAE">
                                            <hr class="KXbwLb" aria-hidden="true">
                                            <h3 aria-hidden="true">
                                                <div class="GNJvt ipz2Oe">
                                                    <span class="kQdGHd">
                                                        <span class="OTvAmd z1asCe QFl0Ff">
                                                            <svg focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                                <path d="M16.59 8.59L12 13.17 7.41 8.59 6 10l6 6 6-6z"></path>
                                                            </svg>
                                                        </span>
                                                    </span>
                                                    <span class="RVQdVd">Kết quả khác</span>
                                                </div>
                                            </h3>
                                        </a>
                                        <a jsname="a79Lwf" jsaction="nF6QQd" class="VknLRd" style="display:none" aria-live="polite" role="button" tabindex="0" data-hveid="CAIQBQ" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQvvYCegQIAhAF">
                                            <hr class="KXbwLb" aria-hidden="true">
                                            <h3>
                                                <span class="GNJvt">Thử lại</span>
                                            </h3>
                                        </a>
                                    </div>
                                    <a jsname="EvDH1d" style="display:none" data-hveid="CAIQBg" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ_skCegQIAhAG"></a>
                                </div>
                                <script nonce="N4ljJHxWoJx3pKoWtd5YIw">
                                    (function() {
                                        var showOptIn = false;
                                        var a = document.getElementsByClassName("o8xTWc")
                                          , b = document.getElementsByClassName("wxIowe");
                                        showOptIn ? (0 < a.length && a[0].classList.add("kur4we"),
                                        0 < b.length && b[0].classList.remove("kur4we")) : (0 < a.length && a[0].classList.remove("kur4we"),
                                        0 < b.length && b[0].classList.add("kur4we"));
                                    }
                                    )();
                                </script>
                            </div>
                        </div>
                        <div data-hveid="CAcQBQ" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQh6kJegQIBxAF"></div>
                        <div jscontroller="GU4Gab" style="display:none" data-pcs="0" jsaction="rcuQ6b:npT2md"></div>
                        <div role="navigation">
                            <span id="xjs"></span>
                            <div id="gfn"></div>
                            <span id="fvf"></span>
                        </div>
                    </div>
                </div>
                <style>
                    .Tg0csd {
                        bottom: 0;
                        left: 0;
                        position: fixed;
                        right: 0;
                        z-index: 129
                    }
                </style>
                <div class="Tg0csd">
                    <div jscontroller="tboZfc" jsdata="C4mkuf;_;ANVEfI" jsaction="rcuQ6b:npT2md" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQuqMJegQIBhAA"></div>
                </div>
                <div jscontroller="T5VV" data-essb="1" data-ssc="0" jsaction="rcuQ6b:npT2md"></div>
                <div jscontroller="aDVF7" data-lel="U" jsaction="rcuQ6b:npT2md"></div>
                <div jscontroller="rhYw1b" data-dmd="" data-dvt="d" jsaction="rcuQ6b:npT2md"></div>
                <style>
                    @-webkit-keyframes allow-alert {
                        from {
                            opacity: 1
                        }

                        to {
                            opacity: .35
                        }
                    }

                    .TCIIWe {
                        padding-top: 12px;
                    }

                    .yMNJR .qk7LXc {
                        max-width: 100%
                    }

                    .cJFqsd .qk7LXc {
                        height: 100%
                    }

                    .rfx2Y .qk7LXc {
                        width: 100%
                    }

                    @media (min-height: 576px) {
                        .uSolm .qk7LXc {
                            height:100%
                        }

                        .uSolm {
                            padding: 64px 0px
                        }
                    }

                    @media (max-height: 575px) {
                        .uSolm .qk7LXc {
                            height:100%;
                            max-height: 448px
                        }
                    }

                    .BhUHze .qk7LXc {
                        width: 75%
                    }

                    @media (min-height: 496px) {
                        .GeOznc .qk7LXc {
                            height:100%
                        }

                        .GeOznc {
                            padding: 24px 0px
                        }
                    }

                    @media (max-height: 495px) {
                        .GeOznc .qk7LXc {
                            height:100%;
                            max-height: 448px
                        }
                    }

                    .dgVGnc .qk7LXc {
                        width: 90%
                    }

                    .KUf18.ivkdbf {
                        background-color: rgba(0,0,0,0.6);
                        opacity: 1;
                        visibility: inherit
                    }

                    .VfsLpf.ivkdbf {
                        background-color: #000;
                        opacity: .4;
                        visibility: inherit
                    }

                    .J3Hnlf.ivkdbf {
                        background-color: #202124;
                        opacity: .7;
                        visibility: inherit
                    }

                    .X46m8.ivkdbf {
                        background-color: #000;
                        opacity: .8;
                        visibility: inherit
                    }

                    .cBoDed.ivkdbf {
                        background-color: #f8f9fa;
                        opacity: .85;
                        visibility: inherit
                    }

                    .kyk7qb.ivkdbf {
                        background-color: #202124;
                        opacity: .6;
                        visibility: inherit
                    }

                    .qk7LXc.ivkdbf {
                        opacity: 1
                    }

                    .mcPPZ.ivkdbf {
                        opacity: 1;
                        visibility: inherit
                    }

                    .mcPPZ.nP0TDe {
                        cursor: pointer
                    }

                    .mcPPZ.nP0TDe .qk7LXc {
                        cursor: default
                    }

                    .kJFf0c {
                        position: fixed;
                        z-index: 9997;
                        right: 0;
                        bottom: -200px;
                        top: 0;
                        left: 0;
                        -webkit-transition: opacity .25s;
                        transition: opacity .25s;
                        opacity: 0;
                        visibility: hidden
                    }

                    .qk7LXc {
                        display: inline-block;
                        z-index: 9997;
                        background-color: #fff;
                        opacity: 0;
                        white-space: normal;
                        overflow: hidden
                    }

                    .qk7LXc {
                        border-radius: 8px
                    }

                    .qk7LXc {
                        box-shadow: 0px 5px 26px 0px rgba(0,0,0,0.22),0px 20px 28px 0px rgba(0,0,0,0.3)
                    }

                    .qk7LXc.DJEOfc {
                        background-color: transparent
                    }

                    .qk7LXc.DJEOfc {
                        box-shadow: none
                    }

                    .qk7LXc.Fb1AKc {
                        position: relative;
                        vertical-align: middle
                    }

                    .qk7LXc.ulWzbd {
                        position: absolute
                    }

                    .qk7LXc.P1WYLb {
                        border: 1px solid #dadce0;
                        box-shadow: #dadce0
                    }

                    .mcPPZ {
                        position: fixed;
                        right: 0;
                        bottom: 0;
                        top: 0;
                        left: 0;
                        z-index: 9997;
                        vertical-align: middle;
                        visibility: hidden;
                        white-space: nowrap;
                        max-height: 100%;
                        max-width: 100%;
                        overflow-x: hidden;
                        overflow-y: auto
                    }

                    .mcPPZ.xg7rAe {
                        text-align: center
                    }

                    .mcPPZ::after {
                        content: "";
                        display: inline-block;
                        height: 100%;
                        vertical-align: middle
                    }

                    .mcPPZ {
                        tap-highlight-color: rgba(0,0,0,0)
                    }

                    .LjfRsf {
                        height: 0;
                        opacity: 0;
                        position: absolute;
                        width: 0
                    }

                    .VH47ed {
                        visibility: hidden
                    }

                    .TaoyYc {
                        overflow: hidden
                    }

                    .qk7LXc.aJPx6e {
                        overflow: visible
                    }

                    .vAJJzd {
                        opacity: .999
                    }

                    sentinel {
                    }

                    .hObAcc {
                        margin-left: 4px;
                        margin-right: 4px
                    }

                    sentinel {
                    }

                    .gTewb {
                        padding-left: 8px;
                        padding-right: 8px
                    }

                    sentinel {
                    }
                </style>
                <div id="bfoot">
                    <span style="display:none">
                        <span jscontroller="DhPYme" style="display:none" data-atsd="5" data-mmcnt="100" jsaction="rcuQ6b:npT2md"></span>
                    </span>
                </div>
                <div class="spch" style="display:none" id="spch"></div>
                <div jscontroller="YFicMc" style="display:none" jsaction="L6fTBf:SMCzH" id="sfooter" role="contentinfo" data-hveid="CAMQAA" data-ved="2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQpyp6BAgDEAA">
                    <h1 class="bNg8Rb OhScic zsYMMe BBwThe" style="clip:rect(1px,1px,1px,1px);height:1px;overflow:hidden;position:absolute;white-space:nowrap;width:1px;z-index:-1000;-webkit-user-select:none">Đường liên kết ở chân trang</h1>
                    <div id="footcnt">
                        <div class="TCIIWe" style="height:106px" id="fbarcnt">
                            <div class="f6F9Be TrMVnc" id="fbar"></div>
                        </div>
                    </div>
                </div>
                <script nonce="N4ljJHxWoJx3pKoWtd5YIw">
                    (function() {
                        var d = google.c.sxs
                          , e = google.c.wfo;
                        (function() {
                            var f = Date.now()
                              , a = d ? "load2" : "load";
                            if (google.timers && google.timers[a].t) {
                                for (var b = document.getElementsByTagName("img"), g = 0, c = void 0; c = b[g++]; )
                                    google.c.setup(c, !1, -1);
                                google.c.bofr = !1;
                                google.c.e(a, "imn", String(b.length));
                                google.c.ubr(!0, f);
                                google.c.glu && google.c.glu();
                                google.rll(window, !1, function() {
                                    google.tick(a, "ol");
                                    e && google.c.u("pr", a)
                                })
                            }
                        }
                        )();
                    }
                    ).call(this);
                </script>
            </div>
        </div>
        <script nonce="N4ljJHxWoJx3pKoWtd5YIw">
            (function() {
                for (var i in google.iir || {}) {
                    _setImagesSrc([i], google.iir[i]);
                }
                google.iir = {};
            }
            )();
            (function() {
                google.xjs = {
                    ck: 'xjs.s.MzD2MCWNgIg.L.W.O',
                    cs: 'ACT90oG3qa93mkN7bkE2I-0mHN3jIiNwyg',
                    cssopt: false,
                    csss: 'ACT90oFniOGepW-ZN0hndk3u6FRFUVYiPQ',
                    excm: ['NsEUGe', 'y25qZb', 'AD6AIb', 'fNMhz', 'bXyZdf', 'ZrXR8b', 'ABxRVc', 'rL2AR', 'yChgtb', 'vJPFse', 'JxE93', 'VZLyBe', 'U3Ovcc', 'TO0csb', 'Oa7Qpb', 'zs9f9d', 'tzTB5', 'XHo6qe', 'FmnE6b', 'jkRPje', 'PoJj8d', 'KzZUob', 'WxJ6g', 'kOSi0d', 'pOYYce', 'eTv59e', 'SKZSKc', 'T3q8Wd', 'Ok4XMd', 'Trirbc', 'hfJ9hb'],
                    sepcss: false
                };
            }
            )();
        </script>
        <!-- cctlcm 5 cctlcm -->
        <div id="_Ny0hZajKHuSv2roPysWswAY_27"></div>
        <style>
            .RTZ84b {
                color: #70757a;
                cursor: pointer;
                padding-right: 8px
            }

            .c2xzTb .RTZ84b {
                padding-top: 1px;
                padding-right: 4px
            }

            .XEKxtf {
                color: #70757a;
                float: right;
                font-size: 12px;
                line-height: 16px;
                padding-bottom: 4px
            }

            .CvDJxb.minidiv {
                margin-top: 0
            }

            #gb {
                min-width: unset;
                position: relative
            }

            .minidiv #gb {
                top: 2px
            }

            #gba {
                display: none
            }

            .Q3DXx #gb>div {
                padding-left: 0
            }

            .minidiv .RNNXgb {
                min-height: 32px;
                border-radius: 16px;
                background: #fff;
                margin: 10px 0 0;
                box-shadow: none;
                border: 1px solid #dfe1e5
            }

            .emcav.emcat .RNNXgb {
                border-bottom-left-radius: 24px;
                border-bottom-right-radius: 24px
            }

            .minidiv .emcav.emcat .RNNXgb {
                border-bottom-left-radius: 16px;
                border-bottom-right-radius: 16px
            }

            .minidiv .SDkEP {
                padding-top: 0
            }

            .FgNLaf {
                display: none
            }

            .minidiv .logo {
                padding: 0 32px
            }

            .emcav.A8SBwf.h3L8Ub {
                z-index: 989
            }

            .minidiv .iblpc {
                margin-top: 0;
                height: 32px
            }

            .CKb9sd {
                background: none;
                display: flex;
                flex: 0 0 auto
            }

            .minidiv .jfN4p {
                height: 28px;
                width: 86px
            }

            .sbfc textarea.gLFyf {
                white-space: pre-line;
                overflow-y: auto
            }

            .minidiv .gLFyf {
                padding: 0;
                line-height: 22px;
                margin-bottom: 0
            }

            .minidiv .a4bIc {
                margin-top: 5px
            }

            .gLFyf.CJxXMe {
                margin-top: 0
            }

            .VZUv6d {
                font-size: 11px;
                font-weight: bold;
                white-space: nowrap;
                color: #fff;
                line-height: 29px;
                padding: 0 10px
            }

            .minidiv .dRYYxd {
                margin-top: 0;
                height: 32px
            }

            .minidiv .vOY7J {
                line-height: 32px
            }

            .minidiv .ExCKkf {
                width: 20px
            }

            .minidiv .XDyW0e {
                line-height: 32px
            }

            .minidiv .goxjub {
                width: 20px;
                height: 20px
            }

            .minidiv .nDcEnd {
                line-height: 32px
            }

            .minidiv .Gdd5U {
                width: 20px;
                height: 20px
            }

            .minidiv .Tg7LZd {
                height: 32px;
                line-height: 32px
            }

            .minidiv .Tg7LZd .zgAlFc {
                height: 20px;
                width: 20px
            }

            .minidiv .Tg7LZd svg {
                height: 20px;
                width: 20px
            }

            .h3L8Ub .rLrQHf {
                padding-bottom: 16px
            }

            .h3L8Ub .rLrQHf {
                min-width: 47%;
                width: 47%;
                margin: 8px 16px 0
            }

            .S3nFnd {
                display: flex
            }

            .lh87ke:link,.lh87ke:visited {
                color: #1a0dab;
                cursor: pointer;
                font: 11px arial,sans-serif;
                padding: 0 5px;
                text-decoration: none;
                flex: auto;
                align-self: flex-end;
                margin: 0 16px 5px 0
            }

            .lh87ke:hover {
                text-decoration: underline
            }

            .sb27 {
                background: url(/images/searchbox/desktop_searchbox_sprites318_hr.webp) no-repeat 0 -21px;
                background-size: 20px;
                min-height: 20px;
                min-width: 20px;
                height: 20px;
                width: 20px
            }

            .sb43 {
                background: url(/images/searchbox/desktop_searchbox_sprites318_hr.webp) no-repeat 0 0;
                background-size: 20px;
                min-height: 20px;
                min-width: 20px;
                height: 20px;
                width: 20px
            }

            .sb53.sb53 {
                padding: 0 4px;
                margin: 0
            }

            .Ye4jfc {
                flex-direction: row;
                flex-wrap: wrap
            }

            .sbic.vYOkbe {
                background: center/contain no-repeat;
                border-radius: 4px;
                min-height: 32px;
                min-width: 32px;
                margin: 4px 7px 4px -5px;
            }

            .sbre .wM6W7d {
                line-height: 18px
            }

            .minidiv .wM6W7d {
                font-size: 14px
            }

            .WggQGd {
                color: #52188c
            }

            .h3L8Ub .yMAEcf {
                border-radius: 100px;
                box-sizing: border-box;
                display: flex;
                min-height: 40px;
                margin: 4px 0 4px 16px;
                width: 396px
            }

            @media (forced-colors:none) {
                .h3L8Ub .yMAEcf {
                    background: #f8f9fa
                }
            }

            .h3L8Ub .yMAEcf {
                width: fit-content
            }

            .minidiv .h3L8Ub .yMAEcf .wM6W7d {
                font-size: 16px
            }

            @media (forced-colors:none) {
                .h3L8Ub .yMAEcf.sbhl {
                    background: #e8eaed
                }
            }

            .sbhl {
                border-radius: 4px;
                background: #f8f9fa;
            }

            @media (forced-colors:active) {
                .sbhl {
                    background-color: highlight
                }
            }

            .mus_pc {
                display: block;
                margin: 6px 0
            }

            .mus_il {
                font-family: Arial,Helvetica Neue Light,Helvetica Neue,Helvetica;
                padding-top: 7px;
                position: relative
            }

            .mus_il:first-child {
                padding-top: 0
            }

            .mus_il_at {
                margin-left: 10px
            }

            .mus_il_st {
                right: 52px;
                position: absolute
            }

            .mus_il_i {
                align: left;
                margin-right: 10px
            }

            .mus_it3 {
                margin-bottom: 3px;
                max-height: 24px;
                vertical-align: bottom
            }

            .mus_it5 {
                height: 24px;
                width: 24px;
                vertical-align: bottom;
                margin-left: 10px;
                margin-right: 10px;
                transform: rotate(90deg)
            }

            .mus_tt3 {
                color: #767676;
                font-size: 12px;
                vertical-align: top
            }

            .mus_tt5 {
                color: #d93025;
                font-size: 14px
            }

            .mus_tt6 {
                color: #188038;
                font-size: 14px
            }

            .mus_tt8 {
                font-size: 16px;
                font-family: Arial,sans-serif
            }

            .mus_tt17 {
                color: #212121;
                font-size: 20px
            }

            .mus_tt18 {
                color: #212121;
                font-size: 28px
            }

            .mus_tt19 {
                color: #767676;
                font-size: 12px
            }

            .mus_tt20 {
                color: #767676;
                font-size: 14px
            }

            .mus_tt23 {
                color: #767676;
                font-size: 18px
            }

            .DJbVFb .TfeWfb {
                display: flex;
                flex-wrap: wrap;
                overflow-x: hidden;
                width: 100%;
                height: 52px
            }

            .DJbVFb .AQZ9Vd {
                display: none
            }

            .DJbVFb .xAmryf {
                border-radius: 100px;
                background-color: #fff
            }

            .DJbVFb .TfeWfb {
                padding-left: 10px;
                display: inherit
            }

            .DJbVFb .xAmryf .eL7oAc {
                display: none
            }

            .DJbVFb {
                background: #f8f9fa;
                border-radius: 20px
            }

            .DJbVFb:hover {
                background: #e8eaed
            }

            .DJbVFb .vYOkbe {
                height: 200px;
                width: 200px;
                flex-shrink: 0;
                margin: 20px 0 20px 8px;
                float: right;
                border-radius: 16px;
                background-color: #fff
            }

            .DJbVFb.sbhl {
                background: #e8eaed
            }

            .DJbVFb .ClJ9Yb {
                display: none
            }

            .DJbVFb .wM6W7d {
                flex: initial
            }

            .DJbVFb .wM6W7d span {
                text-overflow: ellipsis;
                -webkit-box-orient: vertical;
                display: -webkit-box;
                -webkit-line-clamp: 2;
                overflow: hidden
            }

            .DJbVFb .eIPGRd {
                display: flex;
                flex-direction: row-reverse;
                align-items: stretch;
                margin: 0 20px 0 14px
            }

            .DJbVFb.ytLedb .vYOkbe {
                background-color: #f8f9fa
            }

            .DJbVFb .kzCE2 {
                font-size: 16px
            }

            .DJbVFb .pcTkSc {
                margin: 20px 6px;
                padding: 0
            }

            .DJbVFb .vYOkbe {
                margin: 20px 0 20px 18px;
                background-color: #fff;
                border-radius: 20px
            }

            .DJbVFb .EOLKOc {
                width: calc(50% - 1px)
            }

            .DJbVFb .EOLKOc:first-child {
                border-bottom-left-radius: 20px
            }

            .DJbVFb .EOLKOc:last-child {
                border-bottom-right-radius: 20px
            }

            .DJbVFb .AZNDm {
                border-top-right-radius: 20px;
                border-top-left-radius: 20px
            }

            .DJbVFb .a5RLac.kzCE2 span {
                -webkit-line-clamp: 3
            }

            .DJbVFb .lnnVSe {
                margin-bottom: auto
            }

            .DJbVFb .a5RLac span {
                text-overflow: ellipsis;
                -webkit-box-orient: vertical;
                display: -webkit-box;
                -webkit-line-clamp: 2;
                overflow: hidden;
                margin-right: 10px
            }

            .xAmryf .eL7oAc {
                fill: #4d5156;
                padding-top: 1px
            }

            .xAmryf.LvqzR {
                background-color: #e8f0fe;
                cursor: pointer;
                color: #1a73e8
            }

            .xAmryf.LvqzR .eL7oAc {
                fill: #1a73e8
            }

            .Hulzgf {
            }

            .uhebGb {
                font-style: italic
            }

            .sOmPcf .ZFiwCf {
                background-color: #D8D7DC
            }

            .U48fD.df13ud {
                margin-top: 16px
            }

            .U48fD.TOQyFc {
                margin-top: 0
            }

            .U48fD.p8FEIf {
                padding-bottom: 0
            }

            .jRKCUd::before {
                bottom: 12px;
                content: '';
                left: 16px;
                position: absolute;
                right: 16px;
                top: -4px
            }

            a.jRKCUd:hover {
                text-decoration: none
            }

            .TQc1id .ZFiwCf {
                max-width: unset
            }

            .nCFUpc .ZFiwCf {
                width: 100%
            }

            .TQc1id .Bi9oQd {
                display: none
            }

            .kC8B4e .Bi9oQd {
                display: none
            }

            .JCHpcb:hover,.LvqzR .JCHpcb {
                color: #1558d6;
                text-decoration: underline
            }

            .JCHpcb {
                color: #70757a;
                font: 13px arial,sans-serif;
                cursor: pointer;
                align-self: center
            }

            .s2Wjec {
                display: block
            }

            .Q82Okf {
                font-size: 16px;
                font-family: Arial,sans-serif
            }

            .DJbVFb,.o6OF0 {
                background: #f8f9fa;
                border-radius: 20px
            }

            .o6OF0:hover,.o6OF0.LvqzR {
                background: #e7e8e9
            }

            .o6OF0 .eIPGRd {
                display: block
            }

            @media (forced-colors:none) {
                .o6OF0.sbhl {
                    background: #e7e8e9
                }
            }

            @media (forced-colors:active) {
                .o6OF0.sbhl {
                    background-color: highlight
                }
            }

            .o6OF0 .AQZ9Vd {
                display: none
            }

            .o6OF0 .sbic {
                display: none
            }

            .o6OF0 .pcTkSc {
                display: none
            }

            .o6OF0 .wM6W7d {
                display: none
            }

            .o6OF0 .eIPGRd {
                max-width: 100%;
                margin: 0
            }

            .az9Ajc {
                padding_top: 0px
            }

            .o6OF0 .SHFPkb.ZJ594e {
                padding-right: 58px
            }

            .z76Rnb.LvqzR {
                color: #202124;
                background-color: #D8D7DC
            }

            .o6OF0 .TfeWfb {
                display: flex;
                gap: 6px;
                height: 42px;
                flex-wrap: wrap;
                overflow: hidden;
                padding: 0;
                margin-top: 16px
            }

            .xAmryf.LvqzR {
                color: #202124;
                background-color: #D8D7DC
            }

            .cRV9hb .pcTkSc .ClJ9Yb.ENMKxf span {
                -webkit-line-clamp: 1
            }

            .aVbWac .sbic.vYOkbe {
                height: 90px;
                width: 90px;
                border-radius: 12px;
                margin: 0
            }

            .fLciMb {
                border-radius: 50%;
                color: #5f6368;
                cursor: pointer;
                height: 24px;
                margin-top: 4px;
                padding: 8px;
                width: 24px
            }

            .minidiv .fLciMb {
                margin-top: 6px
            }

            .fLciMb:hover {
                background-color: rgba(218,220,224,.5);
                text-decoration: none
            }

            .ZOyvub {
                visibility: hidden;
                position: absolute;
                top: 50px;
                padding: 5px 6px;
                background-color: #55524d;
                color: #f8f9fa;
                border-radius: 4px;
                font-size: 12px;
                letter-spacing: 1px;
                left: 50%;
                transform: translateX(-50%);
                width: max-content
            }

            #gb {
                height: 0;
                padding-left: 16px;
                padding-right: 16px
            }

            .hdtb-ab-o .LHJvCe {
                opacity: 0;
                top: 13px
            }

            .SknMB,.SknMB:visited {
                align-items: center;
                color: #1a73e8;
                display: flex;
                height: 40px
            }

            .ZI7elf {
                cursor: pointer;
                color: #4d5156
            }

            .q0yked {
                color: #4d5156;
                font-family: arial,sans-serif;
                margin: 0 -24px
            }

            .q0yked:hover {
                background-color: #f1f3f4
            }

            .q0yked a {
                align-items: center;
                display: flex;
                text-decoration: none;
                justify-content: space-between;
                padding: 12px 24px
            }

            .tkWDZc {
                font-family: arial,sans-serif;
                font-size: 12px;
                font-weight: 400;
                line-height: 16px
            }

            .CbAZb {
                background: #fff;
                border-bottom: 1px solid #dadce0;
                bottom: 0;
                overflow-y: auto;
                position: fixed;
                right: -360px;
                top: 0;
                width: 360px;
                font-family: Google Sans,arial,sans-serif;
            }

            .AeB7Sc {
                background: rgba(32, 33, 36, .6);
                bottom: 0;
                display: none;
                left: 0;
                overflow: hidden;
                position: fixed;
                right: 0;
                top: 0;
                z-index: 9000
            }

            .S8wJ3 {
                color: #202124;
                font-family: Google Sans,arial,sans-serif;
                font-size: 28px;
                margin-bottom: 20px;
                text-align: left
            }

            .tGS0Nc {
                border: 1px solid #dadce0;
                border-radius: 8px;
                display: block;
                font-size: 16px;
                padding: 10px;
                text-align: center
            }

            a.tGS0Nc,a:visited.tGS0Nc {
                color: #1a73e8;
                text-decoration: none
            }

            a.tGS0Nc:hover {
                background-color: rgba(26, 115, 232, .08);
                color: #1967d2
            }

            .bepeF {
                color: #5f6368;
                cursor: pointer;
                display: block;
                float: right;
                position: relative;
                top: -50px
            }

            .m0uvVb {
                font-size: 16px;
                border-top: 1px solid #dadce0;
                padding: 4px 24px 10px
            }

            .kQEH5b {
                float: right;
                cursor: pointer
            }

            .cQ2awd {
                padding: 20px 24px
            }

            .kwWBYc {
                color: #202124;
                font-family: arial,sans-serif;
                font-size: 20px;
                font-weight: normal;
                margin-bottom: 8px
            }

            .S4xgid {
                cursor: pointer;
                padding: 12px 24px
            }

            .uWNHce {
                color: #4d5156;
                display: inline-block;
                margin-left: -16px;
                margin-bottom: -16px;
                font-family: arial,sans-serif;
                width: 328px
            }

            .UCGAnb {
                flex: 1
            }

            .LZTko:hover {
                background: #f1f3f4;
                box-shadow: -56px 0 #f1f3f4,24px 0 #f1f3f4,-56px -10px 0 #f1f3f4,24px -10px 0 #f1f3f4;
                cursor: pointer
            }

            .q0yked .z1asCe {
                color: #4d5156
            }

            .UCAEse {
                height: 30px;
                margin-bottom: 5px;
                margin-top: -5px
            }

            .ogD9ue {
                align-items: center;
                display: flex
            }

            .rhJQGd {
                color: #70757a;
                margin-right: 6px
            }

            .W3aG6d {
                align-items: center;
                display: flex;
                min-height: 48px;
                margin: 0 -24px
            }

            .aoMqnc {
                animation: loading-pulse 1.25s ease-out 0s infinite alternate;
                background: #f1f3f4;
                border-radius: 4px;
                height: 24px;
                margin: 0 24px;
                opacity: 0.2;
                width: 100%
            }

            .aztjNb {
                color: #202124;
                font-size: 11px;
                font-weight: 700;
                letter-spacing: 0.3px;
                line-height: 16px;
                text-transform: uppercase
            }

            .dVmoif {
                display: flex
            }

            .RVVZab {
                background-color: #4285f4;
                border-radius: 4px;
                color: #fff;
                height: 14px;
                margin-right: 8px;
                padding: 4px
            }

            .fmxhfc {
                color: #4d5156;
                font-family: arial,sans-serif
            }

            .Z48xed {
                color: #1a73e8;
                font-size: 12px;
                margin-top: 4px
            }

            .XRZSle {
                display: flex;
                flex-direction: column
            }

            .dluk7e {
                margin-left: 48px
            }

            .GZcH3e {
                display: block
            }

            .de2Dud {
                max-width: 100%;
                position: relative
            }

            .de2Dud:focus {
                outline: none
            }

            .KNNyg {
                display: inline-block
            }

            .dsLpHe {
                border: solid 2px;
                border-color: #70757a;
                height: 12px;
                left: 16px;
                position: absolute;
                transition: border-color 0.2s;
                top: 16px;
                width: 12px
            }

            .kaAgDc {
                height: 8px;
                left: 20px;
                position: absolute;
                top: 20px;
                width: 8px;
                transform: scale(0);
                transition: transform 0.2s
            }

            .RvdoFd .kaAgDc {
                transform: scale(1)
            }

            .wT0tpe {
                height: 48px;
                opacity: 0;
                position: absolute;
                transition: opacity 0.2s;
                width: 48px;
                cursor: pointer
            }

            .r0zAxe .wT0tpe {
                opacity: .26
            }

            .qwkefd .wT0tpe {
                opacity: 0
            }

            .Tro82c .RvdoFd .kaAgDc {
                background-color: rgba(0,0,0,.26)
            }

            .Tro82c .dsLpHe {
                border-color: rgba(0,0,0,.26)
            }

            .Tro82c {
                pointer-events: none
            }

            .j0iFNe .RvdoFd .dsLpHe {
                border-color: #4285f4
            }

            .j0iFNe .kaAgDc,.j0iFNe .RvdoFd .wT0tpe,.j0iFNe .r0zAxe .wT0tpe {
                background-color: #4285f4
            }

            @media (forced-colors:active) {
                .j0iFNe .RvdoFd .dsLpHe {
                    border-color: ButtonText
                }

                .j0iFNe .kaAgDc,.j0iFNe .RvdoFd .wT0tpe,.j0iFNe .r0zAxe .wT0tpe {
                    background-color: ButtonText
                }
            }

            .H8eL7d .dluk7e {
                padding-bottom: 15px;
                padding-top: 15px
            }

            .H8eL7d .GZcH3e {
                font-size: 16px;
                line-height: 18px
            }

            .H8eL7d .de2Dud:not(:last-child) {
                margin-bottom: -16px
            }

            .wIV7Db {
                visibility: hidden
            }

            .mn51Ef {
                margin-left: 5px;
                vertical-align: text-bottom
            }

            .cF4V5c {
                background-color: #fff
            }

            .cF4V5c g-menu-item {
                display: block;
                font-size: 14px;
                line-height: 23px;
                white-space: nowrap
            }

            .cF4V5c g-menu-item a,.cF4V5c .y0fQ9c {
                display: block;
                padding-top: 4px;
                padding-bottom: 4px;
                cursor: pointer
            }

            .cF4V5c g-menu-item a,.cF4V5c g-menu-item a:visited,.cF4V5c g-menu-item a:hover {
                text-decoration: inherit;
                color: inherit
            }

            .zriOQb g-menu-item {
                color: #5f6368
            }

            .zriOQb g-menu-item a,.zriOQb .y0fQ9c {
                line-height: 16px;
                padding-top: 8px;
                padding-bottom: 8px
            }

            .hdtb-tl-sel {
                border: 1px solid #dadce0;
                box-shadow: inset 0 1px 2px 0 rgba(0,0,0,0.1);
                background: -webkit-linear-gradient(top,#f8f9fa,#dadce0);
            }

            .cdtWk {
                display: inline-block;
                line-height: 29px
            }

            .Doo7xc {
                line-height: 40px;
                width: 120px
            }

            .RVRNTb div[role="none"] {
                line-height: 36px;
                padding: 0
            }

            .RVRNTb .z4R3Z {
                padding-right: 26px;
                text-align: left;
                color: #202124
            }

            .RVRNTb .z4R3Z.yb2zA {
                color: #1a0dab
            }

            .RVRNTb a.kQyaVc,.RVRNTb a.kQyaVc:visited {
                padding: 0;
                color: #202124
            }

            .RVRNTb a.kQyaVc:hover {
                text-decoration: none;
                color: #202124
            }

            .BslMec {
                cursor: pointer;
                color: #70757a;
                font-size: 12px;
                display: block
            }

            .BpGBNe {
                vertical-align: top
            }

            .L3FBEc {
                width: 26px;
                display: inline-block
            }

            .wWjvRd {
                vertical-align: text-bottom;
                padding: 0 5px
            }

            .muaC1e {
                overflow-x: scroll;
                -ms-overflow-style: none;
                scrollbar-width: none
            }

            .muaC1e::-webkit-scrollbar {
                display: none
            }

            .Lj8KXd .QBbvme {
                margin-top: 44px
            }

            .yyoM4d {
                padding-top: 3px;
                padding-bottom: 7px;
                top: 57px
            }

            .hdtb-mn-hd {
                color: #70757a;
                display: inline-block;
                position: relative;
                padding-top: 0;
                padding-bottom: 0;
                padding-right: 18px;
                padding-left: 12px;
                line-height: 22px;
                cursor: pointer
            }

            .hdtb-mn-hd:hover {
                color: #202124
            }

            .hdtb-mn-hd:hover .gTl8xb {
                border-color: #202124 transparent
            }

            .hdtb-mn-hd:active {
                color: #1a73e8
            }

            .hdtb-mn-hd:active .gTl8xb {
                border-color: #1a73e8 transparent
            }

            .LkcePc {
                display: inline-block;
                width: var(--center-abs-margin);
            }

            .nvELY {
                background-position: left center;
                background-repeat: no-repeat;
                background-image: url(//ssl.gstatic.com/ui/v1/menu/checkmark.png)
            }

            .Tlae9d a,.Tlae9d div.y0fQ9c {
                padding-left: 32px;
                padding-right: 32px
            }

            .KTBKoe {
                display: inline-block;
                padding-right: 6px;
                white-space: nowrap
            }

            .hdtb-mn-hd.Yg3U7e {
                padding-left: 0
            }

            .gTl8xb {
                border-color: #70757a transparent;
                border-style: solid;
                border-width: 5px 4px 0 4px;
                width: 0;
                height: 0;
                margin-left: -2px;
                top: 50%;
                margin-top: -2px;
                position: absolute
            }

            .T3kYXe,.OouJcb,.rzG2be {
                color: #202124
            }

            .OouJcb,.rzG2be {
                background-color: #fff;
                border: 1px solid #dadce0;
                border-radius: 1px;
                font-size: 13px;
                height: 17px;
                left: 50px;
                line-height: 17px;
                margin: 0 4px;
                padding: 5px;
                position: absolute;
                width: 84px
            }

            .OouJcb:focus,.rzG2be:focus {
                border: 1px solid #4285f4;
                box-shadow: inset 0 1px 2px rgba(0,0,0,.3);
                outline: none
            }

            .J6UZg .goog-date-picker {
                left: 154px;
                background-color: #f8f9fa;
                border-radius: 2px;
                border: none;
                font-size: 12px;
                outline: none;
                padding: 5px 1px 10px;
                position: absolute;
                top: 61px;
                -webkit-user-select: none
            }

            .J6UZg .goog-date-picker table {
                padding: 0 10px;
                width: 175px
            }

            .J6UZg .goog-date-picker table thead td {
                border-bottom: 1px solid #dadce0
            }

            .J6UZg .goog-date-picker tbody th {
                width: 0
            }

            .J6UZg tr.goog-date-picker-head {
                height: 27px
            }

            .J6UZg tr.goog-date-picker-head td {
                white-space: nowrap
            }

            .J6UZg .goog-date-picker-monthyear {
                font-size: 13px
            }

            .J6UZg .goog-date-picker tbody {
                outline: none;
                font-size: 13px
            }

            .J6UZg .goog-date-picker td,.J6UZg .goog-date-picker th {
                text-align: center
            }

            .J6UZg .goog-date-picker-btn {
                background: none;
                border: none;
                cursor: pointer;
                font-size: 12px;
                outline: none;
                padding: 0;
                position: relative;
                top: -1px
            }

            .J6UZg .goog-date-picker-btn:not(.suap3e) {
                color: #202124
            }

            .J6UZg button.goog-date-picker-btn {
                font-size: 12px;
                vertical-align: middle
            }

            .J6UZg .goog-date-picker-wday,.J6UZg .goog-date-picker-date {
                font-weight: normal;
                padding: 0 1px
            }

            .J6UZg .goog-date-picker-wday {
                padding-top: 3px;
                line-height: 15px
            }

            .J6UZg td.goog-date-picker-selected {
                background-color: #1a73e8;
                border-radius: 2px;
                color: #fff
            }

            .J6UZg .goog-date-picker-other-month {
                color: #dadce0
            }

            .J6UZg .goog-date-picker-date {
                cursor: pointer;
                width: 20px;
                line-height: 15px
            }

            .J6UZg .goog-date-picker-foot {
                display: none
            }

            .J6UZg td.goog-date-picker-date:hover {
                background-color: #dadce0;
                border-radius: 2px
            }

            .J6UZg td.goog-date-picker-year,.J6UZg td.goog-date-picker-month {
                padding: 3px 0
            }

            .J6UZg button.goog-date-picker-year,.J6UZg button.goog-date-picker-month {
                color: #000
            }

            .J6UZg button.goog-date-picker-month {
                width: 77px
            }

            .J6UZg button.goog-date-picker-year {
                width: 50px
            }

            .J6UZg .goog-date-picker-menu {
                background: #fff;
                border: solid 1px #4285f4;
                cursor: pointer;
                outline: none;
                position: absolute
            }

            .UfY8P tr:nth-child(2) .goog-date-picker-other-month {
                color: #70757a
            }

            .T3kYXe {
                padding: 0 15px
            }

            .suap3e {
                color: #dadce0;
                pointer-events: none
            }

            .vOvh1b {
                left: 0;
                background: #fff;
                height: 100%;
                -ms-filter: "progid:DXImageTransform.Microsoft.Alpha(Opacity=75)";
                opacity: .75;
                position: fixed;
                top: 0;
                width: 100%;
                z-index: 1000
            }

            .J6UZg {
                left: 50%;
                background: #fff;
                border: 1px solid #dadce0;
                box-shadow: 0 4px 16px rgba(0,0,0,.2);
                height: 241px;
                margin-left: -202px;
                position: fixed;
                top: 250px;
                width: 373px;
                z-index: 1001
            }

            .QIQ7Cc.J6UZg {
                left: 0;
                margin-left: 0
            }

            .QIQ7Cc .Jy9Ore,.QIQ7Cc .Qtsmnf {
                left: 5px
            }

            .QIQ7Cc .NwEGxd {
                left: -8px
            }

            .Gwgzqd {
                right: 11px;
                background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAoAAAAKBAMAAAB/HNKOAAAAElBMVEX////39/e9vb2zs7PCwsLv7++5ffrDAAAAL0lEQVQI12MIEWBgdGVwVmQQMmEQMhJUVmRgVFYyEmBgEDJWZICSEBGILEQlWBcAq64Ft1WDk9gAAAAASUVORK5CYII=) center no-repeat;
                cursor: pointer;
                height: 20px;
                position: absolute;
                top: 10px;
                -webkit-user-select: none;
                width: 20px
            }

            .Jy9Ore {
                left: 42px;
                color: #202124;
                font-size: 16px;
                position: absolute;
                top: 34px
            }

            .Qtsmnf {
                left: 42px;
                color: #202124;
                position: absolute
            }

            .tmDYm {
                top: 72px
            }

            .iWBKNe {
                top: 111px
            }

            .OouJcb {
                top: 65px
            }

            .rzG2be {
                top: 104px
            }

            .NwEGxd {
                position: relative
            }

            .qomYCd {
                left: 50px;
                background-color: #f8f9fa;
                border-bottom-left-radius: 2px;
                border-top-left-radius: 2px;
                height: 37px;
                position: absolute;
                top: 61px;
                -webkit-transition: top .13s linear;
                width: 110px
            }

            .KbfSHd {
                top: 100px
            }

            .lRiKjb {
                -webkit-transition: none
            }

            .Ru1Ao {
                left: 54px;
                position: absolute;
                top: 143px
            }

            .BwGU8e {
                border-radius: 2px;
                border-radius: 2px;
                cursor: pointer;
                display: inline-block;
                font-size: 11px;
                font-weight: bold;
                height: 16px;
                line-height: 16px;
                min-width: 54px;
                padding: 6px 8px 5px;
                text-align: center;
                -webkit-transition: all 0.218s,visibility 0s;
                -webkit-user-select: none
            }

            .BwGU8e[disabled] {
                pointer-events: none;
                background-color: #f8f9fa;
                border-color: #f8f9fa;
                color: #70757a
            }

            .fE5Rge {
                color: #1a73e8;
                background-color: #fff;
                border: 1px solid #dadce0
            }

            .fE5Rge:hover {
                background-color: #f8f9fa;
                border: 1px solid #f8f9fa
            }

            .fE5Rge:focus {
                background-color: #e8f0fe;
                border: 1px solid #e8f0fe
            }

            .CBvvz {
                margin: -8px 0px 0px;
                margin: -30px 0px 0px;
            }

            .rskU3c .bOiwif {
                animation: ghost-card-shimmering 1.3s infinite;
                background: -webkit-linear-gradient(left,rgba(255,255,255,0) 0%, rgba(255,255,255,.5) 50%, rgba(255,255,255,0) 99%, rgba(255,255,255,0) 100%);
                background: linear-gradient(to right,rgba(255,255,255,0) 0%, rgba(255,255,255,.5) 50%, rgba(255,255,255,0) 99%, rgba(255,255,255,0) 100%);
                bottom: 0;
                right: 0;
                left: 0;
                position: absolute;
                top: 0;
                transform: translate3d(-100%,0,0)
            }

            .rskU3c {
                overflow-x: hidden;
                position: relative;
                width: 100%
            }

            .G8qI4b {
                padding: 0;
            }

            .DYiTxe {
                padding: 0 0 12px;
                border-bottom: 1px solid rgba(0,0,0,.05)
            }

            .N6dG3e,.e4XSEd {
                display: block;
                width: 100%
            }

            .N6dG3e {
                background-color: #e8f0fe;
                height: 16px;
                margin-bottom: 8px
            }

            .e4XSEd {
                background-color: rgba(0,0,0,.05);
                height: 12px
            }

            .AMbnUc {
                padding: 12px 0 0;
            }

            .ysLSm {
                background-color: rgba(0,0,0,.05);
                display: block;
                height: 60px;
                width: 100%
            }

            #Rlb3e {
                margin: .33em 0 0;
                padding: 0 0 24px;
                display: table
            }

            #Rlb3e p {
                margin: 0;
                padding-top: 5px
            }

            .NYKCib {
                display: inline-block;
                float: left;
                font-size: small;
                white-space: nowrap;
                padding-right: 16px
            }

            .d2IKib {
                color: #ea4335
            }

            .gqLncc {
                margin: .33em 0 17px
            }

            .dksaBb {
                display: inline-block;
                margin: 24px 0 2px 0
            }

            .v5jHUb {
                display: none
            }

            .FcOujd .v5jHUb {
                display: block;
                border: 1px solid #dadce0;
                border-top: 0;
                margin-bottom: 30px
            }

            .ULSxyf {
                margin-bottom: 44px
            }

            .H7QZHe {
                margin: 0 0 8px;
                background-color: #fff
            }

            .hlcw0c {
                margin-bottom: 44px
            }

            .D0ONmb .hlcw0c:last-child {
                margin-bottom: 0
            }

            .FcOujd .ULSxyf:first-child {
                margin-top: 44px
            }

            .A9Y9g {
                flex: 1 1 100%;
                min-width: 0
            }

            .pAEXpf {
                flex: 1 1 auto
            }

            .KAO3Kc {
                display: block;
                height: 100%
            }

            .IajJf {
                flex-shrink: 1
            }

            .myAtwe {
                margin-top: auto
            }

            .cEaSVc {
                margin-right: auto
            }

            .lOdyRd {
                margin-bottom: auto
            }

            .LnCrMe {
                margin-left: auto
            }

            .aBeYNc {
                right: -23px;
                position: absolute;
                top: 0;
                width: 48px;
                height: 48px
            }

            .c2xzTb .LC20lb {
                margin-bottom: 0
            }

            .MMgsKf {
                padding-top: 2px
            }

            .NXKJM {
                display: -webkit-box;
                overflow: hidden;
                -webkit-box-orient: vertical;
                -webkit-line-clamp: 1
            }

            .xvfwl {
                margin-top: 4px
            }

            .TbwUpd.ojE3Fb a.fl {
                padding-top: 0;
                font-size: 12px;
                line-height: 18px;
            }

            .iG7WGe {
                color: #202124;
                padding: 0;
                text-align: center;
                width: 16px
            }

            .qncq2c {
                font-size: 12px;
                line-height: 16px;
                margin-left: 6px
            }

            .YSlTVe.YSlTVe .DVXTI {
                color: #0b57d0;
                background-color: #ebf1ff
            }

            .YSlTVe .bJVp8c {
                color: #0b57d0
            }

            .YSlTVe.YSlTVe .qr5Pe,.YSlTVe.YSlTVe .g7Jr2c {
                background-color: #ebf1ff
            }

            .YSlTVe .CZ61cb {
                background-color: #f7f8f9;
                border: 1px solid #ecedee
            }

            .YSlTVe .yidq7b,.YSlTVe .d0FfLc {
                background-color: #ebf1ff
            }

            .YSlTVe.YSlTVe .Hyrj7c {
                color: #0b57d0
            }

            .lWlVCe {
                border-radius: 50%
            }

            .bJVp8c {
                color: #0060f0
            }

            .Hyrj7c {
                text-align: center;
                vertical-align: middle
            }

            .pBG0nf {
                color: #0060f0;
                font-family: Google Sans,arial,sans-serif;
                font-size: 14px;
                line-height: 18px
            }

            .DVXTI.DVXTI {
                font-family: Google Sans,arial,sans-serif-medium,sans-serif;
                font-weight: 400;
                font-size: 10px;
                text-transform: capitalize;
                margin-bottom: 0;
                color: #0060f0;
                background-color: #e2eeff
            }

            .aH7zee {
                border-radius: 50%;
                background-color: #fff;
            }

            .ob9lvb.HCMUuf {
                color: #70757a
            }

            .LAWljd {
                padding: 0 4px 0 4px
            }

            .LAWljd.BCF2pd {
                padding: 0 2px 0 0;
                text-align: center;
                width: 12px
            }

            .csDOgf.I5pXif {
                position: absolute
            }

            .csDOgf.Pyz0Gd {
                margin-top: 2px
            }

            .TNT2l {
                font-style: normal
            }

            .P1UpZb {
                background-color: #f1f3f4;
                border: 1px solid #ecedef
            }

            .oqQXff {
                height: 16px
            }

            .UfGzPc {
                border-top: 1px solid #ecedef;
                margin-left: 0
            }

            .YeThId {
                border-top: 1px solid #ecedef
            }

            .FalWJb {
                background: #fff
            }

            .rM2aqb {
                display: none
            }

            .adDDi.PJI6ge {
                padding-bottom: 0
            }

            .DhDny {
                color: #3c4043;
                font: 14px/20px Roboto-Medium,HelveticaNeue-Medium,Helvetica Neue,sans-serif-medium,Arial,sans-serif;
                display: inline-block;
                vertical-align: middle
            }

            .EX9eNe {
                color: #70757a;
                margin-left: 4px;
                vertical-align: middle
            }

            .spch-dlg {
                background: transparent;
                border: none
            }

            .spch {
                background: #fff;
                height: 100%;
                left: 0;
                opacity: 0;
                overflow: hidden;
                position: fixed;
                text-align: left;
                top: 0;
                visibility: hidden;
                width: 100%;
                z-index: 10000;
                transition: visibility 0s linear 0.218s,background-color 0.218s;
                background: rgba(255,255,255,0)
            }

            .s2fp.spch {
                opacity: 1;
                transition-delay: 0s;
                visibility: visible;
                background: rgba(255,255,255,0)
            }

            .close-button {
                background: none;
                border: none;
                color: #70757a;
                cursor: pointer;
                font-size: 26px;
                right: 0;
                line-height: 15px;
                opacity: .6;
                margin: -1px -1px 0 0;
                padding: 0 0 2px 0;
                height: 48px;
                width: 48px;
                position: absolute;
                top: 0;
                z-index: 10
            }

            .close-button:hover {
                opacity: .8
            }

            .close-button:active {
                opacity: 1
            }

            .spchc {
                display: block;
                height: 42px;
                pointer-events: none;
            }

            .inner-container {
                height: 100%;
                opacity: .1;
                pointer-events: none;
                width: 100%;
                transition: opacity .318s ease-in
            }

            .s2ml .inner-container,.s2ra .inner-container,.s2er .inner-container,.OJaju .inner-container {
                opacity: 1;
                transition: opacity 0s
            }

            .google-logo {
                background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAALwAAABACAQAAAAKENVCAAAI/ElEQVR4Ae3ae3BU5RnH8e/ZTbIhhIRbRIJyCZcEk4ZyE4RBAiRBxRahEZBLQYUZAjIgoLUWB6wjKIK2MtAqOLVUKSqWQW0ZaOQq0IFAIZVrgFQhXAOShITEbHY7407mnPfc8u6ya2f0fN6/9rzvc87Z39nbed/l/8OhIKMDQ+hHKp1JJB6FKq5QQhH72MZ1IsDRhvkU4bds9WxlLNE4wqg9q6jBL9G+4knc/HB9qXmuG4goD89TjT+IVkimE/zt6sYh/EG3WmaiOMGHbgQ38YfY3ibKCV6GMabHWY0bo+Ps5jjnuYlCczrSk8Hcgd5U1rONoDnG48Ova2W8RGeMXAxiHfWakT4mOx81oRiG1/C5vYh47KSx5fZid4JvxxVd7MdIp3EK06kNNXYneIWtutgLaIasQUwkJE7wE3SxbycWR8SD93BOiL2YRBwRDN5FwOPchaqecZQTQQ4XAApz0FrFQSLPwQD8mlZNEt8L5841D62/cJVIi2cgPelEAlBOCYfYSxXymjKAXqSQAFRwloPspRp5dzOMHiTThEqK2c1OvGHIsg/30YUWKHzDKfZwEB+2xBn3gUSSwmA+MpluruYDySMPYD23TOrX0V/q+CPZYai+yHw8wKscbmhMD+IVfyevcMlkuvxXxGOphTD4Gi4iJ40C/DZtM12wk8Lfbes/oSN27mGPZW0RnVmvebxIMng3z1Bluddz5Mh9wm8icqZIzPHfZDxW8qhotL6cUVh5zP74XOBg0MEnsgW/bfMxzyIOYdgSIuV5/JJtPmZmSlb7mI6ZGTLVQQafSKHUvp7BxFxhSD6N8UsH4An5aT+J3mNB1T+K3hj8YQ/ezRbpvY3CYKEwYFLYgvfTkQZ9qTN8nS3lIdJJZwTLDdNztfwUrTTDp+hllmnqrxo+sLqi1dWwuFPKYnK5h0we5c/UhhT8fF1FHWsZTis8dGAyB4S+67RF5wVhwC/DGHxvAqI4Imyv50Vi0YpjsW4l4AAuGii63yE+lhCHVlOW6o79TxRN/ee64y/SHb8TO4MOvq3uYh6iO1oufiP0r0VnjtA9K4zBDzSdgKtjJGbyqBfG5dFguC62sZiZoLt0Qy3qvYzCKIZNQQYvXupdxGO0Rni5dLebl1wexuD7A4DuC+gprMwTxu2hwT+E7c9iZYEw7lMaiBPeczAXT3EQwcdwTbP1Eq3RiyaPvcIe/4igj9C5NYzBpwOQKmzbh4IVF4dMviOShHfCEdxYieKY8M5qCUCy8E4oxIWVnwcRfK4wdhqitiyk1JBHJc3UU4UT+HDRYADR1GEnB2s9WYrqssn41/BjxcdrrEOVzRogS4hqOfVY8fI6qzWXYTAbgRwUVMvwYeUzzpKCnMGobvIeDRTuZyajiMLoMG2oRONfwnV5kNDNFH5ZKAD8SbPtFrHYaSr8+nkLgCXC53sCdloJz+RlAFYJv5bisPOG9Cv+U+F+O6AZM4Sx2iz+QKZxWrgArSmEbiAIpwvQGdV/qMFOFUdRdTbUn6QCO9c4bajvJhy/GjuFyOqEqhhIZyUXWEk6esd4imTyKTIG/1e08kghNNEMR7WfgERUpTTmPKrmIdSXGupbiHu3dQFZCagy2MGXzCAekZcPySKDlVSYTwsf5QB9aeBiCWMJxcO0RPU5AW5UPuyJI9xhr/diz4ssF6ohGJXyFmu42Fj5MrTGMILgKTyHqpoCAipR3YE9cURFWOorUCVhrzWyKrFWwGg68hIXG79uGziG1rt0IFhPcC+qj6gioARVJm7sRPMTVCWG+u54sBNHqm19Ji7sZCDrv5gp53ekkcNGvHJvGB+zdVd+M60JRi/eREt9VIQqgfuxM5Q4VEcM9R5ysfMAUaA78iFUzRmIfb2sw+j9m6m042lOEqS1hv+R3Y2svpSJCxJCn9hjR5ztywSgg7BtGwpWFHYLY+8CIB2/5Jppj5BvoE7Qz/a8bCVSrIv+quQrYCLVQl0NXVEpnBF6f4aVX+guvELAPmH7GMk/ZX1BgKJb2szBnEJBEMFHUyY841SsjGcr7bGVabLC8z6dsJPC3ww1sxE9LfTeoAdmeumOPkNzYcUb776Y6aebOh5Hg6m6l1MaZhYGOUn2sjD6MAmYyeIWfiqYhoKNLJNlaC/ryCUGvRhyWUedYfx7KIiack4XfZ5ujMI4XewlxIpzMEL04w31k3STtEW4NWd6Uugr4yFEHt4Ielo4iRvC+P20R6QwTZPnFtpjI4dKi5veAlbwLPnM4NesZDs3Tcd9RgxGIw3jdjCeO1FQSGYiuw39D6A1CJ+u/wsm0pZA/STDEnY9A9DKMtRvZjStAIVOzOJMSAsh+YaMltGXGEChHVPYr+s/igsbPTmHP8T2IR7MvW46voZa0+2voLfAor7GdPtz6C0yHVfNt4S+9KewwXTJ8xtumWyv5T6w14pNIYTu40VcWHHzvvSe3sWFnsIq6foVKCb1qyOw2N2EnZJ7+5aRSFAYS2lQp3maLOy5WS61pyW4MKOwCJ/E5X8BBTMuXsW+tpITQQYPcXws8Zyuk420eOZyQSqqy8zDg4yH+cp2T2cYjp1sim3rTzEEO4/YPKNL9AvpD00K+ZTbnZXwc1KSh9FspNrmDbSZicQirwmzLMI7Qb7EnjxM57hp/TGmEUNjEljAZUNtHW/TGvhA+J6QCx4gicVcNT2r7TyIgoEiGf+99CeVLiTSDKimjK85QSH7qCJ4Cr0YRi9SaI6fG5zlIAUcwS9d34Nsen9Xz3f1hRRQJF0fzVCyyaQdcZRzil18zCUAPtHc3s3mTYIRzWCGkEEH4vFSxmn2s5kSJDgOGP/l4Ii8aOHetzeOsIhiNAX0wVq28O3lwXHbklnIeQJ/PHJhQbh72YXjts3Eq4n0t5h7BL+mzcVx29Kpxy9E70IvV5h7qiEJRxiswC+0feTgJkAhg3d098S/J8IUfhziOUAaouscoYJmpNIO0WXSuYYjLLpxFb9U85KNI4wyKJWKfQKOMEtmm33sXCCbCHC4mMxZIWpx/aglEeNwM4J3KNb8jvmaDTxBIt8jhR8vD22IpYYr1PBD5HA4HP8DxVcxdwELEFUAAAAASUVORK5CYII=) no-repeat center;
                background-size: 94px 32px;
                height: 32px;
                width: 94px;
                top: 8px;
                opacity: 0;
                float: right;
                left: 255px;
                pointer-events: none;
                position: relative;
                transition: opacity .5s ease-in,left .5s ease-in
            }

            .s2fp .google-logo {
                opacity: 0.54;
                left: 270px;
                transition: opacity .5s ease-out,left .5s ease-out
            }

            .inner-container {
                width: 572px
            }

            .spchc {
                background: #fff;
                box-shadow: 0 2px 6px rgba(0,0,0,0.2);
                margin: 0;
                min-width: 100%;
                overflow: hidden;
                padding: 51px 0 50px 126px;
                position: absolute
            }

            .spch.s2fp.t2n14d {
                background: rgba(255,255,255,0.9)
            }

            .LgbsSe {
                background-color: #fff;
                border: 1px solid #f8f9fa;
                border-radius: 100%;
                bottom: 0;
                box-shadow: 0 2px 5px rgba(0,0,0,.1);
                cursor: pointer;
                display: inline-block;
                opacity: 0;
                pointer-events: none;
                position: absolute;
                right: 0;
                transition: background-color 0.218s,border 0.218s,box-shadow 0.218s;
                transition-delay: 0;
                position: absolute;
                opacity: 0;
                left: -83px;
                top: -83px;
            }

            .s2fp .LgbsSe {
                opacity: 1;
                pointer-events: auto;
                transform: scale(1);
                left: 0;
                top: 0
            }

            .s2ra .LgbsSe {
                background-color: #ea4335;
                border: 0;
                box-shadow: none
            }

            .r8s4j {
                background-color: #dadce0;
                border-radius: 100%;
                display: inline-block;
                opacity: 1;
                pointer-events: none;
                position: absolute;
                transform: scale(.01);
                transition: opacity 0.218s;
                height: 151px;
                left: -28px;
                top: -28px;
                width: 151px
            }

            .button-container {
                pointer-events: none;
                position: relative;
                transition: transform 0.218s,opacity 0.218s ease-in;
                transform: scale(.1);
                height: 95px;
                right: -31px;
                top: -27px;
                width: 95px;
                float: right
            }

            .s2fp .button-container {
                transform: scale(1)
            }

            .s2ra .LgbsSe:active {
                background-color: #c5221f
            }

            .LgbsSe:active {
                background-color: #f8f9fa
            }

            .microphone {
                height: 87px;
                pointer-events: none;
                position: absolute;
                width: 42px;
                left: 17px;
                top: 7px;
                transform: scale(.53)
            }

            .receiver {
                background-color: #999;
                border-radius: 30px;
                height: 46px;
                left: 25px;
                pointer-events: none;
                position: absolute;
                width: 24px
            }

            .wrapper {
                bottom: 0;
                height: 53px;
                left: 11px;
                overflow: hidden;
                pointer-events: none;
                position: absolute;
                width: 52px
            }

            .stem {
                background-color: #999;
                bottom: 14px;
                height: 14px;
                left: 22px;
                pointer-events: none;
                position: absolute;
                width: 9px;
                z-index: 1
            }

            .shell {
                border: 7px solid #999;
                border-radius: 28px;
                bottom: 27px;
                height: 57px;
                pointer-events: none;
                position: absolute;
                width: 38px;
                z-index: 0;
                left: 0px
            }

            .s2ml .receiver,.s2ml .stem {
                background-color: #f44
            }

            .s2ml .shell {
                border-color: #f44
            }

            .s2ra .receiver,.s2ra .stem {
                background-color: #fff
            }

            .s2ra .shell {
                border-color: #fff
            }

            .text-container {
                pointer-events: none;
                position: relative
            }

            .spcht {
                font-weight: normal;
                line-height: 1.2;
                opacity: 0;
                pointer-events: none;
                position: absolute;
                text-align: left;
                -webkit-font-smoothing: antialiased;
                transition: opacity .1s ease-in,margin-left .5s ease-in,top 0s linear 0.218s;
                font-size: 27px;
                left: 7px;
                top: .2em;
                width: 490px;
                margin-left: 32px
            }

            .s2fp .spcht {
                margin-left: 0;
                opacity: 1;
                transition: opacity .5s ease-out,margin-left .5s ease-out
            }

            .spchta {
                color: #1a0dab;
                cursor: pointer;
                font-size: 18px;
                font-weight: 500;
                pointer-events: auto;
                text-decoration: underline
            }

            .spch-2l.spcht,.spch-3l.spcht,.spch-4l.spcht {
                transition: top 0.218s ease-out
            }

            .spch-2l.spcht {
                top: -.6em
            }

            .spch-3l.spcht {
                top: -1.3em
            }

            .spch-4l.spcht {
                top: -1.7em
            }

            .s2fp .spch-5l.spcht {
                font-size: 24px;
                top: -1.7em;
                transition: font-size 0.218s ease-out
            }

            .permission-bar {
                margin-top: -100px;
                opacity: 0;
                pointer-events: none;
                position: absolute;
                width: 500px;
                transition: opacity 0.218s ease-in,margin-top .4s ease-in
            }

            .s2wfp .permission-bar {
                margin-top: -300px;
                opacity: 1;
                transition: opacity .5s ease-out 0.218s,margin-top 0.218s ease-out 0.218s
            }

            .permission-bar-gradient {
                box-shadow: 0 1px 0px #4285f4;
                height: 80px;
                left: 0;
                margin: 0;
                opacity: 0;
                pointer-events: none;
                position: fixed;
                right: 0;
                top: -80px;
                transition: opacity 0.218s,box-shadow 0.218s
            }

            .s2wfp .permission-bar-gradient {
                box-shadow: 0 1px 80px #4285f4;
                opacity: 1;
                pointer-events: none;
                animation: allow-alert .75s 0 infinite;
                animation-direction: alternate;
                animation-timing-function: ease-out;
                transition: opacity 0.218s,box-shadow 0.218s
            }

            .f6F9Be {
                position: absolute;
                bottom: 0;
                width: 100%
            }

            .fbar a {
                text-decoration: none;
                white-space: nowrap
            }

            .fbar {
                margin-left: -27px
            }

            .Fx4vi {
                padding-left: 27px;
                margin: 0 !important
            }

            #fsl {
                white-space: nowrap
            }

            .f6F9Be {
                background: #f2f2f2;
                line-height: 40px;
                padding-bottom: 12px
            }

            .f6F9Be.TrMVnc {
                padding-top: 12px
            }

            .f6F9Be.dc8jac {
                padding-top: 24px
            }

            .B4GxFc {
                margin-left: var(--center-abs-margin);
            }

            .fbar p,.fbar a {
                color: #70757a
            }

            .fbar a:hover {
                color: #4d5156
            }

            .fbar {
                font-size: 14px
            }

            .RLQCVb {
                line-height: 40px
            }

            .RLQCVb a {
                cursor: pointer;
                font-weight: bold;
                text-decoration: none
            }

            .SLbK8e {
                max-height: 16px;
                vertical-align: text-top
            }

            .b0KoTc {
                color: #70757a;
                padding-left: 27px
            }

            .b2hzT {
                border-bottom: 1px solid #dadce0
            }

            .Q8LRLc {
                font-size: 15px
            }

            .known_loc {
                forced-color-adjust: none;
                background: #4285f4
            }

            @media (prefers-color-scheme: dark) and (forced-colors:active) {
                .known_loc {
                    background:Highlight
                }
            }

            .unknown_loc {
                background: #70757a
            }

            .smiUbb img {
                margin-right: 4px
            }

            .smiUbb {
                margin-left: var(--center-abs-margin);
                line-height: 15px;
                color: #70757a;
            }

            #swml {
                display: inline-block;
                margin-left: 13px;
                padding-left: 16px;
                border-left: 1px solid #dadce0
            }

            .KwU3F {
                color: #1a0dab
            }

            .GNm3Qb {
                display: inline-block
            }

            .xSQxL {
                color: #1a0dab;
                cursor: pointer;
                display: inline-block
            }

            .HDOrGf {
                line-height: 40px
            }

            .EYqSq {
                margin: 6px 4px 9px 0;
                border-radius: 100%;
                display: inline-block;
                height: 10px;
                vertical-align: middle;
                width: 10px
            }

            .dfB0uf {
                color: #4d5156;
                font-weight: bold
            }

            .OosGzb {
                width: 376px
            }

            .U8shWc {
                background-color: transparent;
                border: none;
                border-radius: 8px;
                border-radius: 8px;
                box-sizing: border-box;
                cursor: pointer;
                display: inline-block;
                font-size: 14px;
                font-weight: 500;
                padding-top: 6px;
                padding-bottom: 3px;
                min-width: 88px;
                position: relative;
                text-decoration: none !important;
                -webkit-user-select: none;
                white-space: nowrap
            }

            .U8shWc:disabled,.U8shWc[disabled]:not([disabled=false]) {
                pointer-events: none
            }

            .U8shWc.fSXIc {
                min-width: 64px
            }

            .U8shWc.hpZDWd {
                color: #fff
            }

            .hpZDWd:hover {
                background-color: rgba(204,204,204,.15)
            }

            .hpZDWd:focus {
                background-color: rgba(204,204,204,.15)
            }

            .hpZDWd:active {
                background-color: rgba(204,204,204,.25)
            }

            .U8shWc.hpZDWd:disabled,.U8shWc.hpZDWd[disabled]:not([disabled=false]) {
                color: rgba(255,255,255,.30) !important
            }

            .Omzzbd {
                white-space: normal
            }

            .Z7swgb {
                padding: 14px 0
            }

            .ozC9Cd {
                color: #fff;
                padding-top: 4px;
                margin-bottom: -4px
            }
        </style>
        <script nonce="N4ljJHxWoJx3pKoWtd5YIw">
            (function() {
                var xsrfTokens = '{\x22UPgwmc\x22:\x22ALook6zBjkHkTaMqesENUaUtYwep_9ZZVA:1696673079849\x22}';
                google.xsrf = JSON.parse(xsrfTokens);
            }
            )();
        </script>
        <script nonce="N4ljJHxWoJx3pKoWtd5YIw">
            (function() {
                google.ldi = {};
                google.pim = {};
                (function() {
                    var a = google.ldi || {}, b;
                    for (b in a)
                        if (a.hasOwnProperty(b)) {
                            var c = document.getElementById(b) || document.documentElement.querySelector('img[data-iid="' + b + '"]');
                            c && Number(c.getAttribute("data-atf")) & 1 && (c.setAttribute("data-deferred", "2"),
                            c.src = a[b])
                        }
                    ;
                }
                ).call(this);
            }
            )();
        </script>
        <script nonce="N4ljJHxWoJx3pKoWtd5YIw">
            (function() {
                google.xjs = {
                    ck: 'xjs.s.MzD2MCWNgIg.L.W.O',
                    cs: 'ACT90oG3qa93mkN7bkE2I-0mHN3jIiNwyg',
                    cssopt: false,
                    csss: 'ACT90oFniOGepW-ZN0hndk3u6FRFUVYiPQ',
                    excm: ['NsEUGe', 'y25qZb', 'AD6AIb', 'fNMhz', 'bXyZdf', 'ZrXR8b', 'ABxRVc', 'rL2AR', 'yChgtb', 'vJPFse', 'JxE93', 'VZLyBe', 'U3Ovcc', 'TO0csb', 'Oa7Qpb', 'zs9f9d', 'tzTB5', 'XHo6qe', 'FmnE6b', 'jkRPje', 'PoJj8d', 'KzZUob', 'WxJ6g', 'kOSi0d', 'pOYYce', 'eTv59e', 'SKZSKc', 'T3q8Wd', 'Ok4XMd', 'Trirbc', 'hfJ9hb'],
                    sepcss: false
                };
            }
            )();
        </script>
        <script nonce="N4ljJHxWoJx3pKoWtd5YIw">
            (function() {
                google.kEXPI = '0,3700252,461690,36328,39064,81524,94323,29269,26160,30215,88408,23419,99908,8130,29049,23869,49520,16490,17230,10909,281,297,7090,6393,34829,12431,13241,205,14446,27822,1743,10231,5211435,634,570,5993378,2808674,26709028,1368576,1,3,1732187,23317846,127042,1550,29,6400,8926,11218,2251,4514,3124,638,4623,6421,1531,11027,3848,576,9,4343,1722,225,1841,1750,1917,1196,1896,8,327,278,627,2800,3,2,3518,271,709,2091,422,56,218,3448,1723,288,649,15,426,545,703,95,391,920,188,1027,294,1244,54,123,942,667,1535,197,758,207,1449,190,739,313,538,289,298,892,102,674,11,729,372,744,140,214,658,1196,106,289,1748,1055,3446,91,8,1301';
            }
            )();
            (function() {
                var u = '/xjs/_/js/k\x3dxjs.s.vi.d0MjMZ3TjvQ.O/am\x3dChCAAQIAAAAAAAAAAgAAEBUQDgFsgAH45xQAAAABAAiIkghCMACAAO8_EYEAgAQAAmAAxIE9AAASqgE7AAAA4OwHEQCAIAgAwAIA4QG0JoADIWAREAAAAAB5AHAeQHAQYQEAAAAAAAAAAAAQwATB4ID0eEEABAAAAAAAAAAAACCVTV4cSAAADA/d\x3d1/ed\x3d1/dg\x3d2/br\x3d1/rs\x3dACT90oEUA-iybIKFBfxSvwgHzlD9QTpYmw/ee\x3dcEt90b:ws9Tlc;qddgKe:x4FYXe,d7YSfd;yxTchf:KUM7Z;dtl0hd:lLQWFe;eHDfl:ofjVkb;qaS3gd:yiLg6e;nAFL3:NTMZac,s39S4;oGtAuc:sOXFj;iFQyKf:vfuNJf,QIhFr;SNUn3:ZwDk9d,x8cHvb;io8t5d:sgY6Zb;Oj465e:KG2eXe,KG2eXe;Erl4fe:FloWmf,FloWmf;JsbNhc:Xd8iUd;sP4Vbe:VwDzFe;kMFpHd:OTA3Ae;uY49fb:COQbmf;Pjplud:PoEs9b,EEDORb;QGR0gd:Mlhmy;a56pNe:JEfCwb;Me32dd:MEeYgc;wR5FRb:TtcOte,O1Gjze;pXdRYb:JKoKVe;dIoSBb:ZgGg9b;EmZ2Bf:zr1jrb;NSEoX:lazG7b;eBAeSb:Ck63tb;WCEKNd:I46Hvd;wV5Pjc:L8KGxe;EVNhjf:pw70Gc;sTsDMc:kHVSUb;wQlYve:aLUfP;zOsCQe:Ko78Df;KcokUb:KiuZBf;YV5bee:IvPZ6d;kbAm9d:MkHyGd;ZWEUA:afR4Cf;g8nkx:U4MzKc;lzgfYb:PI40bd;w9w86d:dt4g2b;GleZL:J1A7Od;bcPXSc:gSZLJb;JXS8fb:Qj0suc;IoGlCf:b5lhvb;VN6jIc:ddQyuf;vfVwPd:lcrkwe;xBbsrc:NEW1Qc;ESrPQc:mNTJvc;pNsl2d:j9Yuyc;VGRfx:VFqbr;BjwMce:cXX2Wb;R9Ulx:CR7Ufe;kY7VAf:d91TEb;KpRAue:Tia57b;jY0zg:Q6tNgc;coJ8e:KvoW8;oSUNyd:fTfGO,fTfGO,pnvXVc;SMDL4c:fTfGO,pnvXVc;aZ61od:arTwJ;h3MYod:NpD4ec;ZrFutb:W4Cdfc;K8vqCc:MyIcle;NPKaK:SdcwHb;LBgRLc:XVMNvd,SdcwHb;rQSrae:C6D5Fc;kCQyJ:ueyPK;KQzWid:mB4wNe;EABSZ:MXZt9d;qavrXe:zQzcXe,mYbt1d;TxfV6d:YORN0b;UDrY1c:eps46d;F9mqte:UoRcbe;Nyt6ic:jn2sGd;w3bZCb:ZPGaIb;G0KhTb:LIaoZ;XUezZ:sa7lqb;aAJE9c:WHW6Ef;V2HTTe:RolTY;Wfmdue:g3MJlb;imqimf:jKGL2e;BgS6mb:fidj5d;gtVSi:ekUOYd;UVmjEd:EesRsb;z97YGf:oug9te;AfeaP:TkrAjf;eBZ5Nd:audvde;CxXAWb:YyRLvc;SLtqO:Kh1xYe;tosKvd:ZCqP3;VOcgDe:YquhTb;uuQkY:u2V3ud;WDGyFe:jcVOxd;trZL0b:qY8PFe;VxQ32b:k0XsBb;DULqB:RKfG5c;Np8Qkd:Dpx6qc;qZx2Fc:j0xrE;cFTWae:gT8qnd;gaub4:TN6bMe;DpcR3d:zL72xf;hjRo6e:F62sG;yGxLoc:FmAr0c;oUlnpc:RagDlc;R2kc8b:ALJqWb;pj82le:mg5CW;dLlj2:Qqt3Gf;qGV2uc:HHi04c;UyG7Kb:wQd0G;LsNahb:ucGLNb;xbe2wc:wbTLEd;Q1Ow7b:x5CSu;bFZ6gf:RsDQqe;okUaUd:wItadb;G6wU6e:hezEbd;uknmt:GkPrzb;U96pRd:FsR04;PqHfGe:im2cZe;Fmv9Nc:O1Tzwc;hK67qb:QWEO5b;BMxAGc:E5bFse;R4IIIb:QWfeKf;whEZac:F4AmNb;tH4IIe:Ymry6;lkq0A:JyBE3e;daB6be:lMxGPd;LEikZe:byfTOb,lsjVmc/m\x3dattn,cdos,gwc,hsm,jsa,mb4ZUb,d,csi,cEt90b,SNUn3,qddgKe,sTsDMc,dtl0hd,eHDfl';
                var amd = 0;
                var e = this || self
                  , f = function(a) {
                    return a
                };
                var g;
                var h = function(a) {
                    this.g = a
                };
                h.prototype.toString = function() {
                    return this.g + ""
                }
                ;
                var k = {};
                var l = function() {
                    var a = document;
                    var b = "SCRIPT";
                    "application/xhtml+xml" === a.contentType && (b = b.toLowerCase());
                    return a.createElement(b)
                };
                function m(a, b) {
                    a.src = b instanceof h && b.constructor === h ? b.g : "type_error:TrustedResourceUrl";
                    var c, d;
                    (c = (b = null == (d = (c = (a.ownerDocument && a.ownerDocument.defaultView || window).document).querySelector) ? void 0 : d.call(c, "script[nonce]")) ? b.nonce || b.getAttribute("nonce") || "" : "") && a.setAttribute("nonce", c)
                }
                ;function n(a) {
                    a = null === a ? "null" : void 0 === a ? "undefined" : a;
                    if (void 0 === g) {
                        var b = null;
                        var c = e.trustedTypes;
                        if (c && c.createPolicy) {
                            try {
                                b = c.createPolicy("goog#html", {
                                    createHTML: f,
                                    createScript: f,
                                    createScriptURL: f
                                })
                            } catch (d) {
                                e.console && e.console.error(d.message)
                            }
                            g = b
                        } else
                            g = b
                    }
                    a = (b = g) ? b.createScriptURL(a) : a;
                    return new h(a,k)
                }
                ;void 0 === google.ps && (google.ps = []);
                function p() {
                    var a = u
                      , b = function() {};
                    google.lx = google.stvsc ? b : function() {
                        q(a);
                        google.lx = b
                    }
                    ;
                    google.bx || google.lx()
                }
                function r(a, b) {
                    b && m(a, n(b));
                    var c = a.onload;
                    a.onload = function(d) {
                        c && c(d);
                        google.ps = google.ps.filter(function(t) {
                            return a !== t
                        })
                    }
                    ;
                    google.ps.push(a);
                    document.body.appendChild(a)
                }
                google.as = r;
                function q(a) {
                    google.timers && google.timers.load && google.tick && google.tick("load", "xjsls");
                    var b = l();
                    b.onerror = function() {
                        google.ple = 1
                    }
                    ;
                    b.onload = function() {
                        google.ple = 0
                    }
                    ;
                    google.xjsus = void 0;
                    r(b, a);
                    google.aple = -1;
                    google.psa = !0
                }
                ;google.xjsu = u;
                e._F_jsUrl = u;
                setTimeout(function() {
                    0 < amd ? google.caft(function() {
                        return p()
                    }, amd) : p()
                }, 0);
            }
            )();
            window._ = window._ || {};
            window._DumpException = _._DumpException = function(e) {
                throw e;
            }
            ;
            window._s = window._s || {};
            _s._DumpException = _._DumpException;
            window._qs = window._qs || {};
            _qs._DumpException = _._DumpException;
            (function() {
                window._F_toggles = [25170026, 8, 0, 128, 235934992, 101036037, 21921664, 4194304, 310904832, 12650530, 1055918080, 2114639, 33555584, 118489472, 536871896, 784362116, 536870912, 4464563, 8521728, 45056, 649331169, 8654336, 65814, 507510784, 1995264, 92553665, 0, 0, 1048576, 58917907, 68652872, 256, 0, 0, 98883922, 4615, 12];
            }
            )();
            function _F_installCss(c) {}
            (function() {
                google.jl = {
                    blt: 'none',
                    chnk: 0,
                    dw: false,
                    dwu: true,
                    emtn: 0,
                    end: 0,
                    ico: false,
                    ikb: 0,
                    ine: false,
                    injs: 'none',
                    injt: 0,
                    injth: 0,
                    injv2: false,
                    lls: 'viewport',
                    pdt: 0,
                    rep: 0,
                    snet: true,
                    strt: 0,
                    ubm: false,
                    uwp: true
                };
            }
            )();
            (function() {
                var pmc = '{\x22aa\x22:{},\x22abd\x22:{\x22abd\x22:false,\x22deb\x22:false,\x22det\x22:false},\x22async\x22:{},\x22attn\x22:{},\x22bgd\x22:{\x22ac\x22:true,\x22as\x22:true,\x22at\x22:0,\x22ea\x22:true,\x22ed\x22:0,\x22ei\x22:true,\x22el\x22:true,\x22ep\x22:true,\x22er\x22:true,\x22et\x22:0,\x22eu\x22:false,\x22wl\x22:false},\x22cdos\x22:{\x22cdobsel\x22:false},\x22csi\x22:{},\x22d\x22:{},\x22foot\x22:{},\x22gf\x22:{\x22pid\x22:196},\x22gwc\x22:{},\x22hsm\x22:{},\x22jsa\x22:{\x22csi\x22:true,\x22csir\x22:100},\x22kyn\x22:{},\x22lli\x22:{},\x22mb4ZUb\x22:{},\x22mu\x22:{\x22murl\x22:\x22https://adservice.google.com/adsid/google/ui\x22},\x22pHXghd\x22:{},\x22sb_wiz\x22:{\x22onf\x22:\x22EAEYlNqnsN-7wvN-GJKIjbXRyqqHngEYjtfYtPXs8MpeGPLB0Y2U2ZWqIxjA08-qzq6qphIyzAEKHwodU2hhcmUgR29vZ2xlIE1hcCBBUEkga2V5IGZyZWUKJQojR29vZ2xlIG1hcCBBUEkga2V5IGZyZWUgZm9yIHRlc3RpbmcKFQoTQ8OhY2ggbOG6pXkgQVBJIGtleQoUChJHb29nbGUgQVBJIENvbnNvbGUKEAoOR29vZ2xlIEFQSSBrZXkKGAoWR2V0IEFQSSBrZXkgR29vZ2xlIE1hcAoRCg9BUEkga2V5IENoYXRHUFQKFAoST0F1dGgyIFNwcmluZyBCb290EEc\x22,\x22scq\x22:\x22code mau token google\x22,\x22stok\x22:\x22-S-UrUG5C-kNKVtTt42SzkGDRqU\x22,\x22zps\x22:\x22GJTap7Dfu8LzfhiSiI210cqqh54BGI7X2LT17PDKXhjywdGNlNmVqiMYwNPPqs6uqqYS\x22},\x22sf\x22:{},\x22sonic\x22:{},\x22spch\x22:{\x22ae\x22:\x22Vui l\\u00f2ng ki\\u1ec3m tra micr\\u00f4 c\\u1ee7a b\\u1ea1n.  \\u003Ca href\x3d\\\x22https://support.google.com/chrome/?p\x3dui_voice_search\\\x22 target\x3d\\\x22_blank\\\x22\\u003ET\\u00ecm hi\\u1ec3u th\\u00eam\\u003C/a\\u003E\x22,\x22ak\x22:\x22\x22,\x22cd\x22:0,\x22fp\x22:false,\x22hl\x22:\x22vi-VN\x22,\x22im\x22:\x22Nh\\u1ea5p v\\u00e0o \\u003Cb\\u003ECho ph\\u00e9p\\u003C/b\\u003E \\u0111\\u1ec3 b\\u1eaft \\u0111\\u1ea7u t\\u00ecm ki\\u1ebfm b\\u1eb1ng gi\\u1ecdng n\\u00f3i\x22,\x22iw\x22:\x22\\u0110ang ch\\u1edd...\x22,\x22lm\x22:\x22\\u0110ang nghe\\u2026\x22,\x22lu\x22:\x22T\\u00ecm ki\\u1ebfm b\\u1eb1ng gi\\u1ecdng n\\u00f3i %1$s kh\\u00f4ng kh\\u1ea3 d\\u1ee5ng\x22,\x22mb\x22:false,\x22ne\x22:\x22Kh\\u00f4ng c\\u00f3 k\\u1ebft n\\u1ed1i Internet\x22,\x22nt\x22:\x22Kh\\u00f4ng th\\u1ec3 d\\u1ecbch \\u0111\\u01b0\\u1ee3c. \\u003Cspan\\u003ETh\\u1eed l\\u1ea1i\\u003C/span\\u003E\x22,\x22nv\x22:\x22Vui l\\u00f2ng ki\\u1ec3m tra micr\\u00f4 v\\u00e0 \\u00e2m l\\u01b0\\u1ee3ng c\\u1ee7a b\\u1ea1n.  \\u003Ca href\x3d\\\x22https://support.google.com/chrome/?p\x3dui_voice_search\\\x22 target\x3d\\\x22_blank\\\x22\\u003ET\\u00ecm hi\\u1ec3u th\\u00eam\\u003C/a\\u003E\x22,\x22pe\x22:\x22T\\u00ecm ki\\u1ebfm b\\u1eb1ng gi\\u1ecdng n\\u00f3i \\u0111\\u00e3 b\\u1ecb t\\u1eaft.  \\u003Ca href\x3d\\\x22https://support.google.com/chrome/?p\x3dui_voice_search\\\x22 target\x3d\\\x22_blank\\\x22\\u003EChi ti\\u1ebft\\u003C/a\\u003E\x22,\x22rm\x22:\x22Xin m\\u1eddi n\\u00f3i\x22,\x22s3\x22:false},\x22tl\x22:{\x22rvkey\x22:\x22AIzaSyC_9Rt88UMjzgg5pIVArnfuIVkJx4zCdTY\x22}}';
                google.pmc = JSON.parse(pmc);
            }
            )();
            (function() {
                var r = ['sb_wiz', 'aa', 'abd', 'async', 'bgd', 'foot', 'kyn', 'lli', 'mu', 'pHXghd', 'sf', 'sonic', 'spch', 'tl'];
                google.plm(r);
            }
            )();
            (function() {
                var m = ['ANVEfE', '[\x22gws-wiz-serp\x22,\x22\x22,\x22code mau token gooogle\x22,\x22\x22,null,1,0,0,13,\x22vi\x22,\x22-S-UrUG5C-kNKVtTt42SzkGDRqU\x22,\x22\x22,\x22Ny0hZajKHuSv2roPysWswAY\x22,0,\x22vi\x22,null,null,null,3,5,-1,null,null,0,1,1,1800000,1,0,10,6,null,null,null,1.15,0,null,1,1,9,1,1,0,null,0,null,1,1,1,1,1,null,\x22\x22,0,1,0,-1,null,null,0,0,null,0,0,0,\x22futura_sug_zp_si_0000000_e\x22,null,null,\x22\x22,0,null,1,-1,-1,null,1,0,1,1000,null,null,0,[\x22gws-wiz-serp\x22,\x22\x22,\x22\x22],0,[\x22gws-wiz-local\x22,\x22\x22,\x22\x22],0,[\x22img\x22,\x22gws-wiz-img\x22,\x22i\x22],0,[\x22products-cc\x22,\x22\x22,\x22sh\x22],0,[\x22gws-wiz-modeless\x22,\x22gws-wiz-perspectives\x22,\x22\x22],0,[\x22hotel-searchbox\x22,\x22mobile-gws-wiz-hotel\x22,\x22\x22],0,[\x22gws-wiz-serp\x22,\x22\x22,\x22\x22],0,null,0,0,0,null,0,[\x22gws-wiz-serp\x22,\x22\x22,\x22\x22],0,[\x22gws-wiz-serp\x22,\x22\x22,\x22\x22],0,[\x22gws-wiz-serp\x22,\x22\x22,\x22\x22],1,0,0,[\x22gws-wiz-video\x22,\x22\x22,\x22v\x22],0]', 'ANVEfM', '[null,null,null,[null,null,[[[3,null,null,[null,[[\x22lr_\x22,1,6],[\x22lr_lang_1vi\x22,0,6]],0]],[3,null,null,[null,[[\x22qdr_\x22,1,6],[\x22qdr_h\x22,0,6],[\x22qdr_d\x22,0,6],[\x22qdr_w\x22,0,6],[\x22qdr_m\x22,0,6],[\x22qdr_y\x22,0,6],[\x22cdr_opt\x22,0,1,[1,\x22Phạm vi tùy chỉnh...\x22,null,\x22cdr:1,cd_min:x,cd_max:x\x22,\x22\x22,\x22text\x22,\x22\x22,\x22\x22,6,null,[[[\x22q\x22,\x22code mau token google\x22],[\x22sca_esv\x22,\x22571531489\x22]]],\x22cdr_opt\x22,\x2223/05/2004\x22,0]]],1]],[3,null,null,[null,[[\x22li_\x22,1,6],[\x22li_1\x22,0,6]],2]]],null,[\x22tbs\x22]]],null,null,[null,[[\x22/search?q\\u003dcode+mau+token+google\\u0026sca_esv\\u003d571531489\\u0026source\\u003dlnms\x22,null,null,\x22Tất cả\x22,1,0,1,null,null,\x22WEB\x22,[0,2],null,null,0],[\x22/search?q\\u003dcode+mau+token+google\\u0026sca_esv\\u003d571531489\\u0026tbm\\u003disch\\u0026source\\u003dlnms\x22,null,null,\x22Hình ảnh\x22,0,0,1,null,null,\x22IMAGES\x22,[6,2],null,null,6],[\x22/search?q\\u003dcode+mau+token+google\\u0026sca_esv\\u003d571531489\\u0026tbm\\u003dvid\\u0026source\\u003dlnms\x22,null,null,\x22Video\x22,0,0,1,null,null,\x22VIDEOS\x22,[13,2],null,null,13],[\x22/search?q\\u003dcode+mau+token+google\\u0026sca_esv\\u003d571531489\\u0026tbm\\u003dbks\\u0026source\\u003dlnms\x22,null,null,\x22Sách\x22,0,0,1,null,null,\x22BOOKS\x22,[2,2],null,null,2],[\x22/search?q\\u003dcode+mau+token+google\\u0026sca_esv\\u003d571531489\\u0026tbm\\u003dnws\\u0026source\\u003dlnms\x22,null,null,\x22Tin tức\x22,0,0,1,null,null,\x22NEWS\x22,[10,2],null,null,10]],[[\x22/search?q\\u003dcode+mau+token+google\\u0026sca_esv\\u003d571531489\\u0026tbm\\u003dshop\\u0026source\\u003dlnms\x22,null,null,\x22Mua sắm\x22,0,0,1,null,null,\x22SHOPPING\x22,[12,2],null,null,12],[\x22https://www.google.com/travel/flights?q\\u003dcode+mau+token+google\\u0026sca_esv\\u003d571531489\\u0026tbm\\u003dflm\\u0026source\\u003dlnms\x22,null,null,\x22Chuyến bay\x22,0,0,1,null,null,\x22FLIGHTS\x22,[20,2],null,null,20],[\x22//www.google.com/finance\x22,null,null,\x22Tài chính\x22,0,0,1,null,null,\x22FINANCE\x22,[22,2],null,null,22]]]]', 'ANVEfk', '[4,1,null,null,1,1,0,0,0,0,0,0]', 'ANVEfo', '[\x22\x22,6,0]', 'ANVEfs', '[\x22\x22,4,0]', 'ANVEf4', '[null,null,null,null,null,null,null,null,null,null,null,null,0,[[[null,null,null,null,null,[\x22\x22,\x22https://webcache.googleusercontent.com/search?q\\u003dcache:FO0J9t0J534J:https://support.haravan.com/support/solutions/articles/42000087477-c%25C3%25A1ch-l%25E1%25BA%25A5y-m%25C3%25A3-google-api-key\\u0026cd\\u003d1\\u0026hl\\u003dvi\\u0026ct\\u003dclnk\\u0026gl\\u003dvn\x22,null,[null,[32,null,2]],null,null,null,[[\x22Bản\\u0026nbsp;lưu\x22]]]]]],null,null,null,\x22\x22,null,\x22WEB_RESULT_INNER\x22,[],0,[null,null,null,null,null,null,[null,null,null,\x22/search/about-this-result?origin\\u003dwww.google.com\\u0026ons\\u003d2586\\u0026ri\\u003dChMSCAoEY29kZRADGgcKA23DoxADCgkSBwoDbWF1EAMKDBIKCgZnb29nbGUQAxIAGgAiACoAMgYIARICdm46AEIECAEQQkoAWgBqAHIA\\u0026fd\\u003dGgIIAQ\\u0026dis\\u003dEAE\\u0026url\\u003dhttps%3A%2F%2Fsupport.haravan.com%2Fsupport%2Fsolutions%2Farticles%2F42000087477-c%25C3%25A1ch-l%25E1%25BA%25A5y-m%25C3%25A3-google-api-key\\u0026hl\\u003dvi_VN\\u0026gl\\u003dVN\x22],\x22https://www.google.com\x22],0,[],0,0,0,0]', 'ANVEf8', '[\x22https://support.haravan.com/support/solutions/articles/42000087477-c%C3%A1ch-l%E1%BA%A5y-m%C3%A3-google-api-key\x22,\x22Cách lấy mã Google API Key\x22,\x221. Tạo Google App · 2. Tạo giấy giới thiệu · 3. Tạo Google API cho Google Maps · 4. Tạo API để đăng nhập bằng tài khoản Google ...\x22,1,\x22vi\x22,\x22VN\x22,null,\x22/s?tbm\\u003dmap\\u0026gs_ri\\u003dmaps\\u0026suggest\\u003dp\x22,\x22ALook6xyqGxte6Y6DweP7uhI7smToqXYoQ:1696673079819\x22]', 'ANVEfw', '[null,null,null,null,null,null,null,null,null,null,null,null,0,[[[null,null,null,null,null,[\x22\x22,\x22https://webcache.googleusercontent.com/search?q\\u003dcache:EkSjFlWqDp4J:https://viblo.asia/p/thao-tac-voi-google-drive-api-znmMd050Mr69\\u0026cd\\u003d2\\u0026hl\\u003dvi\\u0026ct\\u003dclnk\\u0026gl\\u003dvn\x22,null,[null,[32,null,2]],null,null,null,[[\x22Bản\\u0026nbsp;lưu\x22]]]]]],null,null,null,\x22\x22,null,\x22WEB_RESULT_INNER\x22,[],0,[null,null,null,null,null,null,[null,null,null,\x22/search/about-this-result?origin\\u003dwww.google.com\\u0026ons\\u003d2586\\u0026ri\\u003dCgoSCAoEY29kZRADChQSBwoDbWF1EAMaCQoFbeG6q3UQAwoLEgkKBXRva2VuEAMKDBIKCgZnb29nbGUQAxIAGgAiACoAMgYIARICdm46AEIECAEQQkoAWgBqAHIA\\u0026fd\\u003dGgIIAQ\\u0026dis\\u003dEAE\\u0026url\\u003dhttps%3A%2F%2Fviblo.asia%2Fp%2Fthao-tac-voi-google-drive-api-znmMd050Mr69\\u0026hl\\u003dvi_VN\\u0026gl\\u003dVN\x22],\x22https://www.google.com\x22],0,[],0,0,0,0]', 'ANVEf0', '[\x22https://viblo.asia/p/thao-tac-voi-google-drive-api-znmMd050Mr69\x22,\x22Thao tác với Google Drive API\x22,\x22Việc sử dụng gem google-api-client giúp chúng ta không cần phải thao tác trực tiếp với token ... Bài viết trên đã mô tả các bước thực hiện, có code mẫu cũng như ...\x22,1,\x22vi\x22,\x22VN\x22,null,\x22/s?tbm\\u003dmap\\u0026gs_ri\\u003dmaps\\u0026suggest\\u003dp\x22,\x22ALook6xyqGxte6Y6DweP7uhI7smToqXYoQ:1696673079819\x22]', 'ANVEgA', '[null,null,null,null,null,null,null,null,null,null,null,null,0,[[[null,null,null,null,null,[\x22\x22,\x22https://webcache.googleusercontent.com/search?q\\u003dcache:jiuWVmfDlV4J:https://g.suite.vn/index.php%3Frp%3D/knowledgebase/8/huong-dan-tao-g-suite-transfer-token.html\\u0026cd\\u003d3\\u0026hl\\u003dvi\\u0026ct\\u003dclnk\\u0026gl\\u003dvn\x22,null,[null,[32,null,2]],null,null,null,[[\x22Bản\\u0026nbsp;lưu\x22]]]]]],null,null,null,\x22\x22,null,\x22WEB_RESULT_INNER\x22,[],0,[null,null,null,null,null,null,[null,null,null,\x22/search/about-this-result?origin\\u003dwww.google.com\\u0026ons\\u003d2586\\u0026ri\\u003dCgkSBwoDbWF1EAMKCxIJCgV0b2tlbhADCgwSCgoGZ29vZ2xlEAMSABoAIgAqADIGCAESAnZuOgBCBAgBEEJKAFoAagByAA\\u0026fd\\u003dGgIIAQ\\u0026dis\\u003dEAE\\u0026url\\u003dhttps%3A%2F%2Fg.suite.vn%2Findex.php%3Frp%3D%2Fknowledgebase%2F8%2Fhuong-dan-tao-g-suite-transfer-token.html\\u0026hl\\u003dvi_VN\\u0026gl\\u003dVN\x22],\x22https://www.google.com\x22],0,[],0,0,0,0]', 'ANVEgI', '[\x22https://g.suite.vn/index.php?rp\\u003d/knowledgebase/8/huong-dan-tao-g-suite-transfer-token.html\x22,\x22Hướng dẫn tạo G Suite Transfer Token - Kiến thức chung\x22,\x22Để tạo được Transfer Token bạn cần làm theo các bước sau: Bước 1: Truy cập trang https://admin.google.com/TransferToken. Bước 2: Đăng nhập với tài khoản ...\x22,1,\x22vi\x22,\x22VN\x22,null,\x22/s?tbm\\u003dmap\\u0026gs_ri\\u003dmaps\\u0026suggest\\u003dp\x22,\x22ALook6xyqGxte6Y6DweP7uhI7smToqXYoQ:1696673079819\x22]', 'ANVEgE', '[null,null,null,null,null,null,null,null,null,null,null,null,0,[[[null,null,null,null,null,[\x22\x22,\x22https://webcache.googleusercontent.com/search?q\\u003dcache:8mC0QclWVCMJ:https://viblo.asia/p/tim-hieu-doi-chut-ve-oauth2-eW65GvMLlDO\\u0026cd\\u003d4\\u0026hl\\u003dvi\\u0026ct\\u003dclnk\\u0026gl\\u003dvn\x22,null,[null,[32,null,2]],null,null,null,[[\x22Bản\\u0026nbsp;lưu\x22]]]]]],null,null,null,\x22\x22,null,\x22WEB_RESULT_INNER\x22,[],0,[null,null,null,null,null,null,[null,null,null,\x22/search/about-this-result?origin\\u003dwww.google.com\\u0026ons\\u003d2586\\u0026ri\\u003dCgoSCAoEY29kZRADCgsSCQoFdG9rZW4QAwoMEgoKBmdvb2dsZRADEgAaACIAKgAyBggBEgJ2bjoAQgQIARBCSgBaAGoAcgA\\u0026fd\\u003dGgIIAQ\\u0026dis\\u003dEAE\\u0026url\\u003dhttps%3A%2F%2Fviblo.asia%2Fp%2Ftim-hieu-doi-chut-ve-oauth2-eW65GvMLlDO\\u0026hl\\u003dvi_VN\\u0026gl\\u003dVN\x22],\x22https://www.google.com\x22],0,[],0,0,0,0]', 'ANVEgM', '[\x22https://viblo.asia/p/tim-hieu-doi-chut-ve-oauth2-eW65GvMLlDO\x22,\x22Tìm hiểu đôi chút về OAuth2\x22,\x22Access token chỉ được sử dụng một lần duy nhất, khi nó hết hiệu lực Client sẽ phải gửi lại yêu cầu đến Authorization server để lấy một mã access token mới.\x22,1,\x22vi\x22,\x22VN\x22,null,\x22/s?tbm\\u003dmap\\u0026gs_ri\\u003dmaps\\u0026suggest\\u003dp\x22,\x22ALook6xyqGxte6Y6DweP7uhI7smToqXYoQ:1696673079819\x22]', 'ANVEgY', '[null,null,null,null,null,null,null,null,null,null,null,null,0,[[[null,null,null,null,null,[\x22\x22,\x22http://webcache.googleusercontent.com/search?q\\u003dcache:oBwXAckby-MJ:manuals.ts24.com.vn/support/solutions/articles/16000145545-t%25E1%25BA%25A1o-access-token\\u0026cd\\u003d5\\u0026hl\\u003dvi\\u0026ct\\u003dclnk\\u0026gl\\u003dvn\x22,null,[null,[32,null,2]],null,null,null,[[\x22Bản\\u0026nbsp;lưu\x22]]]]]],null,null,null,\x22\x22,null,\x22WEB_RESULT_INNER\x22,[],0,[null,null,null,null,null,null,[null,null,null,\x22/search/about-this-result?origin\\u003dwww.google.com\\u0026ons\\u003d2586\\u0026ri\\u003dCgoSCAoEY29kZRADChQSBwoDbWF1EAMaCQoFbeG6q3UQAwoLEgkKBXRva2VuEAMKDBIKCgZnb29nbGUQAxIAGgAiACoAMgYIARICdm46AEIECAEQQkoAWgBqAHIA\\u0026fd\\u003dGgIIAQ\\u0026dis\\u003dEAE\\u0026url\\u003dhttp%3A%2F%2Fmanuals.ts24.com.vn%2Fsupport%2Fsolutions%2Farticles%2F16000145545-t%25E1%25BA%25A1o-access-token\\u0026hl\\u003dvi_VN\\u0026gl\\u003dVN\x22],\x22https://www.google.com\x22],0,[],0,0,0,0]', 'ANVEgg', '[\x22http://manuals.ts24.com.vn/support/solutions/articles/16000145545-t%E1%BA%A1o-access-token\x22,\x22Tạo Access Token - Hướng dẫn sử dụng\x22,\x22Lập hồ sơ từ Google Forms | Tải tập tin mẫu về Drive · Lập hồ sơ từ Google ... (*) Chuỗi mã Access Token này chỉ xuất hiện 1 lần duy nhất; sau khi đóng bảng ...\x22,1,\x22vi\x22,\x22VN\x22,null,\x22/s?tbm\\u003dmap\\u0026gs_ri\\u003dmaps\\u0026suggest\\u003dp\x22,\x22ALook6yWw_UCDjgnxH_wctBdXXEpfVv66Q:1696673079830\x22]', 'ANVEg4', '[null,null,null,null,null,null,null,null,null,null,null,null,0,[[[null,null,null,null,null,[\x22\x22,\x22https://webcache.googleusercontent.com/search?q\\u003dcache:TAZVnZK8RhEJ:https://duthanhduoc.com/blog/p5-giai-ngo-authentication-OAuth2\\u0026cd\\u003d6\\u0026hl\\u003dvi\\u0026ct\\u003dclnk\\u0026gl\\u003dvn\x22,null,[null,[32,null,2]],null,null,null,[[\x22Bản\\u0026nbsp;lưu\x22]]]]]],null,null,null,\x22\x22,null,\x22WEB_RESULT_INNER\x22,[],0,[null,null,null,null,null,null,[null,null,null,\x22/search/about-this-result?origin\\u003dwww.google.com\\u0026ons\\u003d2586\\u0026ri\\u003dCgoSCAoEY29kZRADCgsSCQoFdG9rZW4QAwoMEgoKBmdvb2dsZRADEgAaACIAKgAyBggBEgJ2bjoAQgQIARBCSgBaAGoAcgA\\u0026fd\\u003dGgIIAQ\\u0026dis\\u003dEAE\\u0026url\\u003dhttps%3A%2F%2Fduthanhduoc.com%2Fblog%2Fp5-giai-ngo-authentication-OAuth2\\u0026hl\\u003dvi_VN\\u0026gl\\u003dVN\x22],\x22https://www.google.com\x22],0,[],0,0,0,0]', 'ANVEg8', '[\x22https://duthanhduoc.com/blog/p5-giai-ngo-authentication-OAuth2\x22,\x22[P5] Giải ngố authentication: OAuth 2.0\x22,\x22Server sẽ lấy được giá trị code thông qua query và tiến hành gọi lên Google API để lấy thông tin id_token và access_token . Server sẽ lấy thông ...\x22,1,\x22vi\x22,\x22VN\x22,null,\x22/s?tbm\\u003dmap\\u0026gs_ri\\u003dmaps\\u0026suggest\\u003dp\x22,\x22ALook6xK0L6cfZ14Oxx4E4t73zUqAZRNSg:1696673079831\x22]', 'ANVEgw', '[null,null,null,null,null,null,null,null,null,null,null,null,0,[[[null,null,null,null,null,[\x22\x22,\x22https://webcache.googleusercontent.com/search?q\\u003dcache:m3LCu1Y2jiYJ:https://autoitvn.com/threads/get-access_token-authorization-oauth-2-0-ho-tro-tuong-tac-google-apis-nhu-gmail-youtube.631/\\u0026cd\\u003d7\\u0026hl\\u003dvi\\u0026ct\\u003dclnk\\u0026gl\\u003dvn\x22,null,[null,[32,null,2]],null,null,null,[[\x22Bản\\u0026nbsp;lưu\x22]]]]]],null,null,null,\x22\x22,null,\x22WEB_RESULT_INNER\x22,[],0,[null,null,null,null,null,null,[null,null,null,\x22/search/about-this-result?origin\\u003dwww.google.com\\u0026ons\\u003d2586\\u0026ri\\u003dCgoSCAoEY29kZRADCgkSBwoDbWF1EAMKCxIJCgV0b2tlbhADCgwSCgoGZ29vZ2xlEAMSAggAGgAiACoAMgYIARICdm46AEIECAEQQkoAWgBqAHIA\\u0026fd\\u003dGgIIAQ\\u0026dis\\u003dEAE\\u0026url\\u003dhttps%3A%2F%2Fautoitvn.com%2Fthreads%2Fget-access_token-authorization-oauth-2-0-ho-tro-tuong-tac-google-apis-nhu-gmail-youtube.631%2F\\u0026hl\\u003dvi_VN\\u0026gl\\u003dVN\x22],\x22https://www.google.com\x22],0,[],0,0,0,0]', 'ANVEg0', '[\x22https://autoitvn.com/threads/get-access_token-authorization-oauth-2-0-ho-tro-tuong-tac-google-apis-nhu-gmail-youtube.631/\x22,\x22UDF - Get access_token - Authorization (oAuth 2.0) hỗ trợ ...\x22,\x22... google.com/identity/protocols/OAuth2WebServer. Cơ bản là ta phải Tạo Credentials \\u003e oAuth Client ID \\u003e Exchange Code \\u003e Access Token *** Các ...\x22,1,\x22vi\x22,\x22VN\x22,null,\x22/s?tbm\\u003dmap\\u0026gs_ri\\u003dmaps\\u0026suggest\\u003dp\x22,\x22ALook6yWw_UCDjgnxH_wctBdXXEpfVv66Q:1696673079830\x22]', 'ANVEhA', '[null,null,null,null,null,null,null,null,null,null,null,null,0,[[[null,null,null,null,null,[\x22\x22,\x22https://webcache.googleusercontent.com/search?q\\u003dcache:qLDh36kixUAJ:https://developers.google.com/search/apis/indexing-api/v3/core-errors%3Fhl%3Dvi\\u0026cd\\u003d8\\u0026hl\\u003dvi\\u0026ct\\u003dclnk\\u0026gl\\u003dvn\x22,null,[null,[32,null,2]],null,null,null,[[\x22Bản\\u0026nbsp;lưu\x22]]]]]],null,null,null,\x22\x22,null,\x22WEB_RESULT_INNER\x22,[],0,[null,null,null,null,null,null,[null,null,null,\x22/search/about-this-result?origin\\u003dwww.google.com\\u0026ons\\u003d2586\\u0026ri\\u003dCgoSCAoEY29kZRADCgkSBwoDbWF1EAMKDBIKCgZnb29nbGUQAxIAGgAiACoAMgYIARICdm46AEIECAEQQkoAWgBqAHIA\\u0026fd\\u003dGgIIAQ\\u0026dis\\u003dEAE\\u0026url\\u003dhttps%3A%2F%2Fdevelopers.google.com%2Fsearch%2Fapis%2Findexing-api%2Fv3%2Fcore-errors%3Fhl%3Dvi\\u0026hl\\u003dvi_VN\\u0026gl\\u003dVN\x22],\x22https://www.google.com\x22],0,[],0,0,0,0]', 'ANVEhE', '[\x22https://developers.google.com/search/apis/indexing-api/v3/core-errors?hl\\u003dvi\x22,\x22Lỗi gặp phải khi sử dụng API Lập chỉ mục\x22,\x22Hãy khám phá danh sách thông báo và nội dung mô tả lỗi liên quan đến API Lập chỉ mục, ngoài các lỗi chính áp dụng cho mọi API của Google.\x22,1,\x22vi\x22,\x22VN\x22,null,\x22/s?tbm\\u003dmap\\u0026gs_ri\\u003dmaps\\u0026suggest\\u003dp\x22,\x22ALook6xK0L6cfZ14Oxx4E4t73zUqAZRNSg:1696673079831\x22]', 'ANVEgo', '[null,null,null,null,null,null,null,null,null,null,null,null,0,[[[null,null,null,null,null,[\x22\x22,\x22https://webcache.googleusercontent.com/search?q\\u003dcache:5CSRWClsjN8J:https://wiki.matbao.net/token-la-gi-nen-dau-tu-tien-dien-tu-coin-hay-token/\\u0026cd\\u003d9\\u0026hl\\u003dvi\\u0026ct\\u003dclnk\\u0026gl\\u003dvn\x22,null,[null,[32,null,2]],null,null,null,[[\x22Bản\\u0026nbsp;lưu\x22]]]]]],null,null,null,\x22\x22,null,\x22WEB_RESULT_INNER\x22,[],0,[null,null,null,null,null,null,[null,null,null,\x22/search/about-this-result?origin\\u003dwww.google.com\\u0026ons\\u003d2586\\u0026ri\\u003dCgkSBwoDbWF1EAMKCxIJCgV0b2tlbhADCgwSCgoGZ29vZ2xlEAMSAggAGgAiACoAMgYIARICdm46AEIECAEQQkoAWgBqAHIA\\u0026fd\\u003dGgIIAQ\\u0026dis\\u003dEAE\\u0026url\\u003dhttps%3A%2F%2Fwiki.matbao.net%2Ftoken-la-gi-nen-dau-tu-tien-dien-tu-coin-hay-token%2F\\u0026hl\\u003dvi_VN\\u0026gl\\u003dVN\x22],\x22https://www.google.com\x22],0,[],0,0,0,0]', 'ANVEgs', '[\x22https://wiki.matbao.net/token-la-gi-nen-dau-tu-tien-dien-tu-coin-hay-token/\x22,\x22Token là gì? Hướng dẫn cách cài đặt Token đơn giản nhất\x22,\x22Token là một loại tiền điện tử (tiền mã hóa) được tạo ra và hoạt động dựa trên một nền tảng blockchain có sẵn. Đây chỉ là định nghĩa về Token. Để thực sự hiểu ...\x22,1,\x22vi\x22,\x22VN\x22,null,\x22/s?tbm\\u003dmap\\u0026gs_ri\\u003dmaps\\u0026suggest\\u003dp\x22,\x22ALook6xK0L6cfZ14Oxx4E4t73zUqAZRNSg:1696673079831\x22]', 'ANVEgc', '[null,null,null,null,null,null,null,null,null,null,null,null,0,[[[null,null,null,null,null,[\x22\x22,\x22https://webcache.googleusercontent.com/search?q\\u003dcache:mkZJJP1kPTwJ:https://bkhost.vn/blog/oauth-2/\\u0026cd\\u003d10\\u0026hl\\u003dvi\\u0026ct\\u003dclnk\\u0026gl\\u003dvn\x22,null,[null,[32,null,2]],null,null,null,[[\x22Bản\\u0026nbsp;lưu\x22]]]]]],null,null,null,\x22\x22,null,\x22WEB_RESULT_INNER\x22,[],0,[null,null,null,null,null,null,[null,null,null,\x22/search/about-this-result?origin\\u003dwww.google.com\\u0026ons\\u003d2586\\u0026ri\\u003dCgoSCAoEY29kZRADChQSBwoDbWF1EAMaCQoFbeG6q3UQAwoLEgkKBXRva2VuEAMKDBIKCgZnb29nbGUQAxIAGgAiACoAMgYIARICdm46AEIECAEQQkoAWgBqAHIA\\u0026fd\\u003dGgIIAQ\\u0026dis\\u003dEAE\\u0026url\\u003dhttps%3A%2F%2Fbkhost.vn%2Fblog%2Foauth-2%2F\\u0026hl\\u003dvi_VN\\u0026gl\\u003dVN\x22],\x22https://www.google.com\x22],0,[],0,0,0,0]', 'ANVEgk', '[\x22https://bkhost.vn/blog/oauth-2/\x22,\x22OAuth 2 là gì? Vai trò và cách thức hoạt động của OAuth 2.0\x22,\x22Ở quy trình ngầm định này, Access token được Authorization Server trả lại dưới dạng callback URI biểu mẫu. Authorization Code Grant with Proof ...\x22,1,\x22vi\x22,\x22VN\x22,null,\x22/s?tbm\\u003dmap\\u0026gs_ri\\u003dmaps\\u0026suggest\\u003dp\x22,\x22ALook6yWw_UCDjgnxH_wctBdXXEpfVv66Q:1696673079830\x22]', 'ANVEgQ', '[null,null,null,null,null,null,null,null,null,null,null,null,0,[],null,null,null,\x22\x22,0,\x22EXPLORE_UNIVERSAL_BOTTOM_BLOCK\x22,null,0,[null,null,null,null,null,null,[null,null,null,\x22/search/about-this-result?origin\\u003dwww.google.com\\u0026ons\\u003d3560\\u0026ri\\u003d\\u0026fd\\u003dCgwKBAgwSBAKBAg_UEISBAoCCA8aAggB\\u0026dis\\u003dEAE\\u0026hl\\u003dvi_VN\\u0026gl\\u003dVN\x22],\x22https://www.google.com\x22],0,[],0,0,0,0]', 'ANVEgU', '[]', 'ANVEfU', '[\x22code mau token google\x22,null,null,\x22all\x22,350,5,1,null,null,0,null,1,1,null,null,null,\x22all\x22,0,\x22srp_1\x22,null,null,10,\x22/search?q\\u003dcode+mau+token+google\\u0026sca_esv\\u003d571531489\\u0026ei\\u003dNy0hZajKHuSv2roPysWswAY\\u0026start\\u003d10\\u0026sa\\u003dN\x22,0,0,null,0,null,null,0,null,null,null,null,null,null,null,0,null,null,null,null,null,null,null,null,null,null,null,0,\x22\x22,\x22\x22,null,null,null,null,\x22NONE\x22,null,null,null,null,0,null,\x22NONE\x22,0,0,0,\x22\x22,0,[],1,0,null,null,0,0,0,0,0,0,null,0,10,0,5]', 'ANVEfI', '[null,null,1,null,null,null,null,null,null,null,3,null,null,null,null,null,null,null,null,null,1,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,1,null,null,[\x2286400000\x22,\x22604800000\x22,2],null,null,null,null,null,null,null,null,null,null,null,null,null,0,1,null,null,null,null,null,null,null,1,1,\x22DESKTOP_CHROME\x22,1]', 'ANVEfQ', '[null,null,null,1,[\x22bshqp\x22,\x22bshwcqp\x22,\x22rimc\x22,\x22rime\x22]]', 'ANVEfY', '[4,\x22AUNGdZXoM8g_MvqwMIFByD_7wrvMcMj9P_Sf98kryv0_\x22]', 'ANVEfc', '[1,null,null,1,0,0,0,null,0]', 'ANVEfg', '[null,null,1,null,null,null,1,1]', 'tq7Pxb', '[[[\x22q49bvd\x22,0],[\x22LrGvF\x22,0],[\x22VXIo7d\x22,null,\x228px\x22],[\x22LACYrf\x22,0],[\x22TW7Aod\x22,1],[\x22ziwEW\x22,null,\x22#70757a\x22],[\x22SA0BPe\x22,1],[\x22IBWrx\x22,null,null,18],[\x22AoIPu\x22,1],[\x22EgTnfe\x22,1],[\x22CgDdte\x22,1],[\x22I6R5lf\x22,null,\x22#f8f9fa\x22],[\x22v4iQCe\x22,null,\x22#4285f4\x22],[\x22IfdAAd\x22,null,\x22#70757a\x22],[\x22Sa67Pc\x22,null,\x22rgba(32,33,36,.28)\x22],[\x22OmYlge\x22,null,\x22#34a853\x22],[\x22H4gDmf\x22,null,\x22#ea4335\x22],[\x22KkPbyc\x22,null,\x22#fbbc04\x22],[\x22o28sBd\x22,0],[\x22QQVhX\x22,0],[\x22ULXB9b\x22,0],[\x22r9V7hf\x22,0],[\x22FEmOOb\x22,null,null,48],[\x22cWwp7b\x22,0],[\x22wsRfI\x22,0],[\x22WkjuOe\x22,0],[\x22h6eQZc\x22,0],[\x22b0Jode\x22,0],[\x22WitVqe\x22,1],[\x22YjL9Ce\x22,0],[\x22mIjP6d\x22,0],[\x22m8l8td\x22,null,\x22CARET\x22],[\x22QuXhMb\x22,0],[\x22JyBo2c\x22,0],[\x22bmQ7Rb\x22,0],[\x22xT28q\x22,0],[\x22VBSc8c\x22,0],[\x22qdoinb\x22,null,\x22#70757a\x22],[\x22HjM8R\x22,null,\x22#fff\x22],[\x22JdPOaf\x22,0],[\x22bDOvJc\x22,0],[\x22HCImye\x22,0],[\x22zBxT5\x22,1],[\x22m4Aoxd\x22,0],[\x22SOoLvb\x22,null,null,8],[\x22MRtzJd\x22,0],[\x22kjIzLb\x22,1],[\x22voc95c\x22,0],[\x22I3x8Lb\x22,1],[\x22qmcJmd\x22,null,null,6],[\x22aZFNNe\x22,1],[\x22Rvxsx\x22,null,\x221px solid #dadce0\x22],[\x22xNPzic\x22,null,\x22#fff\x22],[\x22rzzybc\x22,null,\x22#d93025\x22],[\x22zRpUk\x22,null,\x22#4285f4\x22],[\x22sBpVac\x22,null,\x22rgba(0,0,0,.26)\x22],[\x22JuqxTb\x22,null,\x22#202124\x22],[\x22Fcb4A\x22,null,\x22#1a73e8\x22],[\x22yqqDTc\x22,0],[\x22uDSxz\x22,null,\x22#dadce0\x22],[\x22oHxv0d\x22,null,null,16],[\x22A1m1qe\x22,1],[\x22Y6rSjc\x22,1],[\x22ghpS4b\x22,null,\x22#d2e3fc\x22],[\x22Zun3Ef\x22,0],[\x22AP8pqf\x22,null,\x22#dadce0\x22],[\x22ZMIIMe\x22,1],[\x22LVoecd\x22,null,\x22rgba(0,0,0,.16)\x22],[\x22yHlFbb\x22,null,\x22rgba(0,0,0,.40)\x22],[\x22OL2x3c\x22,0],[\x22wFGKdc\x22,0],[\x22ywhzh\x22,0],[\x22HIMA4e\x22,0],[\x22m2hzy\x22,0],[\x22Lxmjn\x22,1],[\x22FydCC\x22,1],[\x22wku5sd\x22,0],[\x22pbvXic\x22,1],[\x22j7hDXe\x22,0],[\x22rRH6Ed\x22,null,\x22#1a73e8\x22],[\x22DU6xHc\x22,0],[\x22XuC5Td\x22,null,null,24],[\x22g34kCb\x22,0],[\x22h58vfb\x22,0],[\x22vhNSCe\x22,0],[\x22lYyelb\x22,null,\x22rgba(0,0,0,.54)\x22],[\x22oY6Swe\x22,0],[\x22cGEPwe\x22,0],[\x22vNcih\x22,0],[\x22WOsyy\x22,0],[\x22Fa0cAb\x22,0],[\x22g2CbC\x22,null,null,1],[\x22gSzSKd\x22,null,\x22\x22],[\x22G0mITe\x22,0],[\x22pnaHhb\x22,0],[\x22rEYaZe\x22,null,\x22\x22],[\x22xXrl9\x22,null,\x22\x22],[\x22V4p6F\x22,0],[\x22uXUEhb\x22,0],[\x22mNmrAb\x22,null,\x22#ebebeb\x22],[\x22JJFoUe\x22,1],[\x22o40Eoc\x22,0],[\x22irjI3c\x22,0],[\x22xnaMFd\x22,null,\x22feedback\x22],[\x22ptnYGd\x22,null,\x22[[[\\\x22box-shadow\\\x22,\\\x22box-shadow\\\x22],[\\\x22box-sizing\\\x22,\\\x22box-sizing\\\x22],[\\\x22keyframes\\\x22,\\\x22keyframes\\\x22],[\\\x22border-radius\\\x22,\\\x22border-radius\\\x22],[\\\x22transform\\\x22,\\\x22transform\\\x22],[\\\x22transform-origin\\\x22,\\\x22transform-origin\\\x22],[\\\x22flex-direction\\\x22,\\\x22flex-direction\\\x22],[\\\x22flex-grow\\\x22,\\\x22flex-grow\\\x22],[\\\x22flex\\\x22,\\\x22flex\\\x22]]]\x22]]]'];
                var a = m;
                window.W_jd = window.W_jd || {};
                for (var b = 0; b < a.length; b += 2)
                    window.W_jd[a[b]] = JSON.parse(a[b + 1]);
            }
            )();
            (function() {
                window.WIZ_global_data = {
                    "NCGTLe": "%.@.\"ANIgHNnuViWpORO61cLK1cVmeWe+qC7m160vGUUeVGva4Fck/IvHwY8l2OZn5dl31DDRGVpYLrY0iIG3fby8iLao+lzC34I0Ng\\u003d\\u003d\"]",
                    "S6lZl": "89978449",
                    "eptZe": "/wizrpcui/_/WizRpcUi/",
                    "S06Grb": "",
                    "Im6cmf": "/wizrpcui/_/WizRpcUi",
                    "Yllh3e": "%.@.1696673079501032,22452196,1745560266]",
                    "SNlM0e": "",
                    "GWsdKe": "vi-VN",
                    "LVIXXb": "1",
                    "QrtxK": "0",
                    "w2btAe": "%.@.\"\",\"\",\"0\",null,null,null,1]",
                    "oxN3nb": {
                        "1": false
                    },
                    "zChJod": "%.@.]"
                };
                window.IJ_values = {
                    "eG8Zqf": 1.0,
                    "IvNqzc": true,
                    "ZAVjNb": false,
                    "oI8LH": false,
                    "IXFWPb": false,
                    "vSjUZd": 24,
                    "P59QTc": false,
                    "gfq1Ic": false,
                    "HKzGBb": false,
                    "B4LUOc": false,
                    "q9jm5e": false,
                    "zIfn3e": false,
                    "bs2drc": false,
                    "hnypGb": false,
                    "yys2yc": false,
                    "Rbaz9c": false,
                    "SoPmHd": true,
                    "lCCykc": false,
                    "ro3IRe": false,
                    "eflcTd": false,
                    "NdHRde": false,
                    "MlUHWc": false,
                    "CzxWj": false,
                    "kyqNwe": false,
                    "ucii4d": false,
                    "vwAn2d": false,
                    "hK1XQe": "#fff",
                    "O3122d": 14,
                    "CUOpOb": 18,
                    "KrguY": "#ecedef",
                    "DONkrd": "#f1f3f4",
                    "AILAfd": "#0060f0",
                    "WdWVbc": false,
                    "Tv95nc": false,
                    "urls1d": false,
                    "mhcbZb": false,
                    "ogmk0d": false,
                    "RK9az": false,
                    "T62UHb": false,
                    "jCekpb": false,
                    "cTU58": false,
                    "kRerQb": false,
                    "oS0end": false,
                    "AoIPu": true,
                    "CieUQe": true,
                    "HCMJkf": true,
                    "zNiNDd": false,
                    "EsWLY": false,
                    "XP4Noc": false,
                    "jqcxU": "#4285f4",
                    "toVELc": "#f8f9fa",
                    "V1TJEb": "#1a73e8",
                    "eavN9c": 36,
                    "XuC5Td": 24,
                    "ivyWed": 28,
                    "psmQyf": 6,
                    "osNyZ": 1.0,
                    "L6WyEf": true,
                    "tswRXd": "none",
                    "vq4Rhf": true,
                    "mtmrtb": "0 1px 6px rgba(32,33,36,0.28)",
                    "hOdcKb": false,
                    "vkQXZ": "#fff",
                    "U2GTk": "#fff",
                    "WgRLme": "#dadce0",
                    "QcZxSd": "#3c4043",
                    "g4ToDf": "0 1px 2px rgba(60,64,67,.3), 0 2px 6px 2px rgba(60,64,67,.15)",
                    "AsC4Mb": "#9aa0a6",
                    "mub7Fd": "#f1f3f4",
                    "z2SQwf": "#bdc1c6",
                    "ob4Y0c": "#e8eaed",
                    "M1fk3b": "#dadce0",
                    "gWINCf": "#9aa0a6",
                    "I6R5lf": "#f8f9fa",
                    "KCMXVb": "#202124",
                    "vzRvgb": "#e8f0fe",
                    "HNLwz": "#d2e3fc",
                    "uD3Lwc": "#d2e3fc",
                    "MLAA8d": "0 1px 2px rgba(66,133,244,.3), 0 1px 3px 1px rgba(66,133,244,.15)",
                    "TqDTGf": "#aecbfa",
                    "m7EnTc": "#8ab4f8",
                    "jyEUXe": "#d2e3fc",
                    "QyzZ8e": "#174ea6",
                    "CFgsb": "#1558d6",
                    "lYyelb": "rgba(0,0,0,.54)",
                    "gdL5yf": "rgba(0,0,0,.26)",
                    "uWxHhb": "#fff",
                    "tCxmde": "rgba(255,255,255,.30)",
                    "m0RlKb": false,
                    "wFGKdc": false,
                    "klgere": "invert(1) hue-rotate(180deg)",
                    "gHo7b": "#b8bbbe",
                    "VBSc8c": false,
                    "oX2r2c": true,
                    "WitVqe": true,
                    "JuXRyb": true,
                    "zsYZK": "#dadce0",
                    "Pi4f8d": false,
                    "nNHNPc": false,
                    "VD4u1d": false,
                    "xxthqf": true,
                    "XIHhCb": true,
                    "UsVc8e": false,
                    "HIMA4e": false,
                    "YjL9Ce": false,
                    "wsRfI": false,
                    "UZoA2e": false,
                    "q49bvd": false,
                    "m2hzy": false,
                    "jBwTk": "#3c4043",
                    "eOLVib": 10,
                    "fTZUNc": false,
                    "YrTYaf": true,
                    "WvdhF": false,
                    "Rojixc": "#aecbfa",
                    "QOuvIc": "#1a73e8",
                    "hhsybf": false,
                    "Zxl9ce": false,
                    "OL2x3c": false,
                    "Zun3Ef": false,
                    "SOm4o": false,
                    "lL47Xc": false,
                    "l4Npee": false,
                    "tyCgpc": "#fff",
                    "H7aRye": "0px 5px 26px 0px rgba(0, 0, 0, 0.22), 0px 20px 28px 0px rgba(0, 0, 0, 0.30)",
                    "U6xP0": "#4285f4",
                    "A5tF3b": false,
                    "j0DpSe": false,
                    "GUwCvc": false,
                    "ilb27b": "#4285f4",
                    "jfyszc": "#1558d6",
                    "MpqkGd": "#202124",
                    "NXDvtf": false,
                    "Lxmjn": true,
                    "FydCC": true,
                    "ywhzh": false,
                    "EgTnfe": true,
                    "kAUP3b": false,
                    "hgWJ8c": false,
                    "TxsTcf": "#000",
                    "v4iQCe": "#4285f4",
                    "OfqeOe": "#4285f4",
                    "zRpUk": "#4285f4",
                    "QbZklb": "#e8f0fe",
                    "Fcb4A": "#1a73e8",
                    "VRtZRe": "#1558d6",
                    "OmYlge": "#34a853",
                    "y8HGgf": "#1e8e3e",
                    "QDXUyc": "#188038",
                    "JQWqub": "#ea4335",
                    "nRwuZd": "#d93025",
                    "rzzybc": "#d93025",
                    "rZLJJb": "#fff",
                    "hcLEtc": "#81c995",
                    "GJQmmf": "#34a853",
                    "hETIfb": "#dadce0",
                    "NtNjtd": "#dadce0",
                    "vCsrw": "#dadce0",
                    "p9416c": "#f8f9fa",
                    "toQ7tf": "#f8f9fa",
                    "xgY1nc": "#f8f9fa",
                    "p1ocJb": "#f8f9fa",
                    "FCLfBe": "#f8f9fa",
                    "MnC2zf": "#70757a",
                    "IfdAAd": "#70757a",
                    "fP2Yo": "#70757a",
                    "mknyu": "#70757a",
                    "PUenT": "#3c4043",
                    "Z0DEKf": "#202124",
                    "oHHKwf": "#202124",
                    "xNPzic": "#fff",
                    "KkPbyc": "#fbbc04",
                    "uezre": "#fbbc04",
                    "SkGiZd": "#f29900",
                    "OxPRr": "#f1f3f4",
                    "uiKEV": "#202124",
                    "bhxjsd": false,
                    "eCORE": false,
                    "Co7tHc": true,
                    "qcvoqe": false,
                    "BPltf": "#f1f3f4",
                    "kcrUme": 14,
                    "bKebqb": "#202124",
                    "m8l8td": "CARET",
                    "qeEJkc": 40,
                    "zHsZtb": "#3c4043",
                    "urZDtf": "#202124",
                    "zeWvtf": false,
                    "qdoinb": "#70757a",
                    "a4qLne": "#ea4335",
                    "RifN2d": "#000",
                    "Fpi7Rc": "arial,sans-serif-medium,sans-serif",
                    "a2ykac": "arial,sans-serif",
                    "ME4NMc": "#000",
                    "BpPAcd": "#dadce0",
                    "N0wyZ": "#000",
                    "jxZxne": "#70757a",
                    "CQvMbe": "#1a73e8",
                    "fRkoq": true,
                    "c4qycc": true,
                    "MWZX1c": 20,
                    "IBWrx": 18,
                    "N98mef": false,
                    "WkjuOe": false,
                    "mIjP6d": false,
                    "uJ8Xid": false,
                    "cWwp7b": false,
                    "h6eQZc": false,
                    "b0Jode": false,
                    "mo8CW": true,
                    "CAM7Vc": false,
                    "QuXhMb": false,
                    "fd9gQc": false,
                    "MomrM": false,
                    "Vb9YJ": true,
                    "OQZvxe": "0 2px 10px 0 rgba(0,0,0,0.2)",
                    "fI0P7e": true,
                    "Asoj0e": false,
                    "AP8pqf": "#dadce0",
                    "sBpVac": "rgba(0,0,0,.26)",
                    "JcUGee": "#70757a",
                    "PngPbb": "#202124",
                    "ENmP1c": "rgba(204,204,204,.15)",
                    "I69zkb": "rgba(204,204,204,.25)",
                    "ib0wve": "rgba(112,117,122,.20)",
                    "a8Umdd": "rgba(112,117,122,.40)",
                    "LVoecd": "rgba(0,0,0,.16)",
                    "yHlFbb": "rgba(0,0,0,.40)",
                    "seVajd": "rgba(0,0,0,.12)",
                    "esUgv": "#fff",
                    "KVmtZc": "rgba(255,255,255,.30)",
                    "MoAfyf": "#fff",
                    "oyB9kf": "#202124",
                    "bXvyY": "#fff",
                    "ALMSwe": "Roboto,RobotoDraft,Helvetica,Arial,sans-serif",
                    "Sgnmlc": "14px",
                    "qkXvHd": "500",
                    "SezQgf": "500",
                    "EJG4vf": "pointer",
                    "WyvaRd": "0 1px 1px rgba(0,0,0,.16)",
                    "ROAn0e": "0 2px 2px 0 rgba(0,0,0,.14),0 3px 1px -2px rgba(0,0,0,.2),0 1px 5px 0 rgba(0,0,0,.12)",
                    "rgHLF": true,
                    "KzjxBb": false,
                    "NQ4wzb": false,
                    "TLsp9d": false,
                    "S3hspc": false,
                    "RxFwtc": "0 4px 16px rgba(0,0,0,0.2)",
                    "aM8S7c": "#666",
                    "Tae7A": true,
                    "c5h25": true,
                    "MCowFd": false,
                    "LACYrf": false,
                    "uZLNF": true,
                    "wku5sd": false,
                    "JdPOaf": false,
                    "zBxT5": true,
                    "bDOvJc": false,
                    "HCImye": false,
                    "ZMIIMe": true,
                    "B0husb": true,
                    "o28sBd": false,
                    "n4eEIc": true,
                    "tqmosb": "#fff",
                    "HjM8R": "#fff",
                    "ruFjfe": false,
                    "FqP1Fc": "#000",
                    "SATNMc": "1px solid #dadce0",
                    "V0Bluc": "none",
                    "X1bUEc": "arial,sans-serif-medium,sans-serif",
                    "QZheGe": "Google Sans,arial,sans-serif-medium,sans-serif",
                    "LIYDac": "arial,sans-serif",
                    "mNmrAb": "#ebebeb",
                    "x0VCkc": "1px solid #dadce0",
                    "Rvxsx": "1px solid #dadce0",
                    "qmcJmd": 6,
                    "JuqxTb": "#202124",
                    "E6Gkjd": "0 2px 10px 0 rgba(0,0,0,0.2)",
                    "MClBOe": "rgba(0,0,0,0.1)",
                    "V6eh7c": 16,
                    "ZxI7Af": "#D8D7DC",
                    "sKPNrc": "#e6e6e6",
                    "AgJzQ": "rgba(255,255,255,0)",
                    "FagChc": "#f1f3f4",
                    "tCGJz": "#D8D7DC",
                    "oqx7yb": "#70757a",
                    "khoEPb": "#1a0dab",
                    "SfSmD": "#dadce0",
                    "auaxA": "#202124",
                    "qtDmFc": "rgba(255,255,255,0)",
                    "v44rSc": "#70757a",
                    "YkyDVb": false,
                    "s6k9tc": true,
                    "tdC6kd": true,
                    "fhD9ff": false,
                    "avBLic": true,
                    "UjGOq": false,
                    "sib8M": true,
                    "PGBLg": false,
                    "pWkoAb": false,
                    "IUj4Ye": true,
                    "KYi16e": false,
                    "wUvFOb": false,
                    "a1lsHe": true,
                    "z8cfje": false,
                    "kBxgab": true,
                    "aMqn0b": true,
                    "PUtLDb": false,
                    "lHLMtb": false,
                    "Erzlz": false,
                    "KQw3Q": false,
                    "OQFPef": false,
                    "m19P4e": false,
                    "P6Ur2b": "#1a73e8",
                    "uhXPIc": "#8ab4f8",
                    "e127Sb": "#1c3aa9",
                    "ezFdNd": "#0f9d58",
                    "Wja4f": "#87ceac",
                    "jjajId": "#9e9e9e",
                    "d1ULv": "rgba(0,0,0,.26)",
                    "lQ1kYd": "#bdbdbd",
                    "fAus6": "#000",
                    "NNBneb": "#5f6368",
                    "MDi8Rd": "#dadce0",
                    "BoJtxf": false,
                    "ZTuJNc": false,
                    "So4wae": false,
                    "XgWQKd": true,
                    "fjc61": false,
                    "y1HZEd": false,
                    "zAKfhf": false,
                    "D8A8he": true,
                    "bmQ7Rb": false,
                    "nMRhJe": false,
                    "xT28q": false,
                    "KTkDB": false,
                    "JyBo2c": false,
                    "xDKXr": false,
                    "FYBlgf": false,
                    "FELoce": false,
                    "HpkQdc": true,
                    "wwQMXe": false,
                    "FuMeW": false,
                    "bcz7kc": true,
                    "hVG5ce": false,
                    "KCmv6e": false,
                    "IAtx5d": true,
                    "VXIo7d": "8px",
                    "EiEfXb": "#dadce0",
                    "IFkMhd": false,
                    "lsK6rd": true,
                    "zhkRO": "%.@.1,1,1,1,1,1,0,0,null,1,null,0,0,null,0,1,0,\"/setprefs?sig\\u003d0_xDO3A9IdJDyLMySgNKVsRhDATyU%3D\\u0026szl\\u003d0\"]",
                    "w2btAe": "%.@.\"\",\"\",\"0\",null,null,null,1]",
                    "pxO4Zd": "0",
                    "mXOY5d": "%.@.null,1,1,null,[null,757,1440]]",
                    "SsQ4x": "N4ljJHxWoJx3pKoWtd5YIw",
                    "IYFWl": "%.@.\"#b8bbbe\"]",
                    "Ht1O2b": "%.@.0]",
                    "d6J1ld": "%.@.0]",
                    "Oo3dKf": "%.@.\"0px 5px 26px 0px rgba(0,0,0,0.22),0px 20px 28px 0px rgba(0,0,0,0.3)\",\"#fff\"]",
                    "uUBnEb": "%.@.\"#ebeced\",\"#fff\",\"#dadce0\",\"#fff\",\"#202124\",\"#dadce0\",\"#dadce0\",\"#9aa0a6\",\"#fff\",\"#fff\",\"#202124\",\"#3c4043\",\"#ea4335\",\"#34a853\",\"#202124\",\"#fff\",\"#fff\",\"#202124\",\"#202124\",\"#3c4043\"]",
                    "nfxEDe": "%.@.[],0,null,0,0]",
                    "auIt8": "%.@.0,1]",
                    "YPqjbf": "%.@.\"rgba(0,0,0,0.9)\",\"#fff\",\"0 0 2px 0 rgba(0,0,0,0.12),0 2px 2px 0 rgba(0,0,0,0.12)\",\"1px solid #dadce0\",\"#70757a\"]",
                    "MuJWjd": false,
                    "GWsdKe": "vi-VN",
                    "frJqAd": "%.@.\"13px\",\"16px\",\"11px\",13,16,11,\"8px\",8,20]",
                    "N1ycab": "vi_VN",
                    "AB5Xwb": "%.@.\"10px\",10,\"16px\",16,\"18px\"]",
                    "Z8HLFf": "%.@.\"14px\",14]",
                    "ymaOI": "%.@.40,32,14,\"\\\"#3c4043\\\"\"]",
                    "fNpQmb": "%.@.\"Roboto-Bold,HelveticaNeue-Bold,HelveticaNeue,sans-serif-bold,Arial,sans-serif\"]",
                    "aMI2mb": "%.@.\"0 2px 10px 0 rgba(0,0,0,0.2)\"]",
                    "BZUDzc": "%.@.0,\"14px\",\"500\",\"500\",\"0 1px 1px rgba(0,0,0,.16)\",\"pointer\",\"#000\",\"rgba(0,0,0,.26)\",\"#70757a\",\"#202124\",\"rgba(204,204,204,.15)\",\"rgba(204,204,204,.25)\",\"rgba(112,117,122,.20)\",\"rgba(112,117,122,.40)\",\"#34a853\",\"#4285f4\",\"#1558d6\",\"#ea4335\",\"#fbbc04\",\"#f8f9fa\",\"#f8f9fa\",\"#202124\",\"#34a853\",\"rgba(0,0,0,.12)\",null,\"#fff\",\"rgba(255,255,255,.30)\",\"#fff\",\"#202124\",\"#fff\",null,1]",
                    "v7Qvdc": "%.@.\"20px\",\"500\",\"400\",\"13px\",\"15px\",\"15px\",\"Roboto,RobotoDraft,Helvetica,Arial,sans-serif\",\"24px\",\"400\",\"32px\",\"24px\"]",
                    "MgUcDb": "VN",
                    "SIsrTd": false,
                    "fyLpDc": "",
                    "ZxtPCd": "%.@.null,null,null,null,20,20,18,\"40px\",\"36px\",\"36px\",null,null,null,null,null,null,null,null,null,null,\"#fff\",null,null,null,null,null,null,null,null,\"16px\",\"12px\",\"8px\",\"4px\",null,\"#e8f0fe\",\"#1967d2\",\"transparent\",\"#1a0dab\",\"#dadce0\",\"9999px\",\"8px\",\"#1967d2\",\"transparent\",\"#4d5156\",\"#dadce0\",\"#1967d2\",null,null,null,\"9999px\",\"Google Sans,arial,sans-serif-medium,sans-serif\",\"20px\",\"14px\",\"500\",\"#f1f3f4\",\"#202124\",\"#fff\",\"#dadce0\",\"#3c4043\",\"4px\",\"#1967d2\",\"#1967d2\",null,null,null,null,null,null,null,null,null,null,\"#4285f4\",\"2px\",null,null,\"rgba(138,180,248,0.24)\",null,null,null,null,\"34px\",null,\"7px\",\"1px\",null,null,null,null,null,null,\"rgba(26,115,232,0.08)\",\"rgba(26,115,232,0.08)\",null,\"#1967d2\",null,\"#a3c5ff\",\"#001d35\"]",
                    "NyzCwe": "%.@.\"#70757a\",\"#70757a\",\"#70757a\",\"#70757a\",\"#4d5156\",\"#202124\",\"8px\",\"100%\",\"12px\",\"0px\",\"8px\",\"8px\",\"4px\",\"100%\",\"6px\",\"8px\",\"0px\",\"16px\",null,\"#747878\",\"#1f1f1f\",null,\"#5e5e5e\"]",
                    "spz2q": "%.@.\"#fff\",\"0px\",null,\"0px\",null,\"0px\"]",
                    "xFmcof": "%.@.\"100%\",\"4px\",\"0px\",\"20px\",\"12px\"]",
                    "lDqiof": "%.@.\"#202124\",\"#4d5156\",\"#1a73e8\",null,\"#70757a\",\"#1a0dab\",\"#681da8\",null,null,\"#fff\",\"#4285f4\",\"#fff\",\"#e8f0fe\",\"#1967d2\",\"#f1f3f4\",\"#202124\",\"#fff\",\"#3c4043\",\"#202124\",\"#fff\",\"#fff\",\"#fff\",\"#188038\",\"#d93025\",\"#e37400\",\"#dadce0\",\"#fff\",\"rgba(0,0,0,0.6)\",\"#202124\",\"#dadce0\",\"#d2e3fc\",null,\"#1a73e8\",\"#70757a\",null,\"transparent\",\"#ecedef\",\"rgba(0,0,0,0.03)\",null,null,null,null,null,null,null,null,null,\"#ea4335\",\"#34a853\",\"#4285f4\",\"#fbbc04\",\"#fbbc04\",\"#dadce0\",\"#f8f9fa\",null,null,null,null,\"#e8f0fe\",\"#f7f8f9\",\"#ecedee\",\"rgba(32,33,36,0.5)\",\"#d2d2d2\",\"#e0e9ff\"]",
                    "Gpnz4c": "%.@.\"#e0e9ff\",\"#dadce0\",\"#d2d2d2\",\"#0b57d0\",\"#747878\",\"#001d35\",\"#edf1f9\",\"#ebf1ff\",\"#001d35\",\"#d3e3fd\",\"#fff\",\"#5e5e5e\",\"#474747\",\"#1f1f1f\",\"#1a0dab\",\"#d2d2d2\",\"#0b57d0\",\"#0b57d0\",\"#a3c9ff\",\"#001d35\",\"#ecedee\",\"#f7f8f9\",\"#fff\",\"#fff\",\"#f7f8f9\",\"#e0e9ff\",\"#f5f8ff\",\"#d3e3ff\",\"#a3c9ff\",\"#fff\",\"#f5f8ff\",\"#0b57d0\",\"#545d7e\",\"#001d35\",\"#edf1f9\",\"#ebf1ff\",\"#001d35\",\"#c7dbff\",\"#fff\",\"#fff\",\"#545d7e\",\"#001d35\",\"#001d35\",\"#0b57d0\",\"#a3c9ff\",\"#0b57d0\",\"#0b57d0\",\"rgba(0,0,0,0.6)\",\"#a3c5ff\",\"#001d35\",\"#fff\",\"#f5f8ff\",\"#e5edff\"]",
                    "sCU50d": "%.@.null,\"none\",null,\"0px 1px 3px rgba(60,64,67,0.08)\",null,\"0px 2px 6px rgba(60,64,67,0.16)\",null,\"0px 4px 12px rgba(60,64,67,0.24)\",null,null,\"1px solid #dadce0\",\"none\",\"none\",\"none\",\"none\",\"0px 1px 3px rgba(60,64,67,0.24)\"]",
                    "w9Zicc": "%.@.\"#f1f3f4\",\"26px\",\"#e2eeff\",\"#0060f0\",\"#e2eeff\",\"1px\",\"#ecedef\",\"1px\",\"#f1f3f4\",\"#ecedef\",\"#0060f0\",\"12px\",\"12px\",\"10px\",\"16px\",\"16px\",\"20px\",\"12px\",\"10px\",\"8px\",\"#2a4165\"]",
                    "IkSsrf": "%.@.\"Google Sans,arial,sans-serif\",\"Google Sans,arial,sans-serif-medium,sans-serif\",\"arial,sans-serif\",\"arial,sans-serif-medium,sans-serif\",\"arial,sans-serif-light,sans-serif\"]",
                    "OItNqf": "%.@.\"1px\",\"20\",\"20px\",\"14px\",\"#1f1f1f\",\"#747878\",\"#474747\",\"#1f1f1f\"]",
                    "JMyuH": "%.@.null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,null,\"36px\",\"20px\"]",
                    "j2FoS": "%.@.\"#747878\",\"#f7f8f9\",\"#1f1f1f\",\"#1f1f1f\",\"#5e5e5e\",\"#1f1f1f\",\"500\",\"Google Sans,arial,sans-serif-medium,sans-serif\",\"20px\",\"16px\",\"83px\",\"92px\",\"52px\",\"52px\",\"#5e5e5e\"]",
                    "e2zoW": "%.@.\"16px\",\"12px\",\"0px\",\"8px\",\"4px\",\"2px\",\"20px\",\"24px\",\"48px\",\"20px 20px\",null,null,\"0px\",\"20px\",\"36px\",\"20px\"]",
                    "W1Bte": "%.@.\"cubic-bezier(0.1,1,0.2,1)\",\"cubic-bezier(0.8,0,1,0.8)\",\"cubic-bezier(0.2,0.6,0.2,1)\",\"cubic-bezier(0.4,0,1,0.8)\",\"300\",\"100ms\",\"200ms\",\"250ms\",\"cubic-bezier(0.4,0,0.2,1)\",\"cubic-bezier(0.4,0,0.6,1)\",\"cubic-bezier(0.6,0,0,1)\",\"cubic-bezier(0,0,1,1)\",\"cubic-bezier(0.2,0,0,1)\",\"800ms\",\"1000ms\",\"400ms\",\"500ms\",\"600ms\",\"50ms\",\"400ms\",\"300ms\",\"250ms\",\"150ms\",\"250ms\",\"200ms\",\"150ms\",\"150ms\",\"300ms\",\"250ms\",\"200ms\",\"150ms\",\"450ms\",\"400ms\",\"300ms\",\"150ms\",\"300ms\",\"250ms\",\"200ms\",\"100ms\",\"250ms\",\"200ms\",\"150ms\",\"100ms\",\"250ms\",\"200ms\",\"150ms\",\"100ms\",\"300ms\",\"250ms\",\"200ms\",\"100ms\",\"null\",\"cubic-bezier(0.3,0,0.8,0.15)\",\"cubic-bezier(0.05,0.7,0.1,1)\",\"cubic-bezier(0,0,1,1)\",\"cubic-bezier(0.2,0,0,1)\",\"cubic-bezier(0.3,0,1,1)\",\"cubic-bezier(0,0,0,1)\",\"250ms\",\"200ms\",\"150ms\",\"50ms\",\"50ms\",\"50ms\",\"400ms\",\"350ms\",\"250ms\",\"50ms\",\"50ms\",\"50ms\",\"200ms\",\"150ms\",\"100ms\",\"50ms\",\"200ms\",\"150ms\",\"100ms\",\"50ms\",\"50ms\",\"50ms\",\"250ms\",\"200ms\",\"150ms\",\"50ms\",\"50ms\",\"50ms\",\"cubic-bezier(0.05,0.7,0.1,1)\",\"cubic-bezier(0.3,0,0.8,0.15)\"]",
                    "u9mep": "%.@.\"#1a0dab\",\"#1a0dab\",\"#1f1f1f\",\"#1a0dab\"]",
                    "mrqaQb": "%.@.14,6,68,\"#474747\",2,12]",
                    "k7Tqye": "%.@.null,null,null,null,null,null,null,\"16px\",\"12px\",\"8px\",\"20px\",\"4px\",\"9999px\",\"0px\",\"2px\"]",
                    "y50LC": "%.@.null,null,\"#4d5156\",null,\"#5f6368\"]",
                    "jfSEkd": "%.@.\"#4285f4\",\"#e8f0fe\",\"#1967d2\",\"#185abc\",\"#d2e3fc\",\"#d2e3fc\",\"rgba(26,115,232,0.24)\",\"rgba(60,64,67,0.38)\",\"#dadce0\",\"rgba(218,220,224,0.38)\",\"#f8f9fa\",\"#4285f4\",\"#fff\",\"rgba(32,33,36,0.16)\",\"rgba(32,33,36,0.16)\",\"rgba(32,33,36,0.32)\",\"#f1f3f4\",\"#001d35\",\"rgba(32,33,36,0.08)\",\"rgba(32,33,36,0.08)\",\"rgba(32,33,36,0.24)\",\"#fff\",\"#1a73e8\",\"#1967d2\",\"rgba(26,115,232,0.08)\",\"rgba(26,115,232,0.08)\",\"rgba(26,115,232,0.24)\",\"#fff\",\"#4d5156\",\"#4d5156\",\"rgba(60,64,67,0.08)\",\"rgba(60,64,67,0.08)\",\"rgba(60,64,67,0.24)\",\"2px\",\"2px\",null,null,\"#e5edff\",\"1px\"]",
                    "GVtPm": "%.@.\"#fff\",null,null,null,\"8px\",\"0 0 0 1px #dadce0\",\"1px solid #dadce0\",\"#fff\",\"#f7f8f9\",\"#ecedee\",\"#5e5e5e\",\"#474747\",\"26vw\",\"40vw\",\"55vw\"]",
                    "MexNte": "%.@.\"700\",\"400\",\"underline\",\"none\",\"capitalize\",\"none\",\"uppercase\",\"none\",\"500\",\"lowercase\",\"italic\",null,null,\"-1px\",\"0.3px\",\"20px\",\"12px\"]",
                    "Aahcnf": "%.@.\"28px\",\"36px\",\"500\",\"Google Sans,arial,sans-serif\",null,\"arial,sans-serif\",\"14px\",\"400\",\"22px\",null,\"18px\",\"24px\",\"400\",\"Google Sans,arial,sans-serif\",null,\"Google Sans,arial,sans-serif\",\"56px\",\"48px\",\"0\",null,\"400\",\"Google Sans,arial,sans-serif\",\"36px\",\"400\",\"40px\",null,\"Google Sans,arial,sans-serif\",\"36px\",\"28px\",null,\"400\",null,\"arial,sans-serif\",\"24px\",\"16px\",null,\"400\",\"arial,sans-serif\",\"16px\",\"12px\",null,\"400\",\"arial,sans-serif\",\"22px\",\"16px\",null,\"400\",\"arial,sans-serif\",\"24px\",\"20px\",null,\"400\",\"arial,sans-serif\",\"24px\",\"16px\",null,\"400\",\"arial,sans-serif\",\"18px\",\"14px\",null,\"400\",null,null,null,null,null,\"14px\",\"Google Sans,arial,sans-serif-medium,sans-serif\",\"20px\",\"400\",\"Google Sans,arial,sans-serif\",\"28px\",\"22px\",\"400\",\"Google Sans,arial,sans-serif\",\"24px\",\"16px\",\"400\",\"arial,sans-serif-medium,sans-serif\",\"12px\",\"12px\",\"Google Sans,arial,sans-serif\",\"28px\",\"22px\",\"400\"]",
                    "PFhmed": "%.@.\"rgba(255,255,255,0)\"]",
                    "RsSoV": "%.@.\"rgba(1,1,1,0.25)\",\"rgba(0,0,0,0)\",\"0.87\",\"3px\",14,\"10px\",\"16px\",\"2px\",\"8px\",\"2px\",\"16px\",\"12px\",\"#d93025\",\"8px\",\"12px\",\"rgba(255,255,255,0.5)\",\"4px\",\"7px\",\"700\",\"rgba(255,255,255,0.85)\"]",
                    "mf1yif": "%.@.4]",
                    "aKXqGc": "%.@.\"14px\",14,\"16px\",16,\"0\",0,\"none\",652,\"1px solid #dadce0\",\"normal\",\"normal\",\"#70757a\",\"12px\",\"1.34\",\"1px solid #dadce0\",\"none\",\"0\",\"none\",\"none\",\"none\",\"none\",\"6px\",\"652px\"]",
                    "ZP0oif": "%.@.\"16px\",\"#ebedef\"]",
                    "o0P8Hf": "%.@.\"rgba(0,0,0,0.0)\",null,null,null,\"#202124\",\"#dadce0\",null,null,null,\"#f8f9fa\",\"#000\",\"#1a73e8\",\"#dadce0\",\"#fff\",\"#fff\",null,\"#70757a\",\"rgba(0,0,0,0.26)\",\"rgba(0,0,0,0.2)\",\"rgba(0,0,0,0.5)\",\"rgba(0,0,0,0.2)\",\"#fff\",\"rgba(0,0,0,0.1)\",\"#fff\",\"#70757a\",null,\"#000\",\"#fff\",\"#000\",\"rgba(0,0,0,0.0)\",\"rgba(255,255,255,0.5)\",\"rgba(0,0,0,.03)\",\"rgba(0,0,0,0.3)\",\"rgba(0,0,0,0.2)\",\"rgba(0,0,0,0.5)\",\"rgba(0,0,0,.07)\",\"rgba(0,0,0,.04)\",\"rgba(0,0,0,.26)\",\"rgba(255,255,255,.54)\",\"#70757a\",\"#70757a\",\"rgba(0,0,0,.22)\",\"rgba(0,0,0,.30)\",\"rgba(0,0,0,.06)\",\"rgba(0,0,0,.25)\",\"#d2e3fc\",\"rgba(32,33,36,.5)\",\"rgba(32,33,36,.7)\",\"rgba(255,255,255,.04)\",null,null,\"rgba(255,255,255,.8)\",\"rgba(60,64,67,.15)\",\"rgba(0,0,0,.07)\",\"rgba(0,0,0,.16)\",\"rgba(0,0,0,.08)\",\"rgba(0,0,0,.14)\",\"rgba(0,0,0,.12)\",\"rgba(0,0,0,.28)\",\"rgba(0,0,0,.18)\",\"rgba(0,0,0,.24)\",\"rgba(0,0,0,.05)\",\"rgba(0,0,0,.13)\",\"rgba(60,64,67,.3)\",\"rgba(0,0,0,.36)\",\"rgba(0,0,0,.15)\",\"rgba(32,33,36,.28)\",\"rgba(218,220,224,.7)\",\"#dadce0\",\"#fff\",\"#fff\",\"#1a73e8\",\"#000\",\"rgba(0,0,0,.0)\",\"#202124\",\"rgba(0,0,0,.8)\",\"rgba(26,115,232,0)\",\"rgba(26,115,232,.7)\",\"rgba(66,133,244,.22)\",\"rgba(32,33,36,.7)\",\"rgba(0,0,0,.8)\",\"rgba(255,255,255,.54)\",\"rgba(255,255,255,.87)\",\"rgba(60,64,67,.38)\",\"rgba(0,0,0,.8)\",\"rgba(255,255,255,.54)\",\"rgba(255,255,255,.87)\",\"rgba(60,64,67,.38)\",\"rgba(255,255,255,.3)\",\"rgba(0,0,0,0.54)\",\"rgba(0,0,0,0.8)\",\"rgba(248,249,250,0.85)\",\"#dadce0\",\"#ea4335\",\"#34a853\",\"#3c4043\",\"#f8f9fa\",\"#3c4043\",\"#202124\",{\"100\":\"#f8f9fa\",\"101\":\"#dadce0\",\"102\":\"#3c4043\",\"103\":\"#202124\",\"104\":\"#f8f9fa\",\"105\":\"#dadce0\",\"106\":\"#70757a\",\"107\":\"#3c4043\",\"108\":\"#f8f9fa\",\"109\":\"#3c4043\",\"110\":\"#202124\",\"111\":\"#f8f9fa\",\"112\":\"#dadce0\",\"113\":\"#e8f0fe\",\"114\":\"#4285f4\",\"115\":\"#e8f0fe\",\"116\":\"#d2e3fc\",\"117\":\"#4285f4\",\"118\":\"#1a73e8\",\"119\":\"#e8f0fe\",\"120\":\"#d2e3fc\",\"121\":\"#4285f4\",\"122\":\"#1a73e8\",\"123\":\"#d2e3fc\",\"124\":\"#4285f4\",\"125\":\"#1a73e8\",\"126\":\"#e8f0fe\",\"127\":\"#d2e3fc\",\"128\":\"#4285f4\",\"129\":\"#1a73e8\",\"130\":\"#fce8e6\",\"131\":\"#fad2cf\",\"132\":\"#f28b82\",\"133\":\"#ee675c\",\"134\":\"#d93025\",\"135\":\"#c5221f\",\"136\":\"#a50e0e\",\"137\":\"#ea4335\",\"138\":\"#d93025\",\"139\":\"#ea4335\",\"140\":\"#d93025\",\"141\":\"#c5221f\",\"142\":\"#b31412\",\"143\":\"#a50e0e\",\"144\":\"#d93025\",\"145\":\"#f28b82\",\"146\":\"#ee675c\",\"147\":\"#ea4335\",\"148\":\"#c5221f\",\"149\":\"#a50e0e\",\"150\":\"#fef7e0\",\"151\":\"#feefc3\",\"152\":\"#fde293\",\"153\":\"#fdd663\",\"154\":\"#fcc934\",\"155\":\"#fbbc04\",\"156\":\"#f9ab00\",\"157\":\"#f29900\",\"158\":\"#ea8600\",\"159\":\"#e37400\",\"160\":\"#fbbc04\",\"161\":\"#fbbc04\",\"162\":\"#f29900\",\"163\":\"#fdd663\",\"164\":\"#fbbc04\",\"165\":\"#fcc934\",\"166\":\"#fbbc04\",\"167\":\"#f9ab00\",\"168\":\"#f29900\",\"169\":\"#ea8600\",\"170\":\"#e37400\",\"171\":\"#e6f4ea\",\"172\":\"#ceead6\",\"173\":\"#a8dab5\",\"174\":\"#81c995\",\"175\":\"#5bb974\",\"176\":\"#1e8e3e\",\"177\":\"#188038\",\"178\":\"#34a853\",\"179\":\"#1e8e3e\",\"180\":\"#188038\",\"181\":\"#34a853\",\"182\":\"#1e8e3e\",\"183\":\"#ceead6\",\"184\":\"#a8dab5\",\"185\":\"#34a853\",\"186\":\"#81c995\",\"187\":\"#34a853\",\"188\":\"#1e8e3e\",\"189\":\"#188038\",\"190\":\"#137333\",\"191\":\"#0d652d\",\"192\":\"rgba(0,0,0,.1)\",\"193\":\"rgba(0,0,0,.2)\",\"194\":\"rgba(60,64,67,.1)\",\"195\":\"rgba(60,64,67,.06)\",\"196\":\"rgba(255,255,255,0)\",\"197\":\"rgba(0,0,0,.12)\",\"198\":\"rgba(32,33,36,0)\",\"199\":\"rgba(32,33,36,.1)\",\"200\":\"rgba(0,0,0,.12)\",\"201\":\"rgba(0,0,0,.5)\",\"202\":\"rgba(0,0,0,.54)\",\"203\":\"#000\",\"204\":\"rgba(255,255,255,.5)\",\"205\":\"#1558d6\",\"206\":\"rgba(0,0,0,.24)\",\"207\":\"rgba(0,0,0,.24)\",\"208\":\"#f8f9fa\",\"209\":\"rgba(255,255,255,.6)\",\"210\":\"#1e8e3e\",\"211\":\"rgba(0,0,0,.02)\",\"212\":\"#000\",\"213\":\"rgba(0,0,0,.16)\",\"214\":\"rgba(0,0,0,.7)\",\"215\":\"#1a73e8\",\"216\":\"#d93025\",\"217\":\"#4285f4\",\"218\":\"rgba(0,0,0,.15)\",\"219\":\"rgba(0,0,0,.05)\",\"220\":\"#70757a\",\"221\":\"#dadce0\",\"222\":\"#188038\",\"223\":\"rgba(0,0,0,.6)\",\"224\":\"#34a853\",\"225\":\"rgba(255,255,255,.3)\",\"226\":\"rgba(0,0,0,.05)\",\"227\":\"rgba(0,0,0,.05)\",\"228\":\"rgba(32,33,36,.9)\",\"229\":\"rgba(255,255,255,.6)\",\"230\":\"rgba(0,0,0,.08)\",\"231\":\"rgba(255,255,255,.8)\",\"232\":\"rgba(0,0,0,.05)\",\"233\":\"#4285f4\",\"234\":\"rgba(0,0,0,.16)\",\"235\":\"#fff\",\"236\":\"rgba(0,0,0,.87)\",\"238\":\"#fdd663\",\"239\":\"#fdd663\",\"240\":\"#fff\",\"241\":\"rgba(255,255,255,.5)\",\"242\":\"#f8f9fa\",\"243\":\"#fdd663\",\"244\":\"rgba(255,255,255,.54)\",\"245\":\"rgba(0,0,0,.5)\",\"246\":\"rgba(0,0,0,.26)\",\"247\":\"rgba(0,0,0,.26)\",\"248\":\"rgba(0,0,0,.38)\",\"249\":\"rgba(0,0,0,.03)\",\"250\":\"#4285f4\",\"251\":\"rgba(60,64,67,.12)\",\"252\":\"rgba(255,255,255,0)\",\"253\":\"rgba(0,0,0,0)\",\"254\":\"#3c4043\",\"255\":\"#d2e3fc\",\"256\":\"#3c4043\",\"257\":\"#d2e3fc\",\"258\":\"#d2e3fc\",\"259\":\"#4285f4\",\"260\":\"#202124\",\"261\":\"rgba(0,0,0,.16)\",\"262\":\"rgba(255,255,255,.3)\",\"263\":\"rgba(0,0,0,0)\",\"264\":\"#c5221f\",\"265\":\"#dadce0\",\"266\":\"#ea4335\",\"267\":\"#34a853\",\"268\":\"rgba(60,64,67,.15)\",\"269\":\"rgba(19,115,51,.15)\",\"270\":\"rgba(0,0,0,.15)\",\"271\":\"rgba(0,0,0,.18)\",\"272\":\"rgba(0,0,0,.28)\",\"273\":\"rgba(60,64,67,.3)\",\"274\":\"#1558d6\"}]",
                    "rkD25": "%.@.[[\"hl\",\"vi-VN\"]]]",
                    "WiLzZe": "%.@.\"#202124\",\"#70757a\",\"#4d5156\",\"#5f6368\",\"#fff\",\"rgba(255,255,255,.70)\",28,24,26,20,16,-2,0,-4,2,0,0,24,20,20,14,12]",
                    "AYkLRe": "%.@.\"20px\",20,\"14px\",14,\"\\\"rgba(0, 0, 0, .87)\\\"\"]",
                    "rNyuJc": "",
                    "LU5fGb": false,
                    "gXkHoe": "105250506097979753968",
                    "hevonc": "%.@.1]",
                    "xcljyb": "%.@.\"8px\",8,\"Roboto-Medium,HelveticaNeue-Medium,Helvetica Neue,sans-serif-medium,Arial,sans-serif\"]"
                };
            }
            )();
            (function() {
                var b = function(a) {
                    var c = 0;
                    return function() {
                        return c < a.length ? {
                            done: !1,
                            value: a[c++]
                        } : {
                            done: !0
                        }
                    }
                };
                var e = this || self;
                var g, h;
                a: {
                    for (var k = ["CLOSURE_FLAGS"], l = e, n = 0; n < k.length; n++)
                        if (l = l[k[n]],
                        null == l) {
                            h = null;
                            break a
                        }
                    h = l
                }
                var p = h && h[610401301];
                g = null != p ? p : !1;
                var q, r = e.navigator;
                q = r ? r.userAgentData || null : null;
                function t(a) {
                    return g ? q ? q.brands.some(function(c) {
                        return (c = c.brand) && -1 != c.indexOf(a)
                    }) : !1 : !1
                }
                function u(a) {
                    var c;
                    a: {
                        if (c = e.navigator)
                            if (c = c.userAgent)
                                break a;
                        c = ""
                    }
                    return -1 != c.indexOf(a)
                }
                ;function v() {
                    return g ? !!q && 0 < q.brands.length : !1
                }
                function w() {
                    return u("Safari") && !(x() || (v() ? 0 : u("Coast")) || (v() ? 0 : u("Opera")) || (v() ? 0 : u("Edge")) || (v() ? t("Microsoft Edge") : u("Edg/")) || (v() ? t("Opera") : u("OPR")) || u("Firefox") || u("FxiOS") || u("Silk") || u("Android"))
                }
                function x() {
                    return v() ? t("Chromium") : (u("Chrome") || u("CriOS")) && !(v() ? 0 : u("Edge")) || u("Silk")
                }
                function y() {
                    return u("Android") && !(x() || u("Firefox") || u("FxiOS") || (v() ? 0 : u("Opera")) || u("Silk"))
                }
                ;var z = v() ? !1 : u("Trident") || u("MSIE");
                y();
                x();
                w();
                var A = !z && !w()
                  , D = function(a) {
                    if (/-[a-z]/.test("ved"))
                        return null;
                    if (A && a.dataset) {
                        if (y() && !("ved"in a.dataset))
                            return null;
                        a = a.dataset.ved;
                        return void 0 === a ? null : a
                    }
                    return a.getAttribute("data-" + "ved".replace(/([A-Z])/g, "-$1").toLowerCase())
                };
                var E = []
                  , F = null;
                function G(a) {
                    a = a.target;
                    var c = performance.now()
                      , f = []
                      , H = f.concat
                      , d = E;
                    if (!(d instanceof Array)) {
                        var m = "undefined" != typeof Symbol && Symbol.iterator && d[Symbol.iterator];
                        if (m)
                            d = m.call(d);
                        else if ("number" == typeof d.length)
                            d = {
                                next: b(d)
                            };
                        else
                            throw Error("a`" + String(d));
                        for (var B = []; !(m = d.next()).done; )
                            B.push(m.value);
                        d = B
                    }
                    E = H.call(f, d, [c]);
                    if (a && a instanceof HTMLElement)
                        if (a === F) {
                            if (c = 4 <= E.length)
                                c = 5 > (E[E.length - 1] - E[E.length - 4]) / 1E3;
                            if (c) {
                                c = google.getEI(a);
                                a.hasAttribute("data-ved") ? f = a ? D(a) || "" : "" : f = (f = a.closest("[data-ved]")) ? D(f) || "" : "";
                                f = f || "";
                                if (a.hasAttribute("jsname"))
                                    a = a.getAttribute("jsname");
                                else {
                                    var C;
                                    a = null == (C = a.closest("[jsname]")) ? void 0 : C.getAttribute("jsname")
                                }
                                google.log("rcm", "&ei=" + c + "&ved=" + f + "&jsname=" + (a || ""))
                            }
                        } else
                            F = a,
                            E = [c]
                }
                window.document.addEventListener("DOMContentLoaded", function() {
                    document.body.addEventListener("click", G)
                });
            }
            ).call(this);
            var w = function(a) {
                var b = 0;
                return function() {
                    return b < a.length ? {
                        done: !1,
                        value: a[b++]
                    } : {
                        done: !0
                    }
                }
            };
            window.jsl = window.jsl || {};
            window.jsl.dh = function(a, b, m) {
                try {
                    var h = document.getElementById(a), e;
                    if (!h && (null == (e = google.stvsc) ? 0 : e.dds)) {
                        e = [];
                        var f = e.concat
                          , c = google.stvsc.dds;
                        if (c instanceof Array)
                            var n = c;
                        else {
                            var p = "undefined" != typeof Symbol && Symbol.iterator && c[Symbol.iterator];
                            if (p)
                                var g = p.call(c);
                            else if ("number" == typeof c.length)
                                g = {
                                    next: w(c)
                                };
                            else
                                throw Error(String(c) + " is not an iterable or ArrayLike");
                            c = g;
                            var q;
                            for (g = []; !(q = c.next()).done; )
                                g.push(q.value);
                            n = g
                        }
                        var r = f.call(e, n);
                        for (f = 0; f < r.length && !(h = r[f].getElementById(a)); f++)
                            ;
                    }
                    if (h)
                        h.innerHTML = b,
                        m && m();
                    else {
                        var d = {
                            id: a,
                            script: String(!!m),
                            milestone: String(google.jslm || 0)
                        };
                        google.jsla && (d.async = google.jsla);
                        var t = a.indexOf("_")
                          , k = 0 < t ? a.substring(0, t) : ""
                          , u = document.createElement("div");
                        u.innerHTML = b;
                        var l = u.children[0];
                        if (l && (d.tag = l.tagName,
                        d["class"] = String(l.className || null),
                        d.name = String(l.getAttribute("jsname")),
                        k)) {
                            a = [];
                            var v = document.querySelectorAll('[id^="' + k + '_"]');
                            for (b = 0; b < v.length; ++b)
                                a.push(v[b].id);
                            d.ids = a.join(",")
                        }
                        google.ml(Error(k ? "Missing ID with prefix " + k : "Missing ID"), !1, d)
                    }
                } catch (x) {
                    google.ml(x, !0, {
                        "jsl.dh": !0
                    })
                }
            }
            ;
            (function() {
                var x = true;
                google.jslm = x ? 2 : 1;
            }
            )();
            google.x(null, function() {
                (function() {
                    (function() {
                        google.csct = {};
                        google.csct.ps = 'AOvVaw1eKU-d93efn4KAyxgyr17r\x26ust\x3d1696759479543608';
                    }
                    )();
                }
                )();
                (function() {
                    (function() {
                        google.csct.rl = true;
                    }
                    )();
                }
                )();
                (function() {
                    (function() {
                        google.csct.pi = true;
                    }
                    )();
                }
                )();
                (function() {
                    (function() {
                        function f() {
                            for (var c = "&cshid=" + window._cshid, d = document.querySelectorAll('[href^="/"]'), e = 0, b; b = d[e++]; ) {
                                var a = b.getAttribute("href");
                                a.match(/[\?|&](ei|ved)=/) && -1 === a.indexOf("cshid=") && (-1 === a.search("#") ? b.setAttribute("href", a + c) : (a = a.split("#"),
                                b.setAttribute("href", a[0] + c + "#" + a[1])))
                            }
                            d = document.querySelectorAll("[ping]");
                            for (e = 0; b = d[e++]; )
                                a = b.getAttribute("ping"),
                                -1 === a.indexOf("cshid=") && b.setAttribute("ping", a + c)
                        }
                        ;google.csh = google.csh || {};
                        google.csh.ict = function() {
                            window._cshid && google.dclc(f)
                        }
                        ;
                    }
                    ).call(this);
                }
                )();
                (function() {
                    google.csh.ict();
                }
                )();
                (function() {
                    window.jsl = window.jsl || {};
                    window.jsl.dh = window.jsl.dh || function(i, c, d) {
                        try {
                            var e = document.getElementById(i);
                            if (e) {
                                e.innerHTML = c;
                                if (d) {
                                    d();
                                }
                            } else {
                                if (window.jsl.el) {
                                    window.jsl.el(new Error('Missing ID.'), {
                                        'id': i
                                    });
                                }
                            }
                        } catch (e) {
                            if (window.jsl.el) {
                                window.jsl.el(new Error('jsl.dh'));
                            }
                        }
                    }
                    ;
                }
                )();
                (function() {
                    window.jsl.dh('_Ny0hZajKHuSv2roPysWswAY_1', '\x3cstyle\x3e.gb_eb:not(.gb_gd){font:13px/27px Roboto,Arial,sans-serif;z-index:986}@-webkit-keyframes gb__a{0%{opacity:0}50%{opacity:1}}@keyframes gb__a{0%{opacity:0}50%{opacity:1}}a.gb_va{border:none;color:#4285f4;cursor:default;font-weight:bold;outline:none;position:relative;text-align:center;text-decoration:none;text-transform:uppercase;white-space:nowrap;-webkit-user-select:none}a.gb_va:hover:after,a.gb_va:focus:after{background-color:rgba(0,0,0,.12);content:\x22\x22;height:100%;left:0;position:absolute;top:0;width:100%}a.gb_va:hover,a.gb_va:focus{text-decoration:none}a.gb_va:active{background-color:rgba(153,153,153,.4);text-decoration:none}a.gb_wa{background-color:#4285f4;color:#fff}a.gb_wa:active{background-color:#0043b2}.gb_xa{box-shadow:0 1px 1px rgba(0,0,0,.16)}.gb_va,.gb_wa,.gb_ya,.gb_za{display:inline-block;line-height:28px;padding:0 12px;border-radius:2px}.gb_ya{background:#f8f8f8;border:1px solid #c6c6c6}.gb_za{background:#f8f8f8}.gb_ya,#gb a.gb_ya.gb_ya,.gb_za{color:#666;cursor:default;text-decoration:none}#gb a.gb_za{cursor:default;text-decoration:none}.gb_za{border:1px solid #4285f4;font-weight:bold;outline:none;background:#4285f4;background:-webkit-gradient(linear,left top,left bottom,from(top),color-stop(#4387fd),to(#4683ea));background:-webkit-linear-gradient(top,#4387fd,#4683ea);background:linear-gradient(top,#4387fd,#4683ea);filter:progid:DXImageTransform.Microsoft.gradient(startColorstr\x3d#4387fd,endColorstr\x3d#4683ea,GradientType\x3d0)}#gb a.gb_za{color:#fff}.gb_za:hover{box-shadow:0 1px 0 rgba(0,0,0,.15)}.gb_za:active{box-shadow:inset 0 2px 0 rgba(0,0,0,.15);background:#3c78dc;background:-webkit-gradient(linear,left top,left bottom,from(top),color-stop(#3c7ae4),to(#3f76d3));background:-webkit-linear-gradient(top,#3c7ae4,#3f76d3);background:linear-gradient(top,#3c7ae4,#3f76d3);filter:progid:DXImageTransform.Microsoft.gradient(startColorstr\x3d#3c7ae4,endColorstr\x3d#3f76d3,GradientType\x3d0)}#gb .gb_Aa{background:#fff;border:1px solid #dadce0;color:#1a73e8;display:inline-block;text-decoration:none}#gb .gb_Aa:hover{background:#f8fbff;border-color:#dadce0;color:#174ea6}#gb .gb_Aa:focus{background:#f4f8ff;color:#174ea6;outline:1px solid #174ea6}#gb .gb_Aa:active,#gb .gb_Aa:focus:active{background:#ecf3fe;color:#174ea6}#gb .gb_Aa.gb_j{background:transparent;border:1px solid #5f6368;color:#8ab4f8;text-decoration:none}#gb .gb_Aa.gb_j:hover{background:rgba(255,255,255,.04);color:#e8eaed}#gb .gb_Aa.gb_j:focus{background:rgba(232,234,237,.12);color:#e8eaed;outline:1px solid #e8eaed}#gb .gb_Aa.gb_j:active,#gb .gb_Aa.gb_j:focus:active{background:rgba(232,234,237,.1);color:#e8eaed}.gb_p{display:none!important}.gb_Za{visibility:hidden}.gb_v{display:inline-block;vertical-align:middle}.gb_Pd .gb_o{bottom:-3px;right:-5px}.gb_g{position:relative}.gb_d{display:inline-block;outline:none;vertical-align:middle;border-radius:2px;box-sizing:border-box;height:40px;width:40px;cursor:pointer;text-decoration:none}#gb#gb a.gb_d{cursor:pointer;text-decoration:none}.gb_d,a.gb_d{color:#000}.gb_df{border-color:transparent;border-bottom-color:#fff;border-style:dashed dashed solid;border-width:0 8.5px 8.5px;display:none;position:absolute;left:11.5px;top:33px;z-index:1;height:0;width:0;-webkit-animation:gb__a .2s;animation:gb__a .2s}.gb_ef{border-color:transparent;border-style:dashed dashed solid;border-width:0 8.5px 8.5px;display:none;position:absolute;left:11.5px;z-index:1;height:0;width:0;-webkit-animation:gb__a .2s;animation:gb__a .2s;border-bottom-color:rgba(0,0,0,.2);top:32px}x:-o-prefocus,div.gb_ef{border-bottom-color:#ccc}.gb_3{background:#fff;border:1px solid #ccc;border-color:rgba(0,0,0,.2);color:#000;-webkit-box-shadow:0 2px 10px rgba(0,0,0,.2);box-shadow:0 2px 10px rgba(0,0,0,.2);display:none;outline:none;overflow:hidden;position:absolute;right:8px;top:62px;-webkit-animation:gb__a .2s;animation:gb__a .2s;border-radius:2px;-webkit-user-select:text}.gb_v.gb_Ja .gb_df,.gb_v.gb_Ja .gb_ef,.gb_v.gb_Ja .gb_3,.gb_Ja.gb_3{display:block}.gb_v.gb_Ja.gb_ff .gb_df,.gb_v.gb_Ja.gb_ff .gb_ef{display:none}.gb_Qd{position:absolute;right:8px;top:62px;z-index:-1}.gb_5a .gb_df,.gb_5a .gb_ef,.gb_5a .gb_3{margin-top:-10px}.gb_v:first-child,#gbsfw:first-child+.gb_v{padding-left:4px}.gb_Na.gb_Rd .gb_v:first-child{padding-left:0}.gb_Sd{position:relative}.gb_t.gb_yd.gb_cb.gb_nd{margin:0 12px;padding:0}.gb_t .gb_d{position:relative}.gb_t .gb_v{margin:0 4px;padding:4px}.gb_t .gb_Td{display:inline-block}.gb_t a.gb_jd{-webkit-box-align:center;-webkit-align-items:center;-webkit-align-items:center;align-items:center;-webkit-border-radius:100px;border-radius:100px;border:0;background:#0b57d0;color:#fff;display:-webkit-inline-box;display:-webkit-inline-flex;display:-webkit-inline-box;display:-webkit-inline-flex;display:inline-flex;font-size:14px;font-weight:500;height:40px;white-space:nowrap;width:auto;-webkit-font-smoothing:antialiased}.gb_t a.gb_d.gb_jd{margin:0 4px;padding:4px 24px 4px 24px}.gb_t a.gb_jd.gb_Ud{padding:9px 12px 9px 16px}.gb_t a.gb_jd.gb_x{background:transparent;border:1px solid #747775;color:#0b57d0;outline:0}.gb_t .gb_s{fill:#0b57d0}.gb_t .gb_A{fill:#0b57d0;margin-left:8px}.gb_t .gb_A circle{fill:#fff}.gb_t .gb_jd .gb_Hd{-webkit-box-flex:1;-webkit-flex-grow:1;-webkit-box-flex:1;box-flex:1;-webkit-flex-grow:1;flex-grow:1;text-align:center}.gb_t .gb_jd:hover{background:#3763cd}.gb_t .gb_jd:hover .gb_A{fill:#3763cd}.gb_t .gb_jd:focus,.gb_t .gb_jd:active,.gb_t .gb_jd:focus:hover,.gb_t .gb_jd[aria-expanded\x3dtrue],.gb_t .gb_jd:hover[aria-expanded\x3dtrue]{background:#416acf}.gb_t .gb_jd:focus .gb_A,.gb_t .gb_jd:active .gb_A,.gb_t .gb_jd:focus:hover .gb_A,.gb_t .gb_jd[aria-expanded\x3dtrue] .gb_A,.gb_t .gb_jd:hover[aria-expanded\x3dtrue] .gb_A{fill:#416acf}.gb_t .gb_jd:hover,.gb_t .gb_jd:focus,.gb_t .gb_jd:active,.gb_t .gb_jd[aria-expanded\x3dtrue]{-webkit-box-shadow:0 1px 3px 1px rgba(66,64,67,.15),0 1px 2px 0 rgba(60,64,67,.3);box-shadow:0 1px 3px 1px rgba(66,64,67,.15),0 1px 2px 0 rgba(60,64,67,.3)}.gb_t .gb_jd:focus-visible{outline:1px solid #416acf;outline-offset:2px}.gb_t .gb_Da:focus-visible{outline:1px solid #416acf}.gb_t .gb_j.gb_jd{background:#a8c7fa;color:#062e6f}.gb_t .gb_j.gb_jd .gb_A{fill:#a8c7fa}.gb_t .gb_j.gb_jd .gb_A circle{fill:#062e6f}.gb_t .gb_j.gb_jd:hover{background:#b4cbf6}.gb_t .gb_j.gb_jd:hover .gb_A{fill:#b4cbf6}.gb_t .gb_j.gb_jd:focus,.gb_t .gb_j.gb_jd:focus:hover,.gb_t .gb_j.gb_jd:active,.gb_t .gb_j.gb_jd[aria-expanded\x3dtrue],.gb_t .gb_j.gb_jd:hover[aria-expanded\x3dtrue]{background:#b8cdf7}.gb_t .gb_j.gb_jd:focus .gb_A,.gb_t .gb_j.gb_jd:focus:hover .gb_A,.gb_t .gb_j.gb_jd:active .gb_A,.gb_t .gb_j.gb_jd[aria-expanded\x3dtrue] .gb_A,.gb_t .gb_j.gb_jd:hover[aria-expanded\x3dtrue] .gb_A{fill:#b8cdf7}.gb_t .gb_j.gb_jd:focus-visible{outline-color:#b8cdf7}.gb_t .gb_j.gb_jd:hover,.gb_t .gb_j.gb_jd:focus,.gb_t .gb_j.gb_jd:active,.gb_t .gb_j.gb_jd[aria-expanded\x3dtrue]{-webkit-box-shadow:0 1px 3px 1px rgba(66,64,67,.15),0 1px 2px 0 rgba(60,64,67,.3);box-shadow:0 1px 3px 1px rgba(66,64,67,.15),0 1px 2px 0 rgba(60,64,67,.3)}.gb_t .gb_jd.gb_x:hover,.gb_t .gb_jd.gb_x:focus,.gb_t .gb_jd.gb_x[aria-expanded\x3dtrue],.gb_t .gb_jd.gb_x:hover[aria-expanded\x3dtrue]{background:rgba(11,87,208,.08)}.gb_t .gb_jd.gb_x:active{background:rgba(11,87,208,.12)}.gb_t .gb_jd.gb_x:focus-visible{border-color:#0b57d0;outline:0}.gb_t .gb_j.gb_jd.gb_x{background:transparent;color:#a8c7fa}.gb_t .gb_j.gb_jd.gb_x:hover,.gb_t .gb_j.gb_jd.gb_x:focus,.gb_t .gb_j.gb_jd.gb_x[aria-expanded\x3dtrue],.gb_t .gb_j.gb_jd.gb_x:hover[aria-expanded\x3dtrue]{background:rgba(168,199,250,.08)}.gb_t .gb_j.gb_jd.gb_x:active{background:rgba(168,199,250,.12)}.gb_t .gb_j.gb_jd.gb_x:focus-visible{border-color:#a8c7fa;outline:0}.gb_j .gb_t .gb_s{fill:#a8c7fa}.gb_j .gb_t .gb_Da:focus-visible{outline-color:#a8c7fa}.gb_3c .gb_Sd,.gb_f .gb_Sd{float:right}.gb_d{padding:8px;cursor:pointer}.gb_d:after{content:\x22\x22;position:absolute;top:-4px;bottom:-4px;left:-4px;right:-4px}.gb_Na .gb_ie:not(.gb_va):focus img{background-color:rgba(0,0,0,.2);outline:none;-webkit-border-radius:50%;border-radius:50%}.gb_Vd button svg,.gb_d{-webkit-border-radius:50%;border-radius:50%}.gb_Vd button:focus:not(:focus-visible) svg,.gb_Vd button:hover svg,.gb_Vd button:active svg,.gb_d:focus:not(:focus-visible),.gb_d:hover,.gb_d:active,.gb_d[aria-expanded\x3dtrue]{outline:none}.gb_Mc .gb_Vd.gb_re button:focus-visible svg,.gb_Vd button:focus-visible svg,.gb_d:focus-visible{outline:1px solid #202124}.gb_Mc .gb_Vd button:focus-visible svg,.gb_Mc .gb_d:focus-visible{outline:1px solid #f1f3f4}@media (forced-colors:active){.gb_Mc .gb_Vd.gb_re button:focus-visible svg,.gb_Vd button:focus-visible svg,.gb_Mc .gb_Vd button:focus-visible svg{outline:1px solid currentcolor}}.gb_Mc .gb_Vd.gb_re button:focus svg,.gb_Mc .gb_Vd.gb_re button:focus:hover svg,.gb_Vd button:focus svg,.gb_Vd button:focus:hover svg,.gb_d:focus,.gb_d:focus:hover{background-color:rgba(60,64,67,.1)}.gb_Mc .gb_Vd.gb_re button:active svg,.gb_Vd button:active svg,.gb_d:active{background-color:rgba(60,64,67,.12)}.gb_Mc .gb_Vd.gb_re button:hover svg,.gb_Vd button:hover svg,.gb_d:hover{background-color:rgba(60,64,67,.08)}.gb_Ba .gb_d.gb_Da:hover{background-color:transparent}.gb_d[aria-expanded\x3dtrue],.gb_d:hover[aria-expanded\x3dtrue]{background-color:rgba(95,99,104,.24)}.gb_d[aria-expanded\x3dtrue] .gb_i{fill:#5f6368;opacity:1}.gb_Mc .gb_Vd button:hover svg,.gb_Mc .gb_d:hover{background-color:rgba(232,234,237,.08)}.gb_Mc .gb_Vd button:focus svg,.gb_Mc .gb_Vd button:focus:hover svg,.gb_Mc .gb_d:focus,.gb_Mc .gb_d:focus:hover{background-color:rgba(232,234,237,.1)}.gb_Mc .gb_Vd button:active svg,.gb_Mc .gb_d:active{background-color:rgba(232,234,237,.12)}.gb_Mc .gb_d[aria-expanded\x3dtrue],.gb_Mc .gb_d:hover[aria-expanded\x3dtrue]{background-color:rgba(255,255,255,.12)}.gb_Mc .gb_d[aria-expanded\x3dtrue] .gb_i{fill:#fff;opacity:1}.gb_v{padding:4px}.gb_Na.gb_Rd .gb_v{padding:4px 2px}.gb_Na.gb_Rd .gb_b.gb_v{padding-left:6px}.gb_3{z-index:991;line-height:normal}.gb_3.gb_Wd{left:0;right:auto}@media (max-width:350px){.gb_3.gb_Wd{left:0}}.gb_Xd .gb_3{top:56px}.gb_l .gb_d,.gb_2 .gb_l .gb_d{background-position:-64px -29px}.gb_I .gb_l .gb_d{background-position:-29px -29px;opacity:1}.gb_l .gb_d,.gb_l .gb_d:hover,.gb_l .gb_d:focus{opacity:1}.gb_hd{display:none}@media screen and (max-width:319px){.gb_od:not(.gb_td) .gb_l{display:none;visibility:hidden}}.gb_o{display:none}.gb_bd{font-family:Google Sans,Roboto,Helvetica,Arial,sans-serif;font-size:20px;font-weight:400;letter-spacing:0.25px;line-height:48px;margin-bottom:2px;opacity:1;overflow:hidden;padding-left:16px;position:relative;text-overflow:ellipsis;vertical-align:middle;top:2px;white-space:nowrap;-webkit-flex:1 1 auto;-webkit-box-flex:1;flex:1 1 auto}.gb_bd.gb_cd{color:#3c4043}.gb_Na.gb_Oa .gb_bd{margin-bottom:0}.gb_dd.gb_ed .gb_bd{padding-left:4px}.gb_Na.gb_Oa .gb_fd{position:relative;top:-2px}.gb_Na{color:black;min-width:160px;position:relative;-webkit-transition:box-shadow 250ms;transition:box-shadow 250ms}.gb_Na.gb_Uc{min-width:120px}.gb_Na.gb_md .gb_nd{display:none}.gb_Na.gb_md .gb_od{height:56px}header.gb_Na{display:block}.gb_Na svg{fill:currentColor}.gb_pd{position:fixed;top:0;width:100%}.gb_qd{-webkit-box-shadow:0 4px 5px 0 rgba(0,0,0,.14),0 1px 10px 0 rgba(0,0,0,.12),0 2px 4px -1px rgba(0,0,0,.2);box-shadow:0 4px 5px 0 rgba(0,0,0,.14),0 1px 10px 0 rgba(0,0,0,.12),0 2px 4px -1px rgba(0,0,0,.2)}.gb_rd{height:64px}.gb_od{-webkit-box-sizing:border-box;box-sizing:border-box;position:relative;width:100%;display:-webkit-box;display:-webkit-flex;display:flex;-webkit-box-pack:space-between;-webkit-justify-content:space-between;justify-content:space-between;min-width:-webkit-min-content;min-width:min-content}.gb_Na:not(.gb_Oa) .gb_od{padding:8px}.gb_Na.gb_sd .gb_od{-webkit-flex:1 0 auto;-webkit-box-flex:1;flex:1 0 auto}.gb_Na .gb_od.gb_td.gb_ud{min-width:0}.gb_Na.gb_Oa .gb_od{padding:4px;padding-left:8px;min-width:0}.gb_nd{height:48px;vertical-align:middle;white-space:nowrap;-webkit-box-align:center;-webkit-align-items:center;align-items:center;display:-webkit-box;display:-webkit-flex;display:flex;-webkit-user-select:none}.gb_wd\x3e.gb_nd{display:table-cell;width:100%}.gb_dd{padding-right:30px;box-sizing:border-box;-webkit-flex:1 0 auto;-webkit-box-flex:1;flex:1 0 auto}.gb_Na.gb_Oa .gb_dd{padding-right:14px}.gb_xd{-webkit-flex:1 1 100%;-webkit-box-flex:1;flex:1 1 100%}.gb_xd\x3e:only-child{display:inline-block}.gb_yd.gb_4c{padding-left:4px}.gb_yd.gb_zd,.gb_Na.gb_sd .gb_yd,.gb_Na.gb_Oa:not(.gb_f) .gb_yd{padding-left:0}.gb_Na.gb_Oa .gb_yd.gb_zd{padding-right:0}.gb_Na.gb_Oa .gb_yd.gb_zd .gb_Ba{margin-left:10px}.gb_4c{display:inline}.gb_Na.gb_Xc .gb_yd.gb_Ad,.gb_Na.gb_f .gb_yd.gb_Ad{padding-left:2px}.gb_bd{display:inline-block}.gb_yd{-webkit-box-sizing:border-box;box-sizing:border-box;height:48px;line-height:normal;padding:0 4px;padding-left:30px;-webkit-flex:0 0 auto;-webkit-box-flex:0;flex:0 0 auto;-webkit-box-pack:flex-end;-webkit-justify-content:flex-end;justify-content:flex-end}.gb_f{height:48px}.gb_Na.gb_f{min-width:auto}.gb_f .gb_yd{float:right;padding-left:32px}.gb_f .gb_yd.gb_Bd{padding-left:0}.gb_Cd{font-size:14px;max-width:200px;overflow:hidden;padding:0 12px;text-overflow:ellipsis;white-space:nowrap;-webkit-user-select:text}.gb_id{-webkit-transition:background-color .4s;-webkit-transition:background-color .4s;transition:background-color .4s}.gb_Jd{color:black}.gb_Mc{color:white}.gb_Na a,.gb_Rc a{color:inherit}.gb_S{color:rgba(0,0,0,.87)}.gb_Na svg,.gb_Rc svg,.gb_dd .gb_ld,.gb_3c .gb_ld{color:#5f6368;opacity:1}.gb_Mc svg,.gb_Rc.gb_Vc svg,.gb_Mc .gb_dd .gb_ld,.gb_Mc .gb_dd .gb_Lc,.gb_Mc .gb_dd .gb_fd,.gb_Rc.gb_Vc .gb_ld{color:rgba(255,255,255,.87)}.gb_Mc .gb_dd .gb_Kc:not(.gb_Kd){opacity:.87}.gb_cd{color:inherit;opacity:1;text-rendering:optimizeLegibility;-webkit-font-smoothing:antialiased}.gb_Mc .gb_cd,.gb_Jd .gb_cd{opacity:1}.gb_Dd{position:relative}.gb_Ed{font-family:arial,sans-serif;line-height:normal;padding-right:15px}a.gb_E,span.gb_E{color:rgba(0,0,0,.87);text-decoration:none}.gb_Mc a.gb_E,.gb_Mc span.gb_E{color:white}a.gb_E:focus{outline-offset:2px}a.gb_E:hover{text-decoration:underline}.gb_F{display:inline-block;padding-left:15px}.gb_F .gb_E{display:inline-block;line-height:24px;vertical-align:middle}.gb_Ld{font-family:Google Sans,Roboto,Helvetica,Arial,sans-serif;font-weight:500;font-size:14px;letter-spacing:.25px;line-height:16px;margin-left:10px;margin-right:8px;min-width:96px;padding:9px 23px;text-align:center;vertical-align:middle;border-radius:4px;box-sizing:border-box}.gb_Na.gb_f .gb_Ld{margin-left:8px}#gb a.gb_za.gb_Ld{cursor:pointer}.gb_za.gb_Ld:hover{background:#1b66c9;-webkit-box-shadow:0 1px 3px 1px rgba(66,64,67,.15),0 1px 2px 0 rgba(60,64,67,.3);box-shadow:0 1px 3px 1px rgba(66,64,67,.15),0 1px 2px 0 rgba(60,64,67,.3)}.gb_za.gb_Ld:focus,.gb_za.gb_Ld:hover:focus{background:#1c5fba;-webkit-box-shadow:0 1px 3px 1px rgba(66,64,67,.15),0 1px 2px 0 rgba(60,64,67,.3);box-shadow:0 1px 3px 1px rgba(66,64,67,.15),0 1px 2px 0 rgba(60,64,67,.3)}.gb_za.gb_Ld:active{background:#1b63c1;-webkit-box-shadow:0 1px 3px 1px rgba(66,64,67,.15),0 1px 2px 0 rgba(60,64,67,.3);box-shadow:0 1px 3px 1px rgba(66,64,67,.15),0 1px 2px 0 rgba(60,64,67,.3)}.gb_Ld{background:#1a73e8;border:1px solid transparent}.gb_Na.gb_Oa .gb_Ld{padding:9px 15px;min-width:80px}.gb_Fd{text-align:left}#gb .gb_Mc a.gb_Ld:not(.gb_j),#gb.gb_Mc a.gb_Ld:not(.gb_Md){background:#fff;border-color:#dadce0;-webkit-box-shadow:none;box-shadow:none;color:#1a73e8}#gb a.gb_za.gb_j.gb_Ld{background:#8ab4f8;border:1px solid transparent;-webkit-box-shadow:none;box-shadow:none;color:#202124}#gb .gb_Mc a.gb_Ld:hover:not(.gb_j),#gb.gb_Mc a.gb_Ld:not(.gb_Md):hover{background:#f8fbff;border-color:#cce0fc}#gb a.gb_za.gb_j.gb_Ld:hover{background:#93baf9;border-color:transparent;-webkit-box-shadow:0 1px 3px 1px rgba(0,0,0,.15),0 1px 2px rgba(0,0,0,.3);box-shadow:0 1px 3px 1px rgba(0,0,0,.15),0 1px 2px rgba(0,0,0,.3)}#gb .gb_Mc a.gb_Ld:focus:not(.gb_j),#gb .gb_Mc a.gb_Ld:focus:hover:not(.gb_j),#gb.gb_Mc a.gb_Ld:focus:not(.gb_j),#gb.gb_Mc a.gb_Ld:focus:hover:not(.gb_j){background:#f4f8ff;outline:1px solid #c9ddfc}#gb a.gb_za.gb_j.gb_Ld:focus,#gb a.gb_za.gb_j.gb_Ld:focus:hover{background:#a6c6fa;border-color:transparent;-webkit-box-shadow:none;box-shadow:none}#gb .gb_Mc a.gb_Ld:active:not(.gb_j),#gb.gb_Mc a.gb_Ld:not(.gb_Md):active{background:#ecf3fe}#gb a.gb_za.gb_j.gb_Ld:active{background:#a1c3f9;-webkit-box-shadow:0 1px 2px rgba(60,64,67,.3),0 2px 6px 2px rgba(60,64,67,.15);box-shadow:0 1px 2px rgba(60,64,67,.3),0 2px 6px 2px rgba(60,64,67,.15)}.gb_Nd{display:none}@media screen and (max-width:319px){.gb_od:not(.gb_td) .gb_l{display:none;visibility:hidden}}.gb_Ba{background-color:rgba(255,255,255,.88);border:1px solid #dadce0;-webkit-box-sizing:border-box;box-sizing:border-box;cursor:pointer;display:inline-block;max-height:48px;overflow:hidden;outline:none;padding:0;vertical-align:middle;width:134px;-webkit-border-radius:8px;border-radius:8px}.gb_Ba.gb_j{background-color:transparent;border:1px solid #5f6368}.gb_Ia{display:inherit}.gb_Ba.gb_j .gb_Ia{background:#fff;-webkit-border-radius:4px;border-radius:4px;display:inline-block;left:8px;margin-right:5px;position:relative;padding:3px;top:-1px}.gb_Ba:hover{border:1px solid #d2e3fc;background-color:rgba(248,250,255,.88)}.gb_Ba.gb_j:hover{background-color:rgba(241,243,244,.04);border:1px solid #5f6368}.gb_Ba:focus-visible,.gb_Ba:focus{background-color:#fff;outline:1px solid #202124;-webkit-box-shadow:0 1px 2px 0 rgba(60,64,67,.3),0 1px 3px 1px rgba(60,64,67,.15);box-shadow:0 1px 2px 0 rgba(60,64,67,.3),0 1px 3px 1px rgba(60,64,67,.15)}.gb_Ba.gb_j:focus-visible,.gb_Ba.gb_j:focus{background-color:rgba(241,243,244,.12);outline:1px solid #f1f3f4;-webkit-box-shadow:0 1px 3px 1px rgba(0,0,0,.15),0 1px 2px 0 rgba(0,0,0,.3);box-shadow:0 1px 3px 1px rgba(0,0,0,.15),0 1px 2px 0 rgba(0,0,0,.3)}.gb_Ba.gb_j:active,.gb_Ba.gb_Ja.gb_j:focus{background-color:rgba(241,243,244,.1);border:1px solid #5f6368}.gb_Ka{display:inline-block;padding-bottom:2px;padding-left:7px;padding-top:2px;text-align:center;vertical-align:middle;line-height:32px;width:78px}.gb_Ba.gb_j .gb_Ka{line-height:26px;margin-left:0;padding-bottom:0;padding-left:0;padding-top:0;width:72px}.gb_Ka.gb_La{background-color:#f1f3f4;-webkit-border-radius:4px;border-radius:4px;margin-left:8px;padding-left:0;line-height:30px}.gb_Ka.gb_La .gb_Ma{vertical-align:middle}.gb_Na:not(.gb_Oa) .gb_Ba{margin-left:10px;margin-right:4px}.gb_Pa{max-height:32px;width:78px}.gb_Ba.gb_j .gb_Pa{max-height:26px;width:72px}.gb_n{-webkit-background-size:32px 32px;background-size:32px 32px;border:0;-webkit-border-radius:50%;border-radius:50%;display:block;margin:0px;position:relative;height:32px;width:32px;z-index:0}.gb_0a{background-color:#e8f0fe;border:1px solid rgba(32,33,36,.08);position:relative}.gb_0a.gb_n{height:30px;width:30px}.gb_0a.gb_n:hover,.gb_0a.gb_n:active{-webkit-box-shadow:none;box-shadow:none}.gb_1a{background:#fff;border:none;-webkit-border-radius:50%;border-radius:50%;bottom:2px;-webkit-box-shadow:0px 1px 2px 0px rgba(60,64,67,.30),0px 1px 3px 1px rgba(60,64,67,.15);box-shadow:0px 1px 2px 0px rgba(60,64,67,.30),0px 1px 3px 1px rgba(60,64,67,.15);height:14px;margin:2px;position:absolute;right:0;width:14px}.gb_2a{color:#1f71e7;font:400 22px/32px Google Sans,Roboto,Helvetica,Arial,sans-serif;text-align:center;text-transform:uppercase}@media (-webkit-min-device-pixel-ratio:1.25),(min-resolution:1.25dppx),(min-device-pixel-ratio:1.25){.gb_n::before,.gb_3a::before{display:inline-block;-webkit-transform:scale(0.5);-webkit-transform:scale(0.5);transform:scale(0.5);-webkit-transform-origin:left 0;-webkit-transform-origin:left 0;transform-origin:left 0}.gb_K .gb_3a::before{-webkit-transform:scale(scale(0.416666667));-webkit-transform:scale(scale(0.416666667));transform:scale(scale(0.416666667))}}.gb_n:hover,.gb_n:focus{-webkit-box-shadow:0 1px 0 rgba(0,0,0,.15);box-shadow:0 1px 0 rgba(0,0,0,.15)}.gb_n:active{-webkit-box-shadow:inset 0 2px 0 rgba(0,0,0,.15);box-shadow:inset 0 2px 0 rgba(0,0,0,.15)}.gb_n:active::after{background:rgba(0,0,0,.1);-webkit-border-radius:50%;border-radius:50%;content:\x22\x22;display:block;height:100%}.gb_4a{cursor:pointer;line-height:40px;min-width:30px;opacity:.75;overflow:hidden;vertical-align:middle;text-overflow:ellipsis}.gb_d.gb_4a{width:auto}.gb_4a:hover,.gb_4a:focus{opacity:.85}.gb_5a .gb_4a,.gb_5a .gb_6a{line-height:26px}#gb#gb.gb_5a a.gb_4a,.gb_5a .gb_6a{font-size:11px;height:auto}.gb_7a{border-top:4px solid #000;border-left:4px dashed transparent;border-right:4px dashed transparent;display:inline-block;margin-left:6px;opacity:.75;vertical-align:middle}.gb_Da:hover .gb_7a{opacity:.85}.gb_Ba\x3e.gb_b{padding:3px 3px 3px 4px}.gb_8a.gb_Za{color:#fff}.gb_I .gb_4a,.gb_I .gb_7a{opacity:1}#gb#gb.gb_I.gb_I a.gb_4a,#gb#gb .gb_I.gb_I a.gb_4a{color:#fff}.gb_I.gb_I .gb_7a{border-top-color:#fff;opacity:1}.gb_2 .gb_n:hover,.gb_I .gb_n:hover,.gb_2 .gb_n:focus,.gb_I .gb_n:focus{-webkit-box-shadow:0 1px 0 rgba(0,0,0,.15),0 1px 2px rgba(0,0,0,.2);box-shadow:0 1px 0 rgba(0,0,0,.15),0 1px 2px rgba(0,0,0,.2)}.gb_9a .gb_b,.gb_ab .gb_b{position:absolute;right:1px}.gb_b.gb_H,.gb_bb.gb_H,.gb_Da.gb_H{-webkit-flex:0 1 auto;-webkit-box-flex:0;flex:0 1 auto}.gb_cb.gb_db .gb_4a{width:30px!important}.gb_m{height:40px;position:absolute;right:-5px;top:-5px;width:40px}.gb_eb .gb_m,.gb_fb .gb_m{right:0;top:0}.gb_b .gb_d{padding:4px}.gb_q{display:none}sentinel{}\x3c/style\x3e', function() {
                        ;this.gbar_ = {
                            CONFIG: [[[0, "www.gstatic.com", "og.qtm.en_US.hwyfGG8VptQ.2019.O", "com.vn", "vi", "1", 1, [4, 2, "", "", "", "570237382", "0"], null, "Ny0hZdKCIOGh0-kPx8CT8AI", null, 0, "og.qtm.uGv8uTlIznU.L.W.O", "AA2YrTvixsfv1A3Mw-06Md8Ysk0A4FqoTA", "AA2YrTspfdc2CFY9fQigvAUeVsoR6jxShA", "", 2, 1, 200, "VNM", null, null, "1", "1", 1, null, null, 89978449], null, [1, 0.1000000014901161, 2, 1], null, [0, 0, 0, null, "", "", "", "", 0, 0, 0], [0, 0, "", 1, 0, 0, 0, 0, 0, 0, null, 0, 0, null, 0, 0, null, null, 0, 0, 0, "", "", "", "", "", "", null, 0, 0, 0, 0, 0, null, null, null, "rgba(32,33,36,1)", "rgba(255,255,255,1)", 0, 0, 1, null, null, 1, 0, 0], null, null, ["1", "gci_91f30755d6a6b787dcc2a4062e6e9824.js", "googleapis.client:gapi.iframes", "", "vi"], null, null, null, null, ["m;/_/scs/abc-static/_/js/k=gapi.gapi.en.Ox0HebTIzao.O/d=1/rs=AHpOoo9JBE0z9__nE4FgyS-eLRbRwEP9Gw/m=__features__", "https://apis.google.com", "", "", "", "", null, 1, "es_plusone_gc_20230905.0_p0", "vi", null, 0], [0.009999999776482582, "com.vn", "1", [null, "", "0", null, 1, 5184000, null, null, "", null, null, null, null, null, 0, null, 0, null, 1, 0, 0, 0, null, null, 0, 0, null, 0, 0, 0, 0, 0], null, null, null, 0, null, null, ["5061451", "google\\.(com|ru|ca|by|kz|com\\.mx|com\\.tr)$", 1]], [1, 1, null, 40400, 1, "VNM", "vi", "570237382.0", 8, 0.009999999776482582, 0, 0, null, null, null, null, "", null, null, null, "Ny0hZdKCIOGh0-kPx8CT8AI", 0, 1, 0, null, 2, 5, "ta", 67, 0, 0, 0, 0, 1, 89978449], [[null, null, null, "https://www.gstatic.com/og/_/js/k=og.qtm.en_US.hwyfGG8VptQ.2019.O/rt=j/m=qabr,q_dnp,qcwid,qapid,q_dg/exm=qaaw,qadd,qaid,qein,qhaw,qhba,qhbr,qhch,qhga,qhid,qhin/d=1/ed=1/rs=AA2YrTvixsfv1A3Mw-06Md8Ysk0A4FqoTA"], [null, null, null, "https://www.gstatic.com/og/_/ss/k=og.qtm.uGv8uTlIznU.L.W.O/m=qcwid/excm=qaaw,qadd,qaid,qein,qhaw,qhba,qhbr,qhch,qhga,qhid,qhin/d=1/ed=1/ct=zgms/rs=AA2YrTspfdc2CFY9fQigvAUeVsoR6jxShA"]], null, null, null, [[[null, null, [null, null, null, "https://ogs.google.com/widget/app/so?awwd=1\u0026gm3=1"], 0, 470, 370, 50, 4, 1, 0, 0, 63, 64, 8000, "https://www.google.com.vn/intl/vi/about/products?tab=wh", 67, 1, 69, null, 1, 70, "Đã xảy ra lỗi khi đang tải bộ ứng dụng. Vui lòng thử lại sau vài phút hoặc chuyển đến trang %1$sCác sản phẩm của Google%2$s.", 3, 0, 0, 74, 0, null, null, null, null, null, null, null, "/widget/app/so", null, null, null, null, null, null, null, 0]], null, null, "1", "1", 1, 0, null, "vi", 0, null, 0, 0, 0, null, 0]]],
                        };
                        this.gbar_ = this.gbar_ || {};
                        (function(_) {
                            var window = this;
                            try {
                                /*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
                                var ia, na, qa, ra, za, Aa, Ba, Ca, Da, Ea, Ha, Ta, Va, Ua, Xa, Za, Ya, $a, ab, gb;
                                _.aa = function(a, b) {
                                    if (Error.captureStackTrace)
                                        Error.captureStackTrace(this, _.aa);
                                    else {
                                        const c = Error().stack;
                                        c && (this.stack = c)
                                    }
                                    a && (this.message = String(a));
                                    void 0 !== b && (this.cause = b)
                                }
                                ;
                                _.ca = function(a) {
                                    _.q.setTimeout(()=>{
                                        throw a;
                                    }
                                    , 0)
                                }
                                ;
                                _.ea = function() {
                                    var a = _.q.navigator;
                                    return a && (a = a.userAgent) ? a : ""
                                }
                                ;
                                ia = function(a) {
                                    return fa ? ha ? ha.brands.some(({brand: b})=>b && -1 != b.indexOf(a)) : !1 : !1
                                }
                                ;
                                _.t = function(a) {
                                    return -1 != _.ea().indexOf(a)
                                }
                                ;
                                _.ja = function() {
                                    return fa ? !!ha && 0 < ha.brands.length : !1
                                }
                                ;
                                _.ka = function() {
                                    return _.ja() ? !1 : _.t("Opera")
                                }
                                ;
                                _.la = function() {
                                    return _.ja() ? !1 : _.t("Trident") || _.t("MSIE")
                                }
                                ;
                                _.ma = function() {
                                    return _.t("Firefox") || _.t("FxiOS")
                                }
                                ;
                                _.oa = function() {
                                    return _.t("Safari") && !(na() || (_.ja() ? 0 : _.t("Coast")) || _.ka() || (_.ja() ? 0 : _.t("Edge")) || (_.ja() ? ia("Microsoft Edge") : _.t("Edg/")) || (_.ja() ? ia("Opera") : _.t("OPR")) || _.ma() || _.t("Silk") || _.t("Android"))
                                }
                                ;
                                na = function() {
                                    return _.ja() ? ia("Chromium") : (_.t("Chrome") || _.t("CriOS")) && !(_.ja() ? 0 : _.t("Edge")) || _.t("Silk")
                                }
                                ;
                                _.pa = function() {
                                    return _.t("Android") && !(na() || _.ma() || _.ka() || _.t("Silk"))
                                }
                                ;
                                qa = function() {
                                    return fa ? !!ha && !!ha.platform : !1
                                }
                                ;
                                ra = function() {
                                    return _.t("iPhone") && !_.t("iPod") && !_.t("iPad")
                                }
                                ;
                                _.sa = function() {
                                    return ra() || _.t("iPad") || _.t("iPod")
                                }
                                ;
                                _.ta = function() {
                                    return qa() ? "macOS" === ha.platform : _.t("Macintosh")
                                }
                                ;
                                _.va = function(a, b) {
                                    return 0 <= _.ua(a, b)
                                }
                                ;
                                _.wa = function(a) {
                                    let b = ""
                                      , c = 0;
                                    const d = a.length - 10240;
                                    for (; c < d; )
                                        b += String.fromCharCode.apply(null, a.subarray(c, c += 10240));
                                    b += String.fromCharCode.apply(null, c ? a.subarray(c) : a);
                                    return btoa(b)
                                }
                                ;
                                _.xa = function(a) {
                                    return null != a && a instanceof Uint8Array
                                }
                                ;
                                _.ya = function(a) {
                                    return Array.prototype.slice.call(a)
                                }
                                ;
                                za = function(a) {
                                    const b = a[_.u] | 0;
                                    1 !== (b & 1) && (Object.isFrozen(a) && (a = _.ya(a)),
                                    a[_.u] = b | 1)
                                }
                                ;
                                Aa = function() {
                                    var a = [];
                                    a[_.u] |= 1;
                                    return a
                                }
                                ;
                                Ba = function(a, b) {
                                    b[_.u] = (a | 0) & -255
                                }
                                ;
                                Ca = function(a, b) {
                                    b[_.u] = (a | 34) & -221
                                }
                                ;
                                Da = function(a) {
                                    a = a >> 11 & 1023;
                                    return 0 === a ? 536870912 : a
                                }
                                ;
                                Ea = function(a) {
                                    return null !== a && "object" === typeof a && !Array.isArray(a) && a.constructor === Object
                                }
                                ;
                                _.Fa = function(a) {
                                    if (a & 2)
                                        throw Error();
                                }
                                ;
                                Ha = function(a, b) {
                                    (b = _.Ga ? b[_.Ga] : void 0) && (a[_.Ga] = _.ya(b))
                                }
                                ;
                                _.Ja = function() {
                                    const a = Error();
                                    Ia(a, "incident");
                                    _.ca(a)
                                }
                                ;
                                _.Ka = function() {
                                    const a = Error();
                                    Ia(a, "warning");
                                    return a
                                }
                                ;
                                _.La = function(a) {
                                    Number.isFinite(a) || _.Ja();
                                    return a
                                }
                                ;
                                _.Ma = function(a) {
                                    if ("number" !== typeof a)
                                        throw _.Ka();
                                    Number.isFinite(a) || _.Ja();
                                    return a
                                }
                                ;
                                _.Na = function(a) {
                                    if (null != a && "string" !== typeof a)
                                        throw Error();
                                    return a
                                }
                                ;
                                _.Oa = function(a) {
                                    return null == a || "string" === typeof a ? a : void 0
                                }
                                ;
                                _.Qa = function(a, b, c) {
                                    var d = !1;
                                    if (null != a && "object" === typeof a && !(d = Array.isArray(a)) && a.re === Pa)
                                        return a;
                                    if (d) {
                                        var e = d = a[_.u] | 0;
                                        0 === e && (e |= c & 32);
                                        e |= c & 2;
                                        e !== d && (a[_.u] = e);
                                        return new b(a)
                                    }
                                }
                                ;
                                _.Sa = function(a, b) {
                                    Ra = b;
                                    a = new a(b);
                                    Ra = void 0;
                                    return a
                                }
                                ;
                                Ta = function(a, b, c) {
                                    const d = 1023 + b
                                      , e = a.length;
                                    for (let f = d; f < e; f++) {
                                        const g = a[f];
                                        null != g && g !== c && (c[f - b] = g)
                                    }
                                    a.length = d + 1;
                                    a[d] = c
                                }
                                ;
                                Va = function(a, b) {
                                    return Ua(b)
                                }
                                ;
                                Ua = function(a) {
                                    switch (typeof a) {
                                    case "number":
                                        return isFinite(a) ? a : String(a);
                                    case "boolean":
                                        return a ? 1 : 0;
                                    case "object":
                                        if (a && !Array.isArray(a)) {
                                            if (_.xa(a))
                                                return _.wa(a);
                                            if ("function" == typeof _.Wa && a instanceof _.Wa)
                                                return a.kg()
                                        }
                                    }
                                    return a
                                }
                                ;
                                Xa = function(a, b, c) {
                                    const d = _.ya(a);
                                    var e = d.length;
                                    const f = b & 256 ? d[e - 1] : void 0;
                                    e += f ? -1 : 0;
                                    for (b = b & 512 ? 1 : 0; b < e; b++)
                                        d[b] = c(d[b]);
                                    if (f) {
                                        b = d[b] = {};
                                        for (const g in f)
                                            b[g] = c(f[g])
                                    }
                                    Ha(d, a);
                                    return d
                                }
                                ;
                                Za = function(a, b, c, d, e, f) {
                                    if (null != a) {
                                        if (Array.isArray(a))
                                            a = e && 0 == a.length && (a[_.u] | 0) & 1 ? void 0 : f && (a[_.u] | 0) & 2 ? a : Ya(a, b, c, void 0 !== d, e, f);
                                        else if (Ea(a)) {
                                            const g = {};
                                            for (let h in a)
                                                g[h] = Za(a[h], b, c, d, e, f);
                                            a = g
                                        } else
                                            a = b(a, d);
                                        return a
                                    }
                                }
                                ;
                                Ya = function(a, b, c, d, e, f) {
                                    const g = d || c ? a[_.u] | 0 : 0;
                                    d = d ? !!(g & 32) : void 0;
                                    const h = _.ya(a);
                                    for (let k = 0; k < h.length; k++)
                                        h[k] = Za(h[k], b, c, d, e, f);
                                    c && (Ha(h, a),
                                    c(g, h));
                                    return h
                                }
                                ;
                                $a = function(a) {
                                    return a.re === Pa ? a.toJSON() : Ua(a)
                                }
                                ;
                                ab = function(a, b, c=Ca) {
                                    if (null != a) {
                                        if (a instanceof Uint8Array)
                                            return b ? a : new Uint8Array(a);
                                        if (Array.isArray(a)) {
                                            var d = a[_.u] | 0;
                                            if (d & 2)
                                                return a;
                                            b && (b = 0 === d || !!(d & 32) && !(d & 64 || !(d & 16)));
                                            return b ? (a[_.u] = d | 34,
                                            d & 4 && Object.freeze(a),
                                            a) : Ya(a, ab, d & 4 ? Ca : c, !0, !1, !0)
                                        }
                                        a.re === Pa && (c = a.na,
                                        d = c[_.u],
                                        a = d & 2 ? a : _.Sa(a.constructor, _.bb(c, d, !0)));
                                        return a
                                    }
                                }
                                ;
                                _.bb = function(a, b, c) {
                                    const d = c || b & 2 ? Ca : Ba
                                      , e = !!(b & 32);
                                    a = Xa(a, b, f=>ab(f, e, d));
                                    a[_.u] = a[_.u] | 32 | (c ? 2 : 0);
                                    return a
                                }
                                ;
                                _.cb = function(a) {
                                    const b = a.na
                                      , c = b[_.u];
                                    return c & 2 ? _.Sa(a.constructor, _.bb(b, c, !1)) : a
                                }
                                ;
                                _.db = function(a, b, c, d, e) {
                                    var f = Da(b);
                                    if (c >= f || e) {
                                        e = b;
                                        if (b & 256)
                                            f = a[a.length - 1];
                                        else {
                                            if (null == d)
                                                return;
                                            f = a[f + (+!!(b & 512) - 1)] = {};
                                            e |= 256
                                        }
                                        f[c] = d;
                                        e !== b && (a[_.u] = e)
                                    } else
                                        a[c + (+!!(b & 512) - 1)] = d,
                                        b & 256 && (a = a[a.length - 1],
                                        c in a && delete a[c])
                                }
                                ;
                                _.eb = function(a, b) {
                                    return null != a ? a : b
                                }
                                ;
                                gb = function(a, b, c) {
                                    var d = a.constructor.ya
                                      , e = Da((c ? a.na : b)[_.u])
                                      , f = !1;
                                    if (d) {
                                        if (!c) {
                                            b = _.ya(b);
                                            var g;
                                            if (b.length && Ea(g = b[b.length - 1]))
                                                for (f = 0; f < d.length; f++)
                                                    if (d[f] >= e) {
                                                        Object.assign(b[b.length - 1] = {}, g);
                                                        break
                                                    }
                                            f = !0
                                        }
                                        e = b;
                                        c = !c;
                                        g = a.na[_.u];
                                        a = Da(g);
                                        g = +!!(g & 512) - 1;
                                        var h;
                                        for (let F = 0; F < d.length; F++) {
                                            var k = d[F];
                                            if (k < a) {
                                                k += g;
                                                var m = e[k];
                                                null == m ? e[k] = c ? _.fb : Aa() : c && m !== _.fb && za(m)
                                            } else {
                                                if (!h) {
                                                    var n = void 0;
                                                    e.length && Ea(n = e[e.length - 1]) ? h = n : e.push(h = {})
                                                }
                                                m = h[k];
                                                null == h[k] ? h[k] = c ? _.fb : Aa() : c && m !== _.fb && za(m)
                                            }
                                        }
                                    }
                                    d = b.length;
                                    if (!d)
                                        return b;
                                    let p, v;
                                    if (Ea(h = b[d - 1])) {
                                        a: {
                                            var r = h;
                                            n = {};
                                            e = !1;
                                            for (let F in r)
                                                c = r[F],
                                                Array.isArray(c) && c != c && (e = !0),
                                                null != c ? n[F] = c : e = !0;
                                            if (e) {
                                                for (let F in n) {
                                                    r = n;
                                                    break a
                                                }
                                                r = null
                                            }
                                        }
                                        r != h && (p = !0);
                                        d--
                                    }
                                    for (; 0 < d; d--) {
                                        h = b[d - 1];
                                        if (null != h)
                                            break;
                                        v = !0
                                    }
                                    if (!p && !v)
                                        return b;
                                    var D;
                                    f ? D = b : D = Array.prototype.slice.call(b, 0, d);
                                    b = D;
                                    f && (b.length = d);
                                    r && b.push(r);
                                    return b
                                }
                                ;
                                _.w = function(a, b) {
                                    return null != a ? !!a : !!b
                                }
                                ;
                                _.x = function(a, b) {
                                    void 0 == b && (b = "");
                                    return null != a ? a : b
                                }
                                ;
                                _.hb = function(a, b) {
                                    void 0 == b && (b = 0);
                                    return null != a ? a : b
                                }
                                ;
                                _.jb = function(a, b) {
                                    let c, d;
                                    for (let e = 1; e < arguments.length; e++) {
                                        d = arguments[e];
                                        for (c in d)
                                            a[c] = d[c];
                                        for (let f = 0; f < ib.length; f++)
                                            c = ib[f],
                                            Object.prototype.hasOwnProperty.call(d, c) && (a[c] = d[c])
                                    }
                                }
                                ;
                                var lb, qb, rb;
                                _.kb = _.kb || {};
                                _.q = this || self;
                                lb = _.q._F_toggles || [];
                                _.mb = function(a, b) {
                                    a = a.split(".");
                                    b = b || _.q;
                                    for (var c = 0; c < a.length; c++)
                                        if (b = b[a[c]],
                                        null == b)
                                            return null;
                                    return b
                                }
                                ;
                                _.nb = function(a) {
                                    var b = typeof a;
                                    return "object" != b ? b : a ? Array.isArray(a) ? "array" : b : "null"
                                }
                                ;
                                _.ob = function(a) {
                                    var b = typeof a;
                                    return "object" == b && null != a || "function" == b
                                }
                                ;
                                _.pb = "closure_uid_" + (1E9 * Math.random() >>> 0);
                                qb = function(a, b, c) {
                                    return a.call.apply(a.bind, arguments)
                                }
                                ;
                                rb = function(a, b, c) {
                                    if (!a)
                                        throw Error();
                                    if (2 < arguments.length) {
                                        var d = Array.prototype.slice.call(arguments, 2);
                                        return function() {
                                            var e = Array.prototype.slice.call(arguments);
                                            Array.prototype.unshift.apply(e, d);
                                            return a.apply(b, e)
                                        }
                                    }
                                    return function() {
                                        return a.apply(b, arguments)
                                    }
                                }
                                ;
                                _.y = function(a, b, c) {
                                    _.y = Function.prototype.bind && -1 != Function.prototype.bind.toString().indexOf("native code") ? qb : rb;
                                    return _.y.apply(null, arguments)
                                }
                                ;
                                _.z = function(a, b) {
                                    a = a.split(".");
                                    var c = _.q;
                                    a[0]in c || "undefined" == typeof c.execScript || c.execScript("var " + a[0]);
                                    for (var d; a.length && (d = a.shift()); )
                                        a.length || void 0 === b ? c[d] && c[d] !== Object.prototype[d] ? c = c[d] : c = c[d] = {} : c[d] = b
                                }
                                ;
                                _.A = function(a, b) {
                                    function c() {}
                                    c.prototype = b.prototype;
                                    a.V = b.prototype;
                                    a.prototype = new c;
                                    a.prototype.constructor = a;
                                    a.Di = function(d, e, f) {
                                        for (var g = Array(arguments.length - 2), h = 2; h < arguments.length; h++)
                                            g[h - 2] = arguments[h];
                                        return b.prototype[e].apply(d, g)
                                    }
                                }
                                ;
                                _.A(_.aa, Error);
                                _.aa.prototype.name = "CustomError";
                                _.sb = String.prototype.trim ? function(a) {
                                    return a.trim()
                                }
                                : function(a) {
                                    return /^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]
                                }
                                ;
                                var tb = !!(lb[0] & 512);
                                var ub;
                                if (lb[0] & 256)
                                    ub = tb;
                                else {
                                    var vb = _.mb("WIZ_global_data.oxN3nb")
                                      , wb = vb && vb[610401301];
                                    ub = null != wb ? wb : !1
                                }
                                var fa = ub;
                                var ha, xb = _.q.navigator;
                                ha = xb ? xb.userAgentData || null : null;
                                _.ua = function(a, b) {
                                    return Array.prototype.indexOf.call(a, b, void 0)
                                }
                                ;
                                _.yb = function(a, b, c) {
                                    Array.prototype.forEach.call(a, b, c)
                                }
                                ;
                                _.zb = function(a) {
                                    _.zb[" "](a);
                                    return a
                                }
                                ;
                                _.zb[" "] = function() {}
                                ;
                                var Mb, Nb, Sb;
                                _.Ab = _.ka();
                                _.B = _.la();
                                _.Bb = _.t("Edge");
                                _.Cb = _.Bb || _.B;
                                _.Db = _.t("Gecko") && !(-1 != _.ea().toLowerCase().indexOf("webkit") && !_.t("Edge")) && !(_.t("Trident") || _.t("MSIE")) && !_.t("Edge");
                                _.Eb = -1 != _.ea().toLowerCase().indexOf("webkit") && !_.t("Edge");
                                _.Fb = _.ta();
                                _.Gb = qa() ? "Windows" === ha.platform : _.t("Windows");
                                _.Hb = qa() ? "Android" === ha.platform : _.t("Android");
                                _.Ib = ra();
                                _.Jb = _.t("iPad");
                                _.Kb = _.t("iPod");
                                _.Lb = _.sa();
                                Mb = function() {
                                    var a = _.q.document;
                                    return a ? a.documentMode : void 0
                                }
                                ;
                                a: {
                                    var Ob = ""
                                      , Pb = function() {
                                        var a = _.ea();
                                        if (_.Db)
                                            return /rv:([^\);]+)(\)|;)/.exec(a);
                                        if (_.Bb)
                                            return /Edge\/([\d\.]+)/.exec(a);
                                        if (_.B)
                                            return /\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);
                                        if (_.Eb)
                                            return /WebKit\/(\S+)/.exec(a);
                                        if (_.Ab)
                                            return /(?:Version)[ \/]?(\S+)/.exec(a)
                                    }();
                                    Pb && (Ob = Pb ? Pb[1] : "");
                                    if (_.B) {
                                        var Qb = Mb();
                                        if (null != Qb && Qb > parseFloat(Ob)) {
                                            Nb = String(Qb);
                                            break a
                                        }
                                    }
                                    Nb = Ob
                                }
                                _.Rb = Nb;
                                if (_.q.document && _.B) {
                                    var Tb = Mb();
                                    Sb = Tb ? Tb : parseInt(_.Rb, 10) || void 0
                                } else
                                    Sb = void 0;
                                _.Ub = Sb;
                                _.Vb = _.ma();
                                _.Wb = ra() || _.t("iPod");
                                _.Xb = _.t("iPad");
                                _.Yb = _.pa();
                                _.Zb = na();
                                _.$b = _.oa() && !_.sa();
                                _.ac = "undefined" !== typeof TextDecoder;
                                _.bc = "undefined" !== typeof TextEncoder;
                                _.u = Symbol();
                                var Pa, cc, dc;
                                Pa = {};
                                dc = [];
                                dc[_.u] = 55;
                                _.fb = Object.freeze(dc);
                                var Ia = function(a, b) {
                                    a.__closure__error__context__984382 || (a.__closure__error__context__984382 = {});
                                    a.__closure__error__context__984382.severity = b
                                };
                                var Ra;
                                _.C = function(a, b) {
                                    a = a.na;
                                    return _.fc(a, a[_.u], b)
                                }
                                ;
                                _.fc = function(a, b, c, d) {
                                    if (-1 === c)
                                        return null;
                                    if (c >= Da(b)) {
                                        if (b & 256)
                                            return a[a.length - 1][c]
                                    } else {
                                        var e = a.length;
                                        if (d && b & 256 && (d = a[e - 1][c],
                                        null != d))
                                            return d;
                                        b = c + (+!!(b & 512) - 1);
                                        if (b < e)
                                            return a[b]
                                    }
                                }
                                ;
                                _.gc = function(a, b, c) {
                                    const d = a.na
                                      , e = d[_.u];
                                    _.Fa(e);
                                    _.db(d, e, b, c);
                                    return a
                                }
                                ;
                                _.E = function(a, b) {
                                    a = _.C(a, b);
                                    return null == a ? a : "boolean" !== typeof a && "number" !== typeof a ? void 0 : !!a
                                }
                                ;
                                _.hc = function(a, b, c, d) {
                                    a = a.na;
                                    const e = a[_.u]
                                      , f = _.fc(a, e, c, d);
                                    b = _.Qa(f, b, e);
                                    b !== f && null != b && _.db(a, e, c, b, d);
                                    return b
                                }
                                ;
                                _.G = function(a, b, c, d=!1) {
                                    b = _.hc(a, b, c, d);
                                    if (null == b)
                                        return b;
                                    a = a.na;
                                    const e = a[_.u];
                                    if (!(e & 2)) {
                                        const f = _.cb(b);
                                        f !== b && (b = f,
                                        _.db(a, e, c, b, d))
                                    }
                                    return b
                                }
                                ;
                                _.H = function(a, b, c) {
                                    null == c && (c = void 0);
                                    return _.gc(a, b, c)
                                }
                                ;
                                _.I = function(a, b) {
                                    return _.Oa(_.C(a, b))
                                }
                                ;
                                _.J = function(a, b) {
                                    return _.eb(_.E(a, b), !1)
                                }
                                ;
                                _.ic = function(a, b, c=0) {
                                    a = a.na;
                                    const d = a[_.u]
                                      , e = _.fc(a, d, b);
                                    var f = null == e ? e : "number" === typeof e || "NaN" === e || "Infinity" === e || "-Infinity" === e ? Number(e) : void 0;
                                    null != f && f !== e && _.db(a, d, b, f);
                                    return _.eb(f, c)
                                }
                                ;
                                _.K = function(a, b) {
                                    return _.eb(_.I(a, b), "")
                                }
                                ;
                                _.L = function(a, b, c) {
                                    if (null != c) {
                                        if ("boolean" !== typeof c)
                                            throw Error("q`" + _.nb(c) + "`" + c);
                                        c = !!c
                                    }
                                    return _.gc(a, b, c)
                                }
                                ;
                                _.M = function(a, b, c) {
                                    return _.gc(a, b, null == c ? c : _.Ma(c))
                                }
                                ;
                                _.N = function(a, b, c) {
                                    return _.gc(a, b, _.Na(c))
                                }
                                ;
                                _.O = function(a, b, c) {
                                    return _.gc(a, b, null == c ? c : _.La(c))
                                }
                                ;
                                _.P = class {
                                    constructor(a, b, c) {
                                        a: {
                                            null == a && (a = Ra);
                                            Ra = void 0;
                                            if (null == a) {
                                                var d = 96;
                                                c ? (a = [c],
                                                d |= 512) : a = [];
                                                b && (d = d & -2095105 | (b & 1023) << 11)
                                            } else {
                                                if (!Array.isArray(a))
                                                    throw Error();
                                                d = a[_.u] | 0;
                                                if (d & 64) {
                                                    _.ec && delete a[_.ec];
                                                    break a
                                                }
                                                d |= 64;
                                                if (c && (d |= 512,
                                                c !== a[0]))
                                                    throw Error();
                                                b: {
                                                    c = a;
                                                    var e = c.length;
                                                    if (e) {
                                                        const g = e - 1;
                                                        var f = c[g];
                                                        if (Ea(f)) {
                                                            d |= 256;
                                                            b = +!!(d & 512) - 1;
                                                            e = g - b;
                                                            1024 <= e && (Ta(c, b, f),
                                                            e = 1023);
                                                            d = d & -2095105 | (e & 1023) << 11;
                                                            break b
                                                        }
                                                    }
                                                    b && (f = +!!(d & 512) - 1,
                                                    b = Math.max(b, e - f),
                                                    1024 < b && (Ta(c, f, {}),
                                                    d |= 256,
                                                    b = 1023),
                                                    d = d & -2095105 | (b & 1023) << 11)
                                                }
                                            }
                                            a[_.u] = d
                                        }
                                        this.na = a
                                    }
                                    toJSON() {
                                        if (cc)
                                            var a = gb(this, this.na, !1);
                                        else
                                            a = Ya(this.na, $a, void 0, void 0, !1, !1),
                                            a = gb(this, a, !0);
                                        return a
                                    }
                                    Ia() {
                                        cc = !0;
                                        try {
                                            return JSON.stringify(this.toJSON(), Va)
                                        } finally {
                                            cc = !1
                                        }
                                    }
                                    zc() {
                                        return !!((this.na[_.u] | 0) & 2)
                                    }
                                }
                                ;
                                _.P.prototype.re = Pa;
                                _.P.prototype.toString = function() {
                                    return gb(this, this.na, !1).toString()
                                }
                                ;
                                _.jc = Symbol();
                                _.kc = Symbol();
                                _.lc = Symbol();
                                _.mc = Symbol();
                                _.nc = Symbol();
                                var oc = class extends _.P {
                                    constructor() {
                                        super()
                                    }
                                }
                                ;
                                _.pc = class extends _.P {
                                    constructor() {
                                        super()
                                    }
                                    zd(a) {
                                        return _.M(this, 3, a)
                                    }
                                }
                                ;
                                var qc = class extends _.P {
                                    constructor(a) {
                                        super(a)
                                    }
                                }
                                ;
                                var rc = class extends _.P {
                                    constructor(a) {
                                        super(a)
                                    }
                                    Qc(a) {
                                        return _.N(this, 24, a)
                                    }
                                }
                                ;
                                _.sc = class extends _.P {
                                    constructor(a) {
                                        super(a)
                                    }
                                }
                                ;
                                _.tc = function() {
                                    this.Fa = this.Fa;
                                    this.ma = this.ma
                                }
                                ;
                                _.tc.prototype.Fa = !1;
                                _.tc.prototype.isDisposed = function() {
                                    return this.Fa
                                }
                                ;
                                _.tc.prototype.oa = function() {
                                    this.Fa || (this.Fa = !0,
                                    this.N())
                                }
                                ;
                                _.tc.prototype.N = function() {
                                    if (this.ma)
                                        for (; this.ma.length; )
                                            this.ma.shift()()
                                }
                                ;
                                var uc = class extends _.tc {
                                    constructor() {
                                        var a = window;
                                        super();
                                        this.o = a;
                                        this.i = [];
                                        this.j = {}
                                    }
                                    resolve(a) {
                                        var b = this.o;
                                        a = a.split(".");
                                        for (var c = a.length, d = 0; d < c; ++d)
                                            if (b[a[d]])
                                                b = b[a[d]];
                                            else
                                                return null;
                                        return b instanceof Function ? b : null
                                    }
                                    Yb() {
                                        for (var a = this.i.length, b = this.i, c = [], d = 0; d < a; ++d) {
                                            var e = b[d].i()
                                              , f = this.resolve(e);
                                            if (f && f != this.j[e])
                                                try {
                                                    b[d].Yb(f)
                                                } catch (g) {}
                                            else
                                                c.push(b[d])
                                        }
                                        this.i = c.concat(b.slice(a))
                                    }
                                }
                                ;
                                var wc = class extends _.tc {
                                    constructor() {
                                        var a = _.vc;
                                        super();
                                        this.o = a;
                                        this.v = this.i = null;
                                        this.s = 0;
                                        this.B = {};
                                        this.j = !1;
                                        a = window.navigator.userAgent;
                                        0 <= a.indexOf("MSIE") && 0 <= a.indexOf("Trident") && (a = /\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a)) && a[1] && 9 > parseFloat(a[1]) && (this.j = !0)
                                    }
                                    A(a, b) {
                                        this.i = b;
                                        this.v = a;
                                        b.preventDefault ? b.preventDefault() : b.returnValue = !1
                                    }
                                }
                                ;
                                _.xc = class extends _.P {
                                    constructor(a) {
                                        super(a)
                                    }
                                }
                                ;
                                var yc = class extends _.P {
                                    constructor(a) {
                                        super(a)
                                    }
                                }
                                ;
                                var Ac;
                                _.zc = function(a, b) {
                                    if (a.i) {
                                        const c = new oc;
                                        _.N(c, 1, b.message);
                                        _.N(c, 2, b.stack);
                                        _.M(c, 3, b.lineNumber);
                                        _.O(c, 5, 1);
                                        b = new _.pc;
                                        _.H(b, 40, c);
                                        a.i.log(98, b)
                                    }
                                }
                                ;
                                Ac = class {
                                    constructor() {
                                        this.i = null
                                    }
                                    log(a) {
                                        _.zc(this, a)
                                    }
                                }
                                ;
                                var Ec, Fc, Ic, Kc;
                                _.Bc = class {
                                    constructor(a) {
                                        this.i = a
                                    }
                                    toString() {
                                        return this.i.toString()
                                    }
                                }
                                ;
                                _.Bc.prototype.Cb = !0;
                                _.Bc.prototype.nb = function() {
                                    return this.i.toString()
                                }
                                ;
                                _.Dc = function(a) {
                                    return a instanceof _.Bc && a.constructor === _.Bc ? a.i : "type_error:SafeUrl"
                                }
                                ;
                                Ec = /^data:(.*);base64,[a-z0-9+\/]+=*$/i;
                                Fc = /^(?:(?:https?|mailto|ftp):|[^:/?#]*(?:[/?#]|$))/i;
                                _.Hc = function(a) {
                                    if (a instanceof _.Bc)
                                        return a;
                                    a = "object" == typeof a && a.Cb ? a.nb() : String(a);
                                    Fc.test(a) ? a = _.Gc(a) : (a = String(a).replace(/(%0A|%0D)/g, ""),
                                    a = a.match(Ec) ? _.Gc(a) : null);
                                    return a
                                }
                                ;
                                try {
                                    new URL("s://g"),
                                    Ic = !0
                                } catch (a) {
                                    Ic = !1
                                }
                                _.Jc = Ic;
                                Kc = {};
                                _.Gc = function(a) {
                                    return new _.Bc(a,Kc)
                                }
                                ;
                                _.Lc = _.Gc("about:invalid#zClosurez");
                                var Mc, Pc, Oc;
                                _.Nc = function(a) {
                                    let b;
                                    b = window.google && window.google.logUrl ? "" : "https://www.google.com";
                                    b += "/gen_204?use_corp=on&";
                                    b += a.Ia(2040 - b.length);
                                    Mc(_.Hc(b) || _.Lc)
                                }
                                ;
                                Mc = function(a) {
                                    var b = new Image
                                      , c = Oc;
                                    b.onerror = b.onload = b.onabort = function() {
                                        c in Pc && delete Pc[c]
                                    }
                                    ;
                                    Pc[Oc++] = b;
                                    b.src = _.Dc(a)
                                }
                                ;
                                Pc = [];
                                Oc = 0;
                                _.Qc = class {
                                    constructor() {
                                        this.data = {}
                                    }
                                    Ia(a) {
                                        var b = [], c;
                                        for (c in this.data)
                                            b.push(encodeURIComponent(c) + "=" + encodeURIComponent(String(this.data[c])));
                                        return ("atyp=i&zx=" + (new Date).getTime() + "&" + b.join("&")).substr(0, a)
                                    }
                                }
                                ;
                                var Rc = class extends _.Qc {
                                    constructor(a) {
                                        super();
                                        var b = _.G(a, qc, 8) || new qc;
                                        window.google && window.google.kEI && (this.data.ei = window.google.kEI);
                                        this.data.sei = _.x(_.I(a, 10));
                                        this.data.ogf = _.x(_.I(b, 3));
                                        this.data.ogrp = (window.google && window.google.sn ? !/.*hp$/.test(window.google.sn) : _.w(_.E(a, 7))) ? "1" : "";
                                        this.data.ogv = _.x(_.I(b, 6)) + "." + _.x(_.I(b, 7));
                                        this.data.ogd = _.x(_.I(a, 21));
                                        this.data.ogc = _.x(_.I(a, 20));
                                        this.data.ogl = _.x(_.I(a, 5));
                                        this.data.oggv = "quantum:gapiBuildLabel"
                                    }
                                }
                                ;
                                var ib = "constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");
                                var Sc = [1, 2, 3, 4, 5, 6, 9, 10, 11, 13, 14, 28, 29, 30, 34, 35, 37, 38, 39, 40, 42, 43, 48, 49, 50, 51, 52, 53, 62, 500]
                                  , Uc = function(a) {
                                    if (!Tc) {
                                        Tc = {};
                                        for (var b = 0; b < Sc.length; b++)
                                            Tc[Sc[b]] = !0
                                    }
                                    return !!Tc[a]
                                }
                                  , Vc = function(a) {
                                    a = String(a);
                                    return a.replace(".", "%2E").replace(",", "%2C")
                                }
                                  , Wc = class extends Rc {
                                    constructor(a, b, c, d, e) {
                                        super(a);
                                        _.jb(this.data, {
                                            oge: c,
                                            ogex: _.x(_.I(a, 9)),
                                            ogp: _.x(_.I(a, 6)),
                                            ogsr: Math.round(1 / (Uc(c) ? _.hb(_.ic(b, 3, 1)) : _.hb(_.ic(b, 2, 1E-4)))),
                                            ogus: d
                                        });
                                        if (e) {
                                            "ogw"in e && (this.data.ogw = e.ogw,
                                            delete e.ogw);
                                            "ved"in e && (this.data.ved = e.ved,
                                            delete e.ved);
                                            a = [];
                                            for (var f in e)
                                                0 != a.length && a.push(","),
                                                a.push(Vc(f)),
                                                a.push("."),
                                                a.push(Vc(e[f]));
                                            e = a.join("");
                                            "" != e && (this.data.ogad = e)
                                        }
                                    }
                                }
                                  , Tc = null;
                                var Xc = class extends _.P {
                                    constructor(a) {
                                        super(a)
                                    }
                                }
                                ;
                                var ad = class {
                                    constructor() {
                                        var a = Yc
                                          , b = Zc
                                          , c = $c;
                                        this.i = a;
                                        this.s = b;
                                        this.o = _.hb(_.ic(a, 2, 1E-4), 1E-4);
                                        this.B = _.hb(_.ic(a, 3, 1), 1);
                                        b = Math.random();
                                        this.j = _.w(_.E(a, 1)) && b < this.o;
                                        this.v = _.w(_.E(a, 1)) && b < this.B;
                                        a = 0;
                                        _.w(_.E(c, 1)) && (a |= 1);
                                        _.w(_.E(c, 2)) && (a |= 2);
                                        _.w(_.E(c, 3)) && (a |= 4);
                                        this.A = a
                                    }
                                    log(a, b) {
                                        try {
                                            if (Uc(a) ? this.v : this.j) {
                                                const c = new Wc(this.s,this.i,a,this.A,b);
                                                _.Nc(c)
                                            }
                                        } catch (c) {}
                                    }
                                }
                                ;
                                var cd;
                                _.bd = function(a) {
                                    if (0 < a.j.length) {
                                        var b = void 0 !== a.ua
                                          , c = void 0 !== a.i;
                                        if (b || c) {
                                            b = b ? a.o : a.s;
                                            c = a.j;
                                            a.j = [];
                                            try {
                                                _.yb(c, b, a)
                                            } catch (d) {
                                                console.error(d)
                                            }
                                        }
                                    }
                                }
                                ;
                                _.dd = class {
                                    constructor(a) {
                                        this.ua = a;
                                        this.i = void 0;
                                        this.j = []
                                    }
                                    then(a, b, c) {
                                        this.j.push(new cd(a,b,c));
                                        _.bd(this)
                                    }
                                    resolve(a) {
                                        if (void 0 !== this.ua || void 0 !== this.i)
                                            throw Error("x");
                                        this.ua = a;
                                        _.bd(this)
                                    }
                                    o(a) {
                                        a.j && a.j.call(a.i, this.ua)
                                    }
                                    s(a) {
                                        a.o && a.o.call(a.i, this.i)
                                    }
                                }
                                ;
                                cd = class {
                                    constructor(a, b, c) {
                                        this.j = a;
                                        this.o = b;
                                        this.i = c
                                    }
                                }
                                ;
                                _.ed = a=>{
                                    var b = "xc";
                                    if (a.xc && a.hasOwnProperty(b))
                                        return a.xc;
                                    b = new a;
                                    return a.xc = b
                                }
                                ;
                                _.Q = class {
                                    constructor() {
                                        this.s = new _.dd;
                                        this.i = new _.dd;
                                        this.C = new _.dd;
                                        this.B = new _.dd;
                                        this.A = new _.dd;
                                        this.v = new _.dd;
                                        this.o = new _.dd;
                                        this.j = new _.dd;
                                        this.G = new _.dd
                                    }
                                    J() {
                                        return this.s
                                    }
                                    L() {
                                        return this.i
                                    }
                                    M() {
                                        return this.C
                                    }
                                    K() {
                                        return this.B
                                    }
                                    Fa() {
                                        return this.A
                                    }
                                    ma() {
                                        return this.v
                                    }
                                    H() {
                                        return this.o
                                    }
                                    F() {
                                        return this.j
                                    }
                                    static i() {
                                        return _.ed(_.Q)
                                    }
                                }
                                ;
                                var kd;
                                _.hd = function() {
                                    return _.G(_.fd, rc, 1)
                                }
                                ;
                                _.id = function() {
                                    return _.G(_.fd, _.sc, 5)
                                }
                                ;
                                kd = class extends _.P {
                                    constructor() {
                                        super(jd)
                                    }
                                }
                                ;
                                var jd;
                                window.gbar_ && window.gbar_.CONFIG ? jd = window.gbar_.CONFIG[0] || {} : jd = [];
                                _.fd = new kd;
                                var Zc, $c, Yc;
                                _.G(_.fd, yc, 3) || new yc;
                                _.hd() || new rc;
                                _.vc = new Ac;
                                Zc = _.hd() || new rc;
                                $c = _.id() || new _.sc;
                                Yc = _.G(_.fd, Xc, 4) || new Xc;
                                new ad;
                                _.z("gbar_._DumpException", function(a) {
                                    _.vc ? _.vc.log(a) : console.error(a)
                                });
                                _.ld = new wc;
                                var nd;
                                _.od = function(a, b) {
                                    var c = _.md.i();
                                    if (a in c.i) {
                                        if (c.i[a] != b)
                                            throw new nd;
                                    } else {
                                        c.i[a] = b;
                                        if (b = c.j[a])
                                            for (let d = 0, e = b.length; d < e; d++)
                                                b[d].i(c.i, a);
                                        delete c.j[a]
                                    }
                                }
                                ;
                                _.md = class {
                                    constructor() {
                                        this.i = {};
                                        this.j = {}
                                    }
                                    static i() {
                                        return _.ed(_.md)
                                    }
                                }
                                ;
                                _.pd = class extends _.aa {
                                    constructor() {
                                        super()
                                    }
                                }
                                ;
                                nd = class extends _.pd {
                                }
                                ;
                                _.z("gbar.A", _.dd);
                                _.dd.prototype.aa = _.dd.prototype.then;
                                _.z("gbar.B", _.Q);
                                _.Q.prototype.ba = _.Q.prototype.L;
                                _.Q.prototype.bb = _.Q.prototype.M;
                                _.Q.prototype.bd = _.Q.prototype.Fa;
                                _.Q.prototype.bf = _.Q.prototype.J;
                                _.Q.prototype.bg = _.Q.prototype.K;
                                _.Q.prototype.bh = _.Q.prototype.ma;
                                _.Q.prototype.bj = _.Q.prototype.H;
                                _.Q.prototype.bk = _.Q.prototype.F;
                                _.z("gbar.a", _.Q.i());
                                var qd = new uc;
                                _.od("api", qd);
                                var rd = _.id() || new _.sc;
                                window.__PVT = _.x(_.I(rd, 8));
                                _.od("eq", _.ld);
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                _.sd = class extends _.P {
                                    constructor(a) {
                                        super(a)
                                    }
                                }
                                ;
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                var td = class extends _.P {
                                    constructor() {
                                        super()
                                    }
                                }
                                ;
                                var ud = class extends _.tc {
                                    constructor() {
                                        super();
                                        this.j = [];
                                        this.i = []
                                    }
                                    o(a, b) {
                                        this.j.push({
                                            features: a,
                                            options: b
                                        })
                                    }
                                    init(a, b, c) {
                                        window.gapi = {};
                                        var d = window.___jsl = {};
                                        d.h = _.x(_.I(a, 1));
                                        null != _.E(a, 12) && (d.dpo = _.w(_.J(a, 12)));
                                        d.ms = _.x(_.I(a, 2));
                                        d.m = _.x(_.I(a, 3));
                                        d.l = [];
                                        _.K(b, 1) && (a = _.I(b, 3)) && this.i.push(a);
                                        _.K(c, 1) && (c = _.I(c, 2)) && this.i.push(c);
                                        _.z("gapi.load", (0,
                                        _.y)(this.o, this));
                                        return this
                                    }
                                }
                                ;
                                var vd = _.G(_.fd, _.xc, 14);
                                if (vd) {
                                    var wd = _.G(_.fd, _.sd, 9) || new _.sd
                                      , xd = new td
                                      , yd = new ud;
                                    yd.init(vd, wd, xd);
                                    _.od("gs", yd)
                                }
                                ;
                            } catch (e) {
                                _._DumpException(e)
                            }
                        }
                        )(this.gbar_);
                        // Google Inc.
                        ;
                    });
                }
                )();
                (function() {
                    window.jsl.dh('tsuid_3', '\x3cg-snackbar jsname\x3d\x22Fd92vb\x22 jscontroller\x3d\x22OZLguc\x22 style\x3d\x22display:none\x22 data-dismiss\x3d\x22\x22 jsshadow\x3d\x22\x22 jsaction\x3d\x22rcuQ6b:npT2md\x22\x3e\x3cdiv jsname\x3d\x22sM5MNb\x22 aria-live\x3d\x22polite\x22 class\x3d\x22LH3wG\x22 style\x3d\x22z-index:2000\x22\x3e\x3cdiv jsname\x3d\x22Ng57nc\x22 class\x3d\x22yK6jqe\x22 data-ved\x3d\x220ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ4G8IBg\x22\x3e\x3cdiv class\x3d\x22b77HKf\x22\x3e\x3cdiv class\x3d\x22rIxsve\x22 jsslot\x3d\x22\x22\x3e\x3cspan class\x3d\x22Txngnb wHYlTd yUTMj\x22\x3eKh\xf4ng thi\u1ebft l\u1eadp \u0111\u01b0\u1ee3c l\u1ef1a ch\u1ecdn \u01b0u ti\xean c\u1ee7a b\u1ea1n. H\xe3y th\u1eed l\u1ea1i.\x3c/span\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/g-snackbar\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('_Ny0hZajKHuSv2roPysWswAY_5', '\x3cdiv jscontroller\x3d\x22w4UyN\x22 class\x3d\x22fLciMb\x22 data-po\x3d\x22360\x22 aria-label\x3d\x22C\xe0i \u0111\u1eb7t\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 jsaction\x3d\x22rcuQ6b:npT2md;HfCvm;mouseenter:eGiyHb;focus:eGiyHb;focusin:eGiyHb;mouseleave:LfDNce;focusout:LfDNce\x22 data-ved\x3d\x220ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ6psICBY\x22\x3e\x3cspan class\x3d\x22z1asCe E9hVAb\x22\x3e\x3csvg focusable\x3d\x22false\x22 xmlns\x3d\x22http://www.w3.org/2000/svg\x22 viewBox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M13.85 22.25h-3.7c-.74 0-1.36-.54-1.45-1.27l-.27-1.89c-.27-.14-.53-.29-.79-.46l-1.8.72c-.7.26-1.47-.03-1.81-.65L2.2 15.53c-.35-.66-.2-1.44.36-1.88l1.53-1.19c-.01-.15-.02-.3-.02-.46 0-.15.01-.31.02-.46l-1.52-1.19c-.59-.45-.74-1.26-.37-1.88l1.85-3.19c.34-.62 1.11-.9 1.79-.63l1.81.73c.26-.17.52-.32.78-.46l.27-1.91c.09-.7.71-1.25 1.44-1.25h3.7c.74 0 1.36.54 1.45 1.27l.27 1.89c.27.14.53.29.79.46l1.8-.72c.71-.26 1.48.03 1.82.65l1.84 3.18c.36.66.2 1.44-.36 1.88l-1.52 1.19c.01.15.02.3.02.46s-.01.31-.02.46l1.52 1.19c.56.45.72 1.23.37 1.86l-1.86 3.22c-.34.62-1.11.9-1.8.63l-1.8-.72c-.26.17-.52.32-.78.46l-.27 1.91c-.1.68-.72 1.22-1.46 1.22zm-3.23-2h2.76l.37-2.55.53-.22c.44-.18.88-.44 1.34-.78l.45-.34 2.38.96 1.38-2.4-2.03-1.58.07-.56c.03-.26.06-.51.06-.78s-.03-.53-.06-.78l-.07-.56 2.03-1.58-1.39-2.4-2.39.96-.45-.35c-.42-.32-.87-.58-1.33-.77l-.52-.22-.37-2.55h-2.76l-.37 2.55-.53.21c-.44.19-.88.44-1.34.79l-.45.33-2.38-.95-1.39 2.39 2.03 1.58-.07.56a7 7 0 0 0-.06.79c0 .26.02.53.06.78l.07.56-2.03 1.58 1.38 2.4 2.39-.96.45.35c.43.33.86.58 1.33.77l.53.22.38 2.55z\x22\x3e\x3c/path\x3e\x3ccircle cx\x3d\x2212\x22 cy\x3d\x2212\x22 r\x3d\x223.5\x22\x3e\x3c/circle\x3e\x3c/svg\x3e\x3c/span\x3e\x3cdiv jsname\x3d\x22suEOdc\x22 class\x3d\x22ZOyvub\x22\x3eC\xe0i \u0111\u1eb7t nhanh\x3c/div\x3e\x3c/div\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('_Ny0hZajKHuSv2roPysWswAY_7', '\x3cspan class\x3d\x22gb\x22 style\x3d\x22display:none\x22\x3e\x3c/span\x3e\x3cdiv class\x3d\x22gb_Na gb_f gb_eb\x22 id\x3d\x22gb\x22\x3e\x3cdiv class\x3d\x22gb_yd gb_cb gb_nd\x22 data-ogsr-up\x3d\x22\x22\x3e\x3cdiv class\x3d\x22gb_Sd\x22\x3e\x3cdiv class\x3d\x22gb_4c\x22\x3e\x3cdiv class\x3d\x22gb_l gb_v gb_H\x22 data-ogsr-fb\x3d\x22true\x22 data-ogsr-alt\x3d\x22\x22 id\x3d\x22gbwa\x22\x3e\x3cdiv class\x3d\x22gb_g\x22\x3e\x3ca class\x3d\x22gb_d\x22 aria-label\x3d\x22C\xe1c \u1ee9ng d\u1ee5ng c\u1ee7a Google\x22 href\x3d\x22https://www.google.com.vn/intl/vi/about/products?tab\x3dwh\x22 aria-expanded\x3d\x22false\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22\x3e\x3csvg class\x3d\x22gb_i\x22 focusable\x3d\x22false\x22 viewbox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M6,8c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM12,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM6,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM6,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM12,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM16,6c0,1.1 0.9,2 2,2s2,-0.9 2,-2 -0.9,-2 -2,-2 -2,0.9 -2,2zM12,8c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM18,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM18,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2z\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/a\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3ca class\x3d\x22gb_za gb_jd gb_Ld gb_ie\x22 href\x3d\x22https://accounts.google.com/ServiceLogin?hl\x3dvi\x26amp;passive\x3dtrue\x26amp;continue\x3dhttps://www.google.com/search%3Fq%3Dcode%2Bmau%2Btoken%2Bgooogle%26oq%3Dcode%2Bmau%2Btoken%2Bgooogle%26gs_lcrp%3DEgZjaHJvbWUyBggAEEUYOdIBCDQxMTFqMGoxqAIAsAIA%26sourceid%3Dchrome%26ie%3DUTF-8\x26amp;ec\x3dGAZAAQ\x22 target\x3d\x22_top\x22\x3e\x3cspan class\x3d\x22gb_Hd\x22\x3e\u0110\u0103ng nh\u1eadp\x3c/span\x3e\x3c/a\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('_Ny0hZajKHuSv2roPysWswAY_18', '\x3cg-menu jsname\x3d\x22xl07Ob\x22 class\x3d\x22cF4V5c zriOQb UU8UAb yTik0 wplJBd PBn44e iQXTJe\x22 jscontroller\x3d\x22WlNQGd\x22 role\x3d\x22menu\x22 tabindex\x3d\x22-1\x22 jsaction\x3d\x22PSl28c;focus:h06R8;keydown:uYT2Vb;mouseenter:WOQqYb;mouseleave:Tx5Rb;mouseover:IgJl9c\x22\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;ANVEfo\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3ca href\x3d\x22/search?q\x3dcode+mau+token+google\x26amp;sca_esv\x3d571531489\x26amp;tbm\x3dshop\x26amp;source\x3dlnms\x26amp;sa\x3dX\x26amp;ved\x3d2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ_AUoAHoECAEQCg\x22 role\x3d\x22menuitem\x22 tabindex\x3d\x22-1\x22\x3e\x3cspan class\x3d\x22bmaJhd iJddsb\x22 style\x3d\x22height:16px;width:16px\x22\x3e\x3csvg focusable\x3d\x22false\x22 viewbox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M21.11 2.89A3.02 3.02 0 0 0 18.95 2h-5.8c-.81 0-1.58.31-2.16.89L7.25 6.63 2.9 10.98a3.06 3.06 0 0 0 0 4.32l5.79 5.8a3.05 3.05 0 0 0 4.32.01l8.09-8.1c.58-.58.9-1.34.9-2.16v-5.8c0-.81-.32-1.59-.89-2.16zM20 10.85c0 .28-.12.54-.32.74l-3.73 3.74-4.36 4.36c-.41.41-1.08.41-1.49 0l-2.89-2.9-2.9-2.9a1.06 1.06 0 0 1 0-1.49l8.1-8.1c.2-.2.46-.3.74-.3l5.8-.01A1.05 1.05 0 0 1 20 5.05v5.8zM16 6c1.1 0 2 .9 2 2s-.9 2-2 2-2-.9-2-2 .9-2 2-2\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3eMua s\u1eafm\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;ANVEfo\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3ca href\x3d\x22https://www.google.com/travel/flights?q\x3dcode+mau+token+google\x26amp;sca_esv\x3d571531489\x26amp;tbm\x3dflm\x26amp;source\x3dlnms\x26amp;sa\x3dX\x26amp;ved\x3d2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ_AUoAXoECAEQCw\x22 role\x3d\x22menuitem\x22 tabindex\x3d\x22-1\x22\x3e\x3cspan class\x3d\x22bmaJhd iJddsb\x22 style\x3d\x22height:16px;width:16px\x22\x3e\x3csvg focusable\x3d\x22false\x22 viewbox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M12.98 12.89l-4.03 4.03.42 2.95L8.24 21l-1.87-3.37L3 15.76l1.12-1.12 2.95.42 4.03-4.03L3 6.77l1.5-1.5 10.04 2.32 4.2-4.2a1.32 1.32 0 0 1 1.87 0c.52.52.52 1.36 0 1.87l-4.2 4.2 2.32 10.04-1.5 1.5-4.25-8.11\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3eChuy\u1ebfn bay\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;ANVEfo\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3ca href\x3d\x22https://www.google.com/finance?sa\x3dX\x26amp;ved\x3d2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ_AUoAnoECAEQDA\x22 role\x3d\x22menuitem\x22 tabindex\x3d\x22-1\x22\x3e\x3cspan class\x3d\x22bmaJhd iJddsb\x22 style\x3d\x22height:16px;width:16px\x22\x3e\x3csvg focusable\x3d\x22false\x22 viewbox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M6 15.5l-3 2.94V10h3v5.5zm5-1.84l-1.57-1.34L8 13.64V6h3v7.66zM16 12l-3 3V2h3v10zm2.81-.19L17 10h5v5l-1.79-1.79L13 20.36l-3.47-3.02L5.75 21H3l6.47-6.34L13 17.64l5.81-5.83\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3eTa\u0300i chi\u0301nh\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3c/g-menu\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('_Ny0hZajKHuSv2roPysWswAY_25', '\x3cg-menu jsname\x3d\x22xl07Ob\x22 class\x3d\x22cF4V5c yTik0 wplJBd PBn44e iQXTJe\x22 jscontroller\x3d\x22WlNQGd\x22 role\x3d\x22menu\x22 tabindex\x3d\x22-1\x22 jsaction\x3d\x22PSl28c;focus:h06R8;keydown:uYT2Vb;mouseenter:WOQqYb;mouseleave:Tx5Rb;mouseover:IgJl9c\x22 data-ved\x3d\x222ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQtvsKegQIARAR\x22\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 class\x3d\x22RVRNTb EpPYLd Zt0a5e\x22 jscontroller\x3d\x22CnSW2d\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;ANVEfo\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb\x22 role\x3d\x22none\x22\x3e\x3ca class\x3d\x22kQyaVc\x22 href\x3d\x22/setprefs?sig\x3d0_xDO3A9IdJDyLMySgNKVsRhDATyU%3D\x26amp;prev\x3dhttps://www.google.com/search?q%3Dcode%2Bmau%2Btoken%2Bgooogle%26oq%3Dcode%2Bmau%2Btoken%2Bgooogle%26gs_lcrp%3DEgZjaHJvbWUyBggAEEUYOdIBCDQxMTFqMGoxqAIAsAIA%26sourceid%3Dchrome%26ie%3DUTF-8\x26amp;safeui\x3don\x22 role\x3d\x22menuitem\x22 tabindex\x3d\x22-1\x22 ping\x3d\x22/url?sa\x3dt\x26amp;source\x3dweb\x26amp;rct\x3dj\x26amp;opi\x3d89978449\x26amp;url\x3d/setprefs%3Fsig%3D0_xDO3A9IdJDyLMySgNKVsRhDATyU%253D%26prev%3Dhttps://www.google.com/search%3Fq%253Dcode%252Bmau%252Btoken%252Bgooogle%2526oq%253Dcode%252Bmau%252Btoken%252Bgooogle%2526gs_lcrp%253DEgZjaHJvbWUyBggAEEUYOdIBCDQxMTFqMGoxqAIAsAIA%2526sourceid%253Dchrome%2526ie%253DUTF-8%26safeui%3Don\x26amp;ved\x3d2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ3roKegQIARAT\x22\x3e\x3cdiv class\x3d\x22z4R3Z\x22\x3e\x3cspan class\x3d\x22L3FBEc\x22\x3e\x3c/span\x3eL\u1ecdc b\u1ecf k\u1ebft qu\u1ea3 ph\u1ea3n c\u1ea3m\x3c/div\x3e\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 class\x3d\x22RVRNTb EpPYLd Zt0a5e\x22 jscontroller\x3d\x22CnSW2d\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;ANVEfo\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb\x22 role\x3d\x22none\x22\x3e\x3ca class\x3d\x22kQyaVc\x22 data-nohref\x3d\x221\x22 href\x3d\x22#\x22 aria-label\x3d\x22L\xe0m m\u1edd h\xecnh \u1ea3nh ph\u1ea3n c\u1ea3m, \u0111\xe3 ch\u1ecdn\x22 role\x3d\x22menuitem\x22 tabindex\x3d\x22-1\x22 ping\x3d\x22/url?sa\x3dt\x26amp;source\x3dweb\x26amp;rct\x3dj\x26amp;opi\x3d89978449\x26amp;url\x3d%23\x26amp;ved\x3d2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ3boKegQIARAU\x22\x3e\x3cdiv class\x3d\x22z4R3Z\x22\x3e\x3cspan class\x3d\x22wWjvRd z1asCe rH6l6\x22 style\x3d\x22height:16px;line-height:16px;width:16px\x22\x3e\x3csvg focusable\x3d\x22false\x22 xmlns\x3d\x22http://www.w3.org/2000/svg\x22 viewBox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3eL\xe0m m\u1edd h\xecnh \u1ea3nh ph\u1ea3n c\u1ea3m\x3c/div\x3e\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 class\x3d\x22RVRNTb EpPYLd Zt0a5e\x22 jscontroller\x3d\x22CnSW2d\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;ANVEfo\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb\x22 role\x3d\x22none\x22\x3e\x3ca class\x3d\x22kQyaVc\x22 href\x3d\x22/setprefs?sig\x3d0_xDO3A9IdJDyLMySgNKVsRhDATyU%3D\x26amp;prev\x3dhttps://www.google.com/search?q%3Dcode%2Bmau%2Btoken%2Bgooogle%26oq%3Dcode%2Bmau%2Btoken%2Bgooogle%26gs_lcrp%3DEgZjaHJvbWUyBggAEEUYOdIBCDQxMTFqMGoxqAIAsAIA%26sourceid%3Dchrome%26ie%3DUTF-8\x26amp;safeui\x3doff\x22 role\x3d\x22menuitem\x22 tabindex\x3d\x22-1\x22 ping\x3d\x22/url?sa\x3dt\x26amp;source\x3dweb\x26amp;rct\x3dj\x26amp;opi\x3d89978449\x26amp;url\x3d/setprefs%3Fsig%3D0_xDO3A9IdJDyLMySgNKVsRhDATyU%253D%26prev%3Dhttps://www.google.com/search%3Fq%253Dcode%252Bmau%252Btoken%252Bgooogle%2526oq%253Dcode%252Bmau%252Btoken%252Bgooogle%2526gs_lcrp%253DEgZjaHJvbWUyBggAEEUYOdIBCDQxMTFqMGoxqAIAsAIA%2526sourceid%253Dchrome%2526ie%253DUTF-8%26safeui%3Doff\x26amp;ved\x3d2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ37oKegQIARAV\x22\x3e\x3cdiv class\x3d\x22z4R3Z\x22\x3e\x3cspan class\x3d\x22L3FBEc\x22\x3e\x3c/span\x3eT\u1eaft\x3c/div\x3e\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 style\x3d\x22margin:0\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe LGiluc\x22 aria-hidden\x3d\x22true\x22 role\x3d\x22separator\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;ANVEfs\x22\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 class\x3d\x22RVRNTb EpPYLd Zt0a5e\x22 jscontroller\x3d\x22CnSW2d\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;ANVEfo\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb\x22 role\x3d\x22none\x22\x3e\x3ca class\x3d\x22kQyaVc\x22 href\x3d\x22/safesearch?hl\x3dvi\x26amp;prev\x3dhttps://www.google.com/search?q%3Dcode%2Bmau%2Btoken%2Bgooogle%26oq%3Dcode%2Bmau%2Btoken%2Bgooogle%26gs_lcrp%3DEgZjaHJvbWUyBggAEEUYOdIBCDQxMTFqMGoxqAIAsAIA%26sourceid%3Dchrome%26ie%3DUTF-8\x26amp;sa\x3dX\x26amp;ved\x3d2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ3fwIegQIARAW\x22 role\x3d\x22menuitem\x22 tabindex\x3d\x22-1\x22\x3e\x3cdiv class\x3d\x22z4R3Z yb2zA\x22\x3e\x3cspan class\x3d\x22L3FBEc\x22\x3e\x3c/span\x3eT\xecm hi\u1ec3u th\xeam v\u1ec1 t\xednh n\u0103ng T\xecm ki\u1ebfm an to\xe0n\x3c/div\x3e\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3c/g-menu\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('tn_1', '\x3cdiv class\x3d\x22LkcePc\x22\x3e\x3c/div\x3e\x3cspan jscontroller\x3d\x22nabPbb\x22 data-ffp\x3d\x22false\x22 jsaction\x3d\x22KyPa0e:Y0y4c;BVfjhf:VFzweb;wjOG7e:gDkf4c;\x22\x3e\x3cg-popup jsname\x3d\x22V68bde\x22 jscontroller\x3d\x22DPreE\x22 jsaction\x3d\x22A05xBd:IYtByb;EOZ57e:WFrRFb;\x22 jsdata\x3d\x22mVjAjf;_;ANVEfk\x22\x3e\x3cdiv jsname\x3d\x22oYxtQd\x22 class\x3d\x22CcNe6e\x22 aria-expanded\x3d\x22false\x22 aria-haspopup\x3d\x22true\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 jsaction\x3d\x22WFrRFb;keydown:uYT2Vb\x22\x3e\x3cdiv jsname\x3d\x22LgbsSe\x22\x3e\x3cdiv class\x3d\x22hdtb-mn-hd Yg3U7e\x22\x3e\x3cdiv class\x3d\x22KTBKoe\x22\x3eM\u1ecdi ng\xf4n ng\u1eef\x3c/div\x3e\x3cspan class\x3d\x22gTl8xb\x22\x3e\x3c/span\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv jsname\x3d\x22V68bde\x22 class\x3d\x22UjBGL pkWBse iRQHZe\x22 style\x3d\x22display:none;z-index:200\x22\x3e\x3cg-menu jsname\x3d\x22xl07Ob\x22 class\x3d\x22cF4V5c Tlae9d yTik0 wplJBd PBn44e iQXTJe\x22 jscontroller\x3d\x22WlNQGd\x22 role\x3d\x22menu\x22 tabindex\x3d\x22-1\x22 jsaction\x3d\x22PSl28c;focus:h06R8;keydown:uYT2Vb;mouseenter:WOQqYb;mouseleave:Tx5Rb;mouseover:IgJl9c\x22\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 class\x3d\x22nvELY EpPYLd GZnQqe\x22 jscontroller\x3d\x22CnSW2d\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;ANVEfo\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3cdiv class\x3d\x22y0fQ9c\x22 aria-checked\x3d\x22true\x22 role\x3d\x22menuitemradio\x22 tabindex\x3d\x220\x22\x3eM\u1ecdi ng\xf4n ng\u1eef\x3c/div\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;ANVEfo\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3ca href\x3d\x22/search?q\x3dcode+mau+token+google\x26amp;sca_esv\x3d571531489\x26amp;source\x3dlnt\x26amp;tbs\x3dlr:lang_1vi\x26amp;lr\x3dlang_vi\x26amp;sa\x3dX\x26amp;ved\x3d2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQpwV6BAgBEB0\x22 aria-checked\x3d\x22false\x22 role\x3d\x22menuitemradio\x22\x3eT\xecm nh\u1eefng trang Ti\u1ebfng Vi\u1ec7t\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3c/g-menu\x3e\x3c/div\x3e\x3c/g-popup\x3e\x3c/span\x3e\x3cspan jscontroller\x3d\x22nabPbb\x22 data-ffp\x3d\x22false\x22 jsaction\x3d\x22KyPa0e:Y0y4c;BVfjhf:VFzweb;wjOG7e:gDkf4c;\x22\x3e\x3cg-popup jsname\x3d\x22V68bde\x22 jscontroller\x3d\x22DPreE\x22 jsaction\x3d\x22A05xBd:IYtByb;EOZ57e:WFrRFb;\x22 jsdata\x3d\x22mVjAjf;_;ANVEfk\x22\x3e\x3cdiv jsname\x3d\x22oYxtQd\x22 class\x3d\x22CcNe6e\x22 aria-expanded\x3d\x22false\x22 aria-haspopup\x3d\x22true\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 jsaction\x3d\x22WFrRFb;keydown:uYT2Vb\x22\x3e\x3cdiv jsname\x3d\x22LgbsSe\x22\x3e\x3cdiv class\x3d\x22hdtb-mn-hd\x22\x3e\x3cdiv class\x3d\x22KTBKoe\x22\x3eM\u1ecdi l\xfac\x3c/div\x3e\x3cspan class\x3d\x22gTl8xb\x22\x3e\x3c/span\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv jsname\x3d\x22V68bde\x22 class\x3d\x22UjBGL pkWBse iRQHZe\x22 style\x3d\x22display:none;z-index:200\x22\x3e\x3cg-menu jsname\x3d\x22xl07Ob\x22 class\x3d\x22cF4V5c Tlae9d yTik0 wplJBd PBn44e iQXTJe\x22 jscontroller\x3d\x22WlNQGd\x22 role\x3d\x22menu\x22 tabindex\x3d\x22-1\x22 jsaction\x3d\x22PSl28c;focus:h06R8;keydown:uYT2Vb;mouseenter:WOQqYb;mouseleave:Tx5Rb;mouseover:IgJl9c\x22\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 class\x3d\x22nvELY EpPYLd GZnQqe\x22 jscontroller\x3d\x22CnSW2d\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;ANVEfo\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3cdiv class\x3d\x22y0fQ9c\x22 aria-checked\x3d\x22true\x22 role\x3d\x22menuitemradio\x22 tabindex\x3d\x220\x22\x3eM\u1ecdi l\xfac\x3c/div\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;ANVEfo\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3ca href\x3d\x22/search?q\x3dcode+mau+token+google\x26amp;sca_esv\x3d571531489\x26amp;source\x3dlnt\x26amp;tbs\x3dqdr:h\x26amp;sa\x3dX\x26amp;ved\x3d2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQpwV6BAgBECI\x22 aria-checked\x3d\x22false\x22 role\x3d\x22menuitemradio\x22\x3e Gi\u1edd qua\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;ANVEfo\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3ca href\x3d\x22/search?q\x3dcode+mau+token+google\x26amp;sca_esv\x3d571531489\x26amp;source\x3dlnt\x26amp;tbs\x3dqdr:d\x26amp;sa\x3dX\x26amp;ved\x3d2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQpwV6BAgBECM\x22 aria-checked\x3d\x22false\x22 role\x3d\x22menuitemradio\x22\x3e 24 gi\u1edd qua\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;ANVEfo\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3ca href\x3d\x22/search?q\x3dcode+mau+token+google\x26amp;sca_esv\x3d571531489\x26amp;source\x3dlnt\x26amp;tbs\x3dqdr:w\x26amp;sa\x3dX\x26amp;ved\x3d2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQpwV6BAgBECQ\x22 aria-checked\x3d\x22false\x22 role\x3d\x22menuitemradio\x22\x3e Tu\u1ea7n qua\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;ANVEfo\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3ca href\x3d\x22/search?q\x3dcode+mau+token+google\x26amp;sca_esv\x3d571531489\x26amp;source\x3dlnt\x26amp;tbs\x3dqdr:m\x26amp;sa\x3dX\x26amp;ved\x3d2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQpwV6BAgBECU\x22 aria-checked\x3d\x22false\x22 role\x3d\x22menuitemradio\x22\x3e Th\xe1ng qua\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;ANVEfo\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3ca href\x3d\x22/search?q\x3dcode+mau+token+google\x26amp;sca_esv\x3d571531489\x26amp;source\x3dlnt\x26amp;tbs\x3dqdr:y\x26amp;sa\x3dX\x26amp;ved\x3d2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQpwV6BAgBECY\x22 aria-checked\x3d\x22false\x22 role\x3d\x22menuitemradio\x22\x3e N\u0103m qua\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;ANVEfo\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3cdiv class\x3d\x22y0fQ9c\x22 jscontroller\x3d\x22VD4Qme\x22 data-m\x3d\x22false\x22\x3e\x3cspan role\x3d\x22menuitem\x22 tabindex\x3d\x22-1\x22 jsaction\x3d\x22EEGHee\x22 data-ved\x3d\x222ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQpwV6BAgBECc\x22\x3ePh\u1ea1m vi t\xf9y ch\u1ec9nh...\x3c/span\x3e\x3cdiv class\x3d\x22n5Ug4b\x22 style\x3d\x22display:none\x22\x3e\x3cdiv class\x3d\x22vOvh1b\x22 jsaction\x3d\x22xp3IKd\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22J6UZg\x22 aria-modal\x3d\x22true\x22 role\x3d\x22dialog\x22\x3e\x3cdiv class\x3d\x22Jy9Ore\x22 role\x3d\x22heading\x22\x3ePh\u1ea1m vi ng\xe0y t\xf9y ch\u1ec9nh\x3c/div\x3e\x3clabel class\x3d\x22Qtsmnf tmDYm\x22 for\x3d\x22OouJcb\x22\x3eT\u1eeb\x3c/label\x3e\x3clabel class\x3d\x22Qtsmnf iWBKNe\x22 for\x3d\x22rzG2be\x22\x3eT\u1edbi\x3c/label\x3e\x3cdiv class\x3d\x22Gwgzqd\x22 aria-label\x3d\x22\u0110\xf3ng\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 jsaction\x3d\x22xp3IKd\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22NwEGxd\x22\x3e\x3cdiv class\x3d\x22qomYCd\x22\x3e\x3c/div\x3e\x3cform action\x3d\x22/search\x22 class\x3d\x22T3kYXe\x22 id\x3d\x22T3kYXe\x22 method\x3d\x22get\x22\x3e\x3cinput name\x3d\x22q\x22 value\x3d\x22code mau token google\x22 type\x3d\x22hidden\x22\x3e\x3cinput name\x3d\x22sca_esv\x22 value\x3d\x22571531489\x22 type\x3d\x22hidden\x22\x3e\x3cinput name\x3d\x22source\x22 type\x3d\x22hidden\x22 value\x3d\x22lnt\x22\x3e\x3cinput value\x3d\x22cdr:1,cd_min:x,cd_max:x\x22 id\x3d\x22HjtPBb\x22 name\x3d\x22tbs\x22 type\x3d\x22hidden\x22\x3e\x3cinput value\x3d\x22\x22 name\x3d\x22tbm\x22 type\x3d\x22hidden\x22\x3e\x3cinput class\x3d\x22OouJcb\x22 type\x3d\x22text\x22 value\x3d\x22\x22 autocomplete\x3d\x22off\x22 id\x3d\x22OouJcb\x22 jsaction\x3d\x22focus:daRB0b\x22\x3e\x3cinput class\x3d\x22rzG2be\x22 type\x3d\x22text\x22 value\x3d\x22\x22 autocomplete\x3d\x22off\x22 id\x3d\x22rzG2be\x22 jsaction\x3d\x22focus:daRB0b\x22\x3e\x3cg-button class\x3d\x22Ru1Ao BwGU8e fE5Rge\x22 jsaction\x3d\x22hNEEAb\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22\x3eT\xecm\x3c/g-button\x3e\x3cinput type\x3d\x22submit\x22 jsaction\x3d\x22zbvklb\x22 style\x3d\x22display:none\x22\x3e\x3c/form\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3c/g-menu\x3e\x3c/div\x3e\x3c/g-popup\x3e\x3c/span\x3e\x3cspan jscontroller\x3d\x22nabPbb\x22 data-ffp\x3d\x22false\x22 jsaction\x3d\x22KyPa0e:Y0y4c;BVfjhf:VFzweb;wjOG7e:gDkf4c;\x22\x3e\x3cg-popup jsname\x3d\x22V68bde\x22 jscontroller\x3d\x22DPreE\x22 jsaction\x3d\x22A05xBd:IYtByb;EOZ57e:WFrRFb;\x22 jsdata\x3d\x22mVjAjf;_;ANVEfk\x22\x3e\x3cdiv jsname\x3d\x22oYxtQd\x22 class\x3d\x22CcNe6e\x22 aria-expanded\x3d\x22false\x22 aria-haspopup\x3d\x22true\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 jsaction\x3d\x22WFrRFb;keydown:uYT2Vb\x22\x3e\x3cdiv jsname\x3d\x22LgbsSe\x22\x3e\x3cdiv class\x3d\x22hdtb-mn-hd\x22\x3e\x3cdiv class\x3d\x22KTBKoe\x22\x3eT\xe2\u0301t ca\u0309 k\u1ebft qu\u1ea3\x3c/div\x3e\x3cspan class\x3d\x22gTl8xb\x22\x3e\x3c/span\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv jsname\x3d\x22V68bde\x22 class\x3d\x22UjBGL pkWBse iRQHZe\x22 style\x3d\x22display:none;z-index:200\x22\x3e\x3cg-menu jsname\x3d\x22xl07Ob\x22 class\x3d\x22cF4V5c Tlae9d yTik0 wplJBd PBn44e iQXTJe\x22 jscontroller\x3d\x22WlNQGd\x22 role\x3d\x22menu\x22 tabindex\x3d\x22-1\x22 jsaction\x3d\x22PSl28c;focus:h06R8;keydown:uYT2Vb;mouseenter:WOQqYb;mouseleave:Tx5Rb;mouseover:IgJl9c\x22\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 class\x3d\x22nvELY EpPYLd GZnQqe\x22 jscontroller\x3d\x22CnSW2d\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;ANVEfo\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3cdiv class\x3d\x22y0fQ9c\x22 aria-checked\x3d\x22true\x22 role\x3d\x22menuitemradio\x22 tabindex\x3d\x220\x22\x3eT\xe2\u0301t ca\u0309 k\u1ebft qu\u1ea3\x3c/div\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3cg-menu-item jsname\x3d\x22NNJLud\x22 jscontroller\x3d\x22CnSW2d\x22 class\x3d\x22EpPYLd GZnQqe\x22 role\x3d\x22none\x22 data-short-label\x3d\x22\x22 jsdata\x3d\x22zPXzie;_;ANVEfo\x22\x3e\x3cdiv jsname\x3d\x22ibnC6b\x22 class\x3d\x22YpcDnf OSrXXb HG1dvd\x22 role\x3d\x22none\x22\x3e\x3ca href\x3d\x22/search?q\x3dcode+mau+token+gooogle\x26amp;sca_esv\x3d571531489\x26amp;source\x3dlnt\x26amp;tbs\x3dli:1\x26amp;sa\x3dX\x26amp;ved\x3d2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQpwV6BAgBEC0\x22 aria-checked\x3d\x22false\x22 role\x3d\x22menuitemradio\x22\x3eNguy\xean v\u0103n\x3c/a\x3e\x3c/div\x3e\x3c/g-menu-item\x3e\x3c/g-menu\x3e\x3c/div\x3e\x3c/g-popup\x3e\x3c/span\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('spic_1', '\x3cdiv jsname\x3d\x22TItCJc\x22 class\x3d\x22CbAZb\x22 id\x3d\x22elPddd\x22 tabindex\x3d\x22-1\x22 jsaction\x3d\x22mLt3mc\x22 data-ved\x3d\x222ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQzpwIegQIBRAC\x22\x3e\x3cdiv class\x3d\x22cQ2awd\x22\x3e\x3ch1 class\x3d\x22S8wJ3\x22\x3eC\xe0i \u0111\u1eb7t nhanh\x3c/h1\x3e\x3cspan class\x3d\x22bepeF z1asCe wuXmqc\x22 aria-label\x3d\x22Close\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 jsaction\x3d\x22UVNdjb\x22 data-ved\x3d\x222ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQy9QJegQIBRAD\x22\x3e\x3csvg focusable\x3d\x22false\x22 xmlns\x3d\x22http://www.w3.org/2000/svg\x22 viewBox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M19 6.41L17.59 5 12 10.59 6.41 5 5 6.41 10.59 12 5 17.59 6.41 19 12 13.41 17.59 19 19 17.59 13.41 12z\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3e\x3ca class\x3d\x22tGS0Nc\x22 href\x3d\x22/preferences?hl\x3dvi\x26amp;prev\x3dhttps://www.google.com/search?q%3Dcode%2Bmau%2Btoken%2Bgoogle%26sca_esv%3D571531489\x22 tabindex\x3d\x220\x22 ping\x3d\x22/url?sa\x3dt\x26amp;source\x3dweb\x26amp;rct\x3dj\x26amp;opi\x3d89978449\x26amp;url\x3d/preferences%3Fhl%3Dvi%26prev%3Dhttps://www.google.com/search%3Fq%253Dcode%252Bmau%252Btoken%252Bgoogle%2526sca_esv%253D571531489\x26amp;ved\x3d2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ65sIegQIBRAE\x22\x3eXem t\u1ea5t c\u1ea3 ch\u1ebf \u0111\u1ed9 c\xe0i \u0111\u1eb7t T\xecm ki\u1ebfm\x3c/a\x3e\x3c/div\x3e\x3cdiv class\x3d\x22m0uvVb\x22\x3e\x3ch2 class\x3d\x22kwWBYc\x22\x3eHo\u1ea1t \u0111\u1ed9ng c\u1ee7a b\u1ea1n\x3c/h2\x3e\x3cdiv class\x3d\x22q0yked\x22\x3e\x3ca href\x3d\x22/history/optout?hl\x3dvi\x22 ping\x3d\x22/url?sa\x3dt\x26amp;source\x3dweb\x26amp;rct\x3dj\x26amp;opi\x3d89978449\x26amp;url\x3d/history/optout%3Fhl%3Dvi\x26amp;ved\x3d2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQpdoJegQIBRAF\x22\x3e\x3cspan class\x3d\x22ZI7elf\x22\x3eTu\u1ef3 ch\u1ec9nh t\xecm ki\u1ebfm\x3c/span\x3e\x3cdiv class\x3d\x22ogD9ue\x22\x3e\x3cspan class\x3d\x22rhJQGd tkWDZc\x22\x3e\x3cspan jsname\x3d\x22dYUyg\x22 data-ved\x3d\x222ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQp9oJegQIBRAG\x22\x3e\u0110ang t\u1eaft\x3c/span\x3e\x3c/span\x3e\x3cspan style\x3d\x22color:#5f6368\x22 class\x3d\x22z1asCe eznrjd\x22\x3e\x3csvg focusable\x3d\x22false\x22 xmlns\x3d\x22http://www.w3.org/2000/svg\x22 viewBox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M19 19H5V5h7V3H5c-1.11 0-2 .9-2 2v14c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2v-7h-2v7zM14 3v2h3.59l-9.83 9.83 1.41 1.41L19 6.41V10h2V3h-7z\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3e\x3c/div\x3e\x3c/a\x3e\x3c/div\x3e\x3cdiv\x3e\x3ca class\x3d\x22SknMB\x22 href\x3d\x22/history/privacyadvisor/search/unauth?utm_source\x3dgooglemenu\x22 ping\x3d\x22/url?sa\x3dt\x26amp;source\x3dweb\x26amp;rct\x3dj\x26amp;opi\x3d89978449\x26amp;url\x3d/history/privacyadvisor/search/unauth%3Futm_source%3Dgooglemenu\x26amp;ved\x3d2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ7ZsIegQIBRAH\x22\x3e\x3cspan class\x3d\x22tkWDZc\x22\x3eT\xecm hi\u1ec3u th\xeam v\u1ec1 d\u1eef li\u1ec7u c\u1ee7a b\u1ea1n trong T\xecm ki\u1ebfm\x3c/span\x3e\x3c/a\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22m0uvVb\x22\x3e\x3ch2 class\x3d\x22kwWBYc\x22\x3eS\u1eed d\u1ee5ng T\xecm ki\u1ebfm\x3c/h2\x3e\x3cdiv class\x3d\x22q0yked fmxhfc\x22\x3e\x3ca href\x3d\x22/safesearch?prev\x3dhttps://www.google.com/search?q%3Dcode%2Bmau%2Btoken%2Bgooogle%26oq%3Dcode%2Bmau%2Btoken%2Bgooogle%26gs_lcrp%3DEgZjaHJvbWUyBggAEEUYOdIBCDQxMTFqMGoxqAIAsAIA%26sourceid%3Dchrome%26ie%3DUTF-8\x26amp;sa\x3dX\x26amp;ved\x3d2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ8JsIegQIBRAI\x22\x3e\x3cspan class\x3d\x22XRZSle\x22\x3e\x3cspan class\x3d\x22ZI7elf\x22\x3eT\xecm ki\u1ebfm an to\xe0n\x3c/span\x3e\x3cspan class\x3d\x22Z48xed\x22\x3eGi\xfap qu\u1ea3n l\xfd n\u1ed9i dung ph\u1ea3n c\u1ea3m\x3c/span\x3e\x3c/span\x3e\x3cspan style\x3d\x22color:#5f6368\x22 class\x3d\x22z1asCe eznrjd\x22\x3e\x3csvg focusable\x3d\x22false\x22 xmlns\x3d\x22http://www.w3.org/2000/svg\x22 viewBox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M19 19H5V5h7V3H5c-1.11 0-2 .9-2 2v14c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2v-7h-2v7zM14 3v2h3.59l-9.83 9.83 1.41 1.41L19 6.41V10h2V3h-7z\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3e\x3c/a\x3e\x3c/div\x3e\x3cdiv class\x3d\x22q0yked\x22\x3e\x3ca href\x3d\x22/preferences?lang\x3d1\x26amp;hl\x3dvi\x26amp;prev\x3dhttps://www.google.com/search?q%3Dcode%2Bmau%2Btoken%2Bgoogle%26sca_esv%3D571531489#languages\x22 style\x3d\x22display:flex\x22 ping\x3d\x22/url?sa\x3dt\x26amp;source\x3dweb\x26amp;rct\x3dj\x26amp;opi\x3d89978449\x26amp;url\x3d/preferences%3Flang%3D1%26hl%3Dvi%26prev%3Dhttps://www.google.com/search%3Fq%253Dcode%252Bmau%252Btoken%252Bgoogle%2526sca_esv%253D571531489%23languages\x26amp;ved\x3d2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ8ZsIegQIBRAJ\x22\x3e\x3cdiv class\x3d\x22ZI7elf UCGAnb\x22\x3e\x3cspan\x3eNg\xf4n ng\u1eef\x3c/span\x3e\x3cspan style\x3d\x22font-size:12px\x22\x3e (Languages)\x3c/span\x3e\x3c/div\x3e\x3cspan class\x3d\x22kQEH5b\x22 style\x3d\x22color:#70757a\x22\x3eTi\u1ebfng Vi\u1ec7t\x3c/span\x3e\x3c/a\x3e\x3c/div\x3e\x3cdiv class\x3d\x22q0yked\x22\x3e\x3ca href\x3d\x22/advanced_search?q\x3dcode+mau+token+google\x26amp;sca_esv\x3d571531489\x26amp;hl\x3dvi\x22 ping\x3d\x22/url?sa\x3dt\x26amp;source\x3dweb\x26amp;rct\x3dj\x26amp;opi\x3d89978449\x26amp;url\x3d/advanced_search%3Fq%3Dcode%2Bmau%2Btoken%2Bgoogle%26sca_esv%3D571531489%26hl%3Dvi\x26amp;ved\x3d2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ7psIegQIBRAK\x22\x3e\x3cspan class\x3d\x22ZI7elf\x22\x3eT.ki\u1ebfm n\xe2ng cao\x3c/span\x3e\x3cspan style\x3d\x22color:#5f6368\x22 class\x3d\x22z1asCe eznrjd\x22\x3e\x3csvg focusable\x3d\x22false\x22 xmlns\x3d\x22http://www.w3.org/2000/svg\x22 viewBox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M19 19H5V5h7V3H5c-1.11 0-2 .9-2 2v14c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2v-7h-2v7zM14 3v2h3.59l-9.83 9.83 1.41 1.41L19 6.41V10h2V3h-7z\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3e\x3c/a\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22m0uvVb\x22 jsaction\x3d\x22ivUr0:rJpNrc\x22\x3e\x3ch2 class\x3d\x22kwWBYc\x22\x3eGiao di\u1ec7n\x3c/h2\x3e\x3cg-radio-button-group jsname\x3d\x22sUvgTb\x22 class\x3d\x22uWNHce H8eL7d j0iFNe\x22 jscontroller\x3d\x22SZXsif\x22 aria-disabled\x3d\x22false\x22 data-rwl\x3d\x221\x22 role\x3d\x22radiogroup\x22 jsaction\x3d\x22keydown:uYT2Vb;focus:h06R8;blur:zjh6rb;rcuQ6b:npT2md\x22\x3e\x3cdiv jsname\x3d\x22GCYh9b\x22 class\x3d\x22de2Dud\x22 aria-checked\x3d\x22false\x22 aria-labelledby\x3d\x22_Ny0hZajKHuSv2roPysWswAY_22\x22 data-index\x3d\x220\x22 tabindex\x3d\x22-1\x22 role\x3d\x22radio\x22 jsaction\x3d\x22g6cJHd\x22\x3e\x3cdiv class\x3d\x22dsLpHe OvQkSb\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22kaAgDc OvQkSb\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22wT0tpe OvQkSb\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22dluk7e\x22 id\x3d\x22_Ny0hZajKHuSv2roPysWswAY_22\x22\x3e\x3clabel class\x3d\x22GZcH3e LZTko\x22 jsname\x3d\x22rWsIUb\x22 style\x3d\x22display:flex\x22 data-ved\x3d\x222ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ9JsIegQIBRAL\x22\x3e\x3cdiv class\x3d\x22UCGAnb\x22\x3eGiao di\u1ec7n s\xe1ng\x3c/div\x3e\x3cimg class\x3d\x22UCAEse\x22 src\x3d\x22https://www.gstatic.com/ui/v1/menu/light_thumbnail2.png\x22 alt\x3d\x22\x22\x3e\x3c/label\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv jsname\x3d\x22GCYh9b\x22 class\x3d\x22de2Dud\x22 aria-checked\x3d\x22false\x22 aria-labelledby\x3d\x22_Ny0hZajKHuSv2roPysWswAY_23\x22 data-index\x3d\x221\x22 tabindex\x3d\x22-1\x22 role\x3d\x22radio\x22 jsaction\x3d\x22g6cJHd\x22\x3e\x3cdiv class\x3d\x22dsLpHe OvQkSb\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22kaAgDc OvQkSb\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22wT0tpe OvQkSb\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22dluk7e\x22 id\x3d\x22_Ny0hZajKHuSv2roPysWswAY_23\x22\x3e\x3clabel class\x3d\x22GZcH3e LZTko\x22 jsname\x3d\x22I7WXBf\x22 style\x3d\x22display:flex\x22 data-ved\x3d\x222ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ9ZsIegQIBRAM\x22\x3e\x3cdiv class\x3d\x22UCGAnb\x22\x3eGiao di\u1ec7n t\u1ed1i\x3c/div\x3e\x3cimg class\x3d\x22UCAEse\x22 src\x3d\x22https://www.gstatic.com/ui/v1/menu/dark_thumbnail2.png\x22 alt\x3d\x22\x22\x3e\x3c/label\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv jsname\x3d\x22GCYh9b\x22 class\x3d\x22de2Dud RvdoFd\x22 aria-checked\x3d\x22true\x22 aria-labelledby\x3d\x22_Ny0hZajKHuSv2roPysWswAY_24\x22 data-index\x3d\x222\x22 tabindex\x3d\x220\x22 role\x3d\x22radio\x22 jsaction\x3d\x22g6cJHd\x22\x3e\x3cdiv class\x3d\x22dsLpHe OvQkSb\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22kaAgDc OvQkSb\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22wT0tpe OvQkSb\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22dluk7e\x22 id\x3d\x22_Ny0hZajKHuSv2roPysWswAY_24\x22\x3e\x3clabel class\x3d\x22GZcH3e LZTko\x22 jsname\x3d\x22qk0sxc\x22 style\x3d\x22display:flex\x22 data-ved\x3d\x222ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ9psIegQIBRAN\x22\x3e\x3cdiv class\x3d\x22UCGAnb\x22\x3eTheo gi\xe1 tr\u1ecb m\u1eb7c \u0111\u1ecbnh c\u1ee7a thi\u1ebft b\u1ecb\x3c/div\x3e\x3cimg class\x3d\x22UCAEse\x22 src\x3d\x22https://www.gstatic.com/ui/v1/menu/device_default_thumbnail2.png\x22 alt\x3d\x22\x22\x3e\x3c/label\x3e\x3c/div\x3e\x3c/div\x3e\x3c/g-radio-button-group\x3e\x3c/div\x3e\x3cdiv class\x3d\x22m0uvVb\x22\x3e\x3ch2 class\x3d\x22kwWBYc\x22\x3eH\u1ed7 tr\u1ee3\x3c/h2\x3e\x3cdiv class\x3d\x22q0yked\x22\x3e\x3ca href\x3d\x22https://support.google.com/websearch/?p\x3ddsrp_search_hc\x26amp;hl\x3dvi\x22 ping\x3d\x22/url?sa\x3dt\x26amp;source\x3dweb\x26amp;rct\x3dj\x26amp;opi\x3d89978449\x26amp;url\x3dhttps://support.google.com/websearch/%3Fp%3Ddsrp_search_hc%26hl%3Dvi\x26amp;ved\x3d2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ8psIegQIBRAO\x22\x3e\x3cspan class\x3d\x22ZI7elf\x22\x3eT\xecm trong ph\u1ea7n tr\u1ee3 gi\xfap\x3c/span\x3e\x3cspan style\x3d\x22color:#5f6368\x22 class\x3d\x22z1asCe eznrjd\x22\x3e\x3csvg focusable\x3d\x22false\x22 xmlns\x3d\x22http://www.w3.org/2000/svg\x22 viewBox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M19 19H5V5h7V3H5c-1.11 0-2 .9-2 2v14c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2v-7h-2v7zM14 3v2h3.59l-9.83 9.83 1.41 1.41L19 6.41V10h2V3h-7z\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3e\x3c/a\x3e\x3c/div\x3e\x3cdiv class\x3d\x22q0yked\x22\x3e\x3cdiv jsname\x3d\x22QTykS\x22 class\x3d\x22S4xgid\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 jsaction\x3d\x22VsgDoc\x22 data-ved\x3d\x222ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ85sIegQIBRAP\x22\x3e\x3cspan class\x3d\x22ZI7elf\x22\x3eG\u01b0\u0309i ph\u1ea3n h\u1ed3i\x3c/span\x3e\x3cspan class\x3d\x22kQEH5b dVmoif\x22\x3e\x3cspan class\x3d\x22aztjNb RVVZab\x22\x3eM\u1edbi\x3c/span\x3e\x3cspan style\x3d\x22color:#5f6368\x22 class\x3d\x22z1asCe dC6Tmc\x22\x3e\x3csvg focusable\x3d\x22false\x22 xmlns\x3d\x22http://www.w3.org/2000/svg\x22 viewBox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M20 2H4c-1.1 0-1.99.9-1.99 2L2 22l4-4h14c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2zm0 14H5.17l-.59.59-.58.58V4h16v12z\x22\x3e\x3c/path\x3e\x3cpath d\x3d\x22M11 12h2v2h-2zm0-6h2v4h-2z\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3e\x3c/span\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22q0yked\x22\x3e\x3ca href\x3d\x22https://policies.google.com/privacy?hl\x3dvi\x26amp;fg\x3d1\x22 ping\x3d\x22/url?sa\x3dt\x26amp;source\x3dweb\x26amp;rct\x3dj\x26amp;opi\x3d89978449\x26amp;url\x3dhttps://policies.google.com/privacy%3Fhl%3Dvi%26fg%3D1\x26amp;ved\x3d2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQxZEKegQIBRAQ\x22\x3e\x3cspan class\x3d\x22ZI7elf\x22\x3eQuy\u1ec1n ri\xeang t\u01b0\x3c/span\x3e\x3cspan style\x3d\x22color:#5f6368\x22 class\x3d\x22z1asCe eznrjd\x22\x3e\x3csvg focusable\x3d\x22false\x22 xmlns\x3d\x22http://www.w3.org/2000/svg\x22 viewBox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M19 19H5V5h7V3H5c-1.11 0-2 .9-2 2v14c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2v-7h-2v7zM14 3v2h3.59l-9.83 9.83 1.41 1.41L19 6.41V10h2V3h-7z\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3e\x3c/a\x3e\x3c/div\x3e\x3cdiv class\x3d\x22q0yked\x22\x3e\x3ca href\x3d\x22https://policies.google.com/terms?hl\x3dvi\x26amp;fg\x3d1\x22 ping\x3d\x22/url?sa\x3dt\x26amp;source\x3dweb\x26amp;rct\x3dj\x26amp;opi\x3d89978449\x26amp;url\x3dhttps://policies.google.com/terms%3Fhl%3Dvi%26fg%3D1\x26amp;ved\x3d2ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQu58KegQIBRAR\x22\x3e\x3cspan class\x3d\x22ZI7elf\x22\x3e\u0110i\u1ec1u kho\u1ea3n\x3c/span\x3e\x3cspan style\x3d\x22color:#5f6368\x22 class\x3d\x22z1asCe eznrjd\x22\x3e\x3csvg focusable\x3d\x22false\x22 xmlns\x3d\x22http://www.w3.org/2000/svg\x22 viewBox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M19 19H5V5h7V3H5c-1.11 0-2 .9-2 2v14c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2v-7h-2v7zM14 3v2h3.59l-9.83 9.83 1.41 1.41L19 6.41V10h2V3h-7z\x22\x3e\x3c/path\x3e\x3c/svg\x3e\x3c/span\x3e\x3c/a\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('_Ny0hZajKHuSv2roPysWswAY_9', '  \x3cdiv jsname\x3d\x22rSAM5d\x22\x3e \x3cdiv style\x3d\x22opacity:0\x22 id\x3d\x22arc-stev\x22 data-jiis\x3d\x22up\x22 data-async-type\x3d\x22arc\x22 data-async-context-required\x3d\x22arc_id,q\x22 class\x3d\x22yp\x22 data-async-rclass\x3d\x22search\x22\x3e\x3c/div\x3e \x3c/div\x3e \x3cdiv jsname\x3d\x22UefMMd\x22 class\x3d\x22Lm68h s6JM6d\x22 style\x3d\x22display:none\x22\x3e  \x3cdiv class\x3d\x22rskU3c\x22 aria-valuetext\x3d\x22\u0110ang ta\u0309i...\x22 role\x3d\x22progressbar\x22\x3e\x3cdiv class\x3d\x22G8qI4b Ww4FFb vt6azd\x22\x3e\x3cdiv class\x3d\x22DYiTxe\x22\x3e\x3cdiv class\x3d\x22N6dG3e\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22e4XSEd\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22AMbnUc\x22\x3e\x3cdiv class\x3d\x22ysLSm\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22G8qI4b Ww4FFb vt6azd\x22\x3e\x3cdiv class\x3d\x22DYiTxe\x22\x3e\x3cdiv class\x3d\x22N6dG3e\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22e4XSEd\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22AMbnUc\x22\x3e\x3cdiv class\x3d\x22ysLSm\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22G8qI4b Ww4FFb vt6azd\x22\x3e\x3cdiv class\x3d\x22DYiTxe\x22\x3e\x3cdiv class\x3d\x22N6dG3e\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22e4XSEd\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22AMbnUc\x22\x3e\x3cdiv class\x3d\x22ysLSm\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22G8qI4b Ww4FFb vt6azd\x22\x3e\x3cdiv class\x3d\x22DYiTxe\x22\x3e\x3cdiv class\x3d\x22N6dG3e\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22e4XSEd\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22AMbnUc\x22\x3e\x3cdiv class\x3d\x22ysLSm\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22G8qI4b Ww4FFb vt6azd\x22\x3e\x3cdiv class\x3d\x22DYiTxe\x22\x3e\x3cdiv class\x3d\x22N6dG3e\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22e4XSEd\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22AMbnUc\x22\x3e\x3cdiv class\x3d\x22ysLSm\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22G8qI4b Ww4FFb vt6azd\x22\x3e\x3cdiv class\x3d\x22DYiTxe\x22\x3e\x3cdiv class\x3d\x22N6dG3e\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22e4XSEd\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22AMbnUc\x22\x3e\x3cdiv class\x3d\x22ysLSm\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22bOiwif\x22\x3e\x3c/div\x3e\x3c/div\x3e \x3c/div\x3e \x3cdiv jsname\x3d\x22Ei53Y\x22 style\x3d\x22display:none\x22 data-ved\x3d\x222ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQsMoFegQIBxAA\x22\x3e \x3c/div\x3e    ');
                }
                )();
                (function() {
                    window.jsl.dh('spch', '\x3cbutton class\x3d\x22close-button\x22 id\x3d\x22spchx\x22 aria-label\x3d\x22\u0111\xf3ng\x22\x3e\x26times;\x3c/button\x3e\x3cdiv class\x3d\x22spchc\x22 id\x3d\x22spchc\x22\x3e\x3cdiv class\x3d\x22inner-container\x22\x3e\x3cdiv class\x3d\x22button-container\x22\x3e\x3cspan class\x3d\x22r8s4j\x22 id\x3d\x22spchl\x22\x3e\x3c/span\x3e\x3cspan class\x3d\x22LgbsSe\x22 id\x3d\x22spchb\x22\x3e\x3cdiv class\x3d\x22microphone\x22\x3e\x3cspan class\x3d\x22receiver\x22\x3e\x3c/span\x3e\x3cdiv class\x3d\x22wrapper\x22\x3e\x3cspan class\x3d\x22stem\x22\x3e\x3c/span\x3e\x3cspan class\x3d\x22shell\x22\x3e\x3c/span\x3e\x3c/div\x3e\x3c/div\x3e\x3c/span\x3e\x3c/div\x3e\x3cdiv class\x3d\x22text-container\x22\x3e\x3cspan class\x3d\x22spcht\x22 style\x3d\x22color:#70757a\x22 id\x3d\x22spchi\x22\x3e\x3c/span\x3e\x3cspan class\x3d\x22spcht\x22 style\x3d\x22color:#000\x22 id\x3d\x22spchf\x22\x3e\x3c/span\x3e\x3c/div\x3e\x3cdiv class\x3d\x22google-logo\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv class\x3d\x22permission-bar\x22\x3e\x3cdiv class\x3d\x22permission-bar-gradient\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('fbar', '\x3cdiv jscontroller\x3d\x22a6Sgfb\x22 jsmodel\x3d\x22J9Q59e\x22 jsdata\x3d\x22YzXGMb;_;ANVEfQ\x22 jsaction\x3d\x22rcuQ6b:npT2md\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22fbar b2hzT\x22\x3e\x3cdiv class\x3d\x22b0KoTc B4GxFc\x22\x3e\x3cspan class\x3d\x22Q8LRLc\x22\x3eVi\u1ec7t Nam\x3c/span\x3e\x3cdiv class\x3d\x22fbar smiUbb\x22 id\x3d\x22swml\x22\x3e\x3cdiv jscontroller\x3d\x22qcH9Lc\x22 jsdata\x3d\x22z6bOeb;_;ANVEfY\x22 jsaction\x3d\x22oEnJg:CEnhyd;gJk92:b6DXXd\x22\x3e\x3cdiv class\x3d\x22rwA8ec HDOrGf GNm3Qb\x22 style\x3d\x22white-space:normal\x22\x3e\x3ca jsname\x3d\x22gXWYVe\x22 href\x3d\x22#\x22 style\x3d\x22white-space:normal\x22 data-biw\x3d\x221440\x22 jsaction\x3d\x22click:HTIlC\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 data-ved\x3d\x222ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQuZ0HegQIAxAC\x22\x3e\x3cdiv class\x3d\x22GNm3Qb\x22\x3e\x3cspan class\x3d\x22EYqSq unknown_loc\x22\x3e\x3c/span\x3e\x3cspan class\x3d\x22dfB0uf\x22\x3eG\xf2 V\u1ea5p, Th\xe0nh ph\u1ed1 H\u1ed3 Ch\xed Minh\x3c/span\x3e\x3c/div\x3e\x3cdiv class\x3d\x22GNm3Qb\x22\x3e\x3cspan id\x3d\x22VdZal\x22\x3e\x26nbsp;-\x26nbsp;\x3c/span\x3e\x3cspan class\x3d\x22KwU3F\x22\x3e\x3cspan\x3eD\u1ef1a tr\xean \u0111\u1ecba ch\u1ec9 IP c\u1ee7a b\u1ea1n\x3c/span\x3e\x3c/span\x3e\x3c/div\x3e\x3c/a\x3e\x3cspan id\x3d\x22tsuid_11\x22\x3e\x3c/span\x3e\x3c/div\x3e\x3cspan id\x3d\x22RYW0de\x22\x3e\x26nbsp;-\x26nbsp;\x3c/span\x3e\x3cupdate-location class\x3d\x22xSQxL HDOrGf\x22 jscontroller\x3d\x22KgxeNb\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 jsaction\x3d\x22click:T1dibd;gfszqc:b4F0De;\x22 jsdata\x3d\x22ITZAN;_;ANVEfg\x22 data-ved\x3d\x222ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQpLkCegQIAxAE\x22\x3eC\u1eadp nh\u1eadt v\u1ecb tr\xed\x3cspan id\x3d\x22tsuid_14\x22\x3e\x3c/span\x3e\x3cspan id\x3d\x22tsuid_20\x22\x3e\x3c/span\x3e\x3c/update-location\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3cdiv jscontroller\x3d\x22EfPGub\x22 class\x3d\x22RLQCVb\x22\x3e\x3cspan class\x3d\x22B4GxFc wHYlTd z8gr9e\x22\x3eXem tu\u1ef3 ch\u1ecdn kh\xe1c trong ph\u1ea7n \x3ca jsname\x3d\x22hgPHmf\x22 class\x3d\x22GS5rRd\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 jsaction\x3d\x22em3SNd\x22 data-ved\x3d\x222ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQw6sKegQIAxAK\x22\x3eC\xe0i \u0111\u1eb7t nhanh (\x3cspan class\x3d\x22SLbK8e z1asCe E9hVAb\x22 style\x3d\x22height:16px;line-height:16px;width:16px\x22\x3e\x3csvg focusable\x3d\x22false\x22 xmlns\x3d\x22http://www.w3.org/2000/svg\x22 viewBox\x3d\x220 0 24 24\x22\x3e\x3cpath d\x3d\x22M13.85 22.25h-3.7c-.74 0-1.36-.54-1.45-1.27l-.27-1.89c-.27-.14-.53-.29-.79-.46l-1.8.72c-.7.26-1.47-.03-1.81-.65L2.2 15.53c-.35-.66-.2-1.44.36-1.88l1.53-1.19c-.01-.15-.02-.3-.02-.46 0-.15.01-.31.02-.46l-1.52-1.19c-.59-.45-.74-1.26-.37-1.88l1.85-3.19c.34-.62 1.11-.9 1.79-.63l1.81.73c.26-.17.52-.32.78-.46l.27-1.91c.09-.7.71-1.25 1.44-1.25h3.7c.74 0 1.36.54 1.45 1.27l.27 1.89c.27.14.53.29.79.46l1.8-.72c.71-.26 1.48.03 1.82.65l1.84 3.18c.36.66.2 1.44-.36 1.88l-1.52 1.19c.01.15.02.3.02.46s-.01.31-.02.46l1.52 1.19c.56.45.72 1.23.37 1.86l-1.86 3.22c-.34.62-1.11.9-1.8.63l-1.8-.72c-.26.17-.52.32-.78.46l-.27 1.91c-.1.68-.72 1.22-1.46 1.22zm-3.23-2h2.76l.37-2.55.53-.22c.44-.18.88-.44 1.34-.78l.45-.34 2.38.96 1.38-2.4-2.03-1.58.07-.56c.03-.26.06-.51.06-.78s-.03-.53-.06-.78l-.07-.56 2.03-1.58-1.39-2.4-2.39.96-.45-.35c-.42-.32-.87-.58-1.33-.77l-.52-.22-.37-2.55h-2.76l-.37 2.55-.53.21c-.44.19-.88.44-1.34.79l-.45.33-2.38-.95-1.39 2.39 2.03 1.58-.07.56a7 7 0 0 0-.06.79c0 .26.02.53.06.78l.07.56-2.03 1.58 1.38 2.4 2.39-.96.45.35c.43.33.86.58 1.33.77l.53.22.38 2.55z\x22\x3e\x3c/path\x3e\x3ccircle cx\x3d\x2212\x22 cy\x3d\x2212\x22 r\x3d\x223.5\x22\x3e\x3c/circle\x3e\x3c/svg\x3e\x3c/span\x3e)\x3c/a\x3e\x3c/span\x3e\x3c/div\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('tsuid_11', '\x3cg-dialog jsname\x3d\x22BDbGbf\x22 jscontroller\x3d\x22VEbNoe\x22 data-id\x3d\x22_Ny0hZajKHuSv2roPysWswAY_13\x22 jsaction\x3d\x22jxvro:Imgh9b\x22 jsdata\x3d\x22gctHtc;_;ANVEfc\x22 jsshadow\x3d\x22\x22\x3e\x3cdiv jsname\x3d\x22XKSfm\x22 id\x3d\x22_Ny0hZajKHuSv2roPysWswAY_13\x22 jsaction\x3d\x22dBhwS:TvD9Pc;mLt3mc\x22\x3e\x3c/div\x3e\x3c/g-dialog\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('tsuid_14', '\x3clocation-snackbar-with-learn-more jsname\x3d\x22nw18gf\x22 jscontroller\x3d\x22khkNpe\x22 jsaction\x3d\x22sFrcje:No7Jhf\x22\x3e\x3cspan id\x3d\x22tsuid_16\x22\x3e\x3c/span\x3e\x3c/location-snackbar-with-learn-more\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('tsuid_20', '\x3cg-snackbar jsname\x3d\x22M8d6me\x22 jscontroller\x3d\x22OZLguc\x22 style\x3d\x22display:none\x22 jsshadow\x3d\x22\x22 jsaction\x3d\x22rcuQ6b:npT2md\x22\x3e\x3cdiv jsname\x3d\x22sM5MNb\x22 aria-live\x3d\x22polite\x22 class\x3d\x22LH3wG\x22 style\x3d\x22z-index:2000\x22\x3e\x3cdiv jsname\x3d\x22Ng57nc\x22 class\x3d\x22yK6jqe\x22 data-ved\x3d\x222ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ4G96BAgDEAk\x22\x3e\x3cdiv class\x3d\x22b77HKf\x22\x3e\x3cdiv class\x3d\x22rIxsve\x22 jsslot\x3d\x22\x22\x3e\x3cspan class\x3d\x22Txngnb wHYlTd yUTMj\x22\x3e\u0110ang c\u1eadp nh\u1eadt v\u1ecb tr\xed...\x3c/span\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/g-snackbar\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('_Ny0hZajKHuSv2roPysWswAY_13', '\x3cdiv jsname\x3d\x22bF1uUb\x22 class\x3d\x22kJFf0c KUf18\x22\x3e\x3c/div\x3e\x3cdiv class\x3d\x22mcPPZ yMNJR nP0TDe xg7rAe\x22 jsaction\x3d\x22trigger.dBhwS\x22\x3e\x3cdiv class\x3d\x22LjfRsf\x22 aria-hidden\x3d\x22true\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 jsaction\x3d\x22focus:sT2f3e\x22\x3e\x3c/div\x3e\x3cspan jsslot\x3d\x22\x22 jsaction\x3d\x22mLt3mc\x22\x3e\x3cdiv class\x3d\x22qk7LXc TUOsUe Fb1AKc OosGzb\x22 aria-labelledby\x3d\x22lQ3q8c\x22 role\x3d\x22dialog\x22\x3e\x3cdiv jsname\x3d\x22C8RmQc\x22 id\x3d\x22C8RmQc\x22 data-jiis\x3d\x22up\x22 data-async-type\x3d\x22lbsc\x22 class\x3d\x22yp\x22\x3e\x3c/div\x3e\x3c/div\x3e\x3c/span\x3e\x3cdiv class\x3d\x22LjfRsf\x22 aria-hidden\x3d\x22true\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22 jsaction\x3d\x22focus:tuePCd\x22\x3e\x3c/div\x3e\x3c/div\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('tsuid_16', '\x3cg-snackbar jsname\x3d\x22Ng57nc\x22 jscontroller\x3d\x22OZLguc\x22 style\x3d\x22display:none\x22 data-dismiss\x3d\x22\x22 jsshadow\x3d\x22\x22 jsaction\x3d\x22rcuQ6b:npT2md\x22\x3e\x3cdiv jsname\x3d\x22sM5MNb\x22 aria-live\x3d\x22polite\x22 class\x3d\x22LH3wG\x22 style\x3d\x22z-index:2000\x22\x3e\x3cdiv jsname\x3d\x22Ng57nc\x22 class\x3d\x22yK6jqe\x22 data-ved\x3d\x222ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQ4G96BAgDEAU\x22\x3e\x3cdiv class\x3d\x22b77HKf\x22\x3e\x3cdiv class\x3d\x22rIxsve\x22 jsslot\x3d\x22\x22\x3e\x3cspan class\x3d\x22Txngnb wHYlTd yUTMj\x22\x3eKh\xf4ng th\u1ec3 c\u1eadp nh\u1eadt v\u1ecb tr\xed c\u1ee7a b\u1ea1n\x3c/span\x3e\x3cg-snackbar-action class\x3d\x22sHFNYd zJUuqf AB4Wff Z7swgb\x22 jsname\x3d\x22zrfavf\x22 jscontroller\x3d\x22xRxDld\x22 jsaction\x3d\x22GtUzrb\x22 data-ved\x3d\x222ahUKEwjowdDh1-OBAxXkl1YBHcoiC2gQhbkIegQIAxAH\x22\x3e\x3cg-flat-button class\x3d\x22U8shWc r2fjmd hObAcc gTewb VDgVie hpZDWd fSXIc\x22 style\x3d\x22color:#4285f4\x22 role\x3d\x22button\x22 tabindex\x3d\x220\x22\x3e\x3cspan class\x3d\x22Omzzbd\x22\x3eTi\u0300m hi\xea\u0309u th\xeam\x3c/span\x3e\x3c/g-flat-button\x3e\x3c/g-snackbar-action\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e\x3c/g-snackbar\x3e');
                }
                )();
                (function() {
                    window.jsl.dh('_Ny0hZajKHuSv2roPysWswAY_27', '\x3cdiv\x3e\x3cdiv\x3e\x3cdiv class\x3d\x22gb_hd\x22\x3eC\xe1c \u1ee9ng d\u1ee5ng c\u1ee7a Google\x3c/div\x3e\x3c/div\x3e\x3c/div\x3e', function() {
                        window.gbar && gbar.up && gbar.up.tp && gbar.up.tp();
                        this.gbar_ = this.gbar_ || {};
                        (function(_) {
                            var window = this;
                            try {
                                _.zd = function(a, b, c) {
                                    if (!a.j)
                                        if (c instanceof Array)
                                            for (var d of c)
                                                _.zd(a, b, d);
                                        else {
                                            d = (0,
                                            _.y)(a.A, a, b);
                                            const e = a.s + c;
                                            a.s++;
                                            b.dataset.eqid = e;
                                            a.B[e] = d;
                                            b && b.addEventListener ? b.addEventListener(c, d, !1) : b && b.attachEvent ? b.attachEvent("on" + c, d) : a.o.log(Error("u`" + b))
                                        }
                                }
                                ;
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                _.Ad = function() {
                                    if (!_.q.addEventListener || !Object.defineProperty)
                                        return !1;
                                    var a = !1
                                      , b = Object.defineProperty({}, "passive", {
                                        get: function() {
                                            a = !0
                                        }
                                    });
                                    try {
                                        const c = ()=>{}
                                        ;
                                        _.q.addEventListener("test", c, b);
                                        _.q.removeEventListener("test", c, b)
                                    } catch (c) {}
                                    return a
                                }();
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                var Bd = document.querySelector(".gb_l .gb_d")
                                  , Cd = document.querySelector("#gb.gb_Uc");
                                Bd && !Cd && _.zd(_.ld, Bd, "click");
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                _.rh = function(a) {
                                    const b = [];
                                    let c = 0;
                                    for (const d in a)
                                        b[c++] = a[d];
                                    return b
                                }
                                ;
                                _.sh = function(a) {
                                    if (a.o)
                                        return a.o;
                                    for (const b in a.i)
                                        if (a.i[b].qa() && a.i[b].B())
                                            return a.i[b];
                                    return null
                                }
                                ;
                                _.th = function(a, b) {
                                    a.i[b.J()] = b
                                }
                                ;
                                var uh = new class extends _.tc {
                                    constructor() {
                                        var a = _.vc;
                                        super();
                                        this.B = a;
                                        this.o = null;
                                        this.j = {};
                                        this.A = {};
                                        this.i = {};
                                        this.s = null
                                    }
                                    v(a) {
                                        this.i[a] && (_.sh(this) && _.sh(this).J() == a || this.i[a].O(!0))
                                    }
                                    Wa(a) {
                                        this.s = a;
                                        for (const b in this.i)
                                            this.i[b].qa() && this.i[b].Wa(a)
                                    }
                                    uc(a) {
                                        return a in this.i ? this.i[a] : null
                                    }
                                }
                                ;
                                _.od("dd", uh);
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                _.bj = function(a, b) {
                                    return _.L(a, 36, b)
                                }
                                ;
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                var cj = document.querySelector(".gb_b .gb_d")
                                  , dj = document.querySelector("#gb.gb_Uc");
                                cj && !dj && _.zd(_.ld, cj, "click");
                            } catch (e) {
                                _._DumpException(e)
                            }
                        }
                        )(this.gbar_);
                        // Google Inc.
                        ;this.gbar_ = this.gbar_ || {};
                        (function(_) {
                            var window = this;
                            try {
                                var Ed, Hd;
                                _.Dd = function(a) {
                                    const b = a.length;
                                    if (0 < b) {
                                        const c = Array(b);
                                        for (let d = 0; d < b; d++)
                                            c[d] = a[d];
                                        return c
                                    }
                                    return []
                                }
                                ;
                                Ed = function(a) {
                                    return a
                                }
                                ;
                                _.Fd = function(a) {
                                    var b = null
                                      , c = _.q.trustedTypes;
                                    if (!c || !c.createPolicy)
                                        return b;
                                    try {
                                        b = c.createPolicy(a, {
                                            createHTML: Ed,
                                            createScript: Ed,
                                            createScriptURL: Ed
                                        })
                                    } catch (d) {
                                        _.q.console && _.q.console.error(d.message)
                                    }
                                    return b
                                }
                                ;
                                _.Gd = function(a, b) {
                                    return 0 == a.lastIndexOf(b, 0)
                                }
                                ;
                                _.Id = function() {
                                    void 0 === Hd && (Hd = _.Fd("ogb-qtm#html"));
                                    return Hd
                                }
                                ;
                                try {
                                    (new self.OffscreenCanvas(0,0)).getContext("2d")
                                } catch (a) {}
                                ;_.Jd = {};
                                _.Kd = class {
                                    constructor(a) {
                                        this.i = a;
                                        this.Cb = !0
                                    }
                                    nb() {
                                        return this.i
                                    }
                                    toString() {
                                        return this.i.toString()
                                    }
                                }
                                ;
                                _.Ld = new _.Kd("",_.Jd);
                                _.Md = RegExp("^[-+,.\"'%_!#/ a-zA-Z0-9\\[\\]]+$");
                                _.Nd = RegExp("\\b(url\\([ \t\n]*)('[ -&(-\\[\\]-~]*'|\"[ !#-\\[\\]-~]*\"|[!#-&*-\\[\\]-~]*)([ \t\n]*\\))", "g");
                                _.Od = RegExp("\\b(calc|cubic-bezier|fit-content|hsl|hsla|linear-gradient|matrix|minmax|radial-gradient|repeat|rgb|rgba|(rotate|scale|translate)(X|Y|Z|3d)?|steps|var)\\([-+*/0-9a-zA-Z.%#\\[\\], ]+\\)", "g");
                                var Pd;
                                Pd = {};
                                _.Rd = function(a) {
                                    return a instanceof _.Qd && a.constructor === _.Qd ? a.i : "type_error:SafeHtml"
                                }
                                ;
                                _.Sd = function(a) {
                                    const b = _.Id();
                                    a = b ? b.createHTML(a) : a;
                                    return new _.Qd(a,Pd)
                                }
                                ;
                                _.Qd = class {
                                    constructor(a) {
                                        this.i = a;
                                        this.Cb = !0
                                    }
                                    nb() {
                                        return this.i.toString()
                                    }
                                    toString() {
                                        return this.i.toString()
                                    }
                                }
                                ;
                                _.Td = new _.Qd(_.q.trustedTypes && _.q.trustedTypes.emptyHTML || "",Pd);
                                _.Ud = _.Sd("<br>");
                                var Wd;
                                _.Vd = function(a) {
                                    let b = !1, c;
                                    return function() {
                                        b || (c = a(),
                                        b = !0);
                                        return c
                                    }
                                }(function() {
                                    var a = document.createElement("div")
                                      , b = document.createElement("div");
                                    b.appendChild(document.createElement("div"));
                                    a.appendChild(b);
                                    b = a.firstChild.firstChild;
                                    a.innerHTML = _.Rd(_.Td);
                                    return !b.parentElement
                                });
                                Wd = /^[\w+/_-]+[=]{0,2}$/;
                                _.Xd = function(a) {
                                    a = (a || _.q).document;
                                    return a.querySelector ? (a = a.querySelector('style[nonce],link[rel="stylesheet"][nonce]')) && (a = a.nonce || a.getAttribute("nonce")) && Wd.test(a) ? a : "" : ""
                                }
                                ;
                                _.Yd = function(a, b) {
                                    this.width = a;
                                    this.height = b
                                }
                                ;
                                _.l = _.Yd.prototype;
                                _.l.aspectRatio = function() {
                                    return this.width / this.height
                                }
                                ;
                                _.l.Ib = function() {
                                    return !(this.width * this.height)
                                }
                                ;
                                _.l.ceil = function() {
                                    this.width = Math.ceil(this.width);
                                    this.height = Math.ceil(this.height);
                                    return this
                                }
                                ;
                                _.l.floor = function() {
                                    this.width = Math.floor(this.width);
                                    this.height = Math.floor(this.height);
                                    return this
                                }
                                ;
                                _.l.round = function() {
                                    this.width = Math.round(this.width);
                                    this.height = Math.round(this.height);
                                    return this
                                }
                                ;
                                _.R = function(a, b) {
                                    var c = b || document;
                                    if (c.getElementsByClassName)
                                        a = c.getElementsByClassName(a)[0];
                                    else {
                                        c = document;
                                        var d = b || c;
                                        a = d.querySelectorAll && d.querySelector && a ? d.querySelector(a ? "." + a : "") : _.Zd(c, a, b)[0] || null
                                    }
                                    return a || null
                                }
                                ;
                                _.Zd = function(a, b, c) {
                                    var d;
                                    a = c || a;
                                    if (a.querySelectorAll && a.querySelector && b)
                                        return a.querySelectorAll(b ? "." + b : "");
                                    if (b && a.getElementsByClassName) {
                                        var e = a.getElementsByClassName(b);
                                        return e
                                    }
                                    e = a.getElementsByTagName("*");
                                    if (b) {
                                        var f = {};
                                        for (c = d = 0; a = e[c]; c++) {
                                            var g = a.className;
                                            "function" == typeof g.split && _.va(g.split(/\s+/), b) && (f[d++] = a)
                                        }
                                        f.length = d;
                                        return f
                                    }
                                    return e
                                }
                                ;
                                _.ae = function(a) {
                                    return _.$d(document, a)
                                }
                                ;
                                _.$d = function(a, b) {
                                    b = String(b);
                                    "application/xhtml+xml" === a.contentType && (b = b.toLowerCase());
                                    return a.createElement(b)
                                }
                                ;
                                _.be = function(a) {
                                    for (var b; b = a.firstChild; )
                                        a.removeChild(b)
                                }
                                ;
                                _.ce = function(a) {
                                    return 9 == a.nodeType ? a : a.ownerDocument || a.document
                                }
                                ;
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                var xe, ze;
                                _.se = function(a) {
                                    if (null == a)
                                        return a;
                                    if ("string" === typeof a) {
                                        if (!a)
                                            return;
                                        a = +a
                                    }
                                    if ("number" === typeof a)
                                        return a
                                }
                                ;
                                _.te = function(a, b) {
                                    var c = Array.prototype.slice.call(arguments, 1);
                                    return function() {
                                        var d = c.slice();
                                        d.push.apply(d, arguments);
                                        return a.apply(this, d)
                                    }
                                }
                                ;
                                _.ue = function(a, b) {
                                    return _.se(_.C(a, b))
                                }
                                ;
                                _.ve = function(a, b) {
                                    if (void 0 !== a.ua || void 0 !== a.i)
                                        throw Error("x");
                                    a.i = b;
                                    _.bd(a)
                                }
                                ;
                                _.we = class extends _.P {
                                    constructor(a) {
                                        super(a)
                                    }
                                }
                                ;
                                xe = class extends _.pd {
                                }
                                ;
                                _.ye = function(a, b) {
                                    if (b in a.i)
                                        return a.i[b];
                                    throw new xe;
                                }
                                ;
                                ze = 0;
                                _.Ae = function(a) {
                                    return Object.prototype.hasOwnProperty.call(a, _.pb) && a[_.pb] || (a[_.pb] = ++ze)
                                }
                                ;
                                _.Be = function(a) {
                                    if (a instanceof _.Bc)
                                        return a;
                                    a = "object" == typeof a && a.Cb ? a.nb() : String(a);
                                    a: {
                                        var b = a;
                                        if (_.Jc) {
                                            try {
                                                var c = new URL(b)
                                            } catch (d) {
                                                b = "https:";
                                                break a
                                            }
                                            b = c.protocol
                                        } else
                                            b: {
                                                c = document.createElement("a");
                                                try {
                                                    c.href = b
                                                } catch (d) {
                                                    b = void 0;
                                                    break b
                                                }
                                                b = c.protocol;
                                                b = ":" === b || "" === b ? "https:" : b
                                            }
                                    }
                                    "javascript:" === b && (a = "about:invalid#zClosurez");
                                    return _.Gc(a)
                                }
                                ;
                                _.Ce = function(a) {
                                    return _.ye(_.md.i(), a)
                                }
                                ;
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                /*

 SPDX-License-Identifier: Apache-2.0
*/
                                var ij, jj;
                                ij = function(a) {
                                    return new _.hj(b=>b.substr(0, a.length + 1).toLowerCase() === a + ":")
                                }
                                ;
                                jj = {};
                                _.kj = class {
                                    constructor(a) {
                                        this.i = a
                                    }
                                    toString() {
                                        return this.i + ""
                                    }
                                }
                                ;
                                _.kj.prototype.Cb = !0;
                                _.kj.prototype.nb = function() {
                                    return this.i.toString()
                                }
                                ;
                                _.mj = function(a) {
                                    return _.lj(a).toString()
                                }
                                ;
                                _.lj = function(a) {
                                    return a instanceof _.kj && a.constructor === _.kj ? a.i : "type_error:TrustedResourceUrl"
                                }
                                ;
                                _.nj = function(a) {
                                    const b = _.Id();
                                    a = b ? b.createScriptURL(a) : a;
                                    return new _.kj(a,jj)
                                }
                                ;
                                _.oj = "function" === typeof URL;
                                _.hj = class {
                                    constructor(a) {
                                        this.Lg = a
                                    }
                                }
                                ;
                                _.pj = [ij("data"), ij("http"), ij("https"), ij("mailto"), ij("ftp"), new _.hj(a=>/^[^:]*([/?#]|$)/.test(a))];
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                _.qj = class extends _.P {
                                    constructor(a) {
                                        super(a)
                                    }
                                }
                                ;
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                _.rj = function(a, b, c) {
                                    a.rel = c;
                                    -1 != c.toLowerCase().indexOf("stylesheet") ? (a.href = _.mj(b),
                                    (b = _.Xd(a.ownerDocument && a.ownerDocument.defaultView)) && a.setAttribute("nonce", b)) : a.href = b instanceof _.kj ? _.mj(b) : b instanceof _.Bc ? _.Dc(b) : _.Dc(_.Be(b))
                                }
                                ;
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                _.sj = function(a) {
                                    var b;
                                    let c;
                                    const d = null == (c = (b = (a.ownerDocument && a.ownerDocument.defaultView || window).document).querySelector) ? void 0 : c.call(b, "script[nonce]");
                                    (b = d ? d.nonce || d.getAttribute("nonce") || "" : "") && a.setAttribute("nonce", b)
                                }
                                ;
                                _.tj = function(a, b) {
                                    return (b || document).getElementsByTagName(String(a))
                                }
                                ;
                            } catch (e) {
                                _._DumpException(e)
                            }
                            try {
                                var vj = function(a, b, c) {
                                    a < b ? uj(a + 1, b) : _.vc.log(Error("X`" + a + "`" + b), {
                                        url: c
                                    })
                                }
                                  , uj = function(a, b) {
                                    if (wj) {
                                        const c = _.ae("SCRIPT");
                                        c.async = !0;
                                        c.type = "text/javascript";
                                        c.charset = "UTF-8";
                                        c.src = _.lj(wj);
                                        _.sj(c);
                                        c.onerror = _.te(vj, a, b, c.src);
                                        _.tj("HEAD")[0].appendChild(c)
                                    }
                                }
                                  , xj = class extends _.P {
                                    constructor(a) {
                                        super(a)
                                    }
                                }
                                ;
                                var yj = _.G(_.fd, xj, 17) || new xj, zj, wj = (zj = _.G(yj, _.qj, 1)) ? _.nj(_.I(zj, 4) || "") : null, Aj, Bj = (Aj = _.G(yj, _.qj, 2)) ? _.nj(_.I(Aj, 4) || "") : null, Cj = function() {
                                    uj(1, 2);
                                    if (Bj) {
                                        const a = _.ae("LINK");
                                        a.setAttribute("type", "text/css");
                                        _.rj(a, Bj, "stylesheet");
                                        let b = _.Xd();
                                        b && a.setAttribute("nonce", b);
                                        _.tj("HEAD")[0].appendChild(a)
                                    }
                                };
                                (function() {
                                    const a = _.hd();
                                    if (_.E(a, 18))
                                        Cj();
                                    else {
                                        const b = _.ue(a, 19) || 0;
                                        window.addEventListener("load", ()=>{
                                            window.setTimeout(Cj, b)
                                        }
                                        )
                                    }
                                }
                                )();
                            } catch (e) {
                                _._DumpException(e)
                            }
                        }
                        )(this.gbar_);
                        // Google Inc.
                        ;
                    });
                }
                )();
                (function() {
                    google.drty && google.drty(undefined, true);
                }
                )();
            });
        </script>
        <div></div>
        <div jscontroller="EO13pd" class="fp-nh" id="TWfxFb" jsaction="rcuQ6b:npT2md;Egr1he:f0xwYb;vKbCb:dwOkab">
            <div jsname="J7OdWb" data-jiis="up" data-async-type="vpkg" id="QPwIld" class="yp"></div>
        </div>
        <div id="lfootercc">
            <div id="Un6H4"></div>
            <script nonce="N4ljJHxWoJx3pKoWtd5YIw">
                (function() {
                    var footerDebugCommentsCssId = 'Un6H4';
                    let debugComments = document.getElementById('dc');
                    let footerDebugComments = document.getElementById(footerDebugCommentsCssId);
                    if (debugComments && footerDebugComments) {
                        debugComments.appendChild(footerDebugComments);
                    }
                }
                )();
            </script>
            <script nonce="N4ljJHxWoJx3pKoWtd5YIw">
                (function() {
                    for (var i in google.iir || {}) {
                        _setImagesSrc([i], google.iir[i]);
                    }
                    google.iir = {};
                }
                )();
                google.jslm = 3;
            </script>
            <script nonce="N4ljJHxWoJx3pKoWtd5YIw">
                (function() {
                    var xsrfTokens = '{\x22UPgwmc\x22:\x22ALook6xLqCzG9KzKkHZDsdCQI8A7zgqY1g:1696673079876\x22}';
                    google.xsrf = JSON.parse(xsrfTokens);
                }
                )();
            </script>
            <div id="reviewDialog" data-async-context="async_id_prefix:" data-jiis="up" data-async-type="reviewDialog" data-async-context-required="async_id_prefix" class="yp"></div>
            <div id="dbg_"></div>
        </div>
    </body>
</html>
