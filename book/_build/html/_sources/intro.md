# ESA DHR monthly report

## The ESA DHR project

The European Space Agency (ESA) is in charge for the distribution of data from the Sentinel satellite constellation. In order to maintain a reliable and sustainable data hub, the creation and operation of multiples data hubs is necessary.

Therefore, MET Norway was contracted for the operation of a Data Hub Relay (DHR) in Norway in support of the continued take-up of Sentinel Data Distribution (ESA Contract No. 4000136339/22/I-NS-bgh). The DHR is implementd as a part of the operational infrastructure at MET Norway. As so it follows the normal procedures for planning, implementation and testing , and operationalisation. User access to the DHR is configured according to ESA requirements. This includes the use of ESA's DHS software for synchronization between DHRs and user accessibility..

The present report is part of MET Norway duties to inform about its perfomance as operator of one of the different DHR. Monthly reports will be created mothly to regularly comunicate the status of MET Norway's DHR.  

## The Sentinel products

The ESA DHR project includes the management of the data received from Sentinel-1 (S1), Sentinel-2, Sentinel-3 (S3) and Sentinel-5p (S5p) satellites. Each of the Sentinels has different operational modes for achieving images with different carachteristics. Those images can have different processing levels. The products included in the DHR are Level-1 images for all the Sentinels except for Sentinel-2. For which Level-1 (S2L1C) and Level-2 (S2L2A) are both included in the DHR.  

## BackEnds and FrontEnds

As operator of a DHR, the source of Sentinel data is ESA; and ESA spreads the Sentinel data trough the data hub Scihub (scihub.copernicus.eu).Scihub is ESA's FrontEnd (FE) for Sentinel data accesibility. MET Norway, as any other DHR operator, uses the DHS software for synchronization and creation of other FrontEnds. During the synchronization process a BackEnd (BE) is created. MET Norway is also running two FEs, colhub.met.no and sentinelhub2.met.no. The sentinelhub2 FE includes data from S1, S2L1C, S2L2A and S3 products. The colhub FE includes or will include all the products mentioned for sentinelhub2 FE plus S3 marine products from Copernicus, S1 products from KSAT, and S2 Digital Elevation Model (DEM).

In order to maintain an accountability on products synchronized from ESA's Scihub and available for users at the different FEs, it is necessary to understand the architecture of MET Norway's DHR.

## Key performance indicators and timeliness

According to contract, the DHR can have 5 Performance Classes (1 to 5), which are defined by two Key Performance Indicators (KPI); the availability of the DHR service and the delay in publications. The availability of DHR service is measured monthly as the percentage of time the DHR is available for users to download products. The availability of the DHR service should be of at least 99% and its Performance Modulation is defined by the following table,

| Performance Class | Measured KPI Value | Performance Modulation (PM) |
| :-: | :-: | :-: |
| 1 | >99.0% | 100% |
| 2 | >98.0% to 99.0% | 98% |
| 3 | >95.0% to 98.0% | 95% |
| 4 | >75.0% to 95.0% | 85% |
| 5 | <75% | 0% |

The delay in publications is measured monthly as the average delay for publication on the relay compared with the availability at the source, i.e. Scihub. The delay in publications is often understood as timeliness, however timeliness is understoosd here as the difference in hours between the sensing time and the ingestion time of the product into MET Norway premises. The publication delay Performance Modulation is calculated as following,

| Performance Class | Measured KPI Value | Performance Modulation (PM) |
| :-: | :-: | :-: |
| 1 | <4 hours | 100% |
| 2 | >4 to 12 hours | 98% |
| 3 | >12 to 36 hours | 95% |
| 4 | >36 to 72 hours | 85% |
| 5 | >72 hours | 0% |

The overall performance is estimated according to P = SUM(p(i)*w(i)); where p(i) denotes the performance modulation determined by the KPI and w(i) denotes the weight of the KPI, 50%. The overall performance is then translated into a cost modulation factor according to the table below.

| Performance Class | Overall performance | Cost Modulation |
| :-: | :-: | :-: |
| 1 | <=100% >= 98% | 100% |
| 2 | 98% >= 95% | 97.5% |
| 3 | <95% >= 85% | 95% |
| 4 | <85% >= 50% | 90% |
| 5 | <50% | 85% |

MET Norway targets an overall Performance Class 1.

