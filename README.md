 <script>
        (function(d,t) {
          var g=d.createElement(t),s=d.getElementsByTagName(t)[0];
          g.src="https://test.ca.digital-front-door.stg.gcp.trchq.com/embed.js"
          s.parentNode.insertBefore(g,s);
          g.onload=function(){
            new window.VirtualCareMessengerEncrypted({
              domain: 'https://test.ca.digital-front-door.stg.gcp.trchq.com',
              ws:  'wss://test.ca.digital-front-door.stg.gcp.trchq.com/cable',
              app_id: "D2p3uNwqDtu7pknnG5WAZB6Q",
              data: "YOUR_ENCRYPTED_JWE_DATA",
              lang: "USER_LANG_OR_DEFAULTS_TO_BROWSER_LANG" 
            })
          }
        })(document,"script");
      </script>
