#Wizard for Semantic-UI > 1.0#
==================
##How use:##
```
$(function () {
  var wizard = new WizardModule({
              idForm: 'task-form',
              callable: {
                  beforeInit: function (event, obj) {
                  },
                  afterInit:function(event,obj){
                  }
              }
          });
          wizard.init();
});
```
