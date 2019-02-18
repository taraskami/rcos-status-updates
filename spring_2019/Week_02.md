## Last Week's Accomplishments

Very few accomplishments. I continue to try and correctly install Postgres and PHP onto my Ubuntu within WSL, but now I'm running into new errors. On the plus side, we now have AGENCY creator Ken on our Mattermost channel, so he is available for questions. I have some new info from him already, so that helps.

I am becoming more comfortable with Postgres, and using linux commands are coming back to me. So, that's good.

## This Week's Plan

Continue figuring out how to install everything and have it all connected. Once Postgres is set up and the AGENCY installation is working, the next major issue is figuring out how PHP works. And seeing that I am one of the more active members of this project, I'll have to create documentation on how everything was installed and share it to the rest of the team.

## Anything Blocking?

The biggest blocker is trying to start up postgres from WSL. When i switch-user to postgres and then try to start using the psql command, I get: 
> psql: could not connect to server: No such file or directory Is the server running locally and accepting connections on Unix domain socket “/var/run/postgresql/.s.PGSQL.5432”?

After a lot of digging through github and stack overflow posts, I found a solution that is for my specific setup, that being Ubuntu 18.04 on WSL. So, I will begin following that tutorial to fix that. https://gist.github.com/bushidocodes/4a02f6cc865d280b10400319b128cd92

The next problem was trying to run the AGENCY installation scripts. But, with the combination of Ken's feedback, and some new material from the Database Systems course I am taking here at RPI, I have some workarounds to play with. So, I'll see how it goes.

## Notes

The team went to Albany this week to go over the current state of the database, and what technologies they have. This will be useful info once we begin trying to shape AGENCY to what they need. But first, learning and installation!
