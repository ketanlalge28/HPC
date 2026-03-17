# Facets

### Introduction To Healthcare
- Health insurance is a type of insurance that covers medical expenses that arise due to an illness. These expenses could be related to hospitalization, cost of medicine or doctor fees.. 

- Protect ourselves from risk..

- #### Premium -- Fixed amount to be paid by SPONSOR to the Insurance Company.
- #### Insurance Company -- Payer/Health Plan/MCO (Managed Care Organization)
- #### Insurance Policy -- contract between Patient and the IC

## How do u choose the policy??

- list down the needs
- network of hospitals
- max amount of premium you can afford
- Sum Insured/Amount covered by the Insurance company

#### Service -- treatment 

 ### Max allowed amount -- maximum amount the insurance company will pay for a particular service

#### Example
- policy P1 -- Sum insured -- 3L (per year)

- 2nd month -- 1L -- IC will reimburse
- 5th month -- 2L -- IC will reimburse
- 9th month -- 50K -- IC will not reimburse 

Types of Policy
----------------
Individual Policy -- Member pays the premium, takes care of everything
Group Policy   --- Org/group pays the premium, takes care of everything
Govt Policy -- Govt pays the premium, decides the policy coverage

SPONSOR --> Entity who pays premium to the IC on behalf of the member

Subscriber -- Employee
Dependents -- Dependents of the Subscriber
Member -- Subscriber + Dependents

Provider -- Any entity who provides medical services to the members
Doctors/facility/hospital/lab/Rx...

Types of Transactions
-----------------------

Cashless transaction
	- Raise an authorization request to the Payor by Provider
	- Once approved with proof
	- Provider will raise a claim for all the covered services. Covered services will be paid by the IC
	- Non covered services/expenses need to be paid by the member.

CLAIM -- Process of raising the expenses incurred for medical services.

Cash transaction 
	- Member will get the treatment, pays full cost
	- After discharge, raise a claim request
	- If eligible, IC pays/reimburse to the member

- Inpatient -- Admitted in hospital with min of 24 hrs
Inpatient/Hospital/Facility/Institutional Claims

- Outpatient -- Treatment with member returning back home on the same day < 24 hrs
Outpatient/Medical/Professional Claims

Eligibility (w.r.t Claims)
---------------------------
- Member is active
- Member is enrolled in active policy
- Whether actual treatment was given or not
- Whether the treatment is covered or not
- Whether member already met Sum Insured
- Duplicate Claim or not

### Pre-existing Condition
-----------------------

- A condition for which the individual received medical care prior to the effective date of coverage.

- Before member joins the policy, if already they have an health issue and taking treatment, then for that condition treatment cost will not be covered.

### Policy P1 -- Covers heart disease (Pre-existing excluded)

- M1 - Joins the policy P1 on 1/1/2022
on 4/1/2022, for the first time he got some heart problem, heart problem will be covered. 

- M2 - Joins the Policy P1 on 1/1/2022, already has an heart problem and is under treatment from 2020
On 5/1/2022, member M2 has some heart issues, heart problem will not be covered.

- Network -- 	  Collection of Providers
- Network Group --  Collection of Networks
- Network Set --    Collection of Network Groups/Superset of all networks

CTS IND				-- Network Set
	NRNG
	  MUMNW
	  NOINW

	STNG			-- Network Group
	  CHNNW			-- Network
	    Apollo
	    Cauvery
	    Chettinad
	  BLRNW
	  HYDNW

In Network Providers -- Provider is in contract/tie up with the IC
Provider should be part of a Network to provider services to the members who belong to that particular network and enroll into policy.

Out of Network Providers -- Providers who are not in contract/ tie up with the IC

PCP (Primary Care Physician) -- gatekeeper/first point of contact

Provider Payment method
------------------------

FFS (Fee for Service) --Traditional method of Provider payment
			Provider gets paid for all the services
			Unnecessary treatment is provided
			HC is increased
			IC is loss

Capitation (Per member Per month) - Provider is paid on PMPM basis

Risk Sharing Arrangement -- risk is shared between the Provider and the IC

How many ever enrolled members are there for that month, for every enrolled member they get a fixed cost paid by the IC irrespective of whether the member gets the treatment or not

PMPM - $2000

Provider1

	Jan - 10 Enrolled members -- 10 * $2000 = $20000
        Feb - 15 Enrolled members -- 15 * $2000 = $30000

Jan -- 10 enrolled members

M1 - Health -- No visit
	IC pays $2000 to the Provider
	
	IC -- Loss of $2000
	Provider -- Profit of $2000

M2 - Health issue office visit -- $5000 worth treatment
	IC pays $2000 to the Provider

	IC - Profit of $3000
	Provider - Loss of $3000

TO increase the profit , the providers started focusing on Preventive and Wellness program...

Education
Vaccination
Diet
Camp
Counselling
Exercise/Yoga

Capitation is very useful for IC, as it tries to reduce the HC cost and also ensures good treatment to members.

Cost shifting  (how IC managed the loss)
	
### COB (Coordination of Benefit) -- Non duplication of Benefits
-------------------------------

Mom -- Add kid as a dependent -- Max allowed amount $6000
Dad -- Add kid as a dependent -- Max allowed amount $4000

kid gets a treatment -- $8000

Mom -- $6000
Dad -- $4000
      -------
       $10000 > $8000

Mom -- Add kid as a dependent -- Primary
Dad -- Add kid as a dependent -- Mom's policy is primary and Dad's is secondary

### With COB
--------
 Mom -- Lesser of (Cost, Max allowed amount)
     -- Lesser of ($8000, $6000)
     --- $6000

 Dad -- Lesser of (Diff, max allowed amount)
     -- Lesser of ($2000, $4000)
     -- $2000
	-----
	$8000 <= Actual treatment cost

kid gets a treatment -- $12000

 Mom -- Lesser of (Cost, Max allowed amount)
     -- Lesser of ($12000, $6000)
     --- $6000

 Dad -- Lesser of (Diff, max allowed amount)
     -- Lesser of ($6000, $4000)
     -- $4000

	-----
	$10000 <= Actual treatment cost

### PBM (Pharmacy Benefit Management)
