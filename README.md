# PPL-assignment-2
Adding a new class to L3
  1. Add the new ‘class’ special form to the parser of L3 (the file ‘L3/L3-ast.ts’)
  2. Add the semantics of the new class special form to the interpreter, for both substitutional
    model (L3/L3-eval-sub.ts and L3/L3-value.ts files) and environment model
    (L3/L3-eval-env.ts and L3/L3-value.ts files):
  3. Implement the procedure class2proc (at file L3/LexicalTransformations.ts), which applies
    a syntactic transformation from a ClassExp to an equivalent ProcExp.
    Implement the procedure lexTransform (at file L3/LexicalTransformations.ts), which gets
    a program with class forms and returns an equivalent program with no class forms.
