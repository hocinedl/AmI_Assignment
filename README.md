# SmartStudyRoomsOntology

This is the ReadMe file for the assignment2 of ambient intelligence, where we were asked to develope an ambient intelligence application and create the correspondig Ontology and testing it using Protege.
## Protege 
Protege is an open-source ontology editor and framework for building intelligent systems. It provides a user-friendly interface for creating, editing, and managing ontologies. 
## Ontology
Ontology is a way to represent knowledge about a particular domain and the relationships between the concepts within that domain. Ontologies are used to structure information and provide a common understanding of a subject area, enabling effective communication and reasoning.

## My application (Smart Study Area)

The Smart Study Area is like a bunch of study rooms, not just libraries, with books. It helps students and faculty (professors, researchers, etc.) by making their work or study more comfy. It suggests the best study room based on what they like and what they're doing. It even recommends break and lunch times to keep users comfy. It also takes care of room heating and adjusts desk lighting depending on what the user is doing, whether it's studying, reading, or group work.

### Classes and Subclasses

#### Activity

- GroupDiscussionActivity: An instance of an activity where multiple individuals engage in collaborative discussions within the study area.
  
- StudyingActivity: Represents the act of focused individual or group study within the study environment.

- ReadingActivity: Instances of reading-related activities taking place in the smart study area.

- Suggestions: A class encompassing suggestions provided to users, such as recommending study rooms or break times.

#### Devices

- Ac: Instances of air conditioning devices that contribute to controlling the ambient temperature in study rooms.

- Heaters: Instances of heating devices that regulate room temperature within the smart study area.

#### Person

- Faculty: Represents individuals belonging to the faculty, including professors and researchers.

- Student: Represents individuals enrolled as students within the study area.

#### Sensors

- LightSensor: Instances of sensors that monitor and measure ambient light levels within the study environment.

- NoiseSensor: Sensors designed to detect and measure noise levels in study rooms.

- TmpSensor: Instances of temperature sensors that monitor and measure room temperature.

#### State

Represents the current state of the smart study area, in terma of availability.

#### StudyRoom

- CollaborativeStudyRoom: A subclass of StudyRoom, indicating study rooms designed for collaborative group activities.

- Desks: Represents individual desks within the study area.

- QuietStudyRoom: A subclass of StudyRoom, indicating study rooms suitable for quiet and focused individual study.
![Capture d’écran (108)](https://github.com/hocinedl/AmI_Assignment/assets/114445094/8eee7df3-725e-4a5d-814e-d9009d1bb068)

### Object Properties

#### TurnOn

- Represents the action of turning on a device, such as Ac and Heater.

#### UsesStudyRoom

- Establishes a relationship between a person and a study room, indicating that the person is using the specified study room.

#### Prefers

- Indicates the preference of a user (faculty or student) for certain conditions or features within the smart study area.

#### Suggests

- Denotes a suggestion made by the system, possibly recommending a specific action or feature to a user.

#### SuggestsActivity

- Links the system to an activity suggestion, indicating that the system suggests a particular activity to a user.

#### HasToGoto

- Represents the directive for a person to go to a specific location, often a study room or area within the study environment.

#### Is

- Denotes an association or relationship between two entities.

#### IsIn

- Indicates the containment or location of an entity within another entity, such as a person being in a study room.

### Data Properties

#### HasTmp

- Specifies the temperature of a particular entity, often used in conjunction with temperature sensors.

#### Adjust_LightningTo

- Indicates the action of adjusting lighting conditions to a specific level, based on user preferences or environmental factors.

#### hasCapacity

- Specifies the capacity of a study room, indicating the maximum number of occupants it can accommodate.

#### hasNoiseLevel

- Specifies the noise level in a study room, often measured by noise sensors.

#### hasLighting

- Specifies the lighting conditions in a study room, providing information about the ambient illumination.

#### hasID

- Assigns a unique identifier to an entity, often used for distinguishing between different instances.

#### StaysFor

- Specifies the duration for which a person stays in a particular study room.

