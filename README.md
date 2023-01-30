# www.cwts.edu implemented with Astro.build

## TODO

* [x] Setup Netlify deployment: https://cwts-www.netlify.app/
* [ ] Integrate with netlify CMS
* [ ] Multilingual support
* [ ] CSS framework
* Components
  * [ ] Header component without navigation
  * [ ] Footer component
  * [ ] Desktop navigation
  * [ ] Mobile navigation
  * [ ] Section page side navigation
* Homepage widgets

## Project Structure

<dl>
<dt>src/pages</dt>
<dd>Static routing and dynamic routing, e.g. homepage</dd>
<dt>src/layouts</dt>
<dd>Page template components</dd>
<dt>src/components</dt>
<dd>Reusable components used in pages and layouts</dd>
<dt>src/content</dt>
<dd>Content collections, e.g. sub-section pages, faculty bio</dd>
<dt>public</dt>
<dd>Static files</dd>
</dl>

## Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Installs dependencies                            |
| `npm run dev`          | Starts local dev server at `localhost:3000`      |
| `npm run build`        | Build your production site to `./dist/`          |
| `npm run preview`      | Preview your build locally, before deploying     |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `npm run astro --help` | Get help using the Astro CLI                     |

## Resources

* [Astro documentation](https://docs.astro.build)
