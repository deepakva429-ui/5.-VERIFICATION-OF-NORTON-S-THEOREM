# 5.VERIFICATION-OF-NORTON-S-THEOREM

**AIM:**

To verify Norton’s theorem practically and theoretically for the given DC circuit.

**APPARATUS REQUIRED:**

1.	Regulated Power supply ( RPS)	(0-30 V)	1
2.	Voltmeter	(0-30 V) MC	1
3.	Ammeter	( 0 - 10 mA) MC	1
4.	Resistors	470 Ω 560 Ω 1 K Ω	2 1 1
5.	Bread board	---	1
6.	Multimeter	---	1

**THEORY:**

**NORTON’S THEOREM:**

Norton’s theorem states that, ‘a linear two-terminal circuit can be replaced by an equivalent circuit consisting of a current source, IN (=Isc) in parallel with a resistor RN (= RTh), where IN (=Isc) is the short-circuit current through the load terminals and RN is the equivalent resistance at the load terminals when the independent sources are turned off.Norton’s Current, IN or Isc:
It is the short-circuit current through the load terminals. i.e., IN = Isc

Norton’s Resistance, RN:It is the look-back resistance across the load terminals when all the sources are replaced by their internal resistances. An ideal voltage source is replaced by short- circuiting as its internal resistance is zero. An ideal current source is replaced by open- circuiting as its internal resistance is infinity.
 
**CIRCUIT DIAGRAM: VERIFICATION OF NORTON’S THEOREM**

**To measure IL**
<img width="1600" height="909" alt="image" src="https://github.com/user-attachments/assets/2e03e635-dfa7-47d3-aea8-f35142c3287f" />

**To measure RTh or RN**
<img width="1600" height="743" alt="image" src="https://github.com/user-attachments/assets/5e532839-d2b1-4ad1-8057-329fb18b5152" />

**To measure IN or Isc**
<img width="1600" height="1027" alt="image" src="https://github.com/user-attachments/assets/ab9f6589-aa86-4117-930a-fa322a774c29" />
 
**Thevenin’s equivalent circuit**
<img width="1600" height="657" alt="image" src="https://github.com/user-attachments/assets/fb5ffd01-c0e0-4d3c-bdee-b9757b51ea4f" />

**Norton’s equivalent circuit**
<img width="1600" height="662" alt="image" src="https://github.com/user-attachments/assets/10f6c02f-9a87-4e6d-9f34-e7f55a5f1a28" />


**PROCEDURE:**

1.	Make the connections as per the Circuit Diagram:1

2.	Vary the RPS and set an input voltage of 10V.

3.	Note down the voltmeter reading (Vi) and ammeter reading (IL) in Tabular Column 1.

4.	Switch off the supply and make connections for Circuit Diagram 2.

5.	Measure the Thevenin’s resistance RTh= Norton’s resistance RN .

6.	Switch off the supply and make connections for Circuit Diagram:3.

7.	Set an input voltage of 10V in the RPS and note down the voltmeter readings Vi and VTh(=Voc) in Tabular Column:3

8.	Switch off the supply and make connections for Circuit Diagram 4.

9.	Set an input voltage of 10V in the RPS and note down the voltmeter reading Vi and Ammeter reading IN (= Isc) in Tabular Column 4.

10.	Draw the Thevenin’s equivalent circuit and Nortons’s equivalent circuit as shown in circuit diagrams 5 & 6 respectively.

11.	Calculate the IL value using the formula

   	Thevenin’s Theorem IL = VTh/ ( RTh+ R L)

   	Norton’s Theorem IL = IN * RN / ( RN + RL )

12.	Theoretically verify the Norton’s theorem.

**TABULAR COLUMN: 
<img width="1370" height="1600" alt="image" src="https://github.com/user-attachments/assets/b2f38499-0473-4f15-895b-bd36a8898d6a" />

	
**MODEL CALCULATION:**

Practical value of IL (from tabulation 1) =2.3mA

**Verification of Norton’s theorem**

IL = IN * RN / ( RN+ RL ) = 2.43mA

Theoretical calculation of IL ,IN and RTh(RN) for the given circuit:
<img width="1477" height="1600" alt="image" src="https://github.com/user-attachments/assets/571a65f1-542c-49ad-9d08-c73261621b59" />
<img width="916" height="1527" alt="image" src="https://github.com/user-attachments/assets/8057aebb-ae93-48c6-977f-8012765bc14b" />

Marks Split up:
<img width="1600" height="684" alt="image" src="https://github.com/user-attachments/assets/0225f36c-a5a4-4dc6-9a4b-6d96e24cf67b" />

**RESULT:**

Thus Thevenin’s and Norton’s theorem is verified practically and theoretically.
