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
 
 
 
 
                   PIC 3
                   
                   
                   
 ![](http://www.plantuml.com/plantuml/img/NL2z3e8m4Dxx55-SO921aS60euCEwc3YKk2Kcd8bj1eVt_uGJKoQzBw_krvhw-JidgCMLREh82sQVbGiihCbk84WfqchJZfbE0zo478XjeSBrXjann3F4mmugR679tuC6qUOrNrmCBSq0nLEWxBmHpBeBST9K_5lJNcWGUGxRvNQ6i-q1CEmzA9PQcZ5P0Ln7trBbrKS44j_TuQPEaVzbPtv1atxyAGjLc6xVIcMbL0K0UtBKAH7rBwx_waF)
 
 
 
                   PIC 4
                   
                   
                   
 ![](http://www.plantuml.com/plantuml/img/JOwn3i8m44FtV8L7El03LHKLnC1ITOWO60yugP7Ij93hmD_JkoB1QFl9Tbk4NhACoHtxAve6vsMa3EzTtL7CE97GZGhNe8Bk7Pv9eSCyftWdYPEXkw0bbIPzPeHX4hClXI43WtvufJqQ66qJAsdZUuzlqIPLA-ZSjljdj9mVw-SF)
 
 
 
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

                   PIC 5 CASE 7eleven
                   
                   
                   
 ![](http://www.plantuml.com/plantuml/img/LOyn3i8m34NtdC9ZEvGLgGFg7JY1bPeqQkA4n46gAkvE8X25yV_tz6LFMJ19yKuvkWb8W6JD8Z3RH5fiO9LNon4JUeYeLpHqbSqHDAnGIqYWIvRWANrYNa9SYM8jceHigducHmzYs1LyVHW6w9eTBPk-WYF0wG9TnCqJImyZMDQkpDISXLnyyyCUuLueRVyJTVtdbAUQYEVww0i0)
 
 
 
