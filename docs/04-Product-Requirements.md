---
title: Product Requirements
---

## Project Objective

This project aims to investigate and develop an automatic pet food dispenser that provides pet owners with a convenient, reliable, and consistent way to feed their pets. The product will be designed to dispense predetermined portions of pet food at scheduled times, reducing the need for owners to manually feed their pets throughout the day.
The primary objective is to develop a user-friendly, programmable automatic feeding system that can accommodate the daily routines of pet owners while supporting the nutritional needs of pets. The dispenser will incorporate a timer-based feeding system that allows users to establish feeding schedules able to be customized to consumer need. Depending on the final design and available resources, additional features may include adjustable portion sizes, a food storage container, a manual feeding button, and indicators for low food levels or cleaning and maintenance.
The intended outcome is a functional prototype that demonstrates the ability to automatically dispense pet food according to a user-defined schedule. The prototype will be evaluated based on its dispensing accuracy, scheduling performance, ease of use, reliability, and safety for pets and pet owners alike.


## Stakeholders

* **Target group** Pet owners who have busy or unpredictable schedules and want to maintain a consistent feeding routine for their pets. This includes working professionals, students, frequent travelers, and owners who may not always be home during their pet's normal feeding times. 
* **Target purchaser** Pet owners and household members responsible for purchasing pet-care products and taking care of household pets that have busy schedules, long periods away from home, or travel frequently.
* **Customer service** Prefers a product that is simple to troubleshoot, clean, refill, and maintain with accurate timing and dispensing capabilities. 
* **Marketing & Sales division** Looks for unique selling points centered around convenience, reliable automatic feeding, portion control, and ease of use. 
* **Retailers** Prefer a product that is compact, durable, easy to package, and capable of withstanding normal transportation and storage conditions, as well as state clearly the product's main features, intended pet types, feeding capacity, and ease of use to potential customers to help drive sales. 

## Use Cases

### User Story #1: Working Pet Owner

Jordan is a 29-year-old engineer who works full-time and is usually away from home for most of the day. His dog is normally fed twice a day, once in the morning and again in the evening. However, meetings, traffic, and changes in his work schedule sometimes prevent him from getting home at the dog's normal feeding time.

Before leaving for work, Jordan fills the automatic pet food dispenser and programs the desired feeding schedule and portion size. At the scheduled time, the dispenser automatically releases the predetermined portion of food without requiring Jordan to be home or interact with the device. When Jordan returns, he can check the remaining food supply and refill the dispenser when necessary.

The automatic dispenser allows Jordan to maintain a consistent feeding routine for his dog even when his own schedule changes. It also reduces the need to rely on another person to feed the dog when he is unexpectedly away from home.

### User Story #2: Pet Owner Away for the Day

Maya is a college student who occasionally spends an entire day away from her apartment because of classes, work, and other activities. Her schedule varies throughout the week, but she wants her dog to continue receiving food at consistent times and in consistent portions regardless of when she returns home.

Before leaving for the day, Maya checks that the dispenser contains enough food and adjusts the programmed feeding times if necessary. The dispenser stores the food securely so her dog cannot access additional food between meals. At each scheduled feeding time, it automatically dispenses the selected portion. If Maya's schedule changes on another day, she can modify the feeding schedule to match her dog's routine.

This allows Maya to spend longer periods away from home while maintaining her dog's normal feeding schedule. The adjustable schedule and automatic portioning also reduce the possibility of missed, delayed, or inconsistent feedings.

## Aspects

The automatic pet food dispenser will be designed based on the following requirements. The **P1 - P10** is the "code" to indicate the priority of the requirement, from low to high.

### 1. Hardware / Product Design

- **1.1** The product shall have a container that can store enough pet food for multiple feedings. (P9)
- **1.2** The product shall dispense food without regularly getting jammed. (P10)
- **1.3** The product shall be stable enough that a pet cannot easily knock it over. (P8)
- **1.4** The food container shall be easy for the owner to refill. (P8)

### 2. Software / Functionality

