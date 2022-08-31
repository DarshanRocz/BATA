@isTest
trigger AccountTrigger on Account(before insert,before update){

  if(trigger.isInsert && trigger.isBefore){
      AccountTriggerHandler.beforeInsert(trigger.new);
  }

  if(trigger.isUpdate && trigger.isBefore){
       AccountTriggerHandler.beforeUpdate(trigger.new);
  }
}

public class AccountTriggerHandler{

    public static void beforeUpdate(trigger.new){


    }
}

trigger AccountTrigger on Account(before insert,before update){

  if(trigger.isInsert && trigger.isBefore){
      AccountTriggerHandler.beforeInsert(trigger.new);
  }

  if(trigger.isUpdate && trigger.isBefore){
       AccountTriggerHandler.beforeUpdate(trigger.new);
  }
}

public class AccountTriggerHandler{

    public static void beforeUpdate(trigger.new){

        
    }
}