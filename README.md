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
  <<< Author notes: Course st***REMOVED***rt >>>
  Include st***REMOVED***rt button, ***REMOVED*** note ***REMOVED***bout Actions minutes,
  ***REMOVED***nd tell the le***REMOVED***rner why they should t***REMOVED***ke the course.
-->

## Welcome

A trustworthy commit history is the b***REMOVED***ckbone of version control with Git. As ***REMOVED*** result, ***REMOVED***ltering commit history is difficult by design. Sometimes, the history needs to be ***REMOVED***ltered to remove credenti***REMOVED***ls or other sensitive d***REMOVED***t***REMOVED*** th***REMOVED***t is mist***REMOVED***kenly checked in. In this course, we'll le***REMOVED***rn how to remove content from repository's complete history ***REMOVED***nd ***REMOVED***pply best pr***REMOVED***ctices for preventing ***REMOVED***ccident***REMOVED***l commits in the future.

- **Who is this for**: Intermedi***REMOVED***te users of Git, org***REMOVED***niz***REMOVED***tions
- **Wh***REMOVED***t you'll le***REMOVED***rn**: How to remove ***REMOVED*** file from Git's entire history
- **Wh***REMOVED***t you'll build**: You'll m***REMOVED***nipul***REMOVED***te the history of ***REMOVED*** Git repository
- **Prerequisites**: We recommend you clone this repository to your m***REMOVED***chine ***REMOVED***nd use the comm***REMOVED***nd line to follow ***REMOVED***long. You'll ***REMOVED***lso need to inst***REMOVED***ll BFG Repo-Cle***REMOVED***ner, but the steps will be covered in the course.
- **How long**: This course t***REMOVED***kes less th***REMOVED***n 1 hour to complete.

In this course, you will:

1. Remove content from the root directory of ***REMOVED*** repository
2. Use BFG Repo-Cle***REMOVED***ner to remove content from repository history
3. Avoid future ***REMOVED***ccident***REMOVED***l commits by ***REMOVED***dding ***REMOVED*** p***REMOVED***ttern to `.gitignore`

### How to st***REMOVED***rt this course

<!-- For st***REMOVED***rt course, run in J***REMOVED***v***REMOVED***Script:
'https://github.com/new?' + new URLSe***REMOVED***rchP***REMOVED***r***REMOVED***ms({
  templ***REMOVED***te_owner: 'skills',
  templ***REMOVED***te_n***REMOVED***me: 'ch***REMOVED***nge-commit-history',
  owner: '@me',
  n***REMOVED***me: 'skills-ch***REMOVED***nge-commit-history',
  description: 'My copy of the skills course on ch***REMOVED***nging commit history',
  visibility: 'public',
}).toString()
-->

[![st***REMOVED***rt-course](https://user-im***REMOVED***ges.githubusercontent.com/1221423/235727646-4***REMOVED***590299-ffe5-480d-8cd5-8194e***REMOVED***184546.svg)](https://github.com/new?templ***REMOVED***te_owner=skills&templ***REMOVED***te_n***REMOVED***me=ch***REMOVED***nge-commit-history&owner=%40me&n***REMOVED***me=skills-ch***REMOVED***nge-commit-history&description=My+copy+of+the+skills+course+on+ch***REMOVED***nging+commit+history&visibility=public)

1. Right-click **St***REMOVED***rt course** ***REMOVED***nd open the link in ***REMOVED*** new t***REMOVED***b.
2. In the new t***REMOVED***b, most of the prompts will ***REMOVED***utom***REMOVED***tic***REMOVED***lly fill in for you.
   - For owner, choose your person***REMOVED***l ***REMOVED***ccount or ***REMOVED***n org***REMOVED***niz***REMOVED***tion to host the repository.
   - We recommend cre***REMOVED***ting ***REMOVED*** public repository, ***REMOVED***s priv***REMOVED***te repositories will [use Actions minutes](https://docs.github.com/en/billing/m***REMOVED***n***REMOVED***ging-billing-for-github-***REMOVED***ctions/***REMOVED***bout-billing-for-github-***REMOVED***ctions).
   - Scroll down ***REMOVED***nd click the **Cre***REMOVED***te repository** button ***REMOVED***t the bottom of the form.
3. After your new repository is cre***REMOVED***ted, w***REMOVED***it ***REMOVED***bout 20 seconds, then refresh the p***REMOVED***ge. Follow the step-by-step instructions in the new repository's README.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add ***REMOVED*** link to get support, GitHub st***REMOVED***tus p***REMOVED***ge, code of conduct, license link.
-->

---

Get help: [Post in our discussion bo***REMOVED***rd](https://github.com/orgs/skills/discussions/c***REMOVED***tegories/ch***REMOVED***nge-commit-history) &bull; [Review the GitHub st***REMOVED***tus p***REMOVED***ge](https://www.githubst***REMOVED***tus.com/)

&copy; 2024 GitHub &bull; [Code of Conduct](https://www.contributor-coven***REMOVED***nt.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
