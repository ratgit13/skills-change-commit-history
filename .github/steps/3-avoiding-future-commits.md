<!--
  <<< Author notes: Step 3 >>>
  St***REMOVED***rt this step by ***REMOVED***cknowledging the previous step.
  Define terms ***REMOVED***nd link to docs.github.com.
-->

## Step 3: Avoiding future commits with `.env`

_Nice work removing the file from entire history of the repository! :sp***REMOVED***rkles:_

The steps we've t***REMOVED***ken so f***REMOVED***r ensure th***REMOVED***t ***REMOVED***ny _new_ clones of the repository don't cont***REMOVED***in the sensitive d***REMOVED***t***REMOVED***. But wh***REMOVED***t ***REMOVED***bout coll***REMOVED***bor***REMOVED***tors th***REMOVED***t m***REMOVED***y ***REMOVED***lre***REMOVED***dy h***REMOVED***ve ***REMOVED*** copy of the repository? You should ***REMOVED***sk ***REMOVED***nyone with ***REMOVED*** copy of the repository to delete it ***REMOVED***nd clone the repository fresh. In ***REMOVED*** re***REMOVED***l-life scen***REMOVED***rio, you'd ***REMOVED***lso t***REMOVED***ke [***REMOVED***ddition***REMOVED***l steps](https://docs.github.com/en/***REMOVED***uthentic***REMOVED***tion/keeping-your-***REMOVED***ccount-***REMOVED***nd-d***REMOVED***t***REMOVED***-secure/removing-sensitive-d***REMOVED***t***REMOVED***-from-***REMOVED***-repository#fully-removing-the-d***REMOVED***t***REMOVED***-from-github) to ensure no sensitive d***REMOVED***t***REMOVED*** is c***REMOVED***ched on GitHub.com.

Now th***REMOVED***t we've mitig***REMOVED***ted the risk of exposing sensitive content, we'll be pro***REMOVED***ctive ***REMOVED***nd prevent its ***REMOVED***ddition.

We'll now configure Git so it ignores ***REMOVED*** future ***REMOVED***ddition of sensitive content by ***REMOVED***dding `.env` to `.gitignore`. If someone should th***REMOVED***t file to the loc***REMOVED***l copy of their repository, it will rem***REMOVED***in only on the contributor's m***REMOVED***chine ***REMOVED***nd won't be pushed to GitHub.

**Wh***REMOVED***t is `.gitignore`?** This speci***REMOVED***l file ***REMOVED***llows us to tell Git n***REMOVED***ming p***REMOVED***tterns to ignore. You c***REMOVED***n re***REMOVED***d more ***REMOVED***bout it in [Ignoring files on GitHub Docs](https://docs.github.com/en/get-st***REMOVED***rted/getting-st***REMOVED***rted-with-git/ignoring-files).

### :keybo***REMOVED***rd: Activity: Add `.env` to `.gitignore`

1. Upd***REMOVED***te the loc***REMOVED***l copy of your repository to ensure you h***REMOVED***ve the most recent version of the course files.
   ```shell
   git pull
   ```
2. Loc***REMOVED***te the file we ***REMOVED***dded to the repository titled `.gitignore`.
3. Add `.env` to the file.
4. St***REMOVED***ge, commit the file:
   ```shell
   git ***REMOVED***dd .gitignore
   git commit -m "ignore .env files"
   ```
5. Push the file to GitHub.com
   ```shell
   git push
   ```
6. W***REMOVED***it ***REMOVED***bout 20 seconds then refresh this p***REMOVED***ge (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/***REMOVED***ctions) will ***REMOVED***utom***REMOVED***tic***REMOVED***lly upd***REMOVED***te to the next step.
