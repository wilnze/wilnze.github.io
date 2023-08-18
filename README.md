<!doctype html>
<html itemscope="" itemtype="http://schema.org/SearchResultsPage" lang="en-NG">
<head>
    <meta charset="UTF-8">
    <meta content="dark" name="color-scheme">
    <meta content="origin" name="referrer">
    <meta content="/images/branding/googleg/1x/googleg_standard_color_128dp.png" itemprop="image">
    <title>access website web development with safari - Google Search</title>
    <script nonce="vCFhJHlJMUORr-8JC1FOxQ">
    (function() {
        var b = window.addEventListener;
        window.addEventListener = function(a, c, d) {
            "unload" !== a && b(a, c, d)
        };
    }).call(this);
    (function() {
        var _g = {
            kEI: 'jSDfZMr5G8j1kwWA1bGoAg',
            kEXPI: '31',
            u: 'b6f7cf5e',
            kBL: 'kYBU',
            kOPI: 89978449
        };
        (function() {
            var a;
            (null == (a = window.google) ? 0 : a.stvsc) ? google.kEI = _g.kEI : window.google = _g;
        }).call(this);
    })();
    (function() {
        google.sn = 'web';
        google.kHL = 'en-NG';
    })();
    (function() {
        var h = this || self;
        function l() {
            return void 0 !== window.google && void 0 !== window.google.kOPI && 0 !== window.google.kOPI ? window.google.kOPI : null
        }
        ;
        var m,
            n = [];
        function p(a) {
            for (var b; a && (!a.getAttribute || !(b = a.getAttribute("eid")));)
                a = a.parentNode;
            return b || m
        }
        function q(a) {
            for (var b = null; a && (!a.getAttribute || !(b = a.getAttribute("leid")));)
                a = a.parentNode;
            return b
        }
        function r(a) {
            /^http:/i.test(a) && "https:" === window.location.protocol && (google.ml && google.ml(Error("a"), !1, {
                src: a,
                glmm: 1
            }), a = "");
            return a
        }
        function t(a, b, c, d, k) {
            var e = "";
            -1 === b.search("&ei=") && (e = "&ei=" + p(d), -1 === b.search("&lei=") && (d = q(d)) && (e += "&lei=" + d));
            d = "";
            var g = -1 === b.search("&cshid=") && "slh" !== a,
                f = [];
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
        ;
        m = google.kEI;
        google.getEI = p;
        google.getLEI = q;
        google.ml = function() {
            return null
        };
        google.log = function(a, b, c, d, k, e) {
            e = void 0 === e ? l : e;
            c || (c = t(a, b, e, d, k));
            if (c = r(c)) {
                a = new Image;
                var g = n.length;
                n[g] = a;
                a.onerror = a.onload = a.onabort = function() {
                    delete n[g]
                };
                a.src = c
            }
        };
        google.logUrl = function(a, b) {
            b = void 0 === b ? l : b;
            return t("", a, b)
        };
    }).call(this);
    (function() {
        google.y = {};
        google.sy = [];
        google.x = function(a, b) {
            if (a)
                var c = a.id;
            else {
                do c = Math.random();
                while (google.y[c])
            }
            google.y[c] = [a, b];
            return !1
        };
        google.sx = function(a) {
            google.sy.push(a)
        };
        google.lm = [];
        google.plm = function(a) {
            google.lm.push.apply(google.lm, a)
        };
        google.lq = [];
        google.load = function(a, b, c) {
            google.lq.push([[a], b, c])
        };
        google.loadAll = function(a, b) {
            google.lq.push([a, b])
        };
        google.bx = !1;
        google.lx = function() {};
    }).call(this);
    google.f = {};
    (function() {
        document.documentElement.addEventListener("submit", function(b) {
            var a;
            if (a = b.target) {
                var c = a.getAttribute("data-submitfalse");
                a = "1" === c || "q" === c && !a.elements.q.value ? !0 : !1
            } else
                a = !1;
            a && (b.preventDefault(), b.stopPropagation())
        }, !0);
        document.documentElement.addEventListener("click", function(b) {
            var a;
            a:
            {
                for (a = b.target; a && a !== document.documentElement; a = a.parentElement)
                    if ("A" === a.tagName) {
                        a = "1" === a.getAttribute("data-nohref");
                        break a
                    }
                a = !1
            }a && b.preventDefault()
        }, !0);
    }).call(this);
    (function() {
        google.hs = {
            h: true,
            nhs: false,
            sie: false
        };
    })();
    (function() {
        google.c = {
            bfrt: false,
            bfrte: true,
            bofr: true,
            btfi: false,
            c4t: false,
            cap: 2000,
            fla: false,
            fli: false,
            frt: true,
            frvt: true,
            gl: false,
            irsf: false,
            lhc: false,
            llt: false,
            lsb: false,
            mais: false,
            pbph: false,
            raf: false,
            sxs: false,
            taf: true,
            timl: false,
            upb: false,
            vis: true,
            wh0: false,
            whu: false
        };
    })();
    (function() {
        var f = this || self;
        var g = window.performance;
        var h = google.c.gl,
            k = google.c.sxs;
        function l(a, b, d, c) {
            a.addEventListener ? a.addEventListener(b, d, c || !1) : a.attachEvent && a.attachEvent("on" + b, d)
        }
        function m(a, b, d, c) {
            "addEventListener" in a ? a.removeEventListener(b, d, c || !1) : a.attachEvent && a.detachEvent("on" + b, d)
        }
        ;
        google.c.iim = google.c.iim || {};
        function n(a) {
            a && f.google.aft(a.target)
        }
        var p;
        function q() {
            m(document.documentElement, "load", p, !0);
            m(document.documentElement, "error", p, !0)
        }
        ;
        google.timers = {};
        google.startTick = function(a) {
            google.timers[a] = {
                t: {
                    start: Date.now()
                },
                e: {},
                m: {}
            }
        };
        google.tick = function(a, b, d) {
            google.timers[a] || google.startTick(a);
            d = void 0 !== d ? d : Date.now();
            b instanceof Array || (b = [b]);
            for (var c = 0, e; e = b[c++];)
                google.timers[a].t[e] = d
        };
        google.c.e = function(a, b, d) {
            google.timers[a].e[b] = d
        };
        google.c.b = function(a, b) {
            b = google.timers[b || "load"].m;
            b[a] && google.ml(Error("a"), !1, {
                m: a
            });
            b[a] = !0
        };
        google.c.u = function(a, b) {
            var d = google.timers[b || "load"],
                c = d.m;
            if (c[a]) {
                c[a] = !1;
                for (a in c)
                    if (c[a])
                        return;
                google.csiReport(d, k && "load2" === b ? "all2" : "all")
            } else {
                b = "";
                for (var e in c)
                    b += e + ":" + c[e] + ";";
                google.ml(Error("b"), !1, {
                    m: a,
                    b: !1 === c[a],
                    s: b
                })
            }
        };
        google.rll = function(a, b, d) {
            function c(e) {
                d(e);
                m(a, "load", c);
                m(a, "error", c)
            }
            l(a, "load", c);
            b && l(a, "error", c)
        };
        f.google.aft = function(a) {
            a.setAttribute("data-iml", String(Date.now()))
        };
        google.startTick("load");
        var r = google.timers.load;
        if (!google.stvsc)
            a:
            {
                var t = r.t;
                if (g) {
                    var u = g.timing;
                    if (u) {
                        var v = u.navigationStart,
                            w = u.responseStart;
                        if (w > v && w <= t.start) {
                            t.start = w;
                            r.wsrt = w - v;
                            break a
                        }
                    }
                    g.now && (r.wsrt = Math.floor(g.now()))
                }
            }google.c.b("pr", "load");
        google.c.b("xe", "load");
        var x;
        if (null == (x = google.stvsc) ? 0 : x.start)
            google.timers.load.t.start = google.stvsc.start;
        function y(a) {
            if ("hidden" === document.visibilityState) {
                google.c.fh = a;
                var b;
                window.performance && window.performance.timing && (b = Math.floor(window.performance.timing.navigationStart + a));
                google.tick("load", "fht", b);
                return !0
            }
            return !1
        }
        function z(a) {
            y(a.timeStamp) && m(document, "visibilitychange", z, !0)
        }
        google.c.fh = Infinity;
        l(document, "visibilitychange", z, !0);
        y(0);
        h && (p = n, l(document.documentElement, "load", p, !0), google.c.glu = q);
    }).call(this);
    (function() {
        var h = this || self;
        function k(a) {
            try {
                a()
            } catch (b) {
                google.ml(b, !1)
            }
        }
        google.caft = function(a, b) {
            null === google.aftq ? k(a) : (google.aftq = google.aftq || [], google.aftq.push(a), b && window.setTimeout(function() {
                google.aftq && (google.aftq = google.aftq.filter(function(c) {
                    return a !== c
                }), k(a))
            }, b))
        };
        function q() {
            return window.performance && window.performance.navigation && window.performance.navigation.type
        }
        ;
        function aa(a, b) {
            if (!a || ba(a))
                return 0;
            if (!a.getBoundingClientRect)
                return 1;
            var c = function(d) {
                return d.getBoundingClientRect()
            };
            return ca(a, b, c) ? 0 : da(a, b, c)
        }
        function ca(a, b, c) {
            a:
            {
                for (var d = a; d && d !== b; d = d.parentElement)
                    if ("hidden" === d.style.overflow || "G-EXPANDABLE-CONTENT" === d.tagName && "hidden" === getComputedStyle(d).getPropertyValue("overflow")) {
                        b = d;
                        break a
                    }
                b = null
            }if (!b)
                return !1;
            a = c(a);
            c = c(b);
            return a.bottom < c.top || a.top >= c.bottom || a.right < c.left || a.left >= c.right
        }
        function ba(a) {
            return "none" === a.style.display ? !0 : document.defaultView && document.defaultView.getComputedStyle ? (a = document.defaultView.getComputedStyle(a), !!a && ("hidden" === a.visibility || "0px" === a.height && "0px" === a.width)) : !1
        }
        function da(a, b, c) {
            var d = c(a),
                e = d.left + window.pageXOffset,
                g = d.top + window.pageYOffset,
                m = d.width,
                l = d.height,
                f = 0;
            if (0 >= l && 0 >= m)
                return f;
            var n = window.innerHeight || document.documentElement.clientHeight;
            0 > g + l ? f = 2 : g >= n && (f = 4);
            if (0 > e + m || e >= (window.innerWidth || document.documentElement.clientWidth))
                f |= 8;
            else if (b) {
                for (d = d.left; a && a !== b; a = a.parentElement)
                    d += a.scrollLeft;
                b = c(b);
                if (d + m < b.left || d >= b.right)
                    f |= 8
            }
            f || (f = 1, g + l > n && (f |= 4));
            return f
        }
        ;
        var r = google.c.bfrt,
            ea = google.c.lhc,
            fa = google.c.pbph,
            t = google.c.sxs,
            u = google.c.taf,
            v = google.c.btfi,
            w = google.c.frt,
            x = google.c.frvt,
            y = google.c.timl,
            z = google.c.upb;
        function A(a) {
            return "/gen_204?s=" + google.sn + "&t=" + a + "&atyp=csi&ei=" + google.kEI
        }
        ;
        function B() {
            var a;
            null == (a = C("cap")) || a.sendNow();
            var b;
            null == (b = C("aft")) || b.sendNow();
            var c;
            null == (c = C("all")) || c.sendNow();
            a = window;
            "addEventListener" in a ? a.removeEventListener("pagehide", B, !1) : a.attachEvent && a.detachEvent("onpagehide", B)
        }
        var D = {};
        function E(a) {
            z && (D[a] = new PendingGetBeacon(A(a) + "&inc=1"))
        }
        function C(a) {
            if (z)
                return D[a]
        }
        ;
        var ha = window.location,
            ia = "aft afti aftr afts cbs cbt fht frt frts frvt hct prt sct".split(" ");
        function F(a) {
            return (a = ha.search.match(new RegExp("[?&]" + a + "=(\\d+)"))) ? Number(a[1]) : -1
        }
        function G(a, b) {
            var c = google.timers[b || "load"];
            b = c.m;
            if (!b || !b.prs) {
                var d = q() ? 0 : F("qsubts");
                0 < d && (b = F("fbts"), 0 < b && (c.t.start = Math.max(d, b)));
                var e = c.t,
                    g = e.start;
                b = {
                    wsrt: c.wsrt || 0
                };
                if (g)
                    for (var m = 0, l; l = ia[m++];) {
                        var f = e[l];
                        f && (b[l] = Math.max(f - g, 0))
                    }
                0 < d && (b.gsasrt = c.t.start - d);
                d = c.e;
                c = A(a) + "&rt=";
                e = "";
                for (var n in b)
                    c += "" + e + n + "." + b[n],
                    e = ",";
                for (var p in d)
                    c += "&" + p + "=" + d[p];
                n = c;
                p = "";
                c = [];
                h._cshid && c.push(["cshid", h._cshid]);
                d = void 0 !== window.google && void 0 !== window.google.kOPI && 0 !== window.google.kOPI ? window.google.kOPI : null;
                null != d && c.push(["opi", d.toString()]);
                for (d = 0; d < c.length; d++) {
                    if (0 === d || 0 < d)
                        p += "&";
                    p += c[d][0] + "=" + c[d][1]
                }
                c = n + p;
                2 === q() && (c += "&bb=1");
                1 === q() && (c += "&r=1");
                "gsasrt" in b && (b = F("qsd"), 0 < b && (c += "&qsd=" + b));
                google.kBL && (c += "&bl=" + google.kBL);
                b = c;
                (a = C(a)) ? (a.setURL(b), a.sendNow()) : "function" === typeof navigator.sendBeacon ? navigator.sendBeacon(b, "") : google.log("", "", b)
            }
        }
        ;
        function H(a) {
            a && google.tick("load", "cbs", a);
            google.tick("load", "cbt");
            G("cap")
        }
        ;
        var I = "src bsrc url ll image img-url".split(" ");
        function ja(a) {
            for (var b = 0; b < I.length; ++b)
                if (a.getAttribute("data-" + I[b]))
                    return !0;
            return !1
        }
        function ma(a) {
            for (var b = a; b && "center_col" !== b.id;)
                b = b.parentElement;
            var c = a.parentElement;
            if (c && ("G-IMG" === c.tagName || c.classList.contains("uhHOwf")) && (c.style.height || c.style.width)) {
                var d = c.getBoundingClientRect(),
                    e = a.getBoundingClientRect();
                if (d.height <= e.height || d.width <= e.width)
                    a = c
            }
            return aa(a, b)
        }
        google.c.iim = google.c.iim || {};
        var J = window.performance;
        var K = window.innerHeight || document.documentElement.clientHeight,
            L = 0,
            M = 0,
            N = 0,
            O = 0,
            na = 0,
            oa = 0,
            P = 0,
            Q = 0,
            pa = 0,
            qa = 0,
            R = !0,
            S = !0,
            T = -1,
            U,
            V = t ? "load2" : "load";
        function W(a, b, c, d) {
            var e = google.timers[V].t[a];
            e && (c || d && null != b && b < e) || google.tick(V, a, b)
        }
        function X(a, b, c) {
            var d = "1" === a.getAttribute("data-frt");
            w && d && (W("frt", c, !1, !0), ++O, Y());
            b && (x && d && (W("frvt", c, !1, !0), ++oa), W("aft", c, !1, !0), W("afti", c, !1, !0), ++Q, R || (T = K), Y());
            y && W("iml", c, !1, !0);
            ++M;
            a.setAttribute("data-frt", "0");
            (y || b || r && d) && ra()
        }
        function ra() {
            var a = Q === P,
                b = O === N;
            a = r ? a && b : a;
            a = y ? M === L : a;
            !S && a && google.c.u("il", V)
        }
        function Y() {
            if (!R) {
                var a = Q === P,
                    b = O === N,
                    c = x && oa === na;
                a && (google.c.e(V, "aft", "1"), google.c.e(V, "aftp", String(Math.round(T))));
                if (a && b) {
                    U && clearTimeout(U);
                    var d;
                    null == (d = C("cap")) || d.deactivate();
                    G(t ? "aft2" : "aft", V);
                    if (!t && google.c.c4t && J && J.mark && J.timing) {
                        var e = google.timers.load;
                        d = e.wsrt;
                        e = e.t.aft;
                        d && 0 < d && e && 0 < e && (e -= J.timing.navigationStart, 0 < e && (J.mark("SearchAFTStart", {
                            startTime: d
                        }), J.mark("trigger:SearchAFTEnd", {
                            startTime: e
                        })))
                    }
                }
                "hidden" === document.visibilityState && google.c.e(V, "hddn", "1");
                if (!t &&
                null !== google.aftq && (2 === google.fevent || 3 === google.fevent ? google.fevent : 1) & ((a ? 1 : 0) | (c || b ? 2 : 0))) {
                    google.tick("load", "aftqf", Date.now());
                    var g;
                    for (a = 0; b = null == (g = google.aftq) ? void 0 : g[a++];)
                        k(b);
                    google.aftq = null
                }
            }
        }
        function sa() {
            R && !google.c.bofr && (R = !1, R || (google.c.e(V, "ima", String(P)), google.c.e(V, "imad", String(pa)), google.c.e(V, "imac", String(qa)), google.c.e(V, "imf", String(N)), document.getElementsByClassName("Ib7Efc").length && google.c.e(V, "ddl", "1")), Y())
        }
        function ta(a, b) {
            0 === b || b & 8 || (a.setAttribute("data-frt", "1"), w && ++N)
        }
        if (z && "function" === typeof window.PendingGetBeacon) {
            E("cap");
            E("aft");
            E("all");
            if (fa) {
                var Z = window;
                Z.addEventListener ? Z.addEventListener("pagehide", B, !1) : Z.attachEvent && Z.attachEvent("onpagehide", B)
            }
            google.c.lpb = C("all")
        }
        if (0 < google.c.cap && !t)
            a:
            {
                var ua = google.c.cap;
                if (window.performance && window.performance.timing && "navigationStart" in window.performance.timing) {
                    var va = window.performance.now(),
                        wa = ua - va;
                    if (0 < wa) {
                        U = setTimeout(H, wa, Math.floor(window.performance.timing.navigationStart + va));
                        break a
                    }
                    H()
                }
                U = void 0
            }google.c.wh = Math.floor(window.innerHeight || document.documentElement.clientHeight);
        google.c.e(V, "wh", String(google.c.wh));
        google.c.b("il", V);
        google.c.setup = function(a, b, c) {
            var d = a.getAttribute("data-atf");
            if (d)
                return c = Number(d), b && !a.hasAttribute("data-frt") && ta(a, c), c;
            var e = "string" !== typeof a.src || !a.src,
                g = !!a.getAttribute("data-bsrc"),
                m = !!a.getAttribute("data-deferred"),
                l = !m && ja(a);
            l && a.setAttribute("data-lzy_", "1");
            d = ma(a);
            a.setAttribute("data-atf", String(d));
            var f = !!(d & 1);
            e = (e || a.complete) && !m && !g && !(f && l);
            g = !ea && Number(a.getAttribute("data-iml")) || 0;
            ++L;
            if (e && !g || a.hasAttribute("data-noaft"))
                a.setAttribute("data-frt", "0"),
                ++M,
                f &&
                ++qa;
            else {
                var n = d & 4,
                    p = v && n && g && T < K;
                if (p) {
                    var ka = a.getBoundingClientRect().top + window.pageYOffset;
                    !c || 0 > c || ka < c ? T = f ? K : ka : p = !1
                }
                f && (++P, m && ++pa);
                b && ta(a, d);
                x && f && b && ++na;
                p && (W("aft", g, !1, !0), W("aftb", g, !1, !0));
                if (e && g)
                    X(a, f, v ? 0 : g);
                else {
                    f && (!u && !c || n || c && (0 > c || c >= K)) && (T = K);
                    var la = a.src;
                    google.rll(a, !0, function() {
                        (m || l) && la && la === a.src ? google.rll(a, !0, function() {
                            X(a, f, Date.now())
                        }) : X(a, f, Date.now())
                    })
                }
            }
            return d
        };
        google.c.ubr = function(a, b, c, d) {
            u && T < K ? (T = c || -1, W("aft", b)) : 0 > T && (c && (T = c), v && W("aft", b));
            a || W("afts", b, !0);
            d || (W("aft", b, !0), a && S ? (W("prt", b), y && W("iml", b, !0), S = !1, sa(), ra(), google.c.setup = function() {
                return 0
            }, google.c.ubr = function() {}) : sa())
        };
    }).call(this);
    (function() {
        var b = [function() {
            google.tick && google.tick("load", "dcl")
        }];
        google.dclc = function(a) {
            b.length ? b.push(a) : a()
        };
        function c() {
            for (var a = b.shift(); a;)
                a(),
                a = b.shift()
        }
        window.addEventListener ? (document.addEventListener("DOMContentLoaded", c, !1), window.addEventListener("load", c, !1)) : window.attachEvent && window.attachEvent("onload", c);
    }).call(this);
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
    }).call(this);
    (function() {
        var e = this || self;
        var f = {};
        function w(a, c) {
            if (null === c)
                return !1;
            if ("contains" in a && 1 == c.nodeType)
                return a.contains(c);
            if ("compareDocumentPosition" in a)
                return a == c || !!(a.compareDocumentPosition(c) & 16);
            for (; c && a != c;)
                c = c.parentNode;
            return c == a
        }
        ;
        var y = function(a, c) {
                return function(d) {
                    d || (d = window.event);
                    return c.call(a, d)
                }
            },
            z = "undefined" != typeof navigator && /Macintosh/.test(navigator.userAgent),
            E = function() {
                this._mouseEventsPrevented = !0
            };
        var F = function(a) {
                this.g = a;
                this.h = []
            },
            G = function(a) {
                for (var c = 0; c < a.h.length; ++c) {
                    var d = a.g,
                        b = a.h[c];
                    d.removeEventListener ? d.removeEventListener(b.eventType, b.s, b.capture) : d.detachEvent && d.detachEvent("on" + b.eventType, b.s)
                }
                a.h = []
            };
        var H = e._jsa || {};
        H._cfc = void 0;
        H._aeh = void 0;
        var I = function() {
                this.h = this.g = null
            },
            K = function(a, c) {
                var d = J;
                d.g = a;
                d.h = c;
                return d
            };
        I.prototype.i = function() {
            var a = this.g;
            this.g && this.g != this.h ? this.g = this.g.__owner || this.g.parentNode : this.g = null;
            return a
        };
        var L = function() {
                var a;
                this.j = a = void 0 === a ? [] : a;
                this.g = 0;
                this.h = null;
                this.l = !1
            },
            N = function(a, c) {
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
                a != this.h && a && a.__owner && (this.l = !0, K(a.__owner, this.h));
                return a
            }
            return null
        };
        var J = new I,
            M = new L;
        var Q = function() {
                this.v = [];
                this.g = [];
                this.h = [];
                this.l = {};
                this.i = null;
                this.j = [];
                P(this, "_custom")
            },
            R = function(a) {
                return String.prototype.trim ? a.trim() : a.replace(/^\s+/, "").replace(/\s+$/, "")
            },
            ia = function(a, c) {
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
                    for (var r; r = aa.i();) {
                        var h = r;
                        var p = void 0;
                        r = h;
                        var q = k,
                            ba = b;
                        var n = r.__jsaction;
                        if (!n) {
                            var x;
                            n = null;
                            "getAttribute" in r && (n = r.getAttribute("jsaction"));
                            if (x = n) {
                                n = f[x];
                                if (!n) {
                                    n = {};
                                    for (var A = x.split(ca), da = A ? A.length : 0, B = 0; B < da; B++) {
                                        var v = A[B];
                                        if (v) {
                                            var C = v.indexOf(":"),
                                                O = -1 != C,
                                                fa = O ? R(v.substr(0, C)) : ea;
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
                        "maybe_click" == q && n.click ? (p = q, q = "click") : "clickkey" == q ? q = "click" : "click" != q || n.click || (q = "clickonly");
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
                            if (u = b.relatedTarget, !("mouseover" == b.type && "mouseenter" == k || "mouseout" == b.type && "mouseleave" == k ||
                            "pointerover" == b.type && "pointerenter" == k || "pointerout" == b.type && "pointerleave" == k) || u && (u === h || w(h, u)))
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
                    a.i && !h.event.a11ysgd && (t = S(h.eventType, h.event, h.targetElement, h.action, h.actionElement, h.timeStamp), "clickonly" == t.eventType && (t.eventType = "click"), a.i(t, !0));
                    if (h.actionElement || "maybe_click" == h.eventType) {
                        if (a.i) {
                            if (!h.actionElement || "A" != h.actionElement.tagName || "click" != h.eventType && "clickmod" != h.eventType || (b.preventDefault ? b.preventDefault() : b.returnValue = !1), (b = a.i(h)) && g) {
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
                        H._aeh &&
                        H._aeh(h)
                    }
                }
            },
            S = function(a, c, d, b, g, m) {
                return {
                    eventType: a,
                    event: c,
                    targetElement: d,
                    action: b,
                    actionElement: g,
                    timeStamp: m || Date.now()
                }
            },
            ja = function(a, c) {
                return function(d) {
                    var b = a,
                        g = c,
                        m = !1;
                    "mouseenter" == b ? b = "mouseover" : "mouseleave" == b ? b = "mouseout" : "pointerenter" == b ? b = "pointerover" : "pointerleave" == b && (b = "pointerout");
                    if (d.addEventListener) {
                        if ("focus" == b || "blur" == b || "error" == b || "load" == b || "toggle" == b)
                            m = !0;
                        d.addEventListener(b, g, m)
                    } else
                        d.attachEvent && ("focus" == b ? b = "focusin" : "blur" == b && (b = "focusout"), g = y(d, g), d.attachEvent("on" + b, g));
                    return {
                        eventType: b,
                        s: g,
                        capture: m
                    }
                }
            },
            P = function(a, c) {
                if (!a.l.hasOwnProperty(c)) {
                    var d = ia(a, c),
                        b = ja(c, d);
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
        };
        var W = function(a, c) {
                var d = new F(c);
                a:
                {
                    for (var b = 0; b < a.g.length; b++)
                        if (T(a.g[b].g, c)) {
                            c = !0;
                            break a
                        }
                    c = !1
                }if (c)
                    return a.h.push(d), d;
                U(a, d);
                a.g.push(d);
                V(a);
                return d
            },
            V = function(a) {
                for (var c = a.h.concat(a.g), d = [], b = [], g = 0; g < a.g.length; ++g) {
                    var m = a.g[g];
                    X(m, c) ? (d.push(m), G(m)) : b.push(m)
                }
                for (g = 0; g < a.h.length; ++g)
                    m = a.h[g],
                    X(m, c) ? d.push(m) : (b.push(m), U(a, m));
                a.g = b;
                a.h = d
            },
            U = function(a, c) {
                var d = c.g;
                ka && (d.style.cursor = "pointer");
                for (d = 0; d < a.v.length; ++d)
                    c.h.push(a.v[d].call(null, c.g))
            },
            Y = function(a, c) {
                a.i = c;
                a.j && (0 < a.j.length && c(a.j), a.j = null)
            },
            X = function(a, c) {
                for (var d = 0; d < c.length; ++d)
                    if (c[d].g != a.g && T(c[d].g, a.g))
                        return !0;
                return !1
            },
            T = function(a, c) {
                for (; a != c && c.parentNode;)
                    c = c.parentNode;
                return a == c
            },
            ka = "undefined" != typeof navigator && /iPhone|iPad|iPod/.test(navigator.userAgent),
            ca = /\s*;\s*/,
            ea = "click",
            ha = {};
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
        P(Z, "copy");</body>

</html>
