

<!DOCTYPE html>
<html>
<head>
  <!--
  <style>
    body {
      font-family: Arial, sans-serif;
      color: #333;
      margin: 0;
      padding: 0;
    }
  
    header {
      background-color: #0072C6;
      color: #FFF;
      padding: 20px;
      text-align: center;
      margin-bottom: 20px;
    }
    
    .highlight {
			background-color: #FCD116;
			padding: 3px 5px;
			border-radius: 3px;
		}
  
    h1 {
      font-size: 36px;
      margin: 0;
      line-height: 1.2;
    }
  </style>
  -->
</head>

</head>
<body>
	<header>
		<h1>Economic Impact of Internet Shutdowns in India</h1>
    <h3> 	June, 2022</h3>
	</header>
	<div class="container">
		<h2>Summary</h2>
		<p>India has been often referred as the capital of internet shutdown with having more than 500 complete shutdowns from 2013-21. The highest number being noted in the recent year 2020 itself when number of shutdowns reached 129 as per a report by (https://internetshutdowns.in). Some of the common shutdown in our recent memories include during the protests against the government in Kashmir, growing foreign propaganda during Farmers Protest, maintain peace during violence in the West Bengal Elections (Newslaundry,2021). The study aims to highlight the economic impact on state and its citizens as a result of internet shutdown.
</p>


<h3>What is Internet Shutdown</h3>

<p>According to Access now 2018, “An internet shutdown is an intentional disruption of Internet-based communications, rendering them inaccessible or effectively unavailable, for a specific population, location, or mode of access, often to exert control over the flow of information.” <p>

<h3>Gaps in existing regulation</h3>

Through analysis of secondary Data sources (Suspension of Telecom Services/Internet and Its impact, standing committee on C&IT 2021-22) and other sources, following gaps are identified in the present regulations governing Internet shutdown in India:
<ul>
  <li>No public consultation before enacting the Internet Shutdown law 2017</li>
  <li>Definition of Inevitable circumstance - clear definition of conditions in which Internet Shutdown can be imposed by the state</li>
  <li>Process of Review and power to reverse shutdown - No clear definition of process to be followed by review committee before and after imposing the internet shutdown</li>
  <li>Review period - No rationale of fixing review within 5 days of imposing shutdown</li>
  <li>Composition of Review committee - Non-inclusion of non-executive members in the review committee (Review is done by officials which are working under the same government)</li>
  <li>Redressal mechanism - No redressal mechanism to challenge internet shutdown</li>
  <li>Monetary compensation - No compensation for economic, social and psychological loss (TISP, Consumer, Platforms, startups etc.)</li>
</ul>

<h2>Approach of Regulatory Impact Analysis (StakeHolders)</h2>

<h3>Identification of the parties having economic impacts due to internet shutdown</h3>
		
<ul>
<li> Citizens (Infotainment, Education, Health etc.)</li>
<li> TISP (Telecom & Internet Service Providers)</li>
<li> E- Businesses (Press, OTT Services, e-Commerce platforms etc, eduTech, HealthTech, Startups etc.)</li>
  <li> State</li>
  </ul>

<h3>	Identification of independent variables leading to economic impacts</h3>

<ul>
  <li>Time of internet shutdown (Hours/Days)</li>
  <li> Cost of internet data (perGB/prepaid/postpaid)</li>
 <li>Number of Internet subscribers who are affected</li>
  <li>Geography of internet shutdown (Location/state) - per capita income</li>
  <li>Average data consumption per user in the location/state</li>
  <li>	Digital financial transactions in the state</li>
  </ul>

<h2> Benefit Cost Analysis</h2>
    <p> Check report for details</p>
<ul>
<li> Risk of maintaining the existing Internet shutdown regulation (Benefit to change the regulation)</li>
 <li> Risk of changing the existing Internet shutdown regulation (Cost to change the regulation)</li>
</ul>

<p>As per Top10VPN report[2], there were a total of 8927 hours of IS in India in 2020 and it has affected a total of 10.3 million population. This is taken as the basis for our calculation of economic impact.</p>
The 10 states selected for our analysis are as follows:
<ul>
  <li>Jammu and Kashmir</li>
  <li>Maharashtra</li>
  <li>West Bengal</li>
  <li>Andhra Pradesh</li>
  <li>Madhya Pradesh</li>
  <li>Uttar Pradesh</li>
  <li>Meghalaya</li>
  <li>Manipur</li>
  <li>Rajasthan</li>
  <li>Arunachal Pradesh</li>
</ul>

<h2>Datasets</h2>

<b>Telco Dataset</b>

<p>Objective - To calculate the economic loss (revenue) to Telecom Service Providers due to Internet Shutdown.</p>

<p>Assumption - Revenue loss due to wireless internet services (3G/4G) only considered. Fixed line broadband is not considered. Only revenue loss is calculated. Net loss is not calculated.</p>

<h3>Input Variables</h3>
<ul>
  <li>No Internet users in the affected state</li>
  <li>Average Data usage per user per month (in GigaBytes - GB) for the country</li>
  <li>Average Wireless Data revenue realization per GB for the country</li>
</ul>
<h3>Output</h3>
<ul>
  <li><div class="highlight"><p>Total Revenue realization by TSP per Hour (in Rs) in 2020 in each affected state=  <b>Rs. 67,329,676</b></li>
  <li><div class="highlight"><p>Total Revenue Loss to TSP in affected states due to Internet Shutdown in 2020 in USD = Rs. 154,136,440 / 75 = <b>$2,055,125.87</b></div> </li>
</ul>
<h3> Reference Calculations:</h3>
<ul>
  <li>
    Total data usage per month in 10 states in 2020 =<br>
    No of Internet users in 10 states * Average Data usage per user per month (in GigaBytes - GB) for the country<br>
    = 374.745 million * 11.76 GB
  </li>
<br>
  <li>
    Total Data Usage per Hour (GB) in 10 states in 2020 =<br>
    (Total data usage per month in 10 states * 10<sup>6</sup>) / (30 * 24)<br>
    = 6,180,233 GB
  </li>
<br>
  <li>
    Total Revenue realization per Hour (in Rs) in 2020 =<br>
    Total Data Usage per user per Hour (GB) in 10 states in 2020 * Average Wireless Data Revenue realization per GB for the country<br>
    = 6,180,233 GB * Rs. 10.93 = Rs. 67,329,676
  </li>
<br>
  <li>
    Total Revenue Loss to TSP in affected states due to Internet Shutdown in 2020 =<br>
    Total Revenue realization per Hour (in Rs) in 2020 * Hours of Internet Shutdown in 2020 * ratio of affected population to total internet users in affected states<br>
    = Rs. 67,329,676 * 8,927 * (10.3/374.745) = Rs. 154,136,440
  </li>
</ul>



	
<h2>dComm Dataset - Digital Commerce</h2>
<p>Objective - To calculate the economic loss (revenue) to Digital Platforms due to Internet shutdown.</p>

<p>Assumption - Majority of digital platforms and brick and mortar outlets provide PhonePe option for paying for goods and services. PhonePe is the market leader for digital financial transactions with pan India coverage. The volume and value of transactions on PhonePe reflects economic activities of digital platforms. The offline transactions such as Cash on delivery and direct cash transaction at outlets are not considered in the calculation. Only revenue loss is calculated. Net loss is not calculated.</p>

<h3>Input variables:</h3>
<ul>
  <li>No Transaction Per Hour in 2020</li>
  <li>Value of The Transaction Per Hour (Rs) in 2020</li>
</ul>
<h3>Output:</h3>
<ul>
  <li>Total value of Digital Transaction Per Hour in affected States in 2020 = <strong>77 Cr</strong></li>
  <li>Total Revenue Loss to Digital Commerce in affected states due to Internet Shutdown in 2020= <strong>2.53 Billion</strong></li>
</ul>
<h3>Reference Calculations:</h3>
<ul>
  <li>Total value of Digital Transaction Per Hour in affected States in 2020 = Sum of Value of Transaction per Hour (Rs) in 2020 of each state =<br> <strong>77 Cr</strong></li><br>
  <li>Total Revenue Loss to Digital Commerce in affected states due to Internet Shutdown in 2020 =<br> Total value of Digital Transaction Per Hour in affected States (in Rs) in 2020 * Hours of Internet Shutdown in 2020 * ratio of affected population to total internet users in affected states =<br> 77 cr * 8927 * (10.3/374.745) = <strong>2.53 Billion</strong> USD (1 USD = 75 INR)</li>
</ul>

		
<h2>State GDP Data from RBI</h2>

<p>Objective: To calculate the economic loss (net) to state GDP due to Internet Shutdown.</p>

<p>Assumption: State GDP is the cumulation of multiple factors representing the formal and informal sectors and activities. In our calculation, we have considered the contribution of the Digital economy on state GDP. The contribution of the Digital economy on the country's GDP was 7.7% in 2020.</p>

<h3>Input variables:</h3>
<ul>
  <li>State GDP per capita in Rs in 2020</li>
  <li>State Population in 2020</li>
</ul>
<h3>Output:</h3>
<ul>
  <li>Total state GDP Per Hour in affected States in 2020 = 924.86 Cr.</li>
  <li>Total Net GDP loss due to Internet Shutdown in 2020 = $ 1.25 Billion</li>
</ul>
<h3>Calculation:</h3>
<ul>
    <li>
        Total state GDP Per Hour in affected States in 2020 =  
        <br>
        (State GDP per capita in Rs in 2020 * State Population in 2020)/ (365*24) 
        <br>
        = 924.86 Cr.
    </li>
    <li>
        Total Net GDP loss due to Internet Shutdown in 2020 = 
        <br>
        Total state GDP Per Hour in affected States in 2020 * Hours of Internet Shutdown in 2020 * ratio of affected population to total population in affected states 
        <br>
        = 924.86 cr * 8927 hour * (10.3/701) 
        <br>
        1 US Dollar = 75 INR (2020) 
        <br>
        = $ 1.25 Billion
    </li>
</ul>
<h2> Key Findings</h2>
		<p>After conducting the economic impact analysis, the following key findings were discovered:</p>


<ul>
<li><b>The economic loss to Telecom Service Providers due to internet shutdowns in the 10 states analyzed amounted to  INR 454 crore (approximately USD 60.5 million) in 2020</b>. The loss was the highest in Jammu and Kashmir at INR 151 crore (approximately USD 20.1 million). </li>

<li> <b>The economic loss to E-Businesses due to internet shutdowns in the 10 states analyzed amounted to INR 217 crore (approximately USD 29 million) in 2020</b>. The loss was the highest in Maharashtra at INR 52 crore (approximately USD 6.9 million).</li>
		</ul>

<h2>Loss to Citizens</h2>

<p>The economic loss to citizens due to internet shutdowns in the 10 states analyzed amounted to INR 47,065 crore (approximately USD 6.3 billion) in 2020. The loss was the highest in Uttar Pradesh at INR 11,656 crore (approximately USD 1.5 billion).</p>

<h2>Recommendations</h2>
		<ul>
			<li><span class="bold">Establishment of an independent review committee:</span> A committee should be established to review the necessity of internet shutdowns and ensure that they are proportionate and in accordance with the law.</li>
			<li><span class="bold">Provision for public consultation:</span> The public should be given an opportunity to provide feedback on any proposed internet shutdowns.</li>
			<li><span class="bold">Monetary compensation:</span> Citizens and businesses affected by internet shutdowns should be provided with appropriate compensation.</li>
			<li><span class="bold">Redressal mechanism:</span> A redressal mechanism should be put in place to address the negative effects of internet shutdowns on citizens and businesses.</li>
		</ul>
		<p>Overall, these recommendations aim to balance the need for internet shutdowns with the need to protect the rights of citizens and businesses. They will help ensure that any internet shutdowns in

<h2>Conclusion</h2>
<ul>
<li>The economic impact analysis of internet shutdowns in India revealed the negative effects of such shutdowns on Telecom Service Providers, E-Businesses, and citizens. </li><li>The loss to citizens was the highest, indicating the need for regulatory intervention to address the gaps in the current regulations governing internet shutdowns.</li> <li>The study recommends the establishment of an independent review committee, provision for public consultation, monetary compensation, and a redressal mechanism to address the negative effects of internet shutdowns.</li>
		</ul>
