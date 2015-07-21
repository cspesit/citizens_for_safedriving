# citizens_for_safedriving
An app(web+mobile) which notifies you and your friends on Facebook to make you slow down when you exceed speed limits! Reward for safe driving would be Uber promo codes,safe driver badges with data being sent to insurance companies for better rates!

//Pseudo code


//Step1 :Obtain continous_current_driving_speed and location from either car/mobile GPS
//Step2 :Identify current_speed limits based on current_location data , function continous_monitor(current_speed)
//Step 3:If( current_speed >=.9*speed limit)
          {
            issue_warning();
            check_speed_continously(continous_current_speed);
            if(continous_current_speed >=.9*speed_limit)
              intensify_warning;
              post_on_facebook_whatsapp_socialmedia;
            else
              deintensify_warning;
              
          }
          
        record_driving_speeds_frequency_of_spikes();
        {
           share_with_selected_parties;
           follow_up_for_rewards;
       }
     }
         
