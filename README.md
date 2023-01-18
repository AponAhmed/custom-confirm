# Custom confirm window
 Custom Confirm Box for Web, This is a small package to receive user's confirmation before execute any action.
 Builtin two buttons are shown, One is 'Yes' and other is 'No'.
 
## Installation 
    npm i @aponahmed/confirm

## Uses
``` javascript
    import ConfirmBox from '@aponahmed/confirm';

    new ConfirmBox({
        title: "Confirm Title",
        message: "Some awesome message about confirmation",
        yes:"Yes",  //Label of Yes button defaults is "Yes"
        no:"No",    //Label of No button defaults is "No"
        yesCallback:()=>{
            //Your confirmation action will be here
            alert("You have confirmed");
        },
        noCallback:()=>{
             alert("You Not confirmed");
        }
    });
```