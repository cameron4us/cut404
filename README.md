Welcome to the Cut404 REST API docs page.

Tired of the same plain and ugly 404 page? 
Why not use our badass Cut404 page that is sure to turn heads.

Cut404 is a simple framework that will contruct a custom 404 page.


USAGE

When wanting to implement Cut404 into your own project:

1. Be sure to place the following to use the custom 404 page and content types:

    const Constructor = require('Cut404');
    var con = new Constructor();

    con.four04(res); 
    con.writeHeadHTML(res); 
    con.writeHeadPLAIN(res);
    con.writeHeadJSON(res);

# con.four04(res)
    This function is the main feature of Cut404. This will reference to a custom
    404 Page. This feature removes clutter of typing typical 404 response and 
    presents a readable 404 response to user.

# con.writeHeadHTML(res)
    This function removes clutter of typing the following:
    res.writeHead(200, {'Content-Type': 'text/html'});
    Obviously saves space and is VERY readable.

# con.writeHeadPLAIN(res);
    This function removes clutter of typing the following:
    res.writeHead(200, {'Content-Type': 'text/html'});
    Again, it obviously saves space and is VERY readable.

# con.writeHeadJSON(res);
    This function removes clutter of typing the following:
    res.writeHead(200, {'Content-Type': 'text/html'});
    You already know the answer, it obviously saves space and is VERY readable.
    

last. To view our complete project with test, clone this repo: https://github.com/cut404/cut404


