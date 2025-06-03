# K0XX - torrc generater
K0XX is a Python script that generates a torrc file configured to route traffic through a specified country. Its standout feature is the ability to automatically exclude all countries except the one(s) you choose. By blocking all undesired countries at once, K0XX reduces the risk of unintended routing and simplifies the otherwise tedious process of configuring Tor circuits.

# How To Use
## k0xx-repl

```bash

~ :% k0xx-repl.py
Enter entry countries (space-separated, e.g., 'SG'): SG
Enter include countries (space-separated, e.g., 'SG TH HU AL IN MX BR'): AT
Enter exit countries (space-separated, e.g., 'SG TH HU AL IN MX BR'): JP
Enter forbidden countries (space-separated, press Enter for none):
StrictNodes 1
ExcludeNodes {ec},{fr},{be},{gi},{ki},{yt},{to},{lr},{gb},{as},{bg},{gn},{gp},{kr},{bo},{nu},{pa},{sr},{ua},{gf},{cd},{kw},{na},{no},{jo},{ms},{sc},{tk},{sy},{cw},{pk},{io},{bf},{au},{bt},{uy},{fk},{cn},{dj},{ky},{bv},{tw},{ye},{mo},{jm},{ws},{cr},{bz},{ai},{im},{me},{do},{sb},{by},{sa},{tn},{mg},{mt},{cc},{nc},{la},{my},{ir},{va},{lv},{mh},{kz},{sv},{km},{rw},{wf},{aq},{bd},{lb},{cm},{cl},{cg},{bl},{nf},{za},{pw},{mn},{ma},{bs},{vg},{mm},{tl},{kh},{md},{ba},{sl},{pg},{kn},{dz},{tf},{gw},{ni},{np},{sk},{gg},{id},{sx},{er},{ck},{ly},{mq},{pr},{st},{cf},{ga},{vi},{is},{ph},{cy},{sh},{gr},{py},{gu},{je},{lu},{cz},{ug},{lt},{gq},{sd},{ml},{in},{mz},{ae},{ke},{mx},{ch},{vn},{ag},{gt},{bn},{lc},{iq},{tc},{qa},{sz},{bh},{ao},{mf},{tt},{fj},{rs},{tj},{ar},{hk},{de},{uz},{ss},{pe},{pf},{gd},{vu},{af},{gl},{mr},{us},{re},{mu},{se},{az},{bi},{ps},{es},{ru},{li},{pn},{ht},{om},{mw},{co},{eg},{am},{gh},{nz},{ng},{ax},{tr},{dk},{mc},{gy},{fi},{tv},{ls},{it},{sm},{kg},{zw},{al},{cu},{mp},{kp},{si},{eh},{br},{pm},{sn},{ci},{zm},{mk},{ee},{ie},{pl},{lk},{ro},{bj},{hu},{ne},{nr},{gs},{so},{fo},{tm},{cv},{et},{il},{hn},{ad},{dm},{hr},{bq},{sj},{tg},{vc},{fm},{gm},{bm},{bb},{th},{ca},{mv},{td},{aw},{nl},{pt},{bw},{ge},{um},{ve},{cx},{hm},{tz}
EntryNodes {sg}
ExitNodes {jp}

```
