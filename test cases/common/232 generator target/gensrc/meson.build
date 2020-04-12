compsrc = generator_target('generate',
  sources: xmlloc,
  output: ['@BASENAME@.h', '@BASENAME@.c'],
  command: [find_program('gensrc.py'), '@INPUT@', '@OUTPUT0@', '@OUTPUT1@'])
