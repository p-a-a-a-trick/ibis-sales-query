# ibis-sales-query
Example Sales Data Query using Ibis Expressions (with complimentary fString Representations)

This repository contains:

1. A requirements file to quickly spin up an environment using `venv` or [Binder](https://mybinder.org/)
2. A mock dataset generation notebook to randomly generate sales data for use in the following notebooks
3. A notebook that builds a sales data query using fStrings
4. A notebook that builds a sales data query using Ibis expressions.

Using this notebook set (or, at least, notebook 4), we can take a look at how Ibis can make your python-based data workflows a bit simpler.

Ibis performs type and reference checking throughout script execution, whereas fString SQL only performs checks at query execution.
By performing type and reference checks in-line, we can easily find bugs and errors with our query,
make the code a bit more accessible to Python users,
and allows us to use Python objects when programmatically generating queries.

<hr>
⚠️ <b>For some reason (that I have yet to investigate), Binder is installing v2.1.1.  The Ibis notebook requires 3.0.0+ to run successfully.</b>
<hr>

Try it with Binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/p-a-a-a-trick/ibis-sales-query/HEAD)
