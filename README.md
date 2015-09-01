## Perform a transafccion

In **IBS**, within the claim where you want to perform the transaction, click on **Settlements** and then click on the desired settlement, as in the following example:

![](https://github.com/cadazab/Pant/blob/master/images/pagos1.jpg)   

Then, on the right side of the window, search the _check-box_ **accounting release** and click on it:

![](https://github.com/cadazab/Pant/blob/master/images/pagos2.jpg) 

Finally save:

![](https://github.com/cadazab/Pant/blob/master/images/pagos4.jpg) 

## Close Claim

In case that you want to close the claim, after click on **accounting release**, click on **Close Claim**.

![](https://github.com/cadazab/Pant/blob/master/images/pagos3.jpg) 

Then you will have the option to click on **Suppress claim notification**, do it if you don't want to recive the information related with the claim after it closes. Finally save.

## New Workflow

In order to explain why the process has changed, here is a small diagram of the new workflow necessary in order to meet the requirement of **Sanctions Search**:

![](https://github.com/cadazab/Pant/blob/master/images/workflow.jpg)

1. Someone release a payment in IBS
2. The **Payee** goes to the **Sanctions search** process
3. After, if the **payee** doesn't have problems with the process restrictions, goes to a special list that we will call **Clear list**.
4. Afternoons the process to do the transactions of the day begins, first the process check if the name of the **Payee** is in the **Clear list**, if yes, perform the transaction, if not, cancel the transaction and send an email to the person who has release the payment.
5. If the transaction was successful, and the check-box **Close Claim** was selected, the process close the claim.
   