- **2.1** The product shall allow the user to set specific feeding times. (P10)
- **2.2** The product shall automatically dispense food at the scheduled time. (P10)
- **2.3** The product shall dispense a consistent amount of food for each feeding. (P9)
- **2.4** The product shall have a manual button that allows the user to dispense food when needed. (P7)

### 3. Interactivity & User Experience

- **3.1** The product shall be simple for the user to set up and operate. (P9)
- **3.2** The user shall be able to easily change the feeding schedule. (P9)
- **3.3** The product shall be easy to refill and clean. (P8)
- **3.4** The product shall clearly show the user when it is operating or dispensing food. (P6)

### 4. Customization

- **4.1** The user shall be able to choose different feeding times. (P10)
- **4.2** The user shall be able to select different portion sizes. (P8)
- **4.3** The product shall allow more than one feeding to be scheduled per day. (P9)
- **4.4** The product shall work with common types and sizes of dry pet food. (P7)

### 5. Manufacturing

- **5.1** The product shall use parts that are available within the team's project budget. (P9)
- **5.2** The product shall be designed using materials and manufacturing methods available to the team. (P8)
- **5.3** The product shall be simple enough for the team to assemble and troubleshoot. (P8)
- **5.4** Major components shall be replaceable if they become damaged. (P6)

### 6. Safety

- **6.1** The product shall keep electrical components covered and away from the pet. (P10)
- **6.2** The pet shall not be able to easily reach the moving parts of the dispensing mechanism. (P10)
- **6.3** The product shall not have exposed sharp edges that could harm the pet or owner. (P10)
- **6.4** The product shall operate within the safe voltage and current limits of its electrical components. (P10)

## Requirement Criteria Specifications

* 1.1.1 - Regulate system power from 9 volts to 5 volts
* 1.1.2 - Provide over-amperage project to not exceed 1.5 amps.
* ## Requirement Criteria Specifications

The following criteria translate the product requirements into measurable engineering specifications. Each specification includes a verification method so that the completed prototype can be evaluated through inspection, analysis, testing, or demonstration.

### 1. Hardware / Product Design

* **1.1.1** The food storage container shall provide a usable capacity of at least **8 cups, approximately 2 liters, of dry pet food**.
  **Verification:** Test by filling the container with a measured volume of dry pet food.

* **1.2.1** The dispensing mechanism shall complete **100 consecutive dispensing cycles with no more than one jam or failed dispensing cycle**.
  **Verification:** Test by operating the dispenser for 100 consecutive cycles and recording any jams or failures.

* **1.3.1** The dispenser shall remain upright without tipping when placed on a surface inclined to **15 degrees** with the food container partially and fully loaded.
  **Verification:** Test using an inclined surface at the specified angle.

* **1.4.1** The food container shall be refillable by the user in **2 minutes or less without the use of tools**.
  **Verification:** Demonstration by timing the refill process.

### 2. Software / Functionality

* **2.1.1** The user shall be able to program feeding times throughout a **24 hour period with a resolution of at least 1 minute**.
  **Verification:** Demonstration by programming multiple feeding times and confirming the stored values.

* **2.2.1** The dispenser shall begin dispensing food within **60 seconds before or after the programmed feeding time**.
  **Verification:** Test by comparing the programmed feeding time with the actual dispensing time over at least 10 scheduled feedings.

* **2.3.1** For a selected portion setting, the mass of food dispensed shall remain within **plus or minus 10 percent of the average target portion** over 10 consecutive dispensing cycles.
  **Verification:** Test by weighing 10 dispensed portions using a digital scale and calculating the variation.

* **2.4.1** Activating the manual feeding control shall initiate one dispensing cycle within **5 seconds of user activation**.
  **Verification:** Demonstration using the manual control and timing the response.

### 3. Interactivity & User Experience

* **3.1.1** A user unfamiliar with the prototype shall be able to power on the dispenser and program at least one feeding time within **5 minutes using the provided instructions**.
  **Verification:** Demonstration with a user who did not participate in programming the system.

* **3.2.1** A programmed feeding time shall be changeable in **2 minutes or less without resetting the entire system**.
  **Verification:** Demonstration by modifying an existing feeding schedule and timing the process.

