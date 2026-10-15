<!--
  <<< Author notes: Step 2 >>>
  St***REMOVED***rt this step by ***REMOVED***cknowledging the previous step.
  Define terms ***REMOVED***nd link to docs.github.com.
-->

## Step 2: Removing ***REMOVED*** file from Git history using BFG Repo-Cle***REMOVED***ner

_You removed `.env` from the repository's root directory! :t***REMOVED***d***REMOVED***:_

Now th***REMOVED***t we've deleted the file, people th***REMOVED***t browse the repository on GitHub.com or ***REMOVED***nyone looking ***REMOVED***t just the he***REMOVED***d commit won't see the file. However, due to Git's n***REMOVED***ture, the file is still present in the history. In this step, we'll work on removing the file from the repository history.

**Wh***REMOVED***t is ***REMOVED*** _he***REMOVED***d commit_**? In Git, HEAD points to ***REMOVED*** br***REMOVED***nch or ***REMOVED*** commit. When we s***REMOVED***y [he***REMOVED***d commit](https://docs.github.com/en/get-st***REMOVED***rted/quickst***REMOVED***rt/github-gloss***REMOVED***ry#he***REMOVED***d), we usu***REMOVED***lly me***REMOVED***n the most recent commit in the repository's history.

There ***REMOVED***re multiple tools ***REMOVED***v***REMOVED***il***REMOVED***ble for removing Git history, we'll use BFG Repo-Cle***REMOVED***ner in this step. You c***REMOVED***n find ***REMOVED***ddition***REMOVED***l document***REMOVED***tion on [Using the BFG in GitHub Docs](https://docs.github.com/en/***REMOVED***uthentic***REMOVED***tion/keeping-your-***REMOVED***ccount-***REMOVED***nd-d***REMOVED***t***REMOVED***-secure/removing-sensitive-d***REMOVED***t***REMOVED***-from-***REMOVED***-repository#using-the-bfg).

**Wh***REMOVED***t is _BFG Repo-Cle***REMOVED***ner_**? BFG Repo-Cle***REMOVED***ner is softw***REMOVED***re th***REMOVED***t c***REMOVED***n help you se***REMOVED***rch through ***REMOVED***nd ***REMOVED***lter repository history. Git c***REMOVED***n n***REMOVED***tively do this using [`git filter-repo`](https://docs.github.com/en/***REMOVED***uthentic***REMOVED***tion/keeping-your-***REMOVED***ccount-***REMOVED***nd-d***REMOVED***t***REMOVED***-secure/removing-sensitive-d***REMOVED***t***REMOVED***-from-***REMOVED***-repository#using-git-filter-repo), but it c***REMOVED***n be more complex.

### :keybo***REMOVED***rd: Activity: Use BFG Repo-Cle***REMOVED***ner to remove the `.env` file

1. Upd***REMOVED***te the loc***REMOVED***l copy of your repository to ensure you h***REMOVED***ve the most recent version of the course files.
   ```shell
   git pull
   ```
2. Inst***REMOVED***ll BFG Repo-Cle***REMOVED***ner on your m***REMOVED***chine. You c***REMOVED***n follow the [instructions on the web site](https://rtyley.github.io/bfg-repo-cle***REMOVED***ner/) to do so or you c***REMOVED***n use ***REMOVED*** p***REMOVED***ck***REMOVED***ge m***REMOVED***n***REMOVED***ger for your oper***REMOVED***ting system.
3. Confirm the `.env` file is removed from the root directory. The comm***REMOVED***nd should return empty.
   ```shell
   find . -n***REMOVED***me ".env"
   ```
4. Se***REMOVED***rch for .env in the repository's history. The comm***REMOVED***nd should return ***REMOVED***t le***REMOVED***st 2 commits: the ***REMOVED***ddition of `.env` when you copied this templ***REMOVED***te repository, ***REMOVED***nd the remov***REMOVED***l of `.env`.
   ```shell
   git log --st***REMOVED***t --***REMOVED***ll -- .env
   ```
5. Use BFG Repo-Cle***REMOVED***ner to delete ***REMOVED***ll references to `.env` th***REMOVED***t exist in the repository.
   ```shell
   bfg --delete-files .env
   ```
6. The tool will run ***REMOVED***nd m***REMOVED***ke some suggestions ***REMOVED***bout some follow-up comm***REMOVED***nds. Run those to get your loc***REMOVED***l repository cle***REMOVED***ned up.
7. Repe***REMOVED***t the se***REMOVED***rch for `.env` in the repository's history. This time, the comm***REMOVED***nd should return empty.
   ```shell
   git log --st***REMOVED***t --***REMOVED***ll -- .env
   ```
8. Push your ch***REMOVED***nges to GitHub. Note we're using the `--force` ***REMOVED***rgument in this step since we're ***REMOVED***ltering Git history.
   ```shell
   git push --force
   ```
9. W***REMOVED***it ***REMOVED***bout 20 seconds then refresh this p***REMOVED***ge (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/***REMOVED***ctions) will ***REMOVED***utom***REMOVED***tic***REMOVED***lly upd***REMOVED***te to the next step.
