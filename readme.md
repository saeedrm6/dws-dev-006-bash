#dws-dev-006-bash
<p>
you can run commands with ./try_1 and ./try_2. you need passing args to input. the first app has a basic validation but I cant spend more time on it. if you would like, you can send your
pull requests to get ./try_1 better:)
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