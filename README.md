# CodeRepoQA 📊

CodeRepoQA dataset
🚀

CodeRepoQa is the dataset for the article:

"[CodeRepoQA: A Large-scale Benchmark for Software Engineering Question Answering](https://arxiv.org/abs/2412.14764)"

You can get access to the dataset by: https://drive.google.com/drive/folders/19-7gqlcYuwbbHAqYyzMMov7tuTTwHfcY?usp=sharing
We crawled a total of thirty GitHub open-source repositories and extracted and filtered a total of 585,687 issues as a multi-turn dialogue dataset.
We performed the crawling in August 2024.

| Repo-fullname       | Language       | Number       |
| -------------- | -------------- | -------------- |
| plotly/plotly.py| Python| 2829|
| pandas-dev/pandas| Python| 25055|
| numpy/numpy| Python| 12076|
| python-pillow/Pillow| Python| 2976|
| huggingface/transformers| Python| 15052|
| PyMySQL/PyMySQL| Python| 660|
| nltk/nltk| Python| 1775|
| tree-sitter/py-tree-sitter| Python| 155|
| scipy/scipy| Python| 9775|
| aio-libs/aiohttp| Python| 2870|
| ansible/ansible| Python| 31399|
| Textualize/rich| Python| 1287|
| Significant-Gravitas/AutoGPT| Python| 2229|
| fastapi/fastapi| Python| 3415|
| pytorch/pytorch| Python| 42408|
| home-assistant/core| Python| 50540|
| facebook/react| JavaScript| 12498|
| nodejs/node| JavaScript| 17004|
| vuejs/vue| JavaScript| 9744|
| microsoft/vscode| TypeScript| 148293|
| microsoft/TypeScript| TypeScript| 33607|
| typeorm/typeorm| TypeScript| 7828|
| angular/angular| TypeScript| 25902|
| nestjs/nest| TypeScript| 5254|
| hashicorp/terraform| Go| 20090|
| moby/moby| Go| 21607|
| kubernetes/kubernetes| Go| 44567|
| spring-projects/spring-framework| Java| 24516|
| google/guava| Java| 3342|
| apache/dubbo| Java| 6934|

The properties related to QA are listed below, and the attributes with a green background are directly related to QA:
```diff
               - url
               - repository_url
               - labels_url
               - comments_url
               - events_url
               - html_url
               - id
               - node_id
               - number
+              - title
               - labels
                 - []
                   - id
                   - node_id
                   - url
                   - name
                   - color
                   - default
                   - description
               - state
               - locked
               - assignee
               - assignees
               - milestone
               - comments
+              - created_at
               - updated_at
               - closed_at
               - author_association
               - active_lock_reason
+              - body
               - reactions
                 - url
                 - total_count
                 - +1
                 - -1
                 - laugh
                 - hooray
                 - confused
                 - heart
                 - rocket
                 - eyes
               - timeline_url
               - performed_via_github_app
               - state_reason
+              - comments_details
                 - []
                   - url
                   - html_url
                   - issue_url
                   - id
                   - node_id
                   - user
                     - login
                     - id
                     - node_id
                     - avatar_url
                     - gravatar_id
                     - url
                     - html_url
                     - followers_url
                     - following_url
                     - gists_url
                     - starred_url
                     - subscriptions_url
                     - organizations_url
                     - repos_url
                     - events_url
                     - received_events_url
                     - type
                     - site_admin
                   - created_at
                   - updated_at
+                  - author_association
+                  - body
                   - reactions
                     - url
                     - total_count
                     - +1
                     - -1
                     - laugh
                     - hooray
                     - confused
                     - heart
                     - rocket
                     - eyes
                   - performed_via_github_app
               - issue_or_pr
               - cite
               - cited_by
               - fixed_by
               - duplicate
```
