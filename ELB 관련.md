Network Load Balancer
=====================

1. VPC를 선택한다.
2. AZ를 선택한다.
3. subnet을 선택한다.
4. IPv4 설정을 해야 한다.
    - Assigned by AWS : AWS로부터 DNS 주소를 받는다.
    - 
5. Listner를 설정한다.
    - TCP, UDP, TLS 중 하나를 선택한다.
    - target group을 설정해야 한다. (Target group이 없다면 생성해야 한다.)


<br>
<br>

Load Balancer Target Group
==========================
1. TargetGroup을 생성한다.
    - Instance를 선택하면 EC2 Instance를 등록해야 한다.
        - Register Target을 할때 해당 Instance가 Running 상태여야 한다..

    - *Instance 등록 후 Unused 상태이면 Target Group이 Load Balancer에 등록 안되서 그런것이다.*

