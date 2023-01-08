Customizing the HAProxy Logs

There are plenty of reasons why you might want to customize the fields captured by the HAProxy logs. For example :

the default log format is giving you more information that you need

you’re missing an important piece of information with the default log format
you need to structure the fields in a way that an external tool can read them
you rely on a standard log format and HAProxy must also comply


At the moment, the default HTTP format is defined this way :

    log-format "%ci:%cp [%tr] %ft %b/%s %TR/%Tw/%Tc/%Tr/%Ta %ST %B %CC \
                %CS %tsc %ac/%fc/%bc/%sc/%rc %sq/%bq %hr %hs %{+Q}r"
            
            
 
                

    https://www.haproxy.com/blog/haproxy-log-customization/
