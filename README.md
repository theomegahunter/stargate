# stargate
Homebrewing my own Stargate Dialing Computer, intending to update the UI along the way.

## Goals:
### Runs in a container

### Use Flyway to control database setup

### Container based backing database populated with:
 1. Volume enabled
 2. Known gate symbols
 3. Planetary addresses
 4. Brief dossiers on the planets

### Web based Graphical interface for interacting with a Stargate
  1. Display gate
  2. Display symbols for dialing
  3. Manual dialing of all symbols
  4. Validation of input symbols against database entries
  5. animation of dialing
  6. animation of activation
  7. Show relevant information for planet
  8. Lookup planet information
  8. automatic dialing 

### Sound effects for 
  1. gate activation
  2. gate deactivation
  3. shield open
  4. Shield close

### Restful API
  1. status check
  2. dialing

### Stretch goals
GDO support
DHD Interface
Atlantis Style DHD
Audio visualization?
Easter eggs?

### Exclusions
Time dilation effects
Locking out gate addresses
MALP/UAV/SG Teams
Video clips

## Technologies Used:
[X] Spring boot
[X] Junit
[X] Hibernate
[X] Flyway
[X] MariaSQL
[X] Lombok
[X] Testcontainers?

## References:
https://www.youtube.com/watch?v=qrs6PPQznaA
https://www.youtube.com/watch?v=-y28PdaqZw4
https://www.rdanderson.com/stargate/glyphs/index.htm


# Disclosure:
Stargate and related properties are copyright of MGM. Please support further gate travel by
supporting them.