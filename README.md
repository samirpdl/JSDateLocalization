# JSDateLocalization

    d = new Date();
    d.setUTCFullYear(2004);
    d.setUTCMonth(1);
    d.setUTCDate(29);
    d.setUTCHours(2);
    d.setUTCMinutes(45);
    d.setUTCSeconds(26);
    alert(d);                        // -> Sat Feb 28 2004 23:45:26 GMT-0300 (BRT)
    alert(d.toLocaleString());       // -> Sat Feb 28 23:45:26 2004
    alert(d.toLocaleDateString());   // -> 02/28/2004
    alert(d.toLocaleTimeString());   // -> 23:45:26
