# Enerallt
This repository hosts Enerallt, a multi-country power market and district heating model, developed and maintained by The Energy Efficiency and Systems Laboratory, Department of Mechanical Engineering, Aalto University, Finland. 
The model is an hourly simulation of the operation and dipatch in a group of countries (or price areas) that are interconnected together in a common power market. The model in this repository is calibrated to data of the Nordic power market, including Finland, Norway, Sweden, West Denmark, and East Denmark. 

The main features of the model include:

I. Simulation of hydropower water values at the country level
II. Modelling of hourly district heating (DH) demand and supply, and the operation of combined heat adn power (CHP) plants in both electricity and DH systems
III. Electricity market clearance based on the day-ahead planning horizon for up to 365 days, and represnting the adaptative strategies of some of power producers, where they adjust their future bids based on the outcome of the market in the past runs, i.e., assuming a limited foresight.
IV. Hence, the model is doesn't seek to find the optimal solution for a yearlong period benefiting from a perfect foresight. The model can be used to investigate the most probable operation and outcome an nternational power market, when there exists no central planning.   

For more information, please refer to:

1- Zakeri B., Virasjoki V., Syri S., Connolly D., Mathiesen B.V., Welsch M., Impact of Germany’s Energy Transition on the Nordic power market – A market-based multi-region energy system model, Energy, Vol 115 (part 3), PP 1640-1662, 2016.

2- Zakeri B., Price J., Zeyringer M., Keppo I., Mathiesen B.V., Syri S., The direct interconnection of the UK and Nordic power market – Impact on social welfare and renewable energy integration, Energy, Vol 162, PP 1193-1204, 2018.

3- Helin K., Zakeri B., Syri S., Is District Heating Combined Heat and Power at Risk in the Nordic Area?—An Electricity Market Perspective. Energies, Vol 11, 1256, 2018.

4- Helin K., Syri S., Zakeri B., Improving district heat sustainability and competitiveness with heat pumps in the future Nordic energy system, Energy Procedia, Vol 149, PP 455-464, 2018.

5- Zakeri B., Syri S., Intersection of national renewable energy policies in countries with a common power market. The 13th International Conference on the European Energy Markets (EEM), Porto, Portugal, 6-10 June, 2016. 