---
name: Add a new language
labels: kind/language
about: Use this template to add a new langauge support
---

## How to add a new language?

See also [#138]( https://github.com/wuhan2020/wuhan2020.github.io/issues/138) for latest update.

Please @GindaChen for help if you need it.

1. Check [site_config](https://github.com/wuhan2020/wuhan2020.github.io/tree/dev/site_config) and see if there exist the entry of the langauge you add. If not, **raise an issue** about adding a language (like #120 )
2. Add the entries for all the `js` like [this commit](https://github.com/wuhan2020/wuhan2020.github.io/pull/121/commits/c056842dff02ad58ea9295100b1a22ded8c10ea8) in #121. You will see there are 5 files you need to edit, and basically it's copy and pasting materials and rename them by the country code.

Here is a checklist of all the components to add:
- [ ] Determine you language code: `fr-fr` means French
- [ ] In `site_config/site.js`: add the `{ value: 'fr-fr', text: 'French' },` to `langLis3. t`
- [ ] In `site_config/site.js`: add the language specific dictionary entry [like this](https://github.com/wuhan2020/wuhan2020.github.io/pull/121/commits/c056842dff02ad58ea9295100b1a22ded8c10ea8#diff-354ed30ae55896616d4990040cb68d35R330-R408)
- [ ] In `site_config/home.js`: add an entry [like this](https://github.com/wuhan2020/wuhan2020.github.io/pull/121/commits/c056842dff02ad58ea9295100b1a22ded8c10ea8#diff-2cee9234b2628e76bd8ba03d7c1f6d7cR154-R175)
- [ ] similarly in `doc.js`
- [ ] similarly in `develop.js`
- [ ] similarly in `community.jsx`
- [ ] similarly in `blog.js`

3. Create two direcotry under `/blog` and `/doc` with the language you specify. If you're adding `fr-fr` (French), then 
- [ ] Copy `/doc/en-us` to `/doc/fr-fr`
- [ ] Copy `/blog/en-us` to `/blog/fr-fr`

4. Raise a PR when you're done with the steps above. 
5. When the PR is passed, you can change / upload the documents in the language subdirectory and start translate the documentations.

Thanks for your contribution! If you want to add a translation to this documetation, comment below!
