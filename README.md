Simple Example of How To Combine Nikola and FileTreeSubs
========================================================

To build this Nikola page, you need [Nikola](https://getnikola.com/) and [filetreesubs](https://github.com/felixfontein/filetreesubs/) installed. Then, simply run:

1. Run `nikola build`
2. Run `./subs.sh`
3. Run `./serve.sh`
4. Check the result in your browser at `http://localhost:8000`
5. If you're happy, run `./deploy.sh` to deploy (adjust that script first!)

This is the Nikola demo page with minimal modifications (mainly installing the [sidebar](https://plugins.getnikola.com/v7/sidebar/) plugin and slightly modifying `base.tmpl` of the Bootstrap 3 theme to include the sidebar).

If you don't want to run the shell scripts, or are using Windows, you can execute the following commands instead:

1. Run `nikola build`
2. Run `filetreesubs subs-config.yaml`
3. Run `nikola --conf=final-conf.py serve`
