https://pagefind.app/docs/running-pagefind/
https://embed.figma.com/file/1287828769207775946/hf_embed?community_viewer=true&embed_host=fastma&kind=file&page-selector=0&viewer=1

| css font-size | css em       | css px    | HTML Element |
| ------------- | ------------ | --------- | ------------ |
| xxx-large     | 3em          | 48px      |              |
| xx-large      | 2em          | 32px      | h1           |
| x-large       | 1.5em        | 24px      | h2           |
| larger        | 1.2em        | 19.2px    |              |
|               | 1.17em       | 18.72px   | h3           |
| large         | 1.125em      | 18px      |              |
| medium / math | 1em          | 16px      | h4           |
|               | 0.83em       | 13.28px   | h5           |
| small         | 0.8125em     | 13px      |              |
| smaller       | 0.83333125em | 13.3333px |              |
|               | 0.67em       | 10.72px   | h6           |
| x-small       | 0.625em      | 10px      |              |
| xx-small      | 0.5625em     | 9px       |              |

# Dependencies
| Package                                   | Purpose                               | Optional |
| ----------------------------------------- | ------------------------------------- | -------- |
| @fullhuman/postcss-purgecss               | Purging css in final build            | Yes      |
| postcss-cli                               | Processing CSS in final build         | Yes      |
| wrangler                                  | Uploading build to cloudflare workers | Yes      |
| [lucide-static](https://lucide.dev/icons) | Icons to be used in the website       | No       |

# Deploying
npm run deploy.