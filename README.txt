######################
# Build with profile #
# mvn spring-boot:run -Dspring-boot.run.profile=XXX
######################
# Available Profiles #
#====================#
# local              #
# dev                #
######################

=============================
= Testing for new user:     =
=============================
= POST - http://localhost:8080/auth/sign-up
= POST - http://localhost:8080/auth/login
= GET  - http://localhost:8080/auth/user/all (using Bearer Token)