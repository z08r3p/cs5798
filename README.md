java c
ELEC ENG 3108 Telecommunications Principles 
Assignment 1: Telephony
Due 5pm on   Monday   28 August   2023. This assignment   is worth   20   or   30%   of your   final   grade.
Submission   is via   MyUni.
What to   submit
•          Your   working   and   results
•          30% of your   marks will   be   allocated   to   discussion,   insight   and   original   experimentation   or
analysis. Your   report   is expected to   be written to a   professional   standard   and   show   original   critical   insight.
Question 1: Intelligent Network Implementation (20%) 
A Vodafone   pre-paid customer   is about to   initiate a   phone   call   on the Vodafone   GSM   network   to   a   friend on the Telstra GSM   network.
•             Vodafone   pre-paid services are   handled   by the   Intelligent   Network   platform. Briefly   list the   major steps   involved   in setting   up the call to the Telstra   GSM   network,   assuming the customer   has sufficient credit and the friend   is   available and   answers.
•             Explain why   pre-paid   customers   cannot   (usually)   roam,   and suggest   a   mechanism   by   which   pre-paid   roaming could   be achieved.
Vodafone’s   pre-paid customers were   previously   handled   by a Service   Node. In this   case,   prepaid   call   traffic was   routed through a separate switch, which   would   monitor   calls   and   take   action   when   credit   was   no   longer available. 37% of Vodafone’s   2.2   million customers   are   now   pre-paid,   accounting   for         25% of   busy   hour traffic   (20   mErlang/subscriber).
•             If each   MSC   and   pre-paid   switch   can   handle 4,000   Erlangs   of   traffic,   calculate   the   additional   number of switches   required to   handle the current   pre-paid customers   using   the   Service
Node Architecture, versus   using the   Intelligent   Network scheme
Question 2: Hata-Okumura Model (40%) 
Find a   reliable standards document written after   1998   which   specifies   which   radio   frequencies   are   specified for operating a GSM   radio access   network,   and   summarise   the   frequency   bands.
Now consult the Australian Communications and   Media Authority website   to   identify   how   these bands are allocated and whether they   are   currently   configured for   GSM.   Summarise   your   findings.
Create a function   (Matlab,   Excel,   Python – your choice) which   implements the   Hata-Okumura   model.   Explore the   path   loss   behaviour of the   uplink and downlink   spectrum   bands,   against   a   range   of antenna   heights   (base station and   mobile station).
Your function, or functions, should determine the   path   loss   at   a   given   distance,   and   maximum   coverage distance given a   link   budget.
Question 3: GSM Network Dimensioning (40%) GSM-R   is   a variant   of the   popular   GSM   standard with   specific   changes   to   accommodate   the needs of communication   for   railway    operations. The only difference of interest in this   question is that GSM-R may operate at radio frequencies   outside the spectrum   normally allocated for   public telephone   services.

Your task   is to   prepare a   radio   network   plan for a   railway   network consisting   of:
•          A   metropolitan   area   of   1000   km2    which   requires   extensive   coverage.
•          4000   km   of   railway   track   in   country   areas   代 写ELEC ENG 3108 Telecommunications Principles Assignment 1: TelephonyPython
代做程序编程语言in   a   roughly   circular   layout. There   are   150   country   towns which are spaced   between   15km and   30km apart   along   the   track. There is no requirement for area coverage in the country.
Radio standard:
•             FDMA carriers of   bandwidth   200kHz.
•            8 timeslots   per   FDMA carrier
•            Only one common channel   is   required   per   sector.
•             Frequency   reuse   plan:    3/9 with   no overlay for the   metropolitan   area   only
•             In the country areas, a cell   reuse   distance   equal   to   the   coverage   distance   of   three
intermediate cells   is   required. Each country   base   station   consists   of two   long-distance   high   gain antennas,   pointing along the   railway   line.
Coverage characteristics
•            Very   uniform. flat   urban city
•          Country   areas   are   mountainous   and   path   loss   should   be   assumed   to   be   equivalent   to   an   urban   city.
•          Antenna   height   is   fixed   at   30m   in   the   city   and   200m   for   all   country   areas
•             In the city, there are   200 trains.      Each train generates   3.0   erlangs   of   traffic.      All   trains   are   running   between 5pm and   6pm.
•             In the country, there   are a total   of   10   trains.      Each   train   generates   a   total   of   1.0   erlangs   of   traffic.    98% of the time,   no   more than   2 trains are   within   35km   of   each   other.
Grade of Service of 2% with   mobility   derating   factor   2.2   in   the   city   only.

City Base Station 
Country Base Station 
Mobile Station 
Transmitter 
Transmission power (includes losses) 
125W 
150W 
8W 
Antenna Gain 
13dBi 
17dBi 
0dBi 
Receiver 
Minimum Receive Power (does not include antenna gain) 
-100dBm 
-100dBm 
-100dBm 
Antenna Gain 
13dBi 
17dBi 
0dBi 
Shadow Margin 
10dB 
10dB 
10dB 
You   have the following choices of   radio frequencies, as   specified   in the   GSM   standard. Determine   which spectrum   band   is the   most suitable for   the entire   network   (you   might   need to   answer   this question after considering the following questions considering   both   options):
i.                                  450MHz   band   (paired   3.6MHz   available)
•                Downlink   460.5MHz-464.1MHz
•                Uplink   450.5MHz-454.1MHz
ii.                               850MHz   band   (paired   10.8MHz   available)
•                Downlink   869.1MHz-879.9MHz
•                Uplink   824.1MHz-834.9MHz
Using the   Hata   path   loss   model, calculate the   maximum coverage distance   in the   city   and   the   country. Assume a(hm) = 0 and   be sure to justify why the   uplink   determines   the   cell   size.
Hence, calculate   how   many   base stations are   required for coverage   of   the   rural   railway   tracks.
Is   it   necessary to consider capacity   in country areas?      Explain   your   answer
Calculate   how   many   base stations are   required for   coverage of the   city
Calculate the   number of traffic channels available   per cell   in   the   city,   assuming   all   available   spectrum   is   uniformly   utilised.
Hence, determine the   number of   base stations   required   in the   city   area for   capacity.







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
