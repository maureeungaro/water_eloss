project('water-eloss')

latexmk = find_program('latexmk')

custom_target(
  'proposal',
  input: 'proposal.tex',
  output: 'proposal.pdf',
  command: [
    latexmk,
    '-pdf',
    '-interaction=nonstopmode',
    '-halt-on-error',
    '-outdir=@OUTDIR@',
    '@INPUT@',
  ],
  build_by_default: true,
)