* **3.3.1** The food container and accessible food contact components shall be removable or accessible for routine cleaning without specialized tools, and the cleaning process shall be able to be completed within **10 minutes**.
  **Verification:** Demonstration and inspection.

* **3.4.1** The dispenser shall provide a clearly visible indication whenever a dispensing cycle is occurring. The indication shall be visible from a distance of at least **1 meter under normal indoor lighting**.
  **Verification:** Demonstration and inspection during operation.

### 4. Customization

* **4.1.1** The user shall be able to independently select feeding times anywhere within a **24 hour daily schedule**.
  **Verification:** Demonstration by programming feeding events at different times of day.

* **4.2.1** The dispenser shall provide at least **three selectable portion size settings**.
  **Verification:** Inspection of the controls and demonstration of each setting.

* **4.2.2** Each selectable portion setting shall produce a distinguishable food quantity, and repeated dispensing at the same setting shall meet the accuracy requirement specified in **2.3.1**.
  **Verification:** Test by weighing food dispensed at each available portion setting.

* **4.3.1** The dispenser shall support at least **four independently programmed feeding events within a 24 hour period**.
  **Verification:** Demonstration by programming four different feeding times and observing operation.

* **4.4.1** The dispensing mechanism shall successfully dispense at least **three commercially available types of dry pet food with different kibble sizes and shapes**.
  **Verification:** Test using three documented dry pet food samples and completing repeated dispensing cycles with each.

### 5. Manufacturing

* **5.1.1** The total cost of components and materials required to construct one functional prototype shall remain **at or below the project budget established by the team**.
  **Verification:** Analysis of the final bill of materials and purchase costs.

* **5.2.1** All custom prototype components shall be manufacturable using fabrication methods available to the team or the approved external product designer.
  **Verification:** Inspection of the design files, manufacturing plan, and completed components.

* **5.3.1** The prototype shall be capable of being assembled using standard hand tools and team accessible equipment without requiring specialized industrial equipment.
  **Verification:** Demonstration during prototype assembly.

* **5.3.2** A team member using the assembly documentation shall be able to assemble or disassemble the major prototype components within **30 minutes**.
  **Verification:** Demonstration and timed assembly test.

* **5.4.1** Major replaceable components, including the dispensing mechanism, controller, power components, and user controls, shall be removable without permanently damaging the enclosure or surrounding components.
  **Verification:** Inspection and demonstration.

* **5.4.2** A major replaceable component shall be capable of being removed and replaced within **15 minutes using standard hand tools**.
  **Verification:** Timed demonstration.

### 6. Safety

* **6.1.1** All electrical conductors, circuit boards, and electrical connection points shall be enclosed so that they cannot be directly contacted by the pet during normal operation.
  **Verification:** Inspection of the fully assembled prototype.

* **6.2.1** Moving components of the dispensing mechanism shall not be directly accessible to the pet during normal operation.
  **Verification:** Inspection and demonstration while the dispensing mechanism is operating.

* **6.3.1** All externally accessible surfaces shall be free of exposed sharp points, unfinished cut edges, protruding fasteners, or other features capable of causing injury during normal handling.
  **Verification:** Visual and physical inspection of the completed enclosure.

* **6.4.1** The system shall regulate the **9 volt input supply to 5.0 volts, plus or minus 5 percent, for components requiring 5 volt power**.
  **Verification:** Test using a multimeter while the system is powered and operating.

* **6.4.2** The electrical system shall include current limiting or overcurrent protection so that system current does not exceed **1.5 amperes under normal operating conditions**.
  **Verification:** Test by measuring system current during idle and dispensing operation.

* **6.4.3** Each electrical component shall be operated within the manufacturer specified voltage and current limits.
  **Verification:** Analysis comparing measured operating voltage and current with the component datasheets.


## Open Questions
- What dispensing method will work best without the food getting stuck?
- How much food should the dispenser be able to hold?
- What portion sizes should the user be able to choose from?
- Should the dispenser save the feeding schedule if it loses power?
- What is the best way to make the dispenser easy to refill and clean?
