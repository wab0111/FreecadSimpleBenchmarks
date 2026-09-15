# FreecadSimpleBenchmarks
Simple benchmarks for Freecad that measure time and cpu temperature to update a pattern and run Calculix simulation.

This has been tested on Freecad 1.1.3

Put the macro files in your Freecad macro folder.
Open either of the model docs: "screen test" for pattern or "beam test" for the Calculix benchmark.
Open your report view panel (Menu Bar, View, Panels, Report View)
Open the Macros dialog box (Menu Bar, Macro, Macros)
Execute the corresponding macro: BenchmarkArray for the "screen test" model and BenchmarkFEM for the "beam test" model.
Wait for the operation to finish and you should see the report view of how long the operation takes.

When its done, reset by changing the pattern back to 3x3 and the FEM by deleting the results.

To see the effects of a long run and temperature on the cpu, increase the mesh density or the pattern size.
