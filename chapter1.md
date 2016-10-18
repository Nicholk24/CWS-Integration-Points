# Utility Processes



**ProcessPendingJobOpportunities:**

* Send Open Request to XMS

* Sends any changes to the Request to XMLS

* Notifies XMS when Request status has changed

* Back fills worker payment provider on request created prior to SS and submits to XMS


TypeName: **Beeline.XMS.Integration.Procurement.ProcessPendignContractJobOpportunities,Beeline.XMS.Integration**



**Process Web Hook Events:**

* ApplicationReceived

* OfferAccepted

* OfferDeclined

* SuppliersInvited

* TypeName:** Beeline.XMS.Integration.ProcessWebHookEvent,Beeline.XMS.Integration**




**ProcessPendingJobApplication:**

* Processes any candidate that applies for a job opportunity within XMS

* Processes that also notifies XMS if candidate declination

* TypeName: **Beeline.XMS.Integration.ProcessWebHookEvent,Beeline.XMS.Imtegration**




**Process Pending Contract Job Create\/Withdrawal Offers**

* Created in CWS and sends offer to XMS

* Processes Offers that are withdraws and notifies XMS




**Process Assignment Contract Job:**

* Assignment Created in CWS, Job sent to XMS

* CWS notifies XMS of the following changes: Bill Rate, Pay Rate, Work location, Early Term, Cancellation, No show, Alter Start Date, Alter End Date, Extension, Job Title, general amendment.


TypeName**: Beeline.XMS.Integration.Assignment.ProcessAssignmentContractJob,Beeline.XMS.Integration**







