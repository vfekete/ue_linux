Repository contains files I had to change in order to build UnrealEngine4 under linux (ubuntu 20.04)

SETUP.SH:
 a) http://cdn. ... -> https://cdn. ..., same change in Dependency manifest for GitDependencies program
 b) access https certificates (thnx https://stackoverflow.com/questions/560804/how-do-i-use-webrequest-to-access-an-ssl-encrypted-site-using-https)