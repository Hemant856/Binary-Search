# Binary-Search

//FFFFFFFFFFTTTTTTT
 //Minimize the Answer
bool ok(ll mid){

}

void hemant(){

   ll lo,hi;
   ll ans;
   while(lo<=hi)
   {
     ll mid = (lo + hi) /2;
     if(ok(mid))
     {
          ans = mid;
          hi = mid - 1;
     }
     else
     {
          lo = mid + 1;
     }
   }  
} 


 //TTTTTTTFFFFFFFF
 //Maximize the Answer 
 
bool ok(ll mid){

}

void hemant(){

   ll lo,hi;
   ll ans;
   while(lo<=hi)
   {
     ll mid = (lo + hi) /2;
     if(ok(mid))
     {
          ans = mid;
          lo = mid + 1;
     }
     else
     {
          hi = mid - 1;
     }
   }  
}

