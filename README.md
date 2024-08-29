Fedex Delivery Status Prediction

This project involved analyzing a dataset that includes features like shipment times, carrier details, source and destination locations, distance, and delivery status. 

The primary goal was to identify the key factors contributing to shipment delays and to accurately predict the delivery status.

Data columns (total 15 columns):

             #   Column                 Dtype  
             
            ---  ------                 -----
            
             0    Year                    int64  
             1    Month                   int64  
             2    DayofMonth              int64  
             3    DayOfWeek               int64  
             4    Actual_Shipment_Time    float64
             5    Planned_Shipment_Time   int64  
             6    Planned_Delivery_Time   int64  
             7    Carrier_Name            object 
             8    Carrier_Num             int64  
             9    Planned_TimeofTravel    float64
             10   Shipment_Delay          float64
             11   Source                  object 
             12   Destination             object 
             13   Distance                int64  
             14   Delivery_Status         float64


           Year	Month	DayofMonth	DayOfWeek	Actual_Shipment_Time	Planned_Shipment_Time	Planned_Delivery_Time	Carrier_Name	Carrier_Num	Planned_TimeofTravel	Shipment_Delay	Source	Destination	Distance	Delivery_Status
 
            0  	2008	      1    	3	      4	  1203.0	  1195  	1345	  WN  	335  	150.0	  8.0	  IAD	  TPA	  810  	0
            
            1	  2008	      1    	3	      4	  474.0	    455    	600	    WN	  3231	145.0	  19.0	IAD	  TPA	  810	  1
            
            2	  2008	      1	    3	      4	388.0	380	470	WN	448	90.0	8.0	IND	BWI	515	0
            
            3	  2008	      1	    3	      4	566.0	570	660	WN	1746	90.0	-4.0	IND	BWI	515	0
            
            4	  2008  	    1	    3	      4	1109.0	1075	1165	WN	3920	90.0	34.0	IND	BWI	515	1
            

Fedex-data  file ink : https://www.kaggle.com/datasets/vasudevmaduri/fedexdata/data

Deployment Link : https://fedex-delivery-status-prediction-cvqf9wi3.streamlit.app/


