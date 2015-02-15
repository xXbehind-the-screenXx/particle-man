# particle-man
/*
made by xXbehind_the_screenXx
*/
ModPE.setItem(254,"ruby",0,"Partical Glove");
Item.addCraftRecipe(254,1,0,[266,1,0,334,3,0,331,2,0,334,1,0,331,1,0,264,1,0]);
 function useItem(x,y,z,i,b){
 var count = Player.getInventorySlotCount();
if(i == 254){
 if(count > 1){
 var test =Level.spawnMob(x,y+1,z,18,"mob/creeper.png"); Entity.setHealth(test,999999);Entity.setNameTag(fireman,"f*ireman"); }
 else{
var test=Level.spawnMob(x,y+1,z,18,"particle/flame"); Entity.setHealth(fireman,999999);}}
(c-1)
}
