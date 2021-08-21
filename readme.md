#dws-dev-006-bash
<p>
you can run commands with try by using this shell files. you need 
passing args to input. first app have a basic validation but I
cant spent more times for it. if you would like , you can send your
pull requests :)
</p>
<p>
you can use try_2 with env values too. you can define $TRY_INTERVAL, 
$TRY_NUMBER, $TRY_COMMAND, in system env values if you want.
</p>


###example of try_1
<pre>
    ./try_1 -i 1 -n 4 ping -c 1 google.com    (*successful)
    ./try_1 -i 1 -n 4 ping1 -c 1 google.com    (*error)
</pre>

###example of try_2
<pre>
    export TRY_INTERVAL=10
    ./try_2 -i 1 -n 4 ping -c 1 google.com    (*successful)
    ./try_2 -i 1 -n 4 ping1 -c 1 google.com    (*error)
</pre>



[@dwsclass](https://github.com/dwsclass) dws-dev-006-bash