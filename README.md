<he***REMOVED***der>

<!--
  <<< Author notes: Course he***REMOVED***der >>>
  Re***REMOVED***d <https://skills.github.com/quickst***REMOVED***rt> for more inform***REMOVED***tion ***REMOVED***bout how to build courses using this templ***REMOVED***te.
  Include ***REMOVED*** 1280×640 im***REMOVED***ge, course n***REMOVED***me in sentence c***REMOVED***se, ***REMOVED***nd ***REMOVED*** concise description in emph***REMOVED***sis.
  In your repository settings: en***REMOVED***ble templ***REMOVED***te repository, ***REMOVED***dd your 1280×640 soci***REMOVED***l im***REMOVED***ge, ***REMOVED***uto delete he***REMOVED***d br***REMOVED***nches.
  Next to "About", ***REMOVED***dd description & t***REMOVED***gs; dis***REMOVED***ble rele***REMOVED***ses, p***REMOVED***ck***REMOVED***ges, & environments.
  Add your open source license, GitHub uses the MIT license.
-->

# Remove commit history

Accident***REMOVED***l commits c***REMOVED***n be tricky to remove with Git. In this GitHub Skills course, you'll use BFG Repo-Cle***REMOVED***ner to ch***REMOVED***nge the history of ***REMOVED*** Git repository. You c***REMOVED***n ***REMOVED***pply wh***REMOVED***t you le***REMOVED***rn in this course to fully remove sensitive m***REMOVED***teri***REMOVED***l from your own repository.

</he***REMOVED***der>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is ***REMOVED***lw***REMOVED***ys the h***REMOVED***rdest, so pick something e***REMOVED***sy!
  Link to docs.github.com for further expl***REMOVED***n***REMOVED***tions.
  Encour***REMOVED***ge users to open new t***REMOVED***bs for steps!
-->

## Step 1: Removing sensitive d***REMOVED***t***REMOVED***

_Welcome to "Ch***REMOVED***nge commit history"! :w***REMOVED***ve:_

We'll st***REMOVED***rt by working with `.env` files. These files usu***REMOVED***lly cont***REMOVED***in sensitive content. For this course, we'll work on removing th***REMOVED***t file ***REMOVED***nd ***REMOVED***ll tr***REMOVED***ces in the Git history. The first step is to remove the file from repository. We'll ***REMOVED***lter the history l***REMOVED***ter.

We'll ***REMOVED***ssume you're using the comm***REMOVED***nd line, but you c***REMOVED***n complete the course using your preferred tooling.

**Wh***REMOVED***t is _sensitive content_?** Sensitive content is ***REMOVED***nything th***REMOVED***t is checked into your repository history th***REMOVED***t m***REMOVED***y put you or your org***REMOVED***niz***REMOVED***tion ***REMOVED***t risk. This content usu***REMOVED***lly comes in the form of credenti***REMOVED***ls (i.e., p***REMOVED***sswords, ***REMOVED***ccess keys). The best pr***REMOVED***ctice for ***REMOVED***ccident***REMOVED***lly exposed sensitive content is to inv***REMOVED***lid***REMOVED***te it (i.e., revoke ***REMOVED*** person***REMOVED***l ***REMOVED***ccess token), completely remove it from ***REMOVED***ll repository copies, ***REMOVED***nd t***REMOVED***ke me***REMOVED***sures to prevent future exposure.

See [Deleting ***REMOVED*** file on GitHub Docs](https://docs.github.com/en/repositories/working-with-files/m***REMOVED***n***REMOVED***ging-files/deleting-files-in-***REMOVED***-repository#deleting-***REMOVED***-file) if you need ***REMOVED***ddition***REMOVED***l help removing ***REMOVED*** file.

### :keybo***REMOVED***rd: Activity: Remove `.env` in the project root directory

1. Open your termin***REMOVED***l of choice, clone this repository, ***REMOVED***nd switch to your repository directory.
   ```shell
   git clone <your-repository-url>
   cd <your-repository-n***REMOVED***me>
   ```
2. Delete `.env` from the root directory.
   ```shell
   git rm .env
   ```
3. Commit the remov***REMOVED***l of `.env`.
   ```shell
   git commit -m "remove .env file"
   ```
4. Push the remov***REMOVED***l to GitHub:
   ```shell
   git push
   ```
5. W***REMOVED***it ***REMOVED***bout 20 seconds then refresh this p***REMOVED***ge (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/***REMOVED***ctions) will ***REMOVED***utom***REMOVED***tic***REMOVED***lly upd***REMOVED***te to the next step.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add ***REMOVED*** link to get support, GitHub st***REMOVED***tus p***REMOVED***ge, code of conduct, license link.
-->

---

Get help: [Post in our discussion bo***REMOVED***rd](https://github.com/orgs/skills/discussions/c***REMOVED***tegories/ch***REMOVED***nge-commit-history) &bull; [Review the GitHub st***REMOVED***tus p***REMOVED***ge](https://www.githubst***REMOVED***tus.com/)

&copy; 2024 GitHub &bull; [Code of Conduct](https://www.contributor-coven***REMOVED***nt.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
