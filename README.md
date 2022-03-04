###We are check avaliable for some sites

![Alt text](images/dashboard.png?raw=true "Dashboard")

###Project up and running [https://russianshiptfuckoff.online](https://russianshiptfuckoff.online) and available for public anonymous access

###How to run:

    docker-compose up

###How to get list of avaliable sites by api call:

    curl -g 'https://russianshiptfuckoff.online/prometheus/api/v1/query?query=probe_success{}==1' | jq '.data.result[].metric.target'
    
![Alt text](images/list_of_sites.png?raw=true "Avaliable sites")