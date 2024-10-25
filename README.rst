GitHub Actions Reusable Workflows
=================================
This repository contains our common reusable workflows. You can simply use any of them in your
workflows via the ``uses`` keyword:

.. code-block:: yaml

    jobs:
      run-python-tests:
        uses: logikal-io/github-workflows/.github/workflows/run-python-tests.yml@v9
        permissions:
          contents: read
          id-token: write
        secrets: inherit

You can find more information about reusable workflows in the `GitHub documentation
<https://docs.github.com/en/actions/using-workflows/reusing-workflows>`_.

License
-------
The reusable workflows in this repository are licensed under the MIT open source license.
