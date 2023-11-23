# VotingManagementSystem-Web-Program-by-JSP-Java-Beans
Web server , JDBC base program
voter management system
data transfer fron client -> JSP[controller] -> Java Beans [Service] -> Dao -> Data Base || Dao layer has dependency on DBUtils & POJO layer

voter, admin and candidate all three can use concurrently
voter -> 1)register as new voter[age min 21] 2) login and validate 3)if not voted yet then go to candidate list to voted 4)if voted then logout with message
admin -> 1)get top 2 candidates who got maximum votes 2)get party wise votes 3)got all candidates information who take part in election
candidate -> 1)candidate can register with unique party name
