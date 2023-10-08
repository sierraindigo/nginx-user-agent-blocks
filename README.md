# nginx-user-agent-blocks
 Selected user agents to block within Nginx. 
 
 **Usage** 
 
 Insert an *include* directive within your *server* block and point to the user-agent-blocks.conf file to apply these filters.
 
 EXAMPLE:
 
    server { 
      ...
      
      include /etc/nginx/user-agent-blocks.conf;
      
      ...
    }
