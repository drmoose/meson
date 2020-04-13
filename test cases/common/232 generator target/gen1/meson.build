xml1 = generator_target('gen1',
  input: ['first.component',
          'second.component',
          'third.component',
         ],
  output: '@BASENAME@.xc',
  command: [find_program('comp2xml.py'), '@INPUT@', '@OUTPUT@'])
