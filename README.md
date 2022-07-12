# Burc-bulma
www.patika.dev Burc bulma




        import java.util.Scanner;                                                                                              
                                                                                                                       
        public class Burc_Bulma {                                                                                              
        public static void main(String[] args) {                                                                           
        int day, month;                                                                                                
        String burc = "";                                                                                              
        Scanner input = new Scanner(System.in);                                                                        
        System.out.println("Dogdugunuz ayi giriniz:");                                                                 
        month = input.nextInt();                                                                                       
        System.out.println("Dogdugunuz gunu giriniz:");                                                                
        day = input.nextInt();                                                                                         
                                                                                                                       
        if ((month == 1) && (day <= 31 && day >= 1)) {                                                                 
            if (day < 22) {                                                                                            
                burc = "Oglak";                                                                                        
            } else {                                                                                                   
                burc = "Kova";                                                                                         
            }                                                                                                          
        }                                                                                                              
            if ((month == 2) && (day <= 28 && day >= 1)) {                                                             
                if (day < 19) {                                                                                        
                    burc = "Kova";                                                                                     
                } else {                                                                                               
                    burc = "Balik";                                                                                    
                }                                                                                                      
            }                                                                                                          
                if ((month == 3) && (day <= 31 && day >= 1)) {                                                         
                    if (day < 21) {                                                                                    
                        burc = "Balik";                                                                                
                    } else {                                                                                           
                        burc = "Koc";                                                                                  
                    }                                                                                                  
                }                                                                                                      
                    if ((month == 4) && (day <= 30 && day >= 1)) {                                                     
                        if (day < 21) {                                                                                
                            burc = "Koc";                                                                              
                        } else {                                                                                       
                            burc = "Boga";                                                                             
                        }                                                                                              
                    }                                                                                                  
                        if ((month == 5) && (day <= 31 && day >= 1)) {                                                 
                            if (day < 22) {                                                                            
                                burc = "Boga";                                                                         
                            } else {                                                                                   
                                burc = "Ikizler";                                                                      
                            }                                                                                          
                        }                                                                                              
                            if ((month == 6) && (day <= 30 && day >= 1)) {                                             
                                if (day < 23) {                                                                        
                                    burc = "Ikizler";                                                                  
                                } else {                                                                               
                                    burc = "Yengec";                                                                   
                                }                                                                                      
                            }                                                                                          
                                                                                                                       
                                if ((month == 7) && (day <= 31 && day >= 1)) {                                         
                                    if (day < 23) {                                                                    
                                        burc = "Yengec";                                                               
                                    } else {                                                                           
                                        burc = "Aslan";                                                                
                                    }                                                                                  
                                }                                                                                      
                                    if ((month == 8) && (day <= 31 && day >= 1)) {                                     
                                        if (day < 23) {                                                                
                                            burc = "Aslan";                                                            
                                        } else {                                                                       
                                            burc = "Basak";                                                            
                                        }                                                                              
                                    }                                                                                  
                                        if ((month == 9) && (day <= 30 && day >= 1)) {                                 
                                            if (day < 23) {                                                            
                                                burc = "Basak";                                                        
                                            } else {                                                                   
                                                burc = "Terazi";                                                       
                                            }                                                                          
                                        }                                                                              
                                            if ((month == 10) && (day <= 31 && day >= 1)) {                            
                                                if (day < 23) {                                                        
                                                    burc = "Terazi";                                                   
                                                } else {                                                               
                                                    burc = "Akrep";                                                    
                                                }                                                                      
                                            }                                                                          
                                                if ((month == 11) && (day <= 30 && day >= 1)) {                        
                                                    if (day < 22) {                                                    
                                                        burc = "Akrep";                                                
                                                    } else {                                                           
                                                        burc = "Yay";                                                  
                                                    }                                                                  
                                                }                                                                      
                                                    if ((month == 12) && (day <= 31 && day >= 1)) {                    
                                                        if (day < 22) {                                                
                                                            burc = "Yay";                                              
                                                        } else {                                                       
                                                            burc = "Oglak";                                            
                                                        }                                                              
                                                    }                                                                  
                                                       System.out.println("Burcunuz:" + burc);                         
                                                    }                                                                  
    }                                                                                                                  
