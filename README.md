# cs4150-lab-9-ip-fragmentation-and-checksum-solved
**TO GET THIS SOLUTION VISIT:** [CS4150 Lab 9-IP Fragmentation and Checksum Solved](https://www.ankitcodinghub.com/product/cs4150-lab-9-ip-fragmentation-and-checksum-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94568&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS4150 Lab 9-IP Fragmentation and Checksum Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
(IP Fragmentation and Checksum)

</div>
</div>
<div class="layoutArea">
<div class="column">
1. You are given a virtual network with three hosts h1 (192.168.1.2), r1, and r2 (192.168.101.2).

r1 has two interfaces with IPs 192.168.1.1 and 192.168.101.1, and acts as a router between h1

and r2. Let x be the MTU between r1 and r2. Find the value of x and report the approach

that you used to discover it. Hint: use the tool hping3 installed on h1. Make sure to always

use the -V flag with hping3. [40]

<ol start="2">
<li>Given the value of x from the above questions, the password for r1 is user@x. Using this password, download the file ipfrags.tar.xz from r1 and extract it on your host machine.

The extracted folder contains 540 IPv4 fragments, of which only 54 are legitimate. Use the

IPv4 header checksum to weed out fragments with errors. Print the header details for all the legitimate packets.</li>
<li>Assemblethe54legitimateIPv4fragmentsusingthefragmentflagandfragmentoffsetinformation contained in the IPv4 header. How many IPv4 packet did you obtain after the assembly? What

are the sizes of these packets? What is the message contained within these packets?

Use the following structure to parse IPv4 packets that are stored as files.

<pre>  typedef struct IPPacket_t {
   unsigned char v_hl;
   unsigned char dscp_ecn;
   unsigned short int totalLen;
   unsigned short int id;
   unsigned short int flags_frag_offset;
   unsigned char ttl;
</pre>
<pre>   unsigned char proto;
   unsigned short int checksum;
   unsigned char sAddr[4];
   unsigned char dAddr[4];
   unsigned int o1;
   unsigned int o2;
   unsigned char data[1024];
</pre>
} IPPacket;
</li>
</ol>
</div>
</div>
</div>
