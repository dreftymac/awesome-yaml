  person_table:
    - &person001
      fname:  homer
      lname:  simpson
      role:   dad
      age:    33
      
    - &person002
      fname:  marge
      lname:  simpson
      role:   mom
      age:    34
                  
    - &person003
      fname:  peter
      lname:  griffin
      role:   dad
      age:    34
      
    - &person004
      fname:  lois
      lname:  griffin
      role:   mom
      age:    34

    - &person005
      fname:  bart
      lname:  simpson
      role:   troublemaker
      age:    8

    - &person006
      fname:  stewie
      lname:  griffin
      role:   troublemaker
      age:    3
      
  ## notice the difference between the two
  ## alias dereferencing methods
  ##
  toublemaker_table:
    - char:     *person005
      motto:    kowabunga
      
    - char:     *person006
      motto:    Oh, how ruthlessly absurd.
      
  dad_table:
    - <<:       *person001
      motto:    DOH
      role:     ""
        ## colliding "role" key causes overwrite
      
    - <<:       *person003
      motto:    Aw, c'mon Lois, isn't 'bribe' just another word for 'love'?
      role:     Father
      
