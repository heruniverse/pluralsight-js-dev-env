# pluralsight-js-dev-env
Javascript development
var localtunnel = require('localtunnel');
 
var tunnel = localtunnel(port, function(err, tunnel) {
    if (err) ...
 
    // the assigned public url for your tunnel
    // i.e. https:https://orange-lionfish-74.localtunnel.me/
    tunnel.url;
});
 
tunnel.on('close', function() {
    // tunnels are closed
});
