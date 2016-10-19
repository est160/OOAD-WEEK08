# OOAD-WEEK08

## Use Case Diagram

#code

@startuml

User -> (Start The Application)

User --> (Use the application) : USE Properties with same Main Admin

:Main Admin: ---> (Use the application) : EX YOU CAN\nTranfer Money

:Main Admin: ---> (Use the application) : EX YOU CAN\nDeposit

:Main Admin: ---> (Use the application) : EX YOU CAN\nwithdrawal


@enduml

                   PIC 1 CASE Financial transactions
                   
                   
 ![](http://www.plantuml.com/plantuml/img/dP0n2y9038Nt-nLlrC4_q45Qj6Erq1OKN8ADzA3D7NUHuh_t2e9E3jsIVCbxvELHAUXp6etf8WVizjWqomZjm2Yy7-sTr3hPVlYoa2femlI3aQ5hIjJ1UGvgEMAsEY3InAZ82ef-ic9CzcsofFP7hhpWUkvmA4utQGF98zbNJlYrKkF8taMhAw-NR_f0CwMaSfO-HVO6)
 
 
 
#code

@startuml

:BOSS: -left-> (POGDENGPLAYER1Left) 

:BOSS: -right-> (POGDENGPLAYER3Right) 

:BOSS: -up-> (POGDENGPLAYER2Up)

:BOSS: -down-> (POGDENGPLAYER4Down)

@enduml

                   PIC 2 CASE POGDENG
                   
                   
                   
 ![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuR9oyWyEjbBGpKbDAz6rKz08y7TtSVLp3_1nZ7GDClG1Ycegm1KLPQPdOAeo3W898oahBS1GOnHQe0cNJyalpyDGOU825DNaSaZDIm6w2m00)
 
 
 
#code

@startuml

AIRBUS -up-|> PLANE

Helicopter -up-|> PLANE

JET -up-|> PLANE

AIRBUS --> (flying)

Helicopter --> (flying):I have a propeller

JET --> (flying)

JET --> (speedfastest): speed of sound


@enduml

                   PIC 3 CASE PLANE
                   
                   
                   
 ![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuU9oz0no2WrMq2qjqAsnKmZmSVHpvV98pSbCpYyeIIr25VTo3K4LW6dMjLFGICkfpCnBrqJHZ2HkvQcGaLYMgf2eK52KNv2QavDQ134FMIzSeBWWDJKbBR6u9BMuHDDA0SnLo4zJACulpKlXud98pKi1kXu0)
 
 
 
                 
 
#code

@startuml

left to right direction

skinparam packageStyle rect

actor customer

actor shopkeeper

rectangle 7eleven {

  customer -- (shopping)
  
  (shopping) .> (payment) : include
  
  (help) .> (shopping) : query
  
  (shopping) -- shopkeeper
  
}

@enduml

                   PIC 4 CASE 7eleven
                   
                   
                   
 ![](http://www.plantuml.com/plantuml/img/LOyn3i8m34NtdC9ZEvGLgGFg7JY1bPeqQkA4n46gAkvE8X25yV_tz6LFMJ19yKuvkWb8W6JD8Z3RH5fiO9LNon4JUeYeLpHqbSqHDAnGIqYWIvRWANrYNa9SYM8jceHigducHmzYs1LyVHW6w9eTBPk-WYF0wG9TnCqJImyZMDQkpDISXLnyyyCUuLueRVyJTVtdbAUQYEVww0i0)
 
 
 
#code
 
 @startuml

left to right direction

skinparam packageStyle rect

actor tourist

actor clerk

rectangle travel {

  tourist -- (checkpassport)
  
  (checkpassport) .> (checkbaggage) : query
  
  (checkbaggage) .> (Waiting for a flight) : wait
  
  (help) .> (checkpassport) : extends
  
  (checkpassport) -- clerk
  
}

@enduml


                 PIC 5 Travel
                 
                 
![](http://www.plantuml.com/plantuml/img/RP0n3i8m34NtdC8Z7Se1611tO60smKsZX3GuBb0XxeuZe234cF_VZx-zAO8iup6QI9s03C3UzG87psJ53ycKu5D6nYDaj04TRMMA1DKsQ6LW3Otio_jb8t4mrSRa51J6CqMu6NY3qBQmi3tPaB6KFB0qQluei5o_f3qwfsCRMC5f99vcTZOgkaClFZdej0925-iMDN9HlIPwYldhqy-S5T1LA1tAdmvQzBdEtMmKqJCz0000)
 
 
