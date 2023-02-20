# Economic_Impact_Analysis

<!DOCTYPE html>
<html>
<head>
	<title>Economic Impact of Internet Shutdowns in India</title>
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

		h1 {
			font-size: 36px;
			margin: 0;
			line-height: 1.2;
		}

		h2 {
			font-size: 24px;
			margin-top: 40px;
			margin-bottom: 20px;
			line-height: 1.2;
		}

		p {
			font-size: 16px;
			line-height: 1.5;
			margin-bottom: 20px;
		}

		.container {
			max-width: 800px;
			margin: 0 auto;
			padding: 0 20px;
		}

		ul {
			margin-bottom: 20px;
		}

		li {
			margin-bottom: 10px;
		}

		.bold {
			font-weight: bold;
		}

		.highlight {
			background-color: #FCD116;
			padding: 3px 5px;
			border-radius: 3px;
		}

	
		.btn:hover {
			background-color: #3E8E41;
		}
	</style>
</head>
<body>
	<header>
		<h1>Economic Impact of Internet Shutdowns in India By Vinayak and Sandeep</h1>
    <h3> 	June, 2022</h3>
	</header>
	<div class="container">
		<h2>Summary</h2>
		<p>India has been often referred as the capital of internet shutdown with having more than 500 complete shutdowns from 2013-21. The highest number being noted in the recent year 2020 itself when number of shutdowns reached 129 as per a report by (https://internetshutdowns.in). Some of the common shutdown in our recent memories include during the protests against the government in Kashmir, growing foreign propaganda during Farmers Protest, maintain peace during violence in the West Bengal Elections (Newslaundry,2021). 
</p>


    <h2>	Introduction </h2>


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

<h3>Approach of Regulatory Impact Analysis (StakeHolders)</h3>

Identification of the parties having economic impacts due to internet shutdown
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
  <ll> Risk of changing the existing Internet shutdown regulation (Cost to change the regulation)</li>
</ul>

<p>As per Top10VPN report[2], there were a total of 8927 hours of IS in India in 2020 and it has affected a total of 10.3 million population. This is taken as the basis for our calculation of economic impact.</p>
The 10 states selected for our analysis are as follows:
<ol>
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
</ol>

<h3>Datasets</h3>

<h4>Calculating Economic Impact</h4>

<b>Telco Dataset</b>

<p>Objective - To calculate the economic loss (revenue) to Telecom Service Providers due to Internet Shutdown.</p>

<p>Assumption - Revenue loss due to wireless internet services (3G/4G) only considered. Fixed line broadband is not considered. Only revenue loss is calculated. Net loss is not calculated.</p>

Input Variables - Given the following variables from the dataset:
1.	No Internet users in the affected state
2.	Average Data usage per user per month (in GigaBytes - GB) for the country
3.	Average Wireless Data revenue realization per GB for the country

Output:

1.	Total Revenue realization by TSP per Hour (in Rs) in 2020 in each affected state
2.	Total Revenue Loss to TSP in affected states due to Internet Shutdown in 2020

Calculation: 

1.	Total data usage per month in 10 states in 2020 = 
2.	Total Data Usage per Hour (GB) in 10 states in 2020 = 
3.	Total Revenue realization per Hour (in Rs) in 2020 = 
4.	Total Revenue Loss to TSP in affected states due to Internet Shutdown in 2020 = 

5.2	dComm Dataset - Digital Commerce

Objective - To calculate the economic loss (revenue) to Digital Platforms due to Internet shutdown.

Assumption - Majority of digital platforms and brick and mortar outlets provide PhonePe option for paying for goods and services. PhonePe is the market leader for digital financial transactions with pan India coverage. The volume and value of transactions on PhonePe reflects economic activities of digital platforms. The offline transactions such as Cash on delivery and direct cash transaction at outlets are not considered in the calculation. Only revenue loss is calculated. Net loss is not calculated.

Input variables: 

Given the following variables from the dataset:
1.	No Transaction Per Hour in 2020
2.	Value of The Transaction Per Hour (Rs) in 2020

Output: 

1.	Total value of Digital Transaction Per Hour in affected States in 2020
2.	Total Revenue Loss to Digital Commerce in affected states due to Internet Shutdown in 2020 

Calculations:

1.	Total value of Digital Transaction Per Hour in affected States in 2020 = 
2.	Total Revenue Loss to Digital Commerce in affected states due to Internet Shutdown in 2020 = 

5.3	State GDP Data from RBI

    <p>Objective: To calculate the economic loss (net) to state GDP due to Internet Shutdown.</p>

<p>Assumption: State GDP is the cumulation of multiple factors representing the formal and informal sectors and activities. In our calculation, we have considered the contribution of the Digital economy on state GDP. The contribution of the Digital economy on the country's GDP was 7.7% in 2020.</p>

Input variables: 

Given the following variables from the dataset:
1.	State GDP per capita in Rs in 2020
2.	State Population in 2020

Output:

1.	Total state GDP Per Hour in affected States in 2020
2.	Total Net GDP loss due to Internet Shutdown in 2020 

Calculation:

1.	Total state GDP Per Hour in affected States in 2020 = 
2.	Total Net GDP loss due to Internet Shutdown in 2020 = 


6) Key Findings
After conducting the economic impact analysis, the following key findings were discovered:

6.1 Loss to Telecom Service Providers

The economic loss to Telecom Service Providers due to internet shutdowns in the 10 states analyzed amounted to  INR 454 crore (approximately USD 60.5 million) in 2020. The loss was the highest in Jammu and Kashmir at INR 151 crore (approximately USD 20.1 million).

6.2 Loss to E-Businesses

<p>The economic loss to E-Businesses due to internet shutdowns in the 10 states analyzed amounted to INR 217 crore (approximately USD 29 million) in 2020. The loss was the highest in Maharashtra at INR 52 crore (approximately USD 6.9 million).

6.3 Loss to Citizens

The economic loss to citizens due to internet shutdowns in the 10 states analyzed amounted to INR 47,065 crore (approximately USD 6.3 billion) in 2020. The loss was the highest in Uttar Pradesh at INR 11,656 crore (approximately USD 1.5 billion).

<h2>Recommendations</h2>
		<ul>
			<li><span class="bold">Establishment of an independent review committee:</span> A committee should be established to review the necessity of internet shutdowns and ensure that they are proportionate and in accordance with the law.</li>
			<li><span class="bold">Provision for public consultation:</span> The public should be given an opportunity to provide feedback on any proposed internet shutdowns.</li>
			<li><span class="bold">Monetary compensation:</span> Citizens and businesses affected by internet shutdowns should be provided with appropriate compensation.</li>
			<li><span class="bold">Redressal mechanism:</span> A redressal mechanism should be put in place to address the negative effects of internet shutdowns on citizens and businesses.</li>
		</ul>
		<p>Overall, these recommendations aim to balance the need for internet shutdowns with the need to protect the rights of citizens and businesses. They will help ensure that any internet shutdowns in

7) Conclusion

  The economic impact analysis of internet shutdowns in India revealed the negative effects of such shutdowns on Telecom Service Providers, E-Businesses, and citizens. The loss to citizens was the highest, indicating the need for regulatory intervention to address the gaps in the current regulations governing internet shutdowns. The study recommends the establishment of an independent review committee, provision for public consultation, monetary compensation, and a redressal mechanism to address the negative effects of internet shutdowns.

		

