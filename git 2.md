## The git log command
  
   The Git Log tool allows you to view information about previous commits 
   that have occurred in a project. The simplest version of the log command 
   shows the commits that lead up to the state of the currently checked out branch
   
 ## git log syntax
 
   Display All Commits. You can force the log tool display all commits 
   (regardless of the branch checked out) by using the –all option.
   $ git log --all
   
   View n Most Recent Commits. This can be accomplished using the -<n> option. 
   Replace <n> with the number of commits you would like to see. i.e.
    To see the 3 most recent commits:  $ git log -3

 ## git log flags
 
   ***--git log*** 
  -View changes 
   
   ***--git log --summary***
  -View changes (detailed)   
   
   ***--git log --after <date> --before <date>*** 
  -Filter Commits by Date Range To specify a date range, use both options:
                                                
   
   
 ## References
   	-[thegeekstuff] https://www.thegeekstuff.com/2014/04/git-log/
	-[github]https://github.com/joshnh/Git-Commands
	-[linuxnix]https://www.linuxnix.com/git-log-command-explained-with-examples