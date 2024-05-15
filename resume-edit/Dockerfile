FROM nginx
  
RUN rm /etc/nginx/nginx.conf
 
COPY nginx.conf /etc/nginx/nginx.conf
 
COPY dist/ /opt/resume-edit/

COPY public/ /opt/static/