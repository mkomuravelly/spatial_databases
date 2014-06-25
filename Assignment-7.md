###Assignment-7

## MYSQL QUERY


SELECT e.SHAPE as POINT,state,location,s.shape as POLY    
FROM  `earth_quakes` e,`state_borders` s      
WHERE state = 'California'    
AND WITHIN(e.shape,s.shape)      
