# GOSH-FHIRworks2020-GettingData
My project is: Generating letters, forms and documents prefilled from FHIR records (Word and PDF).

My solution is by searching for user‘s own patient id, the patient can query his or her  personal information and some last observation data in two forms. Besides, patients can choose to download the forms to their computer in pdf format.

The code uses C #. The main function is to get data in the back-end data interface. The method is to analyze the jason file and then send the http request and accept the response. For example, when a patient enters his id, the first form will obtain the patient's information through the interface the teacher given. Then I use the patient's id to get all the historical data of the patient's observation in the hospital, take out the first piece of data and load it into the second table. So in total, there are three interfaces are requested.
