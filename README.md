#include <iostream>
#include "vehicles.h"
#include "soldiers.h"
using namespace std;

int main()
{

    do {
            int commands;
             cout << "welcome to army management/n";
             cout<< "give your army a command/n";
             cout << "1.create army /n";
             cout<< "2.attack/n";
             cout<<"3.defend/n";
             cout<<"4.report/n";
             cin >> commands;


            switch(commands) {
                 
             case 1 : 
                cout <<" create a troop for your army!";
                Armytroop troop1;
                
                
                void setArmyNames()
                void setArmyDamage()
                void setSpecialArmy()
                
                
                
                
                
                
                
                

                case 2 : //the army will attack
                    int whoattack;
                    
                    cout << "lets do it!/n";
                    cout << "which part of the army do you prefer to perform the attack?/n";
                    cout << "1.soldiers/n";
                    cout << "2.vehicles/n";
                    cout << "3.both at once!/n";
                    
                    
                    cin  >> whoattack;
                    
                    
                    switch (whoattack){

                     case 1://only soldiers attack
                         
                         
                         

                      void adaptive::attack()
                      
                      void defensive::attack()

                      void offensive::attack()
                      
                      
                      
                      
                     case 2://only vehicles attack
                         void ballista::attack()

                         void catapult::attack()

                         void seigeTower::attack()

                      //end



                     case 3://soldiers and vehicles attack
                         
                      void ballista::attack()

                      void catapult::attack()

                      void seigeTower::attack()
                      // the next is solders functions
                      
                      void adaptive::attack()
                      
                      void defensive::attack()

                      void offensive::attack()
                      

                    }




                case 3 : // army defend
                
                    cout<<"army is defending!/n";
                    
                    //vehicles move
                    
                    void catapult::move()
                    void ballista::move()
                    void seigeTower::move()
                    
                         //soldiers defend 
                         
                    void adaptive::defend()
                     void Army::armyDefend()
                     void defensive::defend()
                      void offensive::defend()
                    




                case 4 : // everyone reports itself
                          void catapult::report()
                          
                          void ballista::report()

                          void seigeTower::report()
                          
                          void adaptive::report()
                          
                          void defensive:: report()
                          
                          void offensive::report()


            }
    }while (commands != 0);
    return 0;
}
